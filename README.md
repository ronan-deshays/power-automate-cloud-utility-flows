# Mass edit all items of a SharePoint list
Power Automate scripts which perform edit on every item of a sharepoint list, to avoid editing each item manually.

## Prerequisites

A professional Microsoft account (1), which gives access to the following tools :

* Power Automate - [website](https://emea.flow.microsoft.com)
* Sharepoint Lists - [SharePoint website](https://www.microsoft.com/microsoft-365/sharepoint/collaboration)

(1) Microsoft 365 E3 licence or equivalent (see [Microsoft entreprise plans comparison](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)), some educational or non profit plans may also work.

## Installation

1. Download on this GitHub repository the latest release of "<feature>_power_automate_package.zip". 
With <feature>, the name of the package which suits your needs.
2. Go to the Power Automate **Cloud** editor (not Power Automate Desktop) > My flows > Import > Import Package (Legacy) > Upload a .zip package file ;
Select the "<feature>_power_automate_package.zip" file that you previously downloaded ;
[details missing, in part the same process as digital assistant]
 
## Features

Each package has an explicit filename, which explains what kind of operation the flow will perform on items of the SharePoint list. To summarise, these features are available on this repository :

* remove duplicates in SharePoint list (based on any column has duplication criteria)
* empty list [check if it is really useful, can be redundant with "create from another list feature]
* import Excel table in an existing list
* transfer data of each item from one column to another one
