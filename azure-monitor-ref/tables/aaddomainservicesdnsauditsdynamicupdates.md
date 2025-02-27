---
title: Azure Monitor Logs reference - AADDomainServicesDNSAuditsDynamicUpdates
description: Reference for AADDomainServicesDNSAuditsDynamicUpdates table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 5/26/2023
---

# AADDomainServicesDNSAuditsDynamicUpdates

 DNS server audit events enable change tracking on the DNS server. This table contains operational audit events for dynamic updates.

## Solutions

- LogManagement
## Resource types

- Azure AD Domain Services




## Columns

| Column | Type | Description |
| --- | --- | --- |
| _BilledSize | real |  |
| BufferSize | int | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName. Please see the Windows Server description of this event for the meaning of this field. |
| EventType | string | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName. Please see the Windows Server description of this event for the meaning of this field. |
| _IsBillable | string |  |
| Name | string | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName. Please see the Windows Server description of this event for the meaning of this field. |
| operationName | string | Identifies the type of event emitted. |
| operationVersion | string | Version string.  Reserved. |
| RData | string | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName. Please see the Windows Server description of this event for the meaning of this field. |
| RecordId | string | Identifier for the underlying Windows event |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| resultDescription | string | Summary description of the event. |
| Source | string | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName. Please see the Windows Server description of this event for the meaning of this field. |
| SourceSystem | string |  |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string |  |
| TimeGenerated | datetime | The timestamp (UTC) of when the event was generated. |
| Ttl | int | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName. Please see the Windows Server description of this event for the meaning of this field. |
| Type | string | The name of the table |
| Zone | string | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName. Please see the Windows Server description of this event for the meaning of this field. |
| ZoneScope | string | The context of this field is dependent on the Windows Event being emitted, represented in the OperationName. Please see the Windows Server description of this event for the meaning of this field. |
