# <a name="onenote-javascript-api-requirement-sets"></a><span data-ttu-id="d0983-101">Conjuntos de requisitos de API JavaScript do OneNote</span><span class="sxs-lookup"><span data-stu-id="d0983-101">OneNote JavaScript API requirement sets</span></span>

<span data-ttu-id="d0983-102">Os conjuntos de requisitos são grupos nomeados de membros da API.</span><span class="sxs-lookup"><span data-stu-id="d0983-102">Requirement sets are named groups of API members.</span></span> <span data-ttu-id="d0983-103">Suplementos do Office usam conjuntos de requisito especificados no manifesto ou uma seleção de tempo de execução para determinar se um host do Office oferece suporte a APIs que precisa de um suplemento.</span><span class="sxs-lookup"><span data-stu-id="d0983-103">Office Add-ins use requirement sets specified in the manifest or use a runtime check to determine whether an Office host supports APIs that an add-in needs.</span></span> <span data-ttu-id="d0983-104">Para obter mais informações, consulte [define versões do Office e o requisito](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets).</span><span class="sxs-lookup"><span data-stu-id="d0983-104">For more information, see [Office versions and requirement sets](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets).</span></span>

<span data-ttu-id="d0983-105">A tabela a seguir lista os conjuntos de requisitos do OneNote, ou seja, os aplicativos de host do Office que oferecem suporte a esse conjunto de requisitos, e os números de versão ou datas de disponibilidade.</span><span class="sxs-lookup"><span data-stu-id="d0983-105">The following table lists the OneNote requirement sets, the Office host applications that support those requirement sets, and the build versions or availability date.</span></span>

|  <span data-ttu-id="d0983-106">Conjunto de requisitos</span><span class="sxs-lookup"><span data-stu-id="d0983-106">Requirement set</span></span>  |  <span data-ttu-id="d0983-107">Office Online</span><span class="sxs-lookup"><span data-stu-id="d0983-107">Office Online</span></span> | 
|:-----|:-----|
| <span data-ttu-id="d0983-108">OneNoteApi 1.1</span><span class="sxs-lookup"><span data-stu-id="d0983-108">OneNoteApi 1.1</span></span>  | <span data-ttu-id="d0983-109">Setembro de 2016</span><span class="sxs-lookup"><span data-stu-id="d0983-109">September 2016</span></span> |  

## <a name="office-common-api-requirement-sets"></a><span data-ttu-id="d0983-110">Conjuntos de requisitos comuns da API do Office</span><span class="sxs-lookup"><span data-stu-id="d0983-110">Office common API requirement sets</span></span>

<span data-ttu-id="d0983-111">Para saber mais sobre conjuntos de requisitos comuns da API, confira [Conjuntos de requisitos comuns da API do Office](office-add-in-requirement-sets.md).</span><span class="sxs-lookup"><span data-stu-id="d0983-111">For information about common API requirement sets, see [Office common API requirement sets](office-add-in-requirement-sets.md).</span></span>

## <a name="onenote-javascript-api-11"></a><span data-ttu-id="d0983-112">API JavaScript do OneNote 1.1</span><span class="sxs-lookup"><span data-stu-id="d0983-112">OneNote JavaScript API 1.1</span></span> 

<span data-ttu-id="d0983-113">A API JavaScript do OneNote 1.1 é a primeira versão da API.</span><span class="sxs-lookup"><span data-stu-id="d0983-113">OneNote JavaScript API 1.1 is the first version of the API.</span></span> <span data-ttu-id="d0983-114">Para obter detalhes sobre a API, consulte [Visão geral de programação de API do JavaScript OneNote](https://docs.microsoft.com/office/dev/add-ins/onenote/onenote-add-ins-programming-overview).</span><span class="sxs-lookup"><span data-stu-id="d0983-114">For details about the API, see the [OneNote JavaScript API programming overview](https://docs.microsoft.com/office/dev/add-ins/onenote/onenote-add-ins-programming-overview).</span></span>

## <a name="runtime-requirement-support-check"></a><span data-ttu-id="d0983-115">Verificação do suporte a requisitos de tempo de execução</span><span class="sxs-lookup"><span data-stu-id="d0983-115">Runtime requirement support check</span></span>

<span data-ttu-id="d0983-116">Durante o tempo de execução, os suplementos podem verificar se um determinado host oferece suporte a um conjunto de requisitos de API, realizando a seguinte verificação:</span><span class="sxs-lookup"><span data-stu-id="d0983-116">During the runtime, add-ins can check if a particular host supports an API requirement set by doing the following-check:</span></span> 

```js
if (Office.context.requirements.isSetSupported('OneNoteApi', 1.1) === true) {
  /// perform actions
}
else {
  /// provide alternate flow/logic
}
```

## <a name="manifest-based-requirement-support-check"></a><span data-ttu-id="d0983-117">Verificação de suporte a requisitos com base em manifesto</span><span class="sxs-lookup"><span data-stu-id="d0983-117">Manifest-based requirement support check</span></span>

<span data-ttu-id="d0983-p103">Use o elemento Requirements no manifesto do suplemento para especificar conjuntos de requisitos ou membros de API cruciais que o seu suplemento precisa usar. Se o host do Office ou a plataforma não der suporte ao conjunto de requisitos ou membros da API especificados no elemento Requirements, o suplemento não será executado no host ou na plataforma e não será exibido em Meus Suplementos.</span><span class="sxs-lookup"><span data-stu-id="d0983-p103">Use the Requirements element in the add-in manifest to specify critical requirement sets or API members that your add-in must use. If the Office host or platform doesn't support the requirement sets or API members specified in the Requirements element, the add-in won't run in that host or platform, and won't display in My Add-ins.</span></span>

<span data-ttu-id="d0983-120">O exemplo de código a seguir mostra um suplemento que é carregado em todos os aplicativos host do Office que oferecem suporte ao conjunto de requisitos OneNoteApi, versão 1.1.</span><span class="sxs-lookup"><span data-stu-id="d0983-120">The following code example shows an add-in that loads in all Office host applications that support the OneNoteApi requirement set, version 1.1.</span></span>

```xml
<Requirements>
   <Sets DefaultMinVersion="1.1">
      <Set Name="OneNoteApi" MinVersion="1.1"/>
   </Sets>
</Requirements>
```

## <a name="see-also"></a><span data-ttu-id="d0983-121">Confira também</span><span class="sxs-lookup"><span data-stu-id="d0983-121">See also</span></span>

- [<span data-ttu-id="d0983-122">Versões do Office e conjuntos de requisitos</span><span class="sxs-lookup"><span data-stu-id="d0983-122">Office versions and requirement sets</span></span>](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets)
- [<span data-ttu-id="d0983-123">Especificar hosts do Office e requisitos da API</span><span class="sxs-lookup"><span data-stu-id="d0983-123">Specify Office hosts and API requirements</span></span>](https://docs.microsoft.com/office/dev/add-ins/develop/specify-office-hosts-and-api-requirements)
- [<span data-ttu-id="d0983-124">Manifesto XML dos Suplementos do Office</span><span class="sxs-lookup"><span data-stu-id="d0983-124">Office Add-ins XML manifest</span></span>](https://docs.microsoft.com/office/dev/add-ins/develop/add-in-manifests)
