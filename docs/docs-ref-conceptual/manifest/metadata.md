# <a name="metadata-element"></a><span data-ttu-id="1d53e-101">Elemento de metadados</span><span class="sxs-lookup"><span data-stu-id="1d53e-101">Metadata element</span></span>

<span data-ttu-id="1d53e-102">Define as configurações de metadados usadas por uma função personalizada no Excel.</span><span class="sxs-lookup"><span data-stu-id="1d53e-102">Defines the metadata settings used by a custom function in Excel.</span></span>

## <a name="attributes"></a><span data-ttu-id="1d53e-103">Atributos</span><span class="sxs-lookup"><span data-stu-id="1d53e-103">Attributes</span></span>

<span data-ttu-id="1d53e-104">Nenhuma</span><span class="sxs-lookup"><span data-stu-id="1d53e-104">None</span></span>

## <a name="child-elements"></a><span data-ttu-id="1d53e-105">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="1d53e-105">Child elements</span></span>

|  <span data-ttu-id="1d53e-106">Elemento</span><span class="sxs-lookup"><span data-stu-id="1d53e-106">Element</span></span>  |  <span data-ttu-id="1d53e-107">Obrigatório</span><span class="sxs-lookup"><span data-stu-id="1d53e-107">Required</span></span>  |  <span data-ttu-id="1d53e-108">Descrição</span><span class="sxs-lookup"><span data-stu-id="1d53e-108">Description</span></span>  |
|:-----|:-----|:-----|
|  [<span data-ttu-id="1d53e-109">SourceLocation</span><span class="sxs-lookup"><span data-stu-id="1d53e-109">SourceLocation</span></span>](customfunctionssourcelocation.md)  |  <span data-ttu-id="1d53e-110">Sim</span><span class="sxs-lookup"><span data-stu-id="1d53e-110">Yes</span></span>  | <span data-ttu-id="1d53e-111">Cadeia de caracteres com a id de recurso do arquivo JSON usado pelas funções personalizadas.</span><span class="sxs-lookup"><span data-stu-id="1d53e-111">String with the resource id of the JSON file used by custom functions.</span></span> |

## <a name="example"></a><span data-ttu-id="1d53e-112">Exemplo</span><span class="sxs-lookup"><span data-stu-id="1d53e-112">Example</span></span>

```xml
<Metadata>
    <SourceLocation resid="JSON-URL" />
</Metadata>
```
