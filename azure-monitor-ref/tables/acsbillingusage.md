---
title: Azure Monitor Logs reference - ACSBillingUsage
description: Reference for ACSBillingUsage table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 5/26/2023
---

# ACSBillingUsage

 Usage records across all modes of Communication Services.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Communication Services




## Columns

| Column | Type | Description |
| --- | --- | --- |
| _BilledSize | real |  |
| Category | string | The log category of the event. Logs with the same log category and resource type will have the same properties fields. |
| CorrelationId | string | The ID for correlated events. Can be used to identify correlated events between multiple tables. |
| EndTime | datetime | The time when resource consumption ended. Optional, as some events are instant by nature. |
| _IsBillable | string |  |
| OperationName | string | The operation associated with log record. |
| OperationVersion | string | The API-version associated with the operation or version of the operation (if there is no API version). |
| ParticipantId | string | Participant Id is the link between billing data and calling data. |
| Quantity | real | The amount of usage in terms of the specified unit. |
| RecordId | string | The unique ID for a given usage record. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| SourceSystem | string |  |
| StartTime | datetime | Time when the resource consumption started. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TenantId | string |  |
| TimeGenerated | datetime | The timestamp (UTC) of when the log was generated. |
| Type | string | The name of the table |
| UnitType | string | The unit in which the type of usage is measured. |
| UsageType | string | The type of resource being consumed. |
| UserIdA | string | User ID consuming the resource. |
| UserIdB | string | User ID consuming the resource for consumables involving two users. |
