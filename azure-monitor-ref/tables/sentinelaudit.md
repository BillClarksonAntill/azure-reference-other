---
title: Azure Monitor Logs reference - SentinelAudit
description: Reference for SentinelAudit table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 5/26/2023
---

# SentinelAudit

 Audit logs for operations performed on Microsoft Sentinel resources, such as Data Connectors, Analytic Rules and more. These logs can be used to audit operations on your Microsoft Sentinel resources.

## Categories

- Security
- Audit
## Solutions

- Microsoft Sentinel




## Columns

| Column | Type | Description |
| --- | --- | --- |
| _BilledSize | real |  |
| CorrelationId | string | A unique record identifier. |
| Description | string | The operation description. |
| ExtendedProperties | dynamic | Additional information based on the resource type. |
| _IsBillable | string |  |
| OperationName | string | The name of the operation that triggered the event. |
| SentinelResourceId | string | The Sentinel resource ID. |
| SentinelResourceKind | string | The resource kind, for example: connector kind (such as Office365, AmazonWebServicesCloudTrail), alert rule kind (scheduld). |
| SentinelResourceName | string | The Sentinel resource name. |
| SentinelResourceType | string | The resource type, for example: DataConnector, AlertRule, etc. |
| SourceSystem | string |  |
| Status | string | Status of the operation, for example: Success, Failure, Warning, Informational, Partial Success. |
| TenantId | string |  |
| TimeGenerated | datetime | The timestamp (UTC) of when the event was generated. |
| Type | string | The name of the table |
| WorkspaceId | string | The workspace ID. |
