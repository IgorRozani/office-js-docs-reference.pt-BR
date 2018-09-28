# <a name="script-element"></a><span data-ttu-id="38208-101">Elemento de script</span><span class="sxs-lookup"><span data-stu-id="38208-101">Script element</span></span>

<span data-ttu-id="38208-102">Define as configurações de script usadas por uma função personalizada no Excel.</span><span class="sxs-lookup"><span data-stu-id="38208-102">Defines script settings used by a custom function in Excel.</span></span>

## <a name="attributes"></a><span data-ttu-id="38208-103">Atributos</span><span class="sxs-lookup"><span data-stu-id="38208-103">Attributes</span></span>

<span data-ttu-id="38208-104">Nenhuma</span><span class="sxs-lookup"><span data-stu-id="38208-104">None</span></span>

## <a name="child-elements"></a><span data-ttu-id="38208-105">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="38208-105">Child elements</span></span>

|<span data-ttu-id="38208-106">Elementos</span><span class="sxs-lookup"><span data-stu-id="38208-106">Elements</span></span>  |  <span data-ttu-id="38208-107">Obrigatório</span><span class="sxs-lookup"><span data-stu-id="38208-107">Required</span></span>  |  <span data-ttu-id="38208-108">Descrição</span><span class="sxs-lookup"><span data-stu-id="38208-108">Description</span></span>  |
|:-----|:-----|:-----|
|  [<span data-ttu-id="38208-109">SourceLocation</span><span class="sxs-lookup"><span data-stu-id="38208-109">SourceLocation</span></span>](customfunctionssourcelocation.md)  |  <span data-ttu-id="38208-110">Sim</span><span class="sxs-lookup"><span data-stu-id="38208-110">Yes</span></span>  | <span data-ttu-id="38208-111">Cadeia de caracteres com o ID de recurso do arquivo JavaScript usado por funções personalizadas.</span><span class="sxs-lookup"><span data-stu-id="38208-111">String with resource id of the JavaScript file used by custom functions.</span></span>|

## <a name="example"></a><span data-ttu-id="38208-112">Exemplo</span><span class="sxs-lookup"><span data-stu-id="38208-112">Example</span></span>

```xml
<Script>
    <SourceLocation resid="scriptURL" />
    <!-- The Script element is not used in the Developer Preview. -->
</Script>
```
