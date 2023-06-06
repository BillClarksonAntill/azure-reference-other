---
title: Azure Monitor Logs reference - DeviceTvmSecureConfigurationAssessmentKB
description: Reference for DeviceTvmSecureConfigurationAssessmentKB table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 5/26/2023
---

# DeviceTvmSecureConfigurationAssessmentKB

This table is part of Microsoft Defender for Endpoint and captures the Knowledge base of various security configurations used by Threat & Vulnerability Management to assess devices and includes mappings to various standards and benchmarks.

## Categories

- Security
## Solutions

- Microsoft Sentinel
- Microsoft Defender for Endpoint


## Columns

| Column | Type | Description |
| --- | --- | --- |
| _BilledSize | real |  |
| ConfigurationBenchmarks | dynamic | List of industry benchmarks which recommend the same or similar configuration. |
| ConfigurationCategory | string | Category or grouping to which the configuration belongs. |
| ConfigurationDescription | string | Description of the configuration. |
| ConfigurationId | string | Unique identifier for a specific configuration. |
| ConfigurationImpact | real | Rated impact of the configuration to the overall configuration score (1-10). |
| ConfigurationName | string | Display name of the configuration. |
| ConfigurationSubcategory | string | Subcategory or subgrouping to which the configuration belongs. Commonly, this describes specific capabilities or features. |
| _IsBillable | string |  |
| RelatedMitreTactics | dynamic | Related tactics from Mitre knowledge base. |
| RelatedMitreTechniques | dynamic | Related techniques from Mitre knowledge base. |
| RemediationOptions | string | Recommended actions to reduce or address any associated risks |
| RiskDescription | string | Description of any associated risks. |
| SourceSystem | string |  |
| Tags | dynamic | Labels representing various attributes, used to identify or categorize a security configuration. |
| TenantId | string |  |
| TimeGenerated | datetime | Date and time when the record was generated. |
| Timestamp | datetime | Date and time when the record was generated |
| Type | string | The name of the table |
