---
title: Azure Monitor Logs reference - SecurityRecommendation
description: Reference for SecurityRecommendation table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 5/26/2023
---

# SecurityRecommendation

 

## Categories

- Security
## Solutions

- AzureSecurityOfThings
- Security and Audit
- SecurityCenterFree




## Columns

| Column | Type | Description |
| --- | --- | --- |
| AssessedResourceId | string |  |
| _BilledSize | real |  |
| Description | string |  |
| DeviceId | string |  |
| DiscoveredTimeUTC | datetime |  |
| Environment | string |  |
| FirstEvaluationDate | datetime |  |
| _IsBillable | string |  |
| IsSnapshot | bool |  |
| PolicyDefinitionId | string |  |
| Properties | dynamic |  |
| ProviderName | string |  |
| RecommendationAdditionalData | dynamic |  |
| RecommendationDisplayName | string |  |
| RecommendationId | string |  |
| RecommendationName | string |  |
| RecommendationSeverity | string |  |
| RecommendationState | string |  |
| ResolvedTimeUTC | datetime |  |
| ResourceRegion | string |  |
| StatusChangeDate | datetime |  |
| TimeGenerated | datetime |  |
| Type | string | The name of the table |
