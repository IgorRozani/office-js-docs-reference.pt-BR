# <a name="officeapp-element"></a>Elemento OfficeApp

O elemento raiz no manifesto de um Suplemento do Office.

**Tipo de suplemento:** Conteúdo, Painel de tarefas, Email

## <a name="syntax"></a>Sintaxe

```XML
<OfficeApp 
  xmlns="http://schemas.microsoft.com/office/appforoffice/1.1" 
  xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
  xsi:type= ["ContentApp" |"MailApp"| "TaskPaneApp"]>
  ...
</OfficeApp>
```

## <a name="contained-in"></a>Contidos em

 _none_

## <a name="must-contain"></a>Deve conter

|**Elemento**|**Conteúdo**|**Email**|**TaskPane**|
|:-----|:-----|:-----|:-----|
|
  [Id](id.md)|x|x|x|
|[Versão](version.md)|x|x|x|
|[ProviderName](providername.md)|x|x|x|
|[DefaultLocale](defaultlocale.md)|x|x|x|
|[DefaultSettings](defaultsettings.md)|x||x|
|[DisplayName](displayname.md)|x|x|x|
|[Descrição](description.md)|x|x|x|
|[FormSettings](formsettings.md)||x||
|[Permissões](permissions.md)|x||x|
|[Rule](rule.md)||x||

## <a name="can-contain"></a>Pode conter

|**Elemento**|**Conteúdo**|**Email**|**TaskPane**|
|:-----|:-----|:-----|:-----|
|[AlternateId](alternateid.md)|x|x|x|
|[IconUrl](iconurl.md)|x|x|x|
|[HighResolutionIconUrl](highresolutioniconurl.md)|x|x|x|
|[SupportUrl](supporturl.md)|x|x|x|
|[AppDomains](appdomains.md)|x|x|x|
|[Hosts](hosts.md)|x|x|x|
|[Requirements](requirements.md)|x|x|x|
|[AllowSnapshot](allowsnapshot.md)|x|||
|[Permissões](permissions.md)||x||
|[DisableEntityHighlighting](disableentityhighlighting.md)||x||
|[dicionário](dictionary.md)|||x|
|[VersionOverrides](versionoverrides.md)|X|X|X|

## <a name="attributes"></a>Atributos

|||
|:-----|:-----|
|xmlns|Define o namespace do manifesto do Suplemento do Office e o esquema da versão. Esse atributo deve ser sempre definido como `"http://schemas.microsoft.com/office/appforoffice/1.1"`|
|xmlns: xsi|Define a instância XMLSchema. Esse atributo deve ser sempre definido como `"http://www.w3.org/2001/XMLSchema-instance"`|
|xsi:type|Define o tipo de Suplemento do Office. Esse atributo deve ser definido como um destes: `"ContentApp"`, `"MailApp"` ou `"TaskPaneApp"`|
