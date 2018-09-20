# <a name="allformfactors-element"></a><span data-ttu-id="c9daf-101">Elemento AllFormFactors</span><span class="sxs-lookup"><span data-stu-id="c9daf-101">AllFormFactors element</span></span>

<span data-ttu-id="c9daf-102">Especifica as configurações de um suplemento para todos os fatores forma.</span><span class="sxs-lookup"><span data-stu-id="c9daf-102">Specifies the settings for an add-in for all form factors.</span></span> <span data-ttu-id="c9daf-103">Atualmente, o único recurso usando **AllFormFactors** é funções personalizadas.</span><span class="sxs-lookup"><span data-stu-id="c9daf-103">Currently, the only feature using **AllFormFactors** is custom functions.</span></span> <span data-ttu-id="c9daf-104">**AllFormFactors** é um elemento necessário ao usar as funções personalizadas.</span><span class="sxs-lookup"><span data-stu-id="c9daf-104">**AllFormFactors** is a required element when using custom functions.</span></span>

## <a name="child-elements"></a><span data-ttu-id="c9daf-105">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="c9daf-105">Child elements</span></span>

|  <span data-ttu-id="c9daf-106">Elemento</span><span class="sxs-lookup"><span data-stu-id="c9daf-106">Element</span></span> |  <span data-ttu-id="c9daf-107">Obrigatório</span><span class="sxs-lookup"><span data-stu-id="c9daf-107">Required</span></span>  |  <span data-ttu-id="c9daf-108">Descrição</span><span class="sxs-lookup"><span data-stu-id="c9daf-108">Description</span></span>  |
|:-----|:-----|:-----|
|  [<span data-ttu-id="c9daf-109">ExtensionPoint</span><span class="sxs-lookup"><span data-stu-id="c9daf-109">ExtensionPoint</span></span>](extensionpoint.md) |  <span data-ttu-id="c9daf-110">Sim</span><span class="sxs-lookup"><span data-stu-id="c9daf-110">Yes</span></span> |  <span data-ttu-id="c9daf-111">Define onde um suplemento expõe a funcionalidade.</span><span class="sxs-lookup"><span data-stu-id="c9daf-111">Defines where an add-in exposes functionality.</span></span> |

## <a name="allformfactors-example"></a><span data-ttu-id="c9daf-112">Exemplo de AllFormFactors</span><span class="sxs-lookup"><span data-stu-id="c9daf-112">AllFormFactors example</span></span>

```xml
<Hosts>
    <Host xsi:type="Workbook">
        <AllFormFactors>
            <ExtensionPoint xsi:type="CustomFunctions">
                    <!-- Information on this extension point -->
            </ExtensionPoint>
        </AllFormFactors>
    </Host>
</Hosts>
```
