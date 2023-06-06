---
title: Azure Monitor Logs reference - DeviceTvmSoftwareInventory
description: Reference for DeviceTvmSoftwareInventory table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 5/26/2023
---

# DeviceTvmSoftwareInventory

This table is part of Microsoft Defender for Endpoint and captures the Inventory of software installed on devices, including their version information and end-of-support status.

## Categories

- Security
## Solutions

- Microsoft Sentinel
- Microsoft Defender for Endpoint


## Columns

| Column | Type | Description |
| --- | --- | --- |
| _BilledSize | real |  |
| DeviceId | string | Unique identifier for the device in the service |
| DeviceName | string | Fully qualified domain name (FQDN) of the device |
| EndOfSupportDate | datetime | End-of-support (EOS) or end-of-life (EOL) date of the software product |
| EndOfSupportStatus | string | Indicates the lifecycle stage of the software product relative to its specified end-of-support (EOS) or end-of-life (EOL) date |
| _IsBillable | string |  |
| OSArchitecture | string | Architecture of the operating system running on the machine |
| OSPlatform | string | Platform of the operating system running on the device. This indicates specific operating systems, including variations within the same family, such as Windows 10 and Windows 7 |
| OSVersion | string | Version of the operating system running on the machine |
| ProductCodeCpe | string | The standard Common Platform Enumeration (CPE) name of the software product version |
| SoftwareName | string | Name of the software product |
| SoftwareVendor | string | Name of the software vendor |
| SoftwareVersion | string | Version number of the software product |
| SourceSystem | string |  |
| TenantId | string |  |
| TimeGenerated | datetime | Date and time when the record was generated |
| Type | string | The name of the table |
