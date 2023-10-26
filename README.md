# Power Automate Cloud utility flow templates
A set of "ready to import" Power Automate Cloud flow templates, useful for daily automation projects.

## Prerequisites

A professional Microsoft account (1), which gives access to Power Automate Cloud - [website](https://emea.flow.microsoft.com) (please note this is a different software from Power Automate Desktop)

(1) Microsoft 365 E3 licence or equivalent (see [Microsoft entreprise plans comparison](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)), some educational or non profit plans may also work.

## Installation

1. Choose a flow in the *Features* section of this *README*. Download the latest release ZIP file using the hyperlink.

2. Go to the [Power Automate **Cloud** editor](https://make.powerautomate.com) (**not** Power Automate Desktop) > My flows > Import > Import Package (Legacy) > Upload a .zip package file ;
Select the "<feature>_power_automate_package.zip" file that you previously downloaded ;
[details missing]
 
## Features

Each package has an explicit filename, which summarise what it does.

### Turbocharge Power Automate Cloud

A set of Power Automate Cloud flows to extend capabilities of Power Automate.

* workaround to run javascript code in a Power Automate Cloud flow using Excel Online - [latest release](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/releases/latest/download/run_javascript_code_using_excel_online.zip) - [unzipped folder](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/tree/main/run_javascript_code_using_excel_online)

### Turbocharge SharePoint lists using Power Automate Cloud

A set of Power Automate Cloud flows which perform edit on every item of a sharepoint list (e.g. mass edit), to avoid editing each item manually.

* empty a given SharePoint list (delete all items of a given SharePoint list without deleting the SharePoint list itself) - [latest release](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/releases/latest/download/sharepoint_list___empty_list.zip) - [unzipped folder](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/tree/main/sharepoint_list___empty_list)

* import Excel table in an existing SharePoint list - [latest release](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/releases/latest/download/sharepoint_list___import_excel_array_in_existing_list.zip) - [unzipped folder](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/tree/main/sharepoint_list___import_excel_array_in_existing_list)

* remove duplicates in a given SharePoint list (the duplication filter can use any column as reference) - [latest release](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/releases/latest/download/sharepoint_list___remove_duplicates.zip) - [unzipped folder](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/tree/main/sharepoint_list___remove_duplicates)

* transfer data of each item from one column to another one in a given SharePoint list - [latest release](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/releases/latest/download/sharepoint_list___transfert_column_data_to_another_column.zip) - [unzipped folder](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/tree/main/sharepoint_list___transfert_column_data_to_another_column)

### Turbocharge Excel Online using Power Automate Cloud

A set of Power Automate Cloud flows to enable Excel Online to deal with specific use cases.

* give to anybody who knows a given email adress, a write only access to a given Excel table (e.g. user will only be able to write, but will not be able to read) - [latest release](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/releases/latest/download/write_only_access_to_excel_table_using_outlook.zip) - [unzipped folder](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/tree/main/write_only_access_to_excel_table_using_outlook)

*Note* : this flow is secure "by design", because an email sent to only one mail box is only visible by the owner of this mailbox.

* save all messages of all Teams in Microsoft Teams accessible by the user of the flow - [latest release](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/releases/latest/save_all_teams_team_messages.zip) - [unzipped folder](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/tree/main/save_all_teams_team_messages)

## GitHubisation process

Specific setting : flows are exported as "create new", as shown on picture below.

![Export settings screenshot](https://github.com/ronan-deshays/power-automate-cloud-utility-templates/blob/main/0%20-%20docs/ExportProcess1.png)

* ZIP file is uploaded in release.
* ZIP file unzipped is uploaded as source code.
