
# <a name="mailbox"></a><span data-ttu-id="d003e-101">caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-101">mailbox</span></span>

### <span data-ttu-id="d003e-p101">[Office](Office.md)[.context](Office.context.md). mailbox</span><span class="sxs-lookup"><span data-stu-id="d003e-p101">[Office](Office.md)[.context](Office.context.md). mailbox</span></span>

<span data-ttu-id="d003e-104">Fornece acesso ao modelo de objeto do suplemento do Outlook para o Microsoft Outlook e Microsoft Outlook na web.</span><span class="sxs-lookup"><span data-stu-id="d003e-104">Provides access to the Outlook add-in object model for Microsoft Outlook and Microsoft Outlook on the web.</span></span>

##### <a name="requirements"></a><span data-ttu-id="d003e-105">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-105">Requirements</span></span>

|<span data-ttu-id="d003e-106">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-106">Requirement</span></span>| <span data-ttu-id="d003e-107">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-107">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-108">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-108">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-109">1.0</span><span class="sxs-lookup"><span data-stu-id="d003e-109">1.0</span></span>|
|[<span data-ttu-id="d003e-110">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-110">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-111">Restrito</span><span class="sxs-lookup"><span data-stu-id="d003e-111">Restricted</span></span>|
|[<span data-ttu-id="d003e-112">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-112">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-113">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-113">Compose or read</span></span>|

##### <a name="members-and-methods"></a><span data-ttu-id="d003e-114">Membros e métodos</span><span class="sxs-lookup"><span data-stu-id="d003e-114">Members and methods</span></span>

| <span data-ttu-id="d003e-115">Membro</span><span class="sxs-lookup"><span data-stu-id="d003e-115">Member</span></span> | <span data-ttu-id="d003e-116">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-116">Type</span></span> |
|--------|------|
| [<span data-ttu-id="d003e-117">ewsUrl</span><span class="sxs-lookup"><span data-stu-id="d003e-117">ewsUrl</span></span>](#ewsurl-string) | <span data-ttu-id="d003e-118">Membro</span><span class="sxs-lookup"><span data-stu-id="d003e-118">Member</span></span> |
| [<span data-ttu-id="d003e-119">restUrl</span><span class="sxs-lookup"><span data-stu-id="d003e-119">restUrl</span></span>](#resturl-string) | <span data-ttu-id="d003e-120">Membro</span><span class="sxs-lookup"><span data-stu-id="d003e-120">Member</span></span> |
| [<span data-ttu-id="d003e-121">addHandlerAsync</span><span class="sxs-lookup"><span data-stu-id="d003e-121">addHandlerAsync</span></span>](#addhandlerasynceventtype-handler-options-callback) | <span data-ttu-id="d003e-122">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-122">Method</span></span> |
| [<span data-ttu-id="d003e-123">convertToEwsId</span><span class="sxs-lookup"><span data-stu-id="d003e-123">convertToEwsId</span></span>](#converttoewsiditemid-restversion--string) | <span data-ttu-id="d003e-124">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-124">Method</span></span> |
| [<span data-ttu-id="d003e-125">convertToLocalClientTime</span><span class="sxs-lookup"><span data-stu-id="d003e-125">convertToLocalClientTime</span></span>](#converttolocalclienttimetimevalue--localclienttimejavascriptapioutlookofficelocalclienttime) | <span data-ttu-id="d003e-126">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-126">Method</span></span> |
| [<span data-ttu-id="d003e-127">convertToRestId</span><span class="sxs-lookup"><span data-stu-id="d003e-127">convertToRestId</span></span>](#converttorestiditemid-restversion--string) | <span data-ttu-id="d003e-128">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-128">Method</span></span> |
| [<span data-ttu-id="d003e-129">convertToUtcClientTime</span><span class="sxs-lookup"><span data-stu-id="d003e-129">convertToUtcClientTime</span></span>](#converttoutcclienttimeinput--date) | <span data-ttu-id="d003e-130">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-130">Method</span></span> |
| [<span data-ttu-id="d003e-131">displayAppointmentForm</span><span class="sxs-lookup"><span data-stu-id="d003e-131">displayAppointmentForm</span></span>](#displayappointmentformitemid) | <span data-ttu-id="d003e-132">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-132">Method</span></span> |
| [<span data-ttu-id="d003e-133">displayMessageForm</span><span class="sxs-lookup"><span data-stu-id="d003e-133">displayMessageForm</span></span>](#displaymessageformitemid) | <span data-ttu-id="d003e-134">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-134">Method</span></span> |
| [<span data-ttu-id="d003e-135">displayNewAppointmentForm</span><span class="sxs-lookup"><span data-stu-id="d003e-135">displayNewAppointmentForm</span></span>](#displaynewappointmentformparameters) | <span data-ttu-id="d003e-136">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-136">Method</span></span> |
| [<span data-ttu-id="d003e-137">displayNewMessageForm</span><span class="sxs-lookup"><span data-stu-id="d003e-137">displayNewMessageForm</span></span>](#displaynewmessageformparameters) | <span data-ttu-id="d003e-138">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-138">Method</span></span> |
| [<span data-ttu-id="d003e-139">getCallbackTokenAsync</span><span class="sxs-lookup"><span data-stu-id="d003e-139">getCallbackTokenAsync</span></span>](#getcallbacktokenasyncoptions-callback) | <span data-ttu-id="d003e-140">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-140">Method</span></span> |
| [<span data-ttu-id="d003e-141">getCallbackTokenAsync</span><span class="sxs-lookup"><span data-stu-id="d003e-141">getCallbackTokenAsync</span></span>](#getcallbacktokenasynccallback-usercontext) | <span data-ttu-id="d003e-142">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-142">Method</span></span> |
| [<span data-ttu-id="d003e-143">getUserIdentityTokenAsync</span><span class="sxs-lookup"><span data-stu-id="d003e-143">getUserIdentityTokenAsync</span></span>](#getuseridentitytokenasynccallback-usercontext) | <span data-ttu-id="d003e-144">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-144">Method</span></span> |
| [<span data-ttu-id="d003e-145">makeEwsRequestAsync</span><span class="sxs-lookup"><span data-stu-id="d003e-145">makeEwsRequestAsync</span></span>](#makeewsrequestasyncdata-callback-usercontext) | <span data-ttu-id="d003e-146">Método</span><span class="sxs-lookup"><span data-stu-id="d003e-146">Method</span></span> |

### <a name="namespaces"></a><span data-ttu-id="d003e-147">Namespaces</span><span class="sxs-lookup"><span data-stu-id="d003e-147">Namespaces</span></span>

<span data-ttu-id="d003e-148">[diagnostics](Office.context.mailbox.diagnostics.md): Fornece informações de diagnóstico para um suplemento do Outlook.</span><span class="sxs-lookup"><span data-stu-id="d003e-148">[diagnostics](Office.context.mailbox.diagnostics.md): Provides diagnostic information to an Outlook add-in.</span></span>

<span data-ttu-id="d003e-149">[item](Office.context.mailbox.item.md): Fornece propriedades e métodos para acessar uma mensagem ou um compromisso em um suplemento do Outlook.</span><span class="sxs-lookup"><span data-stu-id="d003e-149">[item](Office.context.mailbox.item.md): Provides methods and properties for accessing a message or appointment in an Outlook add-in.</span></span>

<span data-ttu-id="d003e-150">[userProfile](Office.context.mailbox.userProfile.md): Fornece informações sobre o usuário em um suplemento do Outlook.</span><span class="sxs-lookup"><span data-stu-id="d003e-150">[userProfile](Office.context.mailbox.userProfile.md): Provides information about the user in an Outlook add-in.</span></span>

### <a name="members"></a><span data-ttu-id="d003e-151">Membros</span><span class="sxs-lookup"><span data-stu-id="d003e-151">Members</span></span>

#### <a name="ewsurl-string"></a><span data-ttu-id="d003e-152">ewsUrl :String</span><span class="sxs-lookup"><span data-stu-id="d003e-152">ewsUrl :String</span></span>

<span data-ttu-id="d003e-p102">Obtém a URL do ponto de extremidade dos Serviços Web do Exchange (EWS) para esta conta de email. Somente modo de leitura.</span><span class="sxs-lookup"><span data-stu-id="d003e-p102">Gets the URL of the Exchange Web Services (EWS) endpoint for this email account. Read mode only.</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-155">Este membro não é suportado no Outlook para iOS ou no Outlook para Android.</span><span class="sxs-lookup"><span data-stu-id="d003e-155">This member is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="d003e-p103">O valor `ewsUrl` pode ser usado por um serviço remoto para fazer chamadas do EWS à caixa de correio do usuário. Por exemplo, você pode criar um serviço remoto para [obter anexos do item selecionado](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span><span class="sxs-lookup"><span data-stu-id="d003e-p103">The `ewsUrl` value can be used by a remote service to make EWS calls to the user's mailbox. For example, you can create a remote service to [get attachments from the selected item](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span></span>

<span data-ttu-id="d003e-158">Seu aplicativo deve ter a permissão **ReadItem** especificada em seu manifesto para chamar o membro `ewsUrl` em modo de leitura.</span><span class="sxs-lookup"><span data-stu-id="d003e-158">Your app must have the **ReadItem** permission specified in its manifest to call the `ewsUrl` member in read mode.</span></span>

<span data-ttu-id="d003e-p104">No modo de composição, é preciso chamar o método [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) antes de poder usar o membro `ewsUrl`. Seu aplicativo deve ter permissões **ReadWriteItem** para chamar o método `saveAsync`.</span><span class="sxs-lookup"><span data-stu-id="d003e-p104">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method before you can use the `ewsUrl` member. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="type"></a><span data-ttu-id="d003e-161">Tipo:</span><span class="sxs-lookup"><span data-stu-id="d003e-161">Type:</span></span>

*   <span data-ttu-id="d003e-162">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="d003e-162">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="d003e-163">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-163">Requirements</span></span>

|<span data-ttu-id="d003e-164">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-164">Requirement</span></span>| <span data-ttu-id="d003e-165">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-165">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-166">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-166">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-167">1.0</span><span class="sxs-lookup"><span data-stu-id="d003e-167">1.0</span></span>|
|[<span data-ttu-id="d003e-168">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-168">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-169">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-169">ReadItem</span></span>|
|[<span data-ttu-id="d003e-170">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-170">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-171">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-171">Compose or read</span></span>|

#### <a name="resturl-string"></a><span data-ttu-id="d003e-172">restUrl :String</span><span class="sxs-lookup"><span data-stu-id="d003e-172">restUrl :String</span></span>

<span data-ttu-id="d003e-173">Obtém a URL do ponto de extremidade de REST para esta conta de email.</span><span class="sxs-lookup"><span data-stu-id="d003e-173">Gets the URL of the REST endpoint for this email account.</span></span>

<span data-ttu-id="d003e-174">O valor `restUrl` pode ser usado para fazer chamadas da [API REST](https://docs.microsoft.com/outlook/rest/) para a caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="d003e-174">The `restUrl` value can be used to make [REST API](https://docs.microsoft.com/outlook/rest/) calls to the user's mailbox.</span></span>

<span data-ttu-id="d003e-175">Seu aplicativo deve ter a permissão **ReadItem** especificada em seu manifesto para chamar o membro `restUrl` em modo de leitura.</span><span class="sxs-lookup"><span data-stu-id="d003e-175">Your app must have the **ReadItem** permission specified in its manifest to call the `restUrl` member in read mode.</span></span>

<span data-ttu-id="d003e-p105">No modo de composição, é preciso chamar o método [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) antes de poder usar o membro `restUrl`. Seu aplicativo deve ter permissões **ReadWriteItem** para chamar o método `saveAsync`.</span><span class="sxs-lookup"><span data-stu-id="d003e-p105">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method before you can use the `restUrl` member. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="type"></a><span data-ttu-id="d003e-178">Tipo:</span><span class="sxs-lookup"><span data-stu-id="d003e-178">Type:</span></span>

*   <span data-ttu-id="d003e-179">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="d003e-179">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="d003e-180">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-180">Requirements</span></span>

|<span data-ttu-id="d003e-181">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-181">Requirement</span></span>| <span data-ttu-id="d003e-182">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-182">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-183">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-183">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-184">1,5</span><span class="sxs-lookup"><span data-stu-id="d003e-184">1.5</span></span> |
|[<span data-ttu-id="d003e-185">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-185">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-186">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-186">ReadItem</span></span>|
|[<span data-ttu-id="d003e-187">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-187">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-188">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-188">Compose or read</span></span>|

### <a name="methods"></a><span data-ttu-id="d003e-189">Métodos</span><span class="sxs-lookup"><span data-stu-id="d003e-189">Methods</span></span>

####  <a name="addhandlerasynceventtype-handler-options-callback"></a><span data-ttu-id="d003e-190">addHandlerAsync(eventType, handler, [options], [callback])</span><span class="sxs-lookup"><span data-stu-id="d003e-190">addHandlerAsync(eventType, handler, [options], [callback])</span></span>

<span data-ttu-id="d003e-191">Adiciona um manipulador de eventos a um evento com suporte.</span><span class="sxs-lookup"><span data-stu-id="d003e-191">Adds an event handler for a supported event.</span></span>

<span data-ttu-id="d003e-192">Atualmente, os tipos de evento aceitos são `Office.EventType.ItemChanged` e `Office.EventType.OfficeThemeChanged`.</span><span class="sxs-lookup"><span data-stu-id="d003e-192">Currently, the supported event types are `Office.EventType.ItemChanged` and `Office.EventType.OfficeThemeChanged`.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-193">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-193">Parameters:</span></span>

| <span data-ttu-id="d003e-194">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-194">Name</span></span> | <span data-ttu-id="d003e-195">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-195">Type</span></span> | <span data-ttu-id="d003e-196">Atributos</span><span class="sxs-lookup"><span data-stu-id="d003e-196">Attributes</span></span> | <span data-ttu-id="d003e-197">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-197">Description</span></span> |
|---|---|---|---|
| `eventType` | [<span data-ttu-id="d003e-198">Office.EventType</span><span class="sxs-lookup"><span data-stu-id="d003e-198">Office.EventType</span></span>](office.md#eventtype-string) || <span data-ttu-id="d003e-199">O evento que deve invocar o manipulador.</span><span class="sxs-lookup"><span data-stu-id="d003e-199">The event that should invoke the handler.</span></span> |
| `handler` | <span data-ttu-id="d003e-200">Função</span><span class="sxs-lookup"><span data-stu-id="d003e-200">Function</span></span> || <span data-ttu-id="d003e-p106">A função para manipular o evento. A função deve aceitar um parâmetro exclusivo, que é um objeto literal. A propriedade `type` no parâmetro corresponderá ao parâmetro `eventType` passado para `addHandlerAsync`.</span><span class="sxs-lookup"><span data-stu-id="d003e-p106">The function to handle the event. The function must accept a single parameter, which is an object literal. The `type` property on the parameter will match the `eventType` parameter passed to `addHandlerAsync`.</span></span> |
| `options` | <span data-ttu-id="d003e-204">Objeto</span><span class="sxs-lookup"><span data-stu-id="d003e-204">Object</span></span> | <span data-ttu-id="d003e-205">&lt;opcional&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-205">&lt;optional&gt;</span></span> | <span data-ttu-id="d003e-206">Um objeto literal que contém uma ou mais das propriedades a seguir.</span><span class="sxs-lookup"><span data-stu-id="d003e-206">An object literal that contains one or more of the following properties.</span></span> |
| `options.asyncContext` | <span data-ttu-id="d003e-207">Objeto</span><span class="sxs-lookup"><span data-stu-id="d003e-207">Object</span></span> | <span data-ttu-id="d003e-208">&lt;opcional&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-208">&lt;optional&gt;</span></span> | <span data-ttu-id="d003e-209">Os desenvolvedores podem fornecer qualquer objeto que desejarem acessar no método de retorno de chamada.</span><span class="sxs-lookup"><span data-stu-id="d003e-209">Developers can provide any object they wish to access in the callback method.</span></span> |
| `callback` | <span data-ttu-id="d003e-210">function</span><span class="sxs-lookup"><span data-stu-id="d003e-210">function</span></span>| <span data-ttu-id="d003e-211">&lt;opcional&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-211">&lt;optional&gt;</span></span>|<span data-ttu-id="d003e-212">Quando o método for concluído, a função passada ao parâmetro `callback` é chamada com um único parâmetro, `asyncResult`, que é um objeto [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="d003e-212">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-213">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-213">Requirements</span></span>

|<span data-ttu-id="d003e-214">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-214">Requirement</span></span>| <span data-ttu-id="d003e-215">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-215">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-216">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-216">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-217">1,5</span><span class="sxs-lookup"><span data-stu-id="d003e-217">1.5</span></span> |
|[<span data-ttu-id="d003e-218">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-218">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-219">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-219">ReadItem</span></span> |
|[<span data-ttu-id="d003e-220">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-220">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-221">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-221">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="d003e-222">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-222">Example</span></span>

```
Office.initialize = function (reason) {
  $(document).ready(function () {
    Office.context.mailbox.addHandlerAsync(Office.EventType.ItemChanged, loadNewItem, function (result) {
      if (result.status === Office.AsyncResultStatus.Failed) {
        // Handle error
      }
    });
  });
};

function loadNewItem(eventArgs) {
  // Load the properties of the newly selected item
  loadProps(Office.context.mailbox.item);
};
```

####  <a name="converttoewsiditemid-restversion--string"></a><span data-ttu-id="d003e-223">convertToEwsId(itemId, restVersion) → {String}</span><span class="sxs-lookup"><span data-stu-id="d003e-223">convertToEwsId(itemId, restVersion) → {String}</span></span>

<span data-ttu-id="d003e-224">Converte uma ID de item formatada para REST em formato EWS.</span><span class="sxs-lookup"><span data-stu-id="d003e-224">Converts an item ID formatted for REST into EWS format.</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-225">Esse método não é suportado no Outlook para iOS ou no Outlook para Android.</span><span class="sxs-lookup"><span data-stu-id="d003e-225">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="d003e-p107">IDs de itens recuperadas por meio de uma API REST (como a [API do Email do Outlook](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) ou o [Microsoft Graph](http://graph.microsoft.io/)) usam um formato diferente daquele usado pelos Serviços Web do Exchange (EWS). O método `convertToEwsId` converte uma ID formatada como REST para o formato adequado para EWS.</span><span class="sxs-lookup"><span data-stu-id="d003e-p107">Item IDs retrieved via a REST API (such as the [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) or the [Microsoft Graph](http://graph.microsoft.io/)) use a different format than the format used by Exchange Web Services (EWS). The `convertToEwsId` method converts a REST-formatted ID into the proper format for EWS.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-228">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-228">Parameters:</span></span>

|<span data-ttu-id="d003e-229">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-229">Name</span></span>| <span data-ttu-id="d003e-230">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-230">Type</span></span>| <span data-ttu-id="d003e-231">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-231">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="d003e-232">String</span><span class="sxs-lookup"><span data-stu-id="d003e-232">String</span></span>|<span data-ttu-id="d003e-233">Uma ID de item formatada para APIs REST do Outlook</span><span class="sxs-lookup"><span data-stu-id="d003e-233">An item ID formatted for the Outlook REST APIs</span></span>|
|`restVersion`| [<span data-ttu-id="d003e-234">Office.MailboxEnums.RestVersion</span><span class="sxs-lookup"><span data-stu-id="d003e-234">Office.MailboxEnums.RestVersion</span></span>](/javascript/api/outlook/office.mailboxenums.restversion)|<span data-ttu-id="d003e-235">Um valor que indica a versão da API REST do Outlook usada para recuperar a ID do item.</span><span class="sxs-lookup"><span data-stu-id="d003e-235">A value indicating the version of the Outlook REST API used to retrieve the item ID.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-236">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-236">Requirements</span></span>

|<span data-ttu-id="d003e-237">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-237">Requirement</span></span>| <span data-ttu-id="d003e-238">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-238">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-239">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-239">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-240">1.3</span><span class="sxs-lookup"><span data-stu-id="d003e-240">1.3</span></span>|
|[<span data-ttu-id="d003e-241">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-241">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-242">Restrito</span><span class="sxs-lookup"><span data-stu-id="d003e-242">Restricted</span></span>|
|[<span data-ttu-id="d003e-243">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-243">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-244">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-244">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="d003e-245">Retorna:</span><span class="sxs-lookup"><span data-stu-id="d003e-245">Returns:</span></span>

<span data-ttu-id="d003e-246">Tipo: String</span><span class="sxs-lookup"><span data-stu-id="d003e-246">Type: String</span></span>

##### <a name="example"></a><span data-ttu-id="d003e-247">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-247">Example</span></span>

```
// Get an item's ID from a REST API
var restId = 'AAMkAGVlOTZjNTM3LW...';

// Treat restId as coming from the v2.0 version of the
// Outlook Mail API
var ewsId = Office.context.mailbox.convertToEwsId(restId, Office.MailboxEnums.RestVersion.v2_0);
```

####  <a name="converttolocalclienttimetimevalue--localclienttimejavascriptapioutlookofficelocalclienttime"></a><span data-ttu-id="d003e-248">convertToLocalClientTime(timeValue) → {[LocalClientTime](/javascript/api/outlook/office.LocalClientTime)}</span><span class="sxs-lookup"><span data-stu-id="d003e-248">convertToLocalClientTime(timeValue) → {[LocalClientTime](/javascript/api/outlook/office.LocalClientTime)}</span></span>

<span data-ttu-id="d003e-249">Obtém um dicionário contendo informações de hora em tempo local do cliente.</span><span class="sxs-lookup"><span data-stu-id="d003e-249">Gets a dictionary containing time information in local client time.</span></span>

<span data-ttu-id="d003e-p108">As datas e horas usadas por um aplicativo de email para o Outlook ou o Outlook Web App podem usar fusos horários diferentes. O Outlook usa o fuso horário do computador cliente; o Outlook Web App usa o fuso horário definido na Centro de administração do Exchange (EAC). Você deve lidar com valores de data e hora para que os valores exibidos na interface do usuário sejam sempre consistentes com o fuso horário que o usuário espera.</span><span class="sxs-lookup"><span data-stu-id="d003e-p108">The dates and times used by a mail app for Outlook or Outlook Web App can use different time zones. Outlook uses the client computer time zone; Outlook Web App uses the time zone set on the Exchange Admin Center (EAC). You should handle date and time values so that the values you display on the user interface are always consistent with the time zone that the user expects.</span></span>

<span data-ttu-id="d003e-p109">Se o aplicativo de email estiver sendo executado no Outlook, o método `convertToLocalClientTime` retornará um objeto de dicionário com os valores definidos para o fuso horário do computador do cliente. Se o aplicativo de email estiver sendo executado no Outlook Web App, o método `convertToLocalClientTime` retornará um objeto de dicionário com os valores definidos para o fuso horário especificado no EAC.</span><span class="sxs-lookup"><span data-stu-id="d003e-p109">If the mail app is running in Outlook, the `convertToLocalClientTime` method will return a dictionary object with the values set to the client computer time zone. If the mail app is running in Outlook Web App, the `convertToLocalClientTime` method will return a dictionary object with the values set to the time zone specified in the EAC.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-255">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-255">Parameters:</span></span>

|<span data-ttu-id="d003e-256">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-256">Name</span></span>| <span data-ttu-id="d003e-257">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-257">Type</span></span>| <span data-ttu-id="d003e-258">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-258">Description</span></span>|
|---|---|---|
|`timeValue`| <span data-ttu-id="d003e-259">Data</span><span class="sxs-lookup"><span data-stu-id="d003e-259">Date</span></span>|<span data-ttu-id="d003e-260">Um objeto Date</span><span class="sxs-lookup"><span data-stu-id="d003e-260">A Date object</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-261">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-261">Requirements</span></span>

|<span data-ttu-id="d003e-262">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-262">Requirement</span></span>| <span data-ttu-id="d003e-263">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-263">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-264">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-264">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-265">1.0</span><span class="sxs-lookup"><span data-stu-id="d003e-265">1.0</span></span>|
|[<span data-ttu-id="d003e-266">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-266">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-267">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-267">ReadItem</span></span>|
|[<span data-ttu-id="d003e-268">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-268">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-269">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-269">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="d003e-270">Retorna:</span><span class="sxs-lookup"><span data-stu-id="d003e-270">Returns:</span></span>

<span data-ttu-id="d003e-271">Tipo: [LocalClientTime](/javascript/api/outlook/office.LocalClientTime)</span><span class="sxs-lookup"><span data-stu-id="d003e-271">Type: [LocalClientTime](/javascript/api/outlook/office.LocalClientTime)</span></span>

####  <a name="converttorestiditemid-restversion--string"></a><span data-ttu-id="d003e-272">convertToRestId(itemId, restVersion) → {String}</span><span class="sxs-lookup"><span data-stu-id="d003e-272">convertToRestId(itemId, restVersion) → {String}</span></span>

<span data-ttu-id="d003e-273">Converte uma ID de item formatada para EWS em formato REST.</span><span class="sxs-lookup"><span data-stu-id="d003e-273">Converts an item ID formatted for EWS into REST format.</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-274">Esse método não é suportado no Outlook para iOS ou no Outlook para Android.</span><span class="sxs-lookup"><span data-stu-id="d003e-274">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="d003e-p110">IDs de itens recuperadas por EWS ou pela propriedade `itemId` usam um formato diferente daquele usado por APIs REST (como a [API do Email do Outlook](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) ou o [Microsoft Graph](http://graph.microsoft.io/)). O método `convertToRestId` converte uma ID formatada como EWS para o formato adequado para REST.</span><span class="sxs-lookup"><span data-stu-id="d003e-p110">Item IDs retrieved via EWS or via the `itemId` property use a different format than the format used by REST APIs (such as the [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) or the [Microsoft Graph](http://graph.microsoft.io/)). The `convertToRestId` method converts an EWS-formatted ID into the proper format for REST.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-277">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-277">Parameters:</span></span>

|<span data-ttu-id="d003e-278">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-278">Name</span></span>| <span data-ttu-id="d003e-279">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-279">Type</span></span>| <span data-ttu-id="d003e-280">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-280">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="d003e-281">String</span><span class="sxs-lookup"><span data-stu-id="d003e-281">String</span></span>|<span data-ttu-id="d003e-282">Uma ID de item formatada para os Serviços Web do Exchange (EWS)</span><span class="sxs-lookup"><span data-stu-id="d003e-282">An item ID formatted for Exchange Web Services (EWS)</span></span>|
|`restVersion`| [<span data-ttu-id="d003e-283">Office.MailboxEnums.RestVersion</span><span class="sxs-lookup"><span data-stu-id="d003e-283">Office.MailboxEnums.RestVersion</span></span>](/javascript/api/outlook/office.mailboxenums.restversion)|<span data-ttu-id="d003e-284">Um valor que indica a versão da API REST do Outlook com a qual a ID convertida será usada.</span><span class="sxs-lookup"><span data-stu-id="d003e-284">A value indicating the version of the Outlook REST API that the converted ID will be used with.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-285">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-285">Requirements</span></span>

|<span data-ttu-id="d003e-286">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-286">Requirement</span></span>| <span data-ttu-id="d003e-287">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-287">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-288">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-288">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-289">1.3</span><span class="sxs-lookup"><span data-stu-id="d003e-289">1.3</span></span>|
|[<span data-ttu-id="d003e-290">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-290">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-291">Restrito</span><span class="sxs-lookup"><span data-stu-id="d003e-291">Restricted</span></span>|
|[<span data-ttu-id="d003e-292">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-292">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-293">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-293">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="d003e-294">Retorna:</span><span class="sxs-lookup"><span data-stu-id="d003e-294">Returns:</span></span>

<span data-ttu-id="d003e-295">Tipo: String</span><span class="sxs-lookup"><span data-stu-id="d003e-295">Type: String</span></span>

##### <a name="example"></a><span data-ttu-id="d003e-296">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-296">Example</span></span>

```
// Get the currently selected item's ID
var ewsId = Office.context.mailbox.item.itemId;

// Convert to a REST ID for the v2.0 version of the
// Outlook Mail API
var restId = Office.context.mailbox.convertToRestId(ewsId, Office.MailboxEnums.RestVersion.v2_0);
```

####  <a name="converttoutcclienttimeinput--date"></a><span data-ttu-id="d003e-297">convertToUtcClientTime(input) → {Date}</span><span class="sxs-lookup"><span data-stu-id="d003e-297">convertToUtcClientTime(input) → {Date}</span></span>

<span data-ttu-id="d003e-298">Obtém um objeto Date de um dicionário contendo as informações de hora.</span><span class="sxs-lookup"><span data-stu-id="d003e-298">Gets a Date object from a dictionary containing time information.</span></span>

<span data-ttu-id="d003e-299">O método `convertToUtcClientTime` converte um dicionário que contém uma data e hora locais para um objeto Date com os valores corretos para a data e hora locais.</span><span class="sxs-lookup"><span data-stu-id="d003e-299">The `convertToUtcClientTime` method converts a dictionary containing a local date and time to a Date object with the correct values for the local date and time.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-300">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-300">Parameters:</span></span>

|<span data-ttu-id="d003e-301">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-301">Name</span></span>| <span data-ttu-id="d003e-302">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-302">Type</span></span>| <span data-ttu-id="d003e-303">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-303">Description</span></span>|
|---|---|---|
|`input`| [<span data-ttu-id="d003e-304">LocalClientTime</span><span class="sxs-lookup"><span data-stu-id="d003e-304">LocalClientTime</span></span>](/javascript/api/outlook/office.LocalClientTime)|<span data-ttu-id="d003e-305">O valor de hora local a converter.</span><span class="sxs-lookup"><span data-stu-id="d003e-305">The local time value to convert.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-306">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-306">Requirements</span></span>

|<span data-ttu-id="d003e-307">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-307">Requirement</span></span>| <span data-ttu-id="d003e-308">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-308">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-309">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-309">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-310">1.0</span><span class="sxs-lookup"><span data-stu-id="d003e-310">1.0</span></span>|
|[<span data-ttu-id="d003e-311">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-311">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-312">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-312">ReadItem</span></span>|
|[<span data-ttu-id="d003e-313">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-313">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-314">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-314">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="d003e-315">Retorna:</span><span class="sxs-lookup"><span data-stu-id="d003e-315">Returns:</span></span>

<span data-ttu-id="d003e-316">Um objeto Date com a hora expressa em UTC.</span><span class="sxs-lookup"><span data-stu-id="d003e-316">A Date object with the time expressed in UTC.</span></span>

<dl class="param-type"><span data-ttu-id="d003e-317">

<dt>Type</dt>

</span><span class="sxs-lookup"><span data-stu-id="d003e-317">

<dt>Type</dt>

</span></span><dd><span data-ttu-id="d003e-318">Date</span><span class="sxs-lookup"><span data-stu-id="d003e-318">Date</span></span></dd>

</dl>

####  <a name="displayappointmentformitemid"></a><span data-ttu-id="d003e-319">displayAppointmentForm(itemId)</span><span class="sxs-lookup"><span data-stu-id="d003e-319">displayAppointmentForm(itemId)</span></span>

<span data-ttu-id="d003e-320">Exibe um compromisso de calendário existente.</span><span class="sxs-lookup"><span data-stu-id="d003e-320">Displays an existing calendar appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-321">Esse método não é suportado no Outlook para iOS ou no Outlook para Android.</span><span class="sxs-lookup"><span data-stu-id="d003e-321">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="d003e-322">O método `displayAppointmentForm` abre um compromisso de calendário existente em uma nova janela na área de trabalho ou em uma caixa de diálogo em dispositivos móveis.</span><span class="sxs-lookup"><span data-stu-id="d003e-322">The `displayAppointmentForm` method opens an existing calendar appointment in a new window on the desktop or in a dialog box on mobile devices.</span></span>

<span data-ttu-id="d003e-p111">No Outlook para Mac, você pode usar esse método para exibir um único compromisso que não faz parte de uma série recorrente, ou o compromisso mestre de uma série recorrente, mas não pode exibir uma instância da série. Isso ocorre porque no Outlook para Mac você não pode acessar as propriedades (incluindo a ID do item) das instâncias de uma série recorrente.</span><span class="sxs-lookup"><span data-stu-id="d003e-p111">In Outlook for Mac, you can use this method to display a single appointment that is not part of a recurring series, or the master appointment of a recurring series, but you cannot display an instance of the series. This is because in Outlook for Mac, you cannot access the properties (including the item ID) of instances of a recurring series.</span></span>

<span data-ttu-id="d003e-325">No Outlook Web App, este método abre o formulário especificado somente se o corpo do formulário for menor que ou igual ao número de caracteres de 32 KB.</span><span class="sxs-lookup"><span data-stu-id="d003e-325">In Outlook Web App, this method opens the specified form only if the body of the form is less than or equal to 32KB number of characters.</span></span>

<span data-ttu-id="d003e-326">Se o identificador do item especificado não identificar um compromisso existente, um painel em branco abre no dispositivo ou no computador cliente e nenhuma mensagem de erro será exibida.</span><span class="sxs-lookup"><span data-stu-id="d003e-326">If the specified item identifier does not identify an existing appointment, a blank pane opens on the client computer or device, and no error message will be returned.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-327">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-327">Parameters:</span></span>

|<span data-ttu-id="d003e-328">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-328">Name</span></span>| <span data-ttu-id="d003e-329">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-329">Type</span></span>| <span data-ttu-id="d003e-330">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-330">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="d003e-331">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="d003e-331">String</span></span>|<span data-ttu-id="d003e-332">O identificador dos Serviços Web do Exchange (EWS) para um compromisso de calendário existente.</span><span class="sxs-lookup"><span data-stu-id="d003e-332">The Exchange Web Services (EWS) identifier for an existing calendar appointment.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-333">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-333">Requirements</span></span>

|<span data-ttu-id="d003e-334">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-334">Requirement</span></span>| <span data-ttu-id="d003e-335">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-335">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-336">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-336">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-337">1.0</span><span class="sxs-lookup"><span data-stu-id="d003e-337">1.0</span></span>|
|[<span data-ttu-id="d003e-338">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-338">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-339">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-339">ReadItem</span></span>|
|[<span data-ttu-id="d003e-340">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-340">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-341">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-341">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="d003e-342">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-342">Example</span></span>

```
Office.context.mailbox.displayAppointmentForm(appointmentId);
```

####  <a name="displaymessageformitemid"></a><span data-ttu-id="d003e-343">displayMessageForm(itemId)</span><span class="sxs-lookup"><span data-stu-id="d003e-343">displayMessageForm(itemId)</span></span>

<span data-ttu-id="d003e-344">Exibe uma mensagem existente.</span><span class="sxs-lookup"><span data-stu-id="d003e-344">Displays an existing message.</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-345">Esse método não é suportado no Outlook para iOS ou no Outlook para Android.</span><span class="sxs-lookup"><span data-stu-id="d003e-345">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="d003e-346">O método `displayMessageForm` abre uma mensagem existente em uma nova janela na área de trabalho ou em uma caixa de diálogo em dispositivos móveis.</span><span class="sxs-lookup"><span data-stu-id="d003e-346">The `displayMessageForm` method opens an existing message in a new window on the desktop or in a dialog box on mobile devices.</span></span>

<span data-ttu-id="d003e-347">No Outlook Web App, este método abre o formulário especificado somente se o corpo do formulário for menor que ou igual ao número de caracteres de 32 KB.</span><span class="sxs-lookup"><span data-stu-id="d003e-347">In Outlook Web App, this method opens the specified form only if the body of the form is less than or equal to 32 KB number of characters.</span></span>

<span data-ttu-id="d003e-348">Se o identificador do item especificado não identificar uma mensagem existente, não será exibida mensagem no computador cliente e nenhuma mensagem de erro será retornada.</span><span class="sxs-lookup"><span data-stu-id="d003e-348">If the specified item identifier does not identify an existing message, no message will be displayed on the client computer, and no error message will be returned.</span></span>

<span data-ttu-id="d003e-p112">Não use o método `displayMessageForm` com um `itemId` que representa um compromisso. Use o método `displayAppointmentForm` para exibir um compromisso existente e `displayNewAppointmentForm` para exibir um formulário e criar um novo compromisso.</span><span class="sxs-lookup"><span data-stu-id="d003e-p112">Do not use the `displayMessageForm` with an `itemId` that represents an appointment. Use the `displayAppointmentForm` method to display an existing appointment, and `displayNewAppointmentForm` to display a form to create a new appointment.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-351">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-351">Parameters:</span></span>

|<span data-ttu-id="d003e-352">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-352">Name</span></span>| <span data-ttu-id="d003e-353">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-353">Type</span></span>| <span data-ttu-id="d003e-354">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-354">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="d003e-355">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="d003e-355">String</span></span>|<span data-ttu-id="d003e-356">O identificador dos Serviços Web do Exchange (EWS) para uma mensagem existente.</span><span class="sxs-lookup"><span data-stu-id="d003e-356">The Exchange Web Services (EWS) identifier for an existing message.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-357">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-357">Requirements</span></span>

|<span data-ttu-id="d003e-358">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-358">Requirement</span></span>| <span data-ttu-id="d003e-359">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-359">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-360">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-360">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-361">1.0</span><span class="sxs-lookup"><span data-stu-id="d003e-361">1.0</span></span>|
|[<span data-ttu-id="d003e-362">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-362">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-363">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-363">ReadItem</span></span>|
|[<span data-ttu-id="d003e-364">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-364">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-365">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-365">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="d003e-366">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-366">Example</span></span>

```
Office.context.mailbox.displayMessageForm(messageId);
```

#### <a name="displaynewappointmentformparameters"></a><span data-ttu-id="d003e-367">displayNewAppointmentForm(parameters)</span><span class="sxs-lookup"><span data-stu-id="d003e-367">displayNewAppointmentForm(parameters)</span></span>

<span data-ttu-id="d003e-368">Exibe um formulário para criar um novo compromisso no calendário.</span><span class="sxs-lookup"><span data-stu-id="d003e-368">Displays a form for creating a new calendar appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-369">Esse método não é suportado no Outlook para iOS ou no Outlook para Android.</span><span class="sxs-lookup"><span data-stu-id="d003e-369">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="d003e-p113">O método `displayNewAppointmentForm` abre um formulário que permite ao usuário criar um novo compromisso ou reunião. Se os parâmetros forem especificados, os campos de formulário do compromisso serão preenchidos automaticamente com o conteúdo dos parâmetros.</span><span class="sxs-lookup"><span data-stu-id="d003e-p113">The `displayNewAppointmentForm` method opens a form that enables the user to create a new appointment or meeting. If parameters are specified, the appointment form fields are automatically populated with the contents of the parameters.</span></span>

<span data-ttu-id="d003e-p114">No Outlook Web App e no OWA para Dispositivos, este método sempre exibe um formulário com um campo de participantes. Se você não especificar quaisquer participantes como argumentos de entrada, o método exibe um formulário com um botão **Salvar**. Se você especificar participantes, o formulário inclui os participantes e um botão **Enviar**.</span><span class="sxs-lookup"><span data-stu-id="d003e-p114">In Outlook Web App and OWA for Devices, this method always displays a form with an attendees field. If you do not specify any attendees as input arguments, the method displays a form with a **Save** button. If you have specified attendees, the form would include the attendees and a **Send** button.</span></span>

<span data-ttu-id="d003e-p115">No cliente avançado do Outlook e no Outlook RT, se você especificar quaisquer participantes ou recursos nos parâmetros `requiredAttendees`, `optionalAttendees`ou `resources`, este método exibirá um formulário de reunião com um botão **Enviar**. Se você não especificar destinatários, este método exibirá um formulário de compromisso com um botão **Salvar e Fechar**.</span><span class="sxs-lookup"><span data-stu-id="d003e-p115">In the Outlook rich client and Outlook RT, if you specify any attendees or resources in the `requiredAttendees`, `optionalAttendees`, or `resources` parameter, this method displays a meeting form with a **Send** button. If you don't specify any recipients, this method displays an appointment form with a **Save & Close** button.</span></span>

<span data-ttu-id="d003e-377">Se qualquer dos parâmetros exceder os limites de tamanho especificados, ou se um nome de parâmetro desconhecido for especificado, ocorre uma exceção.</span><span class="sxs-lookup"><span data-stu-id="d003e-377">If any of the parameters exceed the specified size limits, or if an unknown parameter name is specified, an exception is thrown.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-378">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-378">Parameters:</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-379">Todos os parâmetros são opcionais.</span><span class="sxs-lookup"><span data-stu-id="d003e-379">All parameters are optional.</span></span>

|<span data-ttu-id="d003e-380">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-380">Name</span></span>| <span data-ttu-id="d003e-381">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-381">Type</span></span>| <span data-ttu-id="d003e-382">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-382">Description</span></span>|
|---|---|---|
| `parameters` | <span data-ttu-id="d003e-383">Object</span><span class="sxs-lookup"><span data-stu-id="d003e-383">Object</span></span> | <span data-ttu-id="d003e-384">Um dicionário de parâmetros que descreve o novo compromisso.</span><span class="sxs-lookup"><span data-stu-id="d003e-384">A dictionary of parameters describing the new appointment.</span></span> |
| `parameters.requiredAttendees` | <span data-ttu-id="d003e-385">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-385">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="d003e-p116">Uma matriz de cadeias de caracteres que contém os endereços de email ou uma matriz contendo um objeto `EmailAddressDetails` para cada um dos participantes obrigatórios do compromisso. A matriz está limitada a um máximo de 100 entradas.</span><span class="sxs-lookup"><span data-stu-id="d003e-p116">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the required attendees for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.optionalAttendees` | <span data-ttu-id="d003e-388">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-388">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="d003e-p117">Uma matriz de cadeias de caracteres que contém os endereços de email ou uma matriz contendo um objeto `EmailAddressDetails` para cada um dos participantes opcionais do compromisso. A matriz está limitada a um máximo de 100 entradas.</span><span class="sxs-lookup"><span data-stu-id="d003e-p117">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the optional attendees for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.start` | <span data-ttu-id="d003e-391">Data</span><span class="sxs-lookup"><span data-stu-id="d003e-391">Date</span></span> | <span data-ttu-id="d003e-392">Um objeto `Date` que especifica a data e a hora de início do compromisso.</span><span class="sxs-lookup"><span data-stu-id="d003e-392">A `Date` object specifying the start date and time of the appointment.</span></span> |
| `parameters.end` | <span data-ttu-id="d003e-393">Data</span><span class="sxs-lookup"><span data-stu-id="d003e-393">Date</span></span> | <span data-ttu-id="d003e-394">Um objeto `Date` que especifica a data e a hora de término do compromisso.</span><span class="sxs-lookup"><span data-stu-id="d003e-394">A `Date` object specifying the end date and time of the appointment.</span></span> |
| `parameters.location` | <span data-ttu-id="d003e-395">String</span><span class="sxs-lookup"><span data-stu-id="d003e-395">String</span></span> | <span data-ttu-id="d003e-p118">Uma cadeia de caracteres que contém o local do compromisso. A cadeia de caracteres está limitada a um máximo de 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="d003e-p118">A string containing the location of the appointment. The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.resources` | <span data-ttu-id="d003e-398">Array.&lt;String&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-398">Array.&lt;String&gt;</span></span> | <span data-ttu-id="d003e-p119">Uma matriz de cadeias de caracteres que contém os recursos necessários para o compromisso. A matriz está limitada a um máximo de 100 entradas.</span><span class="sxs-lookup"><span data-stu-id="d003e-p119">An array of strings containing the resources required for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.subject` | <span data-ttu-id="d003e-401">String</span><span class="sxs-lookup"><span data-stu-id="d003e-401">String</span></span> | <span data-ttu-id="d003e-p120">Uma cadeia de caracteres que contém o assunto do compromisso. A cadeia de caracteres está limitada a um máximo de 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="d003e-p120">A string containing the subject of the appointment. The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.body` | <span data-ttu-id="d003e-404">String</span><span class="sxs-lookup"><span data-stu-id="d003e-404">String</span></span> | <span data-ttu-id="d003e-p121">O corpo do compromisso. O conteúdo do corpo está limitado a um tamanho máximo de 32 KB.</span><span class="sxs-lookup"><span data-stu-id="d003e-p121">The body of the appointment. The body content is limited to a maximum size of 32 KB.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="d003e-407">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-407">Requirements</span></span>

|<span data-ttu-id="d003e-408">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-408">Requirement</span></span>| <span data-ttu-id="d003e-409">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-409">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-410">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-410">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-411">1.0</span><span class="sxs-lookup"><span data-stu-id="d003e-411">1.0</span></span>|
|[<span data-ttu-id="d003e-412">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-412">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-413">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-413">ReadItem</span></span>|
|[<span data-ttu-id="d003e-414">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-414">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-415">Leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-415">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="d003e-416">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-416">Example</span></span>

```
var start = new Date();
var end = new Date();
end.setHours(start.getHours() + 1);

Office.context.mailbox.displayNewAppointmentForm(
  {
    requiredAttendees: ['bob@contoso.com'],
    optionalAttendees: ['sam@contoso.com'],
    start: start,
    end: end,
    location: 'Home',
    resources: ['projector@contoso.com'],
    subject: 'meeting',
    body: 'Hello World!'
  });
```

#### <a name="displaynewmessageformparameters"></a><span data-ttu-id="d003e-417">displayNewMessageForm(parameters)</span><span class="sxs-lookup"><span data-stu-id="d003e-417">displayNewMessageForm(parameters)</span></span>

<span data-ttu-id="d003e-418">Exibe um formulário para criar uma nova mensagem.</span><span class="sxs-lookup"><span data-stu-id="d003e-418">Displays a form for creating a new message.</span></span>

<span data-ttu-id="d003e-419">O método `displayNewMessageForm` abre um formulário que permite ao usuário criar uma nova mensagem.</span><span class="sxs-lookup"><span data-stu-id="d003e-419">The `displayNewMessageForm` method opens a form that enables the user to create a new message.</span></span> <span data-ttu-id="d003e-420">Quando os parâmetros são especificados, os campos do formulário de mensagem são preenchidos automaticamente com o conteúdo dos parâmetros.</span><span class="sxs-lookup"><span data-stu-id="d003e-420">If parameters are specified, the message form fields are automatically populated with the contents of the parameters.</span></span>

<span data-ttu-id="d003e-421">Se qualquer dos parâmetros exceder os limites de tamanho especificados, ou se um nome de parâmetro desconhecido for especificado, ocorre uma exceção.</span><span class="sxs-lookup"><span data-stu-id="d003e-421">If any of the parameters exceed the specified size limits, or if an unknown parameter name is specified, an exception is thrown.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-422">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-422">Parameters:</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-423">Todos os parâmetros são opcionais.</span><span class="sxs-lookup"><span data-stu-id="d003e-423">All parameters are optional.</span></span>

|<span data-ttu-id="d003e-424">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-424">Name</span></span>| <span data-ttu-id="d003e-425">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-425">Type</span></span>| <span data-ttu-id="d003e-426">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-426">Description</span></span>|
|---|---|---|
| `parameters` | <span data-ttu-id="d003e-427">Objeto</span><span class="sxs-lookup"><span data-stu-id="d003e-427">Object</span></span> | <span data-ttu-id="d003e-428">Um dicionário de parâmetros que descreve a nova mensagem.</span><span class="sxs-lookup"><span data-stu-id="d003e-428">A dictionary of parameters describing the new message.</span></span> |
| `parameters.toRecipients` | <span data-ttu-id="d003e-429">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-429">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="d003e-430">Uma matriz de cadeias de caracteres que contém os endereços de email ou uma matriz que contém um objeto `EmailAddressDetails` para cada um dos destinatários na linha Para.</span><span class="sxs-lookup"><span data-stu-id="d003e-430">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the recipients on the To line.</span></span> <span data-ttu-id="d003e-431">A matriz está limitada a um máximo de 100 entradas.</span><span class="sxs-lookup"><span data-stu-id="d003e-431">The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.ccRecipients` | <span data-ttu-id="d003e-432">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-432">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="d003e-433">Uma matriz de cadeias de caracteres que contém os endereços de email ou uma matriz que contém um objeto `EmailAddressDetails` para cada um dos destinatários na linha Cc.</span><span class="sxs-lookup"><span data-stu-id="d003e-433">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the recipients on the Cc line.</span></span> <span data-ttu-id="d003e-434">A matriz está limitada a um máximo de 100 entradas.</span><span class="sxs-lookup"><span data-stu-id="d003e-434">The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.bccRecipients` | <span data-ttu-id="d003e-435">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-435">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="d003e-436">Uma matriz de cadeias de caracteres que contém os endereços de email ou uma matriz que contém um objeto `EmailAddressDetails` para cada um dos destinatários na linha Cco.</span><span class="sxs-lookup"><span data-stu-id="d003e-436">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the recipients on the Bcc line.</span></span> <span data-ttu-id="d003e-437">A matriz está limitada a um máximo de 100 entradas.</span><span class="sxs-lookup"><span data-stu-id="d003e-437">The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.subject` | <span data-ttu-id="d003e-438">String</span><span class="sxs-lookup"><span data-stu-id="d003e-438">String</span></span> | <span data-ttu-id="d003e-439">Uma cadeia de caracteres que contém o assunto da mensagem.</span><span class="sxs-lookup"><span data-stu-id="d003e-439">A string containing the subject of the message.</span></span> <span data-ttu-id="d003e-440">A cadeia de caracteres está limitada a um máximo de 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="d003e-440">The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.htmlBody` | <span data-ttu-id="d003e-441">String</span><span class="sxs-lookup"><span data-stu-id="d003e-441">String</span></span> | <span data-ttu-id="d003e-442">O corpo HTML da mensagem.</span><span class="sxs-lookup"><span data-stu-id="d003e-442">The HTML body of the message.</span></span> <span data-ttu-id="d003e-443">O conteúdo do corpo está limitado a um tamanho máximo de 32 KB.</span><span class="sxs-lookup"><span data-stu-id="d003e-443">The body content is limited to a maximum size of 32 KB.</span></span> |
| `parameters.attachments` | <span data-ttu-id="d003e-444">Array.&lt;Object&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-444">Array.&lt;Object&gt;</span></span> | <span data-ttu-id="d003e-445">Uma matriz de objetos JSON que são anexos de arquivo ou item.</span><span class="sxs-lookup"><span data-stu-id="d003e-445">An array of JSON objects that are either file or item attachments.</span></span> |
| `parameters.attachments.type` | <span data-ttu-id="d003e-446">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="d003e-446">String</span></span> | <span data-ttu-id="d003e-p128">Indica o tipo de anexo. Deve ser `file` para um anexo de arquivo ou `item` para um anexo de item.</span><span class="sxs-lookup"><span data-stu-id="d003e-p128">Indicates the type of attachment. Must be `file` for a file attachment or `item` for an item attachment.</span></span> |
| `parameters.attachments.name` | <span data-ttu-id="d003e-449">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="d003e-449">String</span></span> | <span data-ttu-id="d003e-450">Uma cadeia de caracteres que contém o nome do anexo, até 255 caracteres de comprimento.</span><span class="sxs-lookup"><span data-stu-id="d003e-450">A string that contains the name of the attachment, up to 255 characters in length.</span></span>|
| `parameters.attachments.url` | <span data-ttu-id="d003e-451">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="d003e-451">String</span></span> | <span data-ttu-id="d003e-p129">Usado somente se `type` estiver definido como `file`. O URI do local para o arquivo.</span><span class="sxs-lookup"><span data-stu-id="d003e-p129">Only used if `type` is set to `file`. The URI of the location for the file.</span></span> |
| `parameters.attachments.isInline` | <span data-ttu-id="d003e-454">Boolean</span><span class="sxs-lookup"><span data-stu-id="d003e-454">Boolean</span></span> | <span data-ttu-id="d003e-p130">Usado somente se `type` estiver definido como `file`. Se for `true`, indicará que o anexo será mostrado embutido no corpo da mensagem e não deverá ser exibido na lista de anexos.</span><span class="sxs-lookup"><span data-stu-id="d003e-p130">Only used if `type` is set to `file`. If `true`, indicates that the attachment will be shown inline in the message body, and should not be displayed in the attachment list.</span></span> |
| `parameters.attachments.itemId` | <span data-ttu-id="d003e-457">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="d003e-457">String</span></span> | <span data-ttu-id="d003e-458">Usado somente se `type` estiver definido como `item`.</span><span class="sxs-lookup"><span data-stu-id="d003e-458">Only used if `type` is set to `item`.</span></span> <span data-ttu-id="d003e-459">A id de item do EWS do email existente que deseja anexar para a nova mensagem.</span><span class="sxs-lookup"><span data-stu-id="d003e-459">The EWS item id of the existing e-mail you want to attach to the new message.</span></span> <span data-ttu-id="d003e-460">Isso é uma cadeia de até 100 caracteres.</span><span class="sxs-lookup"><span data-stu-id="d003e-460">This is a string up to 100 characters.</span></span> |


##### <a name="requirements"></a><span data-ttu-id="d003e-461">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-461">Requirements</span></span>

|<span data-ttu-id="d003e-462">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-462">Requirement</span></span>| <span data-ttu-id="d003e-463">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-463">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-464">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-464">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-465">1.6</span><span class="sxs-lookup"><span data-stu-id="d003e-465">1.6</span></span> |
|[<span data-ttu-id="d003e-466">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-466">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-467">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-467">ReadItem</span></span>|
|[<span data-ttu-id="d003e-468">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-468">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-469">Leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-469">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="d003e-470">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-470">Example</span></span>

```
Office.context.mailbox.displayNewMessageForm(
  {
    toRecipients: Office.context.mailbox.item.to, // Copy the To line from current item
    ccRecipients: ['sam@contoso.com'],
    subject: 'Outlook add-ins are cool!',
    htmlBody: 'Hello <b>World</b>!<br/><img src="cid:image.png"></i>',
    attachments: [
      {
        type: 'file',
        name: 'image.png',
        url: 'http://contoso.com/image.png',
        isInline: true
      }
    ]
  });
```

#### <a name="getcallbacktokenasyncoptions-callback"></a><span data-ttu-id="d003e-471">getCallbackTokenAsync([options], callback)</span><span class="sxs-lookup"><span data-stu-id="d003e-471">getCallbackTokenAsync([options], callback)</span></span>

<span data-ttu-id="d003e-472">Obtém uma cadeia de caracteres que contém um token usado para chamar APIs REST ou Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d003e-472">Gets a string that contains a token used to call REST APIs or Exchange Web Services.</span></span>

<span data-ttu-id="d003e-p132">O método `getCallbackTokenAsync` faz uma chamada assíncrona para obter um token opaco do Exchange Server que hospeda a caixa de correio do usuário. A vida útil do token de retorno de chamada é de 5 minutos.</span><span class="sxs-lookup"><span data-stu-id="d003e-p132">The `getCallbackTokenAsync` method makes an asynchronous call to get an opaque token from the Exchange Server that hosts the user's mailbox. The lifetime of the callback token is 5 minutes.</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-475">É recomendável que os suplementos usam as APIs REST em vez de serviços Web do Exchange sempre que possível.</span><span class="sxs-lookup"><span data-stu-id="d003e-475">It is recommended that add-ins use the REST APIs instead of Exchange Web Services whenever possible.</span></span> 

<span data-ttu-id="d003e-476">**Tokens REST**</span><span class="sxs-lookup"><span data-stu-id="d003e-476">**REST Tokens**</span></span>

<span data-ttu-id="d003e-p133">Quando um token REST é solicitado (`options.isRest = true`), o token resultante não funcionará para autenticar as chamadas dos Serviços Web do Exchange. O token será limitado em escopo para acesso somente leitura no item atual e seus anexos, a menos que o suplemento tenha especificado a permissão [`ReadWriteMailbox`](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions#readwritemailbox-permission) em seu manifesto. Se a permissão `ReadWriteMailbox` tiver sido especificada, o token resultante concederá acesso de leitura/gravação a email, calendário e contatos, incluindo a capacidade de enviar emails.</span><span class="sxs-lookup"><span data-stu-id="d003e-p133">When a REST token is requested (`options.isRest = true`), the resulting token will not work to authenticate Exchange Web Services calls. The token will be limited in scope to read-only access to the current item and its attachments, unless the add-in has specified the [`ReadWriteMailbox`](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions#readwritemailbox-permission) permission in its manifest. If the `ReadWriteMailbox` permission is specified, the resulting token will grant read/write access to mail, calendar, and contacts, including the ability to send mail.</span></span>

<span data-ttu-id="d003e-480">O suplemento deve usar a propriedade `restUrl` para determinar a URL correta a ser usada ao fazer chamadas da API REST.</span><span class="sxs-lookup"><span data-stu-id="d003e-480">The add-in should use the `restUrl` property to determine the correct URL to use when making REST API calls.</span></span>

<span data-ttu-id="d003e-481">**Tokens EWS**</span><span class="sxs-lookup"><span data-stu-id="d003e-481">**EWS Tokens**</span></span>

<span data-ttu-id="d003e-p134">Quando um token EWS é solicitado (`options.isRest = false`), o token resultante não funcionará para autenticar as chamadas de API REST. O token será limitado em escopo para acessar o item atual.</span><span class="sxs-lookup"><span data-stu-id="d003e-p134">When an EWS token is requested (`options.isRest = false`), the resulting token will not work to authenticate REST API calls. The token will be limited in scope to accessing the current item.</span></span>

<span data-ttu-id="d003e-484">O suplemento deve usar a propriedade `ewsUrl` para determinar a URL correta a ser usada ao fazer chamadas de EWS.</span><span class="sxs-lookup"><span data-stu-id="d003e-484">The add-in should use the `ewsUrl` property to determine the correct URL to use when making EWS calls.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-485">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-485">Parameters:</span></span>

|<span data-ttu-id="d003e-486">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-486">Name</span></span>| <span data-ttu-id="d003e-487">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-487">Type</span></span>| <span data-ttu-id="d003e-488">Atributos</span><span class="sxs-lookup"><span data-stu-id="d003e-488">Attributes</span></span>| <span data-ttu-id="d003e-489">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-489">Description</span></span>|
|---|---|---|---|
| `options` | <span data-ttu-id="d003e-490">Objeto</span><span class="sxs-lookup"><span data-stu-id="d003e-490">Object</span></span> | <span data-ttu-id="d003e-491">&lt;opcional&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-491">&lt;optional&gt;</span></span> | <span data-ttu-id="d003e-492">Um objeto literal que contém uma ou mais das propriedades a seguir.</span><span class="sxs-lookup"><span data-stu-id="d003e-492">An object literal that contains one or more of the following properties.</span></span> |
| `options.isRest` | <span data-ttu-id="d003e-493">Booliano</span><span class="sxs-lookup"><span data-stu-id="d003e-493">Boolean</span></span> |  <span data-ttu-id="d003e-494">&lt;opcional&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-494">&lt;optional&gt;</span></span> | <span data-ttu-id="d003e-p135">Determina se o token fornecido será usado para as APIs REST do Outlook ou Serviços Web do Exchange. O valor padrão é `false`.</span><span class="sxs-lookup"><span data-stu-id="d003e-p135">Determines if the token provided will be used for the Outlook REST APIs or Exchange Web Services. Default value is `false`.</span></span> |
| `options.asyncContext` | <span data-ttu-id="d003e-497">Objeto</span><span class="sxs-lookup"><span data-stu-id="d003e-497">Object</span></span> |  <span data-ttu-id="d003e-498">&lt;opcional&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-498">&lt;optional&gt;</span></span> | <span data-ttu-id="d003e-499">Quaisquer dados de estado que são passados ao método assíncrono.</span><span class="sxs-lookup"><span data-stu-id="d003e-499">Any state data that is passed to the asynchronous method.</span></span> |
|`callback`| <span data-ttu-id="d003e-500">function</span><span class="sxs-lookup"><span data-stu-id="d003e-500">function</span></span>||<span data-ttu-id="d003e-p136">Quando o método for concluído, a função passada ao parâmetro `callback` é chamada com um único parâmetro, `asyncResult`, que é um objeto [`AsyncResult`](/javascript/api/office/office.asyncresult). O token é fornecido como uma cadeia de caracteres na propriedade `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="d003e-p136">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object. The token is provided as a string in the `asyncResult.value` property.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-503">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-503">Requirements</span></span>

|<span data-ttu-id="d003e-504">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-504">Requirement</span></span>| <span data-ttu-id="d003e-505">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-505">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-506">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-506">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-507">1,5</span><span class="sxs-lookup"><span data-stu-id="d003e-507">1.5</span></span> |
|[<span data-ttu-id="d003e-508">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-508">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-509">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-509">ReadItem</span></span>|
|[<span data-ttu-id="d003e-510">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-510">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-511">Redigir e ler</span><span class="sxs-lookup"><span data-stu-id="d003e-511">Compose and read</span></span>|

##### <a name="example"></a><span data-ttu-id="d003e-512">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-512">Example</span></span>

```js
function getCallbackToken() {
  var options = {
    isRest: true,
    asyncContext: { message: 'Hello World!' }
  };

  Office.context.mailbox.getCallbackTokenAsync(options, cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

#### <a name="getcallbacktokenasynccallback-usercontext"></a><span data-ttu-id="d003e-513">getCallbackTokenAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="d003e-513">getCallbackTokenAsync(callback, [userContext])</span></span>

<span data-ttu-id="d003e-514">Obtém uma cadeia de caracteres que contém um token usado para obter um anexo ou um item de um Exchange Server.</span><span class="sxs-lookup"><span data-stu-id="d003e-514">Gets a string that contains a token used to get an attachment or item from an Exchange Server.</span></span>

<span data-ttu-id="d003e-p137">O método `getCallbackTokenAsync` faz uma chamada assíncrona para obter um token opaco do Exchange Server que hospeda a caixa de correio do usuário. A vida útil do token de retorno de chamada é de 5 minutos.</span><span class="sxs-lookup"><span data-stu-id="d003e-p137">The `getCallbackTokenAsync` method makes an asynchronous call to get an opaque token from the Exchange Server that hosts the user's mailbox. The lifetime of the callback token is 5 minutes.</span></span>

<span data-ttu-id="d003e-p138">Você pode passar o token e um identificador de anexo ou um identificador de item a um sistema de terceiros. O sistema de terceiros usa o token como portador da autorização para chamar as operações [GetAttachment](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getattachment-operation) ou [GetItem](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getitem-operation) dos Serviços Web do Exchange (EWS) para retornar um anexo ou item. Por exemplo, você pode criar um serviço remoto para [obter anexos do item selecionado](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span><span class="sxs-lookup"><span data-stu-id="d003e-p138">You can pass the token and an attachment identifier or item identifier to a third-party system. The third-party system uses the token as a bearer authorization token to call the Exchange Web Services (EWS) [GetAttachment](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getattachment-operation) or [GetItem](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getitem-operation) operation to return an attachment or item. For example, you can create a remote service to [get attachments from the selected item](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span></span>

<span data-ttu-id="d003e-520">Seu aplicativo deve ter a permissão **ReadItem** especificada em seu manifesto para chamar o método `getCallbackTokenAsync` em modo de leitura.</span><span class="sxs-lookup"><span data-stu-id="d003e-520">Your app must have the **ReadItem** permission specified in its manifest to call the `getCallbackTokenAsync` method in read mode.</span></span>

<span data-ttu-id="d003e-p139">No modo de composição, você deve chamar o método [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) para obter um identificador de item para passar ao método `getCallbackTokenAsync`. Seu aplicativo deve ter permissões **ReadWriteItem** para chamar o método `saveAsync`.</span><span class="sxs-lookup"><span data-stu-id="d003e-p139">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method to get an item identifier to pass to the `getCallbackTokenAsync` method. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-523">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-523">Parameters:</span></span>

|<span data-ttu-id="d003e-524">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-524">Name</span></span>| <span data-ttu-id="d003e-525">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-525">Type</span></span>| <span data-ttu-id="d003e-526">Atributos</span><span class="sxs-lookup"><span data-stu-id="d003e-526">Attributes</span></span>| <span data-ttu-id="d003e-527">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-527">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="d003e-528">function</span><span class="sxs-lookup"><span data-stu-id="d003e-528">function</span></span>||<span data-ttu-id="d003e-p140">Quando o método for concluído, a função passada ao parâmetro `callback` é chamada com um único parâmetro, `asyncResult`, que é um objeto [`AsyncResult`](/javascript/api/office/office.asyncresult). O token é fornecido como uma cadeia de caracteres na propriedade `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="d003e-p140">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object. The token is provided as a string in the `asyncResult.value` property.</span></span>|
|`userContext`| <span data-ttu-id="d003e-531">Objeto</span><span class="sxs-lookup"><span data-stu-id="d003e-531">Object</span></span>| <span data-ttu-id="d003e-532">&lt;opcional&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-532">&lt;optional&gt;</span></span>|<span data-ttu-id="d003e-533">Quaisquer dados de estado que são passados ao método assíncrono.</span><span class="sxs-lookup"><span data-stu-id="d003e-533">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-534">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-534">Requirements</span></span>

|<span data-ttu-id="d003e-535">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-535">Requirement</span></span>| <span data-ttu-id="d003e-536">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-536">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-537">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-537">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-538">1.3</span><span class="sxs-lookup"><span data-stu-id="d003e-538">1.3</span></span>|
|[<span data-ttu-id="d003e-539">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-539">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-540">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-540">ReadItem</span></span>|
|[<span data-ttu-id="d003e-541">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-541">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-542">Redigir e ler</span><span class="sxs-lookup"><span data-stu-id="d003e-542">Compose and read</span></span>|

##### <a name="example"></a><span data-ttu-id="d003e-543">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-543">Example</span></span>

```js
function getCallbackToken() {
  Office.context.mailbox.getCallbackTokenAsync(cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

####  <a name="getuseridentitytokenasynccallback-usercontext"></a><span data-ttu-id="d003e-544">getUserIdentityTokenAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="d003e-544">getUserIdentityTokenAsync(callback, [userContext])</span></span>

<span data-ttu-id="d003e-545">Obtém um símbolo que identifica o usuário e o suplemento do Office.</span><span class="sxs-lookup"><span data-stu-id="d003e-545">Gets a token identifying the user and the Office Add-in.</span></span>

<span data-ttu-id="d003e-546">O método `getUserIdentityTokenAsync` retorna um token que pode ser utilizado para identificar e [autenticar o suplemento e o usuário com um sistema de terceiros](https://docs.microsoft.com/outlook/add-ins/authentication).</span><span class="sxs-lookup"><span data-stu-id="d003e-546">The `getUserIdentityTokenAsync` method returns a token that you can use to identify and [authenticate the add-in and user with a third-party system](https://docs.microsoft.com/outlook/add-ins/authentication).</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-547">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-547">Parameters:</span></span>

|<span data-ttu-id="d003e-548">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-548">Name</span></span>| <span data-ttu-id="d003e-549">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-549">Type</span></span>| <span data-ttu-id="d003e-550">Atributos</span><span class="sxs-lookup"><span data-stu-id="d003e-550">Attributes</span></span>| <span data-ttu-id="d003e-551">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-551">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="d003e-552">function</span><span class="sxs-lookup"><span data-stu-id="d003e-552">function</span></span>||<span data-ttu-id="d003e-553">Quando o método for concluído, a função passada ao parâmetro `callback` é chamada com um único parâmetro, `asyncResult`, que é um objeto [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="d003e-553">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="d003e-554">O token é fornecido como uma cadeia de caracteres na propriedade `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="d003e-554">The token is provided as a string in the `asyncResult.value` property.</span></span>|
|`userContext`| <span data-ttu-id="d003e-555">Object</span><span class="sxs-lookup"><span data-stu-id="d003e-555">Object</span></span>| <span data-ttu-id="d003e-556">&lt;opcional&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-556">&lt;optional&gt;</span></span>|<span data-ttu-id="d003e-557">Quaisquer dados de estado que são passados ao método assíncrono.</span><span class="sxs-lookup"><span data-stu-id="d003e-557">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-558">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-558">Requirements</span></span>

|<span data-ttu-id="d003e-559">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-559">Requirement</span></span>| <span data-ttu-id="d003e-560">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-560">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-561">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-561">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-562">1.0</span><span class="sxs-lookup"><span data-stu-id="d003e-562">1.0</span></span>|
|[<span data-ttu-id="d003e-563">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-563">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-564">ReadItem</span><span class="sxs-lookup"><span data-stu-id="d003e-564">ReadItem</span></span>|
|[<span data-ttu-id="d003e-565">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-565">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-566">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-566">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="d003e-567">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-567">Example</span></span>

```js
function getIdentityToken() {
  Office.context.mailbox.getUserIdentityTokenAsync(cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

####  <a name="makeewsrequestasyncdata-callback-usercontext"></a><span data-ttu-id="d003e-568">makeEwsRequestAsync(data, callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="d003e-568">makeEwsRequestAsync(data, callback, [userContext])</span></span>

<span data-ttu-id="d003e-569">Faz uma solicitação assíncrona em um serviço dos Serviços Web do Exchange (EWS) no servidor Exchange que hospeda a caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="d003e-569">Makes an asynchronous request to an Exchange Web Services (EWS) service on the Exchange server that hosts the user’s mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-570">Esse método não é suportado nos seguintes cenários.</span><span class="sxs-lookup"><span data-stu-id="d003e-570">This method is not supported in the following scenarios.</span></span>
> - <span data-ttu-id="d003e-571">No Outlook para iOS ou no Outlook para Android</span><span class="sxs-lookup"><span data-stu-id="d003e-571">In Outlook for iOS or Outlook for Android</span></span>
> - <span data-ttu-id="d003e-572">Quando o suplemento for carregado em uma caixa de correio do Gmail</span><span class="sxs-lookup"><span data-stu-id="d003e-572">When the add-in is loaded in a Gmail mailbox</span></span>
> 
> <span data-ttu-id="d003e-573">Nesses casos, suplementos devem [usar APIs REST](https://docs.microsoft.com/outlook/add-ins/use-rest-api) para acessar a caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="d003e-573">In these cases, add-ins should [use REST APIs](https://docs.microsoft.com/outlook/add-ins/use-rest-api) to access the user's mailbox instead.</span></span>

<span data-ttu-id="d003e-574">O método `makeEwsRequestAsync` envia uma solicitação do EWS em nome do suplemento ao Exchange.</span><span class="sxs-lookup"><span data-stu-id="d003e-574">The `makeEwsRequestAsync` method sends an EWS request on behalf of the add-in to Exchange.</span></span> <span data-ttu-id="d003e-575">Para obter uma lista das operações EWS suportadas, consulte [chame serviços web a partir de um suplemento do Outlook](https://docs.microsoft.com/outlook/add-ins/web-services#ews-operations-that-add-ins-support) .</span><span class="sxs-lookup"><span data-stu-id="d003e-575">See [Call web services from an Outlook add-in](https://docs.microsoft.com/outlook/add-ins/web-services#ews-operations-that-add-ins-support) for a list of the supported EWS operations.</span></span>

<span data-ttu-id="d003e-576">Não é possível solicitar os itens associados da pasta com o método `makeEwsRequestAsync`.</span><span class="sxs-lookup"><span data-stu-id="d003e-576">You cannot request Folder Associated Items with the `makeEwsRequestAsync` method.</span></span>

<span data-ttu-id="d003e-577">A solicitação XML deve especificar a codificação UTF-8.</span><span class="sxs-lookup"><span data-stu-id="d003e-577">The XML request must specify UTF-8 encoding.</span></span>

```
<?xml version="1.0" encoding="utf-8"?>
```

<span data-ttu-id="d003e-p142">O suplemento deve ter a permissão **ReadWriteMailbox** para usar o método `makeEwsRequestAsync`. Para saber mais sobre como usar a permissão **ReadWriteMailbox** e as operações do EWS que você pode chamar com o método `makeEwsRequestAsync`, confira [Especificar permissões para acesso de suplemento de email na caixa de correio do usuário](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions).</span><span class="sxs-lookup"><span data-stu-id="d003e-p142">Your add-in must have the **ReadWriteMailbox** permission to use the `makeEwsRequestAsync` method. For information about using the **ReadWriteMailbox** permission and the EWS operations that you can call with the `makeEwsRequestAsync` method, see [Specify permissions for mail add-in access to the user's mailbox](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions).</span></span>

> [!NOTE]
> <span data-ttu-id="d003e-580">O administrador do servidor deve ser definida `OAuthAuthentication` como true no diretório do EWS de servidor de acesso de cliente para habilitar o `makeEwsRequestAsync` método para tornar o EWS solicita.</span><span class="sxs-lookup"><span data-stu-id="d003e-580">The server administrator must set `OAuthAuthentication` to true on the Client Access Server EWS directory to enable the `makeEwsRequestAsync` method to make EWS requests.</span></span>

##### <a name="version-differences"></a><span data-ttu-id="d003e-581">Diferenças de versão</span><span class="sxs-lookup"><span data-stu-id="d003e-581">Version differences</span></span>

<span data-ttu-id="d003e-582">Ao usar o método `makeEwsRequestAsync` nos aplicativos de email em execução em versões do Outlook anteriores à 15.0.4535.1004, é preciso definir o valor de codificação como `ISO-8859-1`.</span><span class="sxs-lookup"><span data-stu-id="d003e-582">When you use the `makeEwsRequestAsync` method in mail apps running in Outlook versions earlier than version 15.0.4535.1004, you should set the encoding value to `ISO-8859-1`.</span></span>

```
<?xml version="1.0" encoding="iso-8859-1"?>
```

<span data-ttu-id="d003e-p143">Não é necessário definir o valor de codificação quando o aplicativo de email estiver em execução no Outlook na Web. Você pode determinar se o aplicativo de email está em execução no Outlook ou no Outlook na Web usando a propriedade mailbox.diagnostics.hostName. Você pode determinar que versão do Outlook está em execução usando a propriedade mailbox.diagnostics.hostVersion.</span><span class="sxs-lookup"><span data-stu-id="d003e-p143">You do not need to set the encoding value when your mail app is running in Outlook on the web. You can determine whether your mail app is running in Outlook or Outlook on the web by using the mailbox.diagnostics.hostName property. You can determine what version of Outlook is running by using the mailbox.diagnostics.hostVersion property.</span></span>

##### <a name="parameters"></a><span data-ttu-id="d003e-586">Parâmetros:</span><span class="sxs-lookup"><span data-stu-id="d003e-586">Parameters:</span></span>

|<span data-ttu-id="d003e-587">Nome</span><span class="sxs-lookup"><span data-stu-id="d003e-587">Name</span></span>| <span data-ttu-id="d003e-588">Tipo</span><span class="sxs-lookup"><span data-stu-id="d003e-588">Type</span></span>| <span data-ttu-id="d003e-589">Atributos</span><span class="sxs-lookup"><span data-stu-id="d003e-589">Attributes</span></span>| <span data-ttu-id="d003e-590">Descrição</span><span class="sxs-lookup"><span data-stu-id="d003e-590">Description</span></span>|
|---|---|---|---|
|`data`| <span data-ttu-id="d003e-591">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="d003e-591">String</span></span>||<span data-ttu-id="d003e-592">A solicitação do EWS.</span><span class="sxs-lookup"><span data-stu-id="d003e-592">The EWS request.</span></span>|
|`callback`| <span data-ttu-id="d003e-593">function</span><span class="sxs-lookup"><span data-stu-id="d003e-593">function</span></span>||<span data-ttu-id="d003e-594">Quando o método for concluído, a função passada ao parâmetro `callback` é chamada com um único parâmetro, `asyncResult`, que é um objeto [`AsyncResult`](/javascript/api/office/office.asyncresult).</span><span class="sxs-lookup"><span data-stu-id="d003e-594">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="d003e-595">O resultado XML da chamada do EWS é fornecido como uma cadeia de caracteres na propriedade `asyncResult.value`.</span><span class="sxs-lookup"><span data-stu-id="d003e-595">The XML result of the EWS call is provided as a string in the `asyncResult.value` property.</span></span> <span data-ttu-id="d003e-596">Se o resultado exceder 1 MB em tamanho, uma mensagem de erro será retornada em vez disso.</span><span class="sxs-lookup"><span data-stu-id="d003e-596">If the result exceeds 1 MB in size, an error message is returned instead.</span></span>|
|`userContext`| <span data-ttu-id="d003e-597">Objeto</span><span class="sxs-lookup"><span data-stu-id="d003e-597">Object</span></span>| <span data-ttu-id="d003e-598">&lt;opcional&gt;</span><span class="sxs-lookup"><span data-stu-id="d003e-598">&lt;optional&gt;</span></span>|<span data-ttu-id="d003e-599">Quaisquer dados de estado que são passados ao método assíncrono.</span><span class="sxs-lookup"><span data-stu-id="d003e-599">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="d003e-600">Requisitos</span><span class="sxs-lookup"><span data-stu-id="d003e-600">Requirements</span></span>

|<span data-ttu-id="d003e-601">Requisito</span><span class="sxs-lookup"><span data-stu-id="d003e-601">Requirement</span></span>| <span data-ttu-id="d003e-602">Valor</span><span class="sxs-lookup"><span data-stu-id="d003e-602">Value</span></span>|
|---|---|
|[<span data-ttu-id="d003e-603">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="d003e-603">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="d003e-604">1.0</span><span class="sxs-lookup"><span data-stu-id="d003e-604">1.0</span></span>|
|[<span data-ttu-id="d003e-605">Nível de permissão mínimo</span><span class="sxs-lookup"><span data-stu-id="d003e-605">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="d003e-606">ReadWriteMailbox</span><span class="sxs-lookup"><span data-stu-id="d003e-606">ReadWriteMailbox</span></span>|
|[<span data-ttu-id="d003e-607">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="d003e-607">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="d003e-608">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="d003e-608">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="d003e-609">Exemplo</span><span class="sxs-lookup"><span data-stu-id="d003e-609">Example</span></span>

<span data-ttu-id="d003e-610">O exemplo a seguir chama `makeEwsRequestAsync` para usar a operação `GetItem` para obter o assunto de um item.</span><span class="sxs-lookup"><span data-stu-id="d003e-610">The following example calls `makeEwsRequestAsync` to use the `GetItem` operation to get the subject of an item.</span></span>

```js
function getSubjectRequest(id) {
   // Return a GetItem operation request for the subject of the specified item.
   var request =
    '<?xml version="1.0" encoding="utf-8"?>' +
    '<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"' +
    '               xmlns:xsd="http://www.w3.org/2001/XMLSchema"' +
    '               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"' +
    '               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">' +
    '  <soap:Header>' +
    '    <RequestServerVersion Version="Exchange2013" xmlns="http://schemas.microsoft.com/exchange/services/2006/types" soap:mustUnderstand="0" />' +
    '  </soap:Header>' +
    '  <soap:Body>' +
    '    <GetItem xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">' +
    '      <ItemShape>' +
    '        <t:BaseShape>IdOnly</t:BaseShape>' +
    '        <t:AdditionalProperties>' +
    '            <t:FieldURI FieldURI="item:Subject"/>' +
    '        </t:AdditionalProperties>' +
    '      </ItemShape>' +
    '      <ItemIds><t:ItemId Id="' + id + '"/></ItemIds>' +
    '    </GetItem>' +
    '  </soap:Body>' +
    '</soap:Envelope>';

   return request;
}

function sendRequest() {
   // Create a local variable that contains the mailbox.
   Office.context.mailbox.makeEwsRequestAsync(
    getSubjectRequest(mailbox.item.itemId), callback);
}

function callback(asyncResult)  {
   var result = asyncResult.value;
   var context = asyncResult.asyncContext;

   // Process the returned response here.
}
```