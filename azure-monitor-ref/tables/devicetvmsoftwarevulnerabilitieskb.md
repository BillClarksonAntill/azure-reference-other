---
title: Azure Monitor Logs reference - DeviceTvmSoftwareVulnerabilitiesKB
description: Reference for DeviceTvmSoftwareVulnerabilitiesKB table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 5/26/2023
---

# DeviceTvmSoftwareVulnerabilitiesKB

This table is part of Microsoft Defender for Endpoint and captures the Knowledge base of publicly disclosed vulnerabilities, including whether exploit code is publicly available.

## Categories

- Security
## Solutions

- Microsoft Sentinel
- Microsoft Defender for Endpoint


## Columns

| Column | Type | Description |
| --- | --- | --- |
| AffectedSoftware | dynamic | List of all software products affected by the vulnerability. |
| _BilledSize | real |  |
| CveId | string | Unique identifier assigned to the security vulnerability under the Common Vulnerabilities and Exposures (CVE) system. |
| CvssScore | real | Severity score assigned to the security vulnerability under the Common Vulnerability Scoring System (CVSS). |
| _IsBillable | string |  |
| IsExploitAvailable | bool | Indicates whether exploit code for the vulnerability is publicly available. |
| LastModifiedTime | datetime | Date and time the item or related metadata was last modified. |
| PublishedDate | datetime | Date vulnerability was disclosed to the public. |
| SourceSystem | string |  |
| TenantId | string |  |
| TimeGenerated | datetime | Date and time when the record was generated. |
| Timestamp | datetime | Date and time when the record was generated |
| Type | string | The name of the table |
| VulnerabilityDescription | string | Description of the vulnerability and associated risks. |
| VulnerabilitySeverityLevel | string | Severity level assigned to the security vulnerability based on the CVSS score and dynamic factors influenced by the threat landscape. |
