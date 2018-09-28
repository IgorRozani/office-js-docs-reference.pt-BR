# <a name="office"></a><span data-ttu-id="04c92-101">Office</span><span class="sxs-lookup"><span data-stu-id="04c92-101">Office</span></span>

<span data-ttu-id="04c92-p101">O namespace do Office fornece interfaces compartilhadas que são usadas pelos suplementos em todos os aplicativos do Office. Esta listagem documenta somente as interfaces que são usadas pelos suplementos do Outlook. Para obter uma lista completa de namespaces do Office, confira [API compartilhada](/javascript/api/office).</span><span class="sxs-lookup"><span data-stu-id="04c92-p101">The Office namespace provides shared interfaces that are used by add-ins in all of the Office apps. This listing documents only those interfaces that are used by Outlook add-ins. For a full listing of the Office namespace, see the [Shared API](/javascript/api/office).</span></span>

##### <a name="requirements"></a><span data-ttu-id="04c92-104">Requisitos</span><span class="sxs-lookup"><span data-stu-id="04c92-104">Requirements</span></span>

|<span data-ttu-id="04c92-105">Requisito</span><span class="sxs-lookup"><span data-stu-id="04c92-105">Requirement</span></span>| <span data-ttu-id="04c92-106">Valor</span><span class="sxs-lookup"><span data-stu-id="04c92-106">Value</span></span>|
|---|---|
|[<span data-ttu-id="04c92-107">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="04c92-107">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="04c92-108">1.0</span><span class="sxs-lookup"><span data-stu-id="04c92-108">1.0</span></span>|
|[<span data-ttu-id="04c92-109">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="04c92-109">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="04c92-110">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="04c92-110">Compose or read</span></span>|

##### <a name="members-and-methods"></a><span data-ttu-id="04c92-111">Membros e métodos</span><span class="sxs-lookup"><span data-stu-id="04c92-111">Members and methods</span></span>

| <span data-ttu-id="04c92-112">Membro</span><span class="sxs-lookup"><span data-stu-id="04c92-112">Member</span></span> | <span data-ttu-id="04c92-113">Tipo</span><span class="sxs-lookup"><span data-stu-id="04c92-113">Type</span></span> |
|--------|------|
| [<span data-ttu-id="04c92-114">AsyncResultStatus</span><span class="sxs-lookup"><span data-stu-id="04c92-114">AsyncResultStatus</span></span>](#asyncresultstatus-string) | <span data-ttu-id="04c92-115">Membro</span><span class="sxs-lookup"><span data-stu-id="04c92-115">Member</span></span> |
| [<span data-ttu-id="04c92-116">CoercionType</span><span class="sxs-lookup"><span data-stu-id="04c92-116">CoercionType</span></span>](#coerciontype-string) | <span data-ttu-id="04c92-117">Membro</span><span class="sxs-lookup"><span data-stu-id="04c92-117">Member</span></span> |
| [<span data-ttu-id="04c92-118">EventType</span><span class="sxs-lookup"><span data-stu-id="04c92-118">EventType</span></span>](#eventtype-string) | <span data-ttu-id="04c92-119">Membro</span><span class="sxs-lookup"><span data-stu-id="04c92-119">Member</span></span> |
| [<span data-ttu-id="04c92-120">SourceProperty</span><span class="sxs-lookup"><span data-stu-id="04c92-120">SourceProperty</span></span>](#sourceproperty-string) | <span data-ttu-id="04c92-121">Membro</span><span class="sxs-lookup"><span data-stu-id="04c92-121">Member</span></span> |

### <a name="namespaces"></a><span data-ttu-id="04c92-122">Namespaces</span><span class="sxs-lookup"><span data-stu-id="04c92-122">Namespaces</span></span>

<span data-ttu-id="04c92-123">[contexto](office.context.md): fornece interfaces compartilhadas de namespace de contexto a API de suplementos do Office para uso na API do suplemento do Outlook.</span><span class="sxs-lookup"><span data-stu-id="04c92-123">[context](office.context.md): Provides shared interfaces from the Office Add-ins API's context namespace for use in the Outlook add-in API.</span></span>

<span data-ttu-id="04c92-124">[MailboxEnums](/javascript/api/outlook/office.mailboxenums.attachmenttype): Inclui as enumerações ItemType, EntityType, AttachmentType, RecipientType, ResponseType e ItemNotificationMessageType.</span><span class="sxs-lookup"><span data-stu-id="04c92-124">[MailboxEnums](/javascript/api/outlook/office.mailboxenums.attachmenttype): Includes the ItemType, EntityType, AttachmentType, RecipientType, ResponseType, and ItemNotificationMessageType enumerations.</span></span>

### <a name="members"></a><span data-ttu-id="04c92-125">Membros</span><span class="sxs-lookup"><span data-stu-id="04c92-125">Members</span></span>

####  <a name="asyncresultstatus-string"></a><span data-ttu-id="04c92-126">AsyncResultStatus :String</span><span class="sxs-lookup"><span data-stu-id="04c92-126">AsyncResultStatus :String</span></span>

<span data-ttu-id="04c92-127">Especifica o resultado de uma chamada assíncrona.</span><span class="sxs-lookup"><span data-stu-id="04c92-127">Specifies the result of an asynchronous call.</span></span>

##### <a name="type"></a><span data-ttu-id="04c92-128">Tipo:</span><span class="sxs-lookup"><span data-stu-id="04c92-128">Type:</span></span>

*   <span data-ttu-id="04c92-129">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-129">String</span></span>

##### <a name="properties"></a><span data-ttu-id="04c92-130">Propriedades:</span><span class="sxs-lookup"><span data-stu-id="04c92-130">Properties:</span></span>

|<span data-ttu-id="04c92-131">Nome</span><span class="sxs-lookup"><span data-stu-id="04c92-131">Name</span></span>| <span data-ttu-id="04c92-132">Tipo</span><span class="sxs-lookup"><span data-stu-id="04c92-132">Type</span></span>| <span data-ttu-id="04c92-133">Descrição</span><span class="sxs-lookup"><span data-stu-id="04c92-133">Description</span></span>|
|---|---|---|
|`Succeeded`| <span data-ttu-id="04c92-134">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-134">String</span></span>|<span data-ttu-id="04c92-135">A chamada foi bem-sucedida.</span><span class="sxs-lookup"><span data-stu-id="04c92-135">The call succeeded.</span></span>|
|`Failed`| <span data-ttu-id="04c92-136">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-136">String</span></span>|<span data-ttu-id="04c92-137">Falha na chamada.</span><span class="sxs-lookup"><span data-stu-id="04c92-137">The call failed.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="04c92-138">Requisitos</span><span class="sxs-lookup"><span data-stu-id="04c92-138">Requirements</span></span>

|<span data-ttu-id="04c92-139">Requisito</span><span class="sxs-lookup"><span data-stu-id="04c92-139">Requirement</span></span>| <span data-ttu-id="04c92-140">Valor</span><span class="sxs-lookup"><span data-stu-id="04c92-140">Value</span></span>|
|---|---|
|[<span data-ttu-id="04c92-141">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="04c92-141">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="04c92-142">1.0</span><span class="sxs-lookup"><span data-stu-id="04c92-142">1.0</span></span>|
|[<span data-ttu-id="04c92-143">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="04c92-143">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="04c92-144">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="04c92-144">Compose or read</span></span>|

---

####  <a name="coerciontype-string"></a><span data-ttu-id="04c92-145">CoercionType :String</span><span class="sxs-lookup"><span data-stu-id="04c92-145">CoercionType :String</span></span>

<span data-ttu-id="04c92-146">Especifica como forçar os dados retornados ou definir de acordo com o método chamado.</span><span class="sxs-lookup"><span data-stu-id="04c92-146">Specifies how to coerce data returned or set by the invoked method.</span></span>

##### <a name="type"></a><span data-ttu-id="04c92-147">Tipo:</span><span class="sxs-lookup"><span data-stu-id="04c92-147">Type:</span></span>

*   <span data-ttu-id="04c92-148">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-148">String</span></span>

##### <a name="properties"></a><span data-ttu-id="04c92-149">Propriedades:</span><span class="sxs-lookup"><span data-stu-id="04c92-149">Properties:</span></span>

|<span data-ttu-id="04c92-150">Nome</span><span class="sxs-lookup"><span data-stu-id="04c92-150">Name</span></span>| <span data-ttu-id="04c92-151">Tipo</span><span class="sxs-lookup"><span data-stu-id="04c92-151">Type</span></span>| <span data-ttu-id="04c92-152">Descrição</span><span class="sxs-lookup"><span data-stu-id="04c92-152">Description</span></span>|
|---|---|---|
|`Html`| <span data-ttu-id="04c92-153">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-153">String</span></span>|<span data-ttu-id="04c92-154">Solicita que os dados sejam retornados no formato HTML.</span><span class="sxs-lookup"><span data-stu-id="04c92-154">Requests the data be returned in HTML format.</span></span>|
|`Text`| <span data-ttu-id="04c92-155">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-155">String</span></span>|<span data-ttu-id="04c92-156">Solicita que os dados sejam retornados no formato de texto.</span><span class="sxs-lookup"><span data-stu-id="04c92-156">Requests the data be returned in text format.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="04c92-157">Requisitos</span><span class="sxs-lookup"><span data-stu-id="04c92-157">Requirements</span></span>

|<span data-ttu-id="04c92-158">Requisito</span><span class="sxs-lookup"><span data-stu-id="04c92-158">Requirement</span></span>| <span data-ttu-id="04c92-159">Valor</span><span class="sxs-lookup"><span data-stu-id="04c92-159">Value</span></span>|
|---|---|
|[<span data-ttu-id="04c92-160">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="04c92-160">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="04c92-161">1.0</span><span class="sxs-lookup"><span data-stu-id="04c92-161">1.0</span></span>|
|[<span data-ttu-id="04c92-162">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="04c92-162">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="04c92-163">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="04c92-163">Compose or read</span></span>|

---

####  <a name="eventtype-string"></a><span data-ttu-id="04c92-164">EventType :String</span><span class="sxs-lookup"><span data-stu-id="04c92-164">EventType :String</span></span>

<span data-ttu-id="04c92-165">Especifica o evento associado a um manipulador de eventos.</span><span class="sxs-lookup"><span data-stu-id="04c92-165">Specifies the event associated with an event handler.</span></span>

##### <a name="type"></a><span data-ttu-id="04c92-166">Tipo:</span><span class="sxs-lookup"><span data-stu-id="04c92-166">Type:</span></span>

*   <span data-ttu-id="04c92-167">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-167">String</span></span>

##### <a name="properties"></a><span data-ttu-id="04c92-168">Propriedades:</span><span class="sxs-lookup"><span data-stu-id="04c92-168">Properties:</span></span>

| <span data-ttu-id="04c92-169">Nome</span><span class="sxs-lookup"><span data-stu-id="04c92-169">Name</span></span> | <span data-ttu-id="04c92-170">Tipo</span><span class="sxs-lookup"><span data-stu-id="04c92-170">Type</span></span> | <span data-ttu-id="04c92-171">Descrição</span><span class="sxs-lookup"><span data-stu-id="04c92-171">Description</span></span> |
|---|---|---|
|`ItemChanged`| <span data-ttu-id="04c92-172">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-172">String</span></span> | <span data-ttu-id="04c92-173">O item selecionado foi alterado.</span><span class="sxs-lookup"><span data-stu-id="04c92-173">The selected item has changed.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="04c92-174">Requisitos</span><span class="sxs-lookup"><span data-stu-id="04c92-174">Requirements</span></span>

|<span data-ttu-id="04c92-175">Requisito</span><span class="sxs-lookup"><span data-stu-id="04c92-175">Requirement</span></span>| <span data-ttu-id="04c92-176">Valor</span><span class="sxs-lookup"><span data-stu-id="04c92-176">Value</span></span>|
|---|---|
|[<span data-ttu-id="04c92-177">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="04c92-177">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="04c92-178">1,5</span><span class="sxs-lookup"><span data-stu-id="04c92-178">1.5</span></span> |
|[<span data-ttu-id="04c92-179">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="04c92-179">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="04c92-180">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="04c92-180">Compose or read</span></span> |

---

####  <a name="sourceproperty-string"></a><span data-ttu-id="04c92-181">SourceProperty :String</span><span class="sxs-lookup"><span data-stu-id="04c92-181">SourceProperty :String</span></span>

<span data-ttu-id="04c92-182">Especifica a origem dos dados retornados pelo método chamado.</span><span class="sxs-lookup"><span data-stu-id="04c92-182">Specifies the source of the data returned by the invoked method.</span></span>

##### <a name="type"></a><span data-ttu-id="04c92-183">Tipo:</span><span class="sxs-lookup"><span data-stu-id="04c92-183">Type:</span></span>

*   <span data-ttu-id="04c92-184">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-184">String</span></span>

##### <a name="properties"></a><span data-ttu-id="04c92-185">Propriedades:</span><span class="sxs-lookup"><span data-stu-id="04c92-185">Properties:</span></span>

|<span data-ttu-id="04c92-186">Nome</span><span class="sxs-lookup"><span data-stu-id="04c92-186">Name</span></span>| <span data-ttu-id="04c92-187">Tipo</span><span class="sxs-lookup"><span data-stu-id="04c92-187">Type</span></span>| <span data-ttu-id="04c92-188">Descrição</span><span class="sxs-lookup"><span data-stu-id="04c92-188">Description</span></span>|
|---|---|---|
|`Body`| <span data-ttu-id="04c92-189">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-189">String</span></span>|<span data-ttu-id="04c92-190">A origem dos dados é o corpo de uma mensagem.</span><span class="sxs-lookup"><span data-stu-id="04c92-190">The source of the data is from the body of a message.</span></span>|
|`Subject`| <span data-ttu-id="04c92-191">Cadeia de caracteres</span><span class="sxs-lookup"><span data-stu-id="04c92-191">String</span></span>|<span data-ttu-id="04c92-192">A origem dos dados é o assunto de uma mensagem.</span><span class="sxs-lookup"><span data-stu-id="04c92-192">The source of the data is from the subject of a message.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="04c92-193">Requisitos</span><span class="sxs-lookup"><span data-stu-id="04c92-193">Requirements</span></span>

|<span data-ttu-id="04c92-194">Requisito</span><span class="sxs-lookup"><span data-stu-id="04c92-194">Requirement</span></span>| <span data-ttu-id="04c92-195">Valor</span><span class="sxs-lookup"><span data-stu-id="04c92-195">Value</span></span>|
|---|---|
|[<span data-ttu-id="04c92-196">Versão do conjunto de requisitos mínimos da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="04c92-196">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="04c92-197">1.0</span><span class="sxs-lookup"><span data-stu-id="04c92-197">1.0</span></span>|
|[<span data-ttu-id="04c92-198">Modo do Outlook aplicável</span><span class="sxs-lookup"><span data-stu-id="04c92-198">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="04c92-199">Composição ou leitura</span><span class="sxs-lookup"><span data-stu-id="04c92-199">Compose or read</span></span>|