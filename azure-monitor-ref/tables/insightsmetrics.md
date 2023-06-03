---
title: Azure Monitor Logs reference - InsightsMetrics
description: Reference for InsightsMetrics table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 5/26/2023
---

# InsightsMetrics
This table contains additional indicators to monitor system indicators of Azure Virtual Machines resources (CPU, memory, disks etc).


## Categories

- Virtual Machines
- Containers
- Azure Resources
## Solutions

- AzureResources
- ContainerInsights
- InfrastructureInsights
- LogManagement
- Service Map
- Azure Monitor for VMs
## Resource types

- Kubernetes Services
- Workload Monitoring of Azure Monitor Insights
- Virtual machines
- VMware
- Azure Stack HCI
- System Center Virtual Machine Manager
- Virtual Machine Scale Sets
- Azure Arc Enabled Kubernetes
- Azure Arc Provisioned Clusters
- IoT Hub




## Columns

| Column | Type | Description |
| --- | --- | --- |
| AgentId | string |  |
| _BilledSize | real |  |
| Computer | string |  |
| _IsBillable | string |  |
| Name | string |  |
| Namespace | string |  |
| Origin | string |  |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string |  |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| Tags | string |  |
| TimeGenerated | datetime |  |
| Type | string | The name of the table |
| Val | real |  |
| Value | string |  |
