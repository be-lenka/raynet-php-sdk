# # TaskEditDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **string** | [Předmět] | [optional]
**priority** | **string** | [Priorita] | [optional]
**status** | **string** | [Stav] | [optional]
**category** | **int** | [Kategorie] ID záznamu z číselníku ActivityCategory | [optional]
**personal** | **bool** | [Soukromá aktivita] | [optional]
**company** | **int** | [Klient] ID klienta v kontextu záznamu | [optional]
**person** | **int** | [Kontaktní osoba] ID kontaktní osoby v kontextu záznamu | [optional]
**business_case** | **int** | [Obch. případ] ID obch. případu v kontextu záznamu | [optional]
**offer** | **int** | [Nabídka] ID nabídky v kontextu záznamu | [optional]
**sales_order** | **int** | [Objednávka] ID objednávky v kontextu záznamu | [optional]
**project** | **int** | [Projekt] ID projektu v kontextu záznamu | [optional]
**activity** | **int** | [Aktivita] ID aktivity v kontextu záznamu | [optional]
**security_level** | **int** | [Bezpečnostní úroveň] ID bezpečnostní úrovně. Pokud není vyplněna, je nastavena výchozí bezpečnostní skupina. | [optional]
**scheduled_from** | **\DateTime** | [Naplánováno od] datum naplánování od | [optional]
**scheduled_till** | **\DateTime** | [Naplánováno do] datum naplánování do | [optional]
**deadline** | **\DateTime** | [Deadline] deadline datum | [optional]
**completed** | **\DateTime** | [Realizováno] datum realizace aktivity | [optional]
**description** | **string** | [Zadání úkolu] | [optional]
**solution** | **string** | [Řešení úkolu] | [optional]
**tags** | **string** | [Seznam štítků oddělených čárkou] | [optional]
**custom_fields** | [**\belenka\Raynetcrm\Model\CompanyInsertDtoCustomFields**](CompanyInsertDtoCustomFields.md) |  | [optional]
**participants** | [**\belenka\Raynetcrm\Model\TaskEditDtoParticipantsInner[]**](TaskEditDtoParticipantsInner.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
