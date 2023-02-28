# Azure Kubernetes Service Workbook

## Overview

This repository contains an Azure Workbook which can be used to monitor Azure Kubernetes clusters. This workbook is a work in-progress and is provided as a sample for people to build from.

## Workbook Visual Examples

### Traffic Light

![traffic-light](.images/trafficlight.png)
### Failed Events

![events](.images/failed-events.png)

### Logs

![logs](.images/logs.png)

## How To

To use this Workbook you need to:

1. Copy the content from the file `workbook.json`.

2. Open the [Azure Workbook](https://ms.portal.azure.com/#view/Microsoft_Azure_Monitoring/AzureMonitoringBrowseBlade/~/workbooks/menuId/workbooks) page and click `New`.
![new-workbook](.images/workbook-new.png)
3. Click on the `code` button.
![code-button](.images/workbook-developer-import.png)
4. Paste the content copied in step 1 into the page and click `Apply`.
![import](.images/workbook-import.png)
5. Save the Workbook (if you have permissions) and click `Done Editing`.

## To Do

- Optimise queries
- Add request/limit analysis
- Create a namespace parameter to filter with

## Documentation

- [AKS Troubleshooting Guide](https://learn.microsoft.com/en-us/troubleshoot/azure/azure-kubernetes/welcome-azure-kubernetes)
