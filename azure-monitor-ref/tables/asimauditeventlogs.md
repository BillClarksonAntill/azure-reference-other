---
title: Azure Monitor Logs reference - ASimAuditEventLogs
description: Reference for ASimAuditEventLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 5/26/2023
---

# ASimAuditEventLogs

 Microsoft Sentinel normalized audit events table. Stores events associated with the audit trail of information systems and audit trail logs system configuration activities and policy changes. Such changes are often performed by system administrators, but can also be performed by users when configuring the settings of their own applications.

## Categories

- Security
## Solutions

- LogManagement
## Resource types

- Azure Sentinel




## Columns

| Column | Type | Description |
| --- | --- | --- |
| ActingAppId | string | The ID of the application that initiated the activity reported, including a process, browser, or service. |
| ActingAppName | string | The name of the application that initiated the activity reported, including a service, a URL, or a SaaS application. |
| ActingAppType | string | The type of acting application. |
| ActorOriginalUserType | string | The user type as reported by the reporting device. |
| ActorScope | string | The scope, such as Azure AD tenant, in which ActorUserId and ActorUsername are defined. |
| ActorScopeId | string | The scope ID, such as Azure AD tenant ID, in which ActorUserId and ActorUsername are defined. |
| ActorSessionId | string | The unique ID of the sign-in session of the Actor. |
| ActorUserAadId | string | The Azure Active Directory ID of the actor. |
| ActorUserId | string | A machine-readable, alphanumeric, unique representation of the actor. |
| ActorUserIdType | string | The type of the ID stored in the ActorUserId field. |
| ActorUsername | string | The Actor's username, including domain information when available. |
| ActorUsernameType | string | The type of the Actor's username specified in ActionUsername field |
| ActorUserSid | string | The Windows user ID (SIDs) of the actor. |
| ActorUserType | string | The type of the Actor. |
| AdditionalFields | dynamic | Additional information, represented using key/value pairs provided by the source which do not map to ASim. |
| _BilledSize | real |  |
| DvcAction | string | For reporting security systems, the action taken by the system. |
| DvcDescription | string | A descriptive text associated with the device. |
| DvcDomain | string | The domain of the device reporting the event. |
| DvcDomainType | string | The type of DvcDomain. |
| DvcFQDN | string | The hostname of the device on which the event occurred or which reported the event. |
| DvcHostname | string | The hostname of the device reporting the event. |
| DvcId | string | The unique ID of the device on which the event occurred or which reported the event. |
| DvcIdType | string | The type of DvcId. |
| DvcInterface | string | The network interface on which data was captured. |
| DvcIpAddr | string | The IP Address of the device reporting the event. |
| DvcMacAddr | string | The MAC address of the device on which the event occurred or which reported the event. |
| DvcOriginalAction | string | The original DvcAction as provided by the reporting device. |
| DvcOs | string | The operating system running on the device on which the event occurred or which reported the event. |
| DvcOsVersion | string | The version of the operating system on the device on which the event occurred or which reported the event. |
| DvcScope | string | The cloud platform scope the device belongs to. DvcScope map to a subscription ID on Azure and to an account ID on AWS. |
| DvcScopeId | string | The cloud platform scope ID the device belongs to. DvcScopeId map to a subscription ID on Azure and to an account ID on AWS. |
| DvcZone | string | The network on which the event occurred or which reported the event. |
| EventCount | int | The number of events described by the record. |
| EventEndTime | datetime | The time (UTC) in which the event ended. If the source supports aggregation and the record represents multiple events, the time that the last event was generated. If not provided by the source record, this field aliases the TimeGenerated field. |
| EventMessage | string | A general message or description. |
| EventOriginalResultDetails | string | The original result details provided by the source. |
| EventOriginalSeverity | string | The original severity as provided by the reporting device.  |
| EventOriginalSubType | string | The original event subtype or ID, if provided by the source. |
| EventOriginalType | string | The original event type or ID, if provided by the source. |
| EventOriginalUid | string | A unique ID of the original record, if provided by the source. |
| EventOwner | string | The owner of the event, which is usually the department or subsidiary in which it was generated. |
| EventProduct | string | The product generating the event. |
| EventProductVersion | string | The version of the product generating the event. |
| EventReportUrl | string | A URL provided in the event for a resource that provides more information about the event. |
| EventResult | string | The outcome of the event, represented by one of the following values: Success, Partial, Failure, NA (Not Applicable). The value may not be provided directly by the sources, in which case it is derived from other event fields, for example, the EventResultDetails field. |
| EventResultDetails | string | Reason or details for the result reported in the EventResult field. |
| EventSchemaVersion | string | The version of the schema. |
| EventSeverity | string | The severity of the event. Valid values are: Informational, Low, Medium, or High. |
| EventStartTime | datetime | The time (UTC) in which the event started. If the source supports aggregation and the record represents multiple events, the time that the first event was generated. If not provided by the source record, this field aliases the TimeGenerated field. |
| EventSubType | string | Describes a subdivision of the operation reported in the EventType field. |
| EventType | string | Describes the operation reported by the record |
| EventVendor | string | The vendor of the product generating the event. |
| HttpUserAgent | string | When authentication is performed over HTTP or HTTPS, this field's value is the user_agent HTTP header provided by the acting application when performing the authentication. |
| _IsBillable | string |  |
| NewValue | string | The new value of Object after the operation was performed. |
| Object | string | The name of the object on which the operation identified by EventType is performed. |
| ObjectId | string | The name of the object on which the operation identified by EventType is performed. |
| ObjectType | string | The type of Object. |
| OldValue | string | The old value of Object prior to the operation. |
| Operation | string | The operation audited as reported by the reporting device. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| RuleName | string | The name or ID of the rule associated with the inspection results. |
| RuleNumber | int | The number of the rule associated with the inspection results. |
| SourceSystem | string |  |
| SrcDescription | string | A descriptive text associated with the source device. |
| SrcDeviceType | string | The type of the source device. |
| SrcDomain | string | The domain of the source device. |
| SrcDomainType | string | The type of SrcDomain. |
| SrcDvcId | string | The ID of the source device. |
| SrcDvcIdType | string | The type of SrcDvcId. |
| SrcDvcScope | string | The cloud platform scope the source device belongs to. SrcDvcScope map to a subscription ID on Azure and to an account ID on AWS. |
| SrcDvcScopeId | string | The cloud platform scope ID the source device belongs to. SrcDvcScopeId map to a subscription ID on Azure and to an account ID on AWS. |
| SrcFQDN | string | The source device hostname, including domain information when available. |
| SrcGeoCity | string | The city associated with the source IP address. |
| SrcGeoCountry | string | The country associated with the source IP address. |
| SrcGeoLatitude | real | The latitude of the geographical coordinate associated with the source IP address. |
| SrcGeoLongitude | real | The longitude of the geographical coordinate associated with the source IP address. |
| SrcGeoRegion | string | The region within a country associated with the source IP address. |
| SrcHostname | string | The source device hostname, excluding domain information. |
| SrcIpAddr | string | The Source IP address from which the connection or session originated. |
| SrcOriginalRiskLevel | string | The risk level associaeted with the identified Source as reported by the reporting device. |
| SrcPortNumber | int | The Source IP port from which the connection originated. |
| SrcRiskLevel | int | The risk level associated with the identified Source. |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| TargetAppId | string | The ID of the application to which the event applies, including a process, browser, or service. |
| TargetAppName | string | The name of the application to which event applies, including a service, a URL, or a SaaS application. |
| TargetAppType | string | The type of the application authorizing on behalf of the Actor. |
| TargetDescription | string | A descriptive text associated with the target device. |
| TargetDeviceType | string | The type of the target device. |
| TargetDomain | string | The domain of the target device. |
| TargetDomainType | string | The type of TargetDomain. |
| TargetDvcId | string | The ID of the target device. |
| TargetDvcIdType | string | The type of TargetDvcId. |
| TargetDvcOs | string | The OS of the target device. |
| TargetDvcScope | string | The cloud platform scope the target device belongs to. TargetDvcScope map to a subscription ID on Azure and to an account ID on AWS. |
| TargetDvcScopeId | string | The cloud platform scope ID the target device belongs to. TargetDvcScopeId map to a subscription ID on Azure and to an account ID on AWS. |
| TargetFQDN | string | The target device hostname, including domain information when available. |
| TargetGeoCity | string | The city associated with the target IP address. |
| TargetGeoCountry | string | The country associated with the target IP address. |
| TargetGeoLatitude | real | The latitude of the geographical coordinate associated with the target IP address. |
| TargetGeoLongitude | real | The longitude of the geographical coordinate associated with the target IP address. |
| TargetGeoRegion | string | The region within a country associated with the target IP address. |
| TargetHostname | string | The target device hostname, excluding domain information. |
| TargetIpAddr | string | The Target IP address from which the connection or session originated. |
| TargetOriginalRiskLevel | string | The risk level associated with the target, as reported by the reporting device. |
| TargetPortNumber | int | The Target IP port from which the connection originated. |
| TargetRiskLevel | int | The risk level associated with the target. |
| TargetUrl | string | A URL associated with the target application. |
| TenantId | string |  |
| ThreatCategory | string | The category of the threat or malware identified in audit activity. |
| ThreatConfidence | int | The confidence level of the threat identified, normalized to a value between 0 and a 100. |
| ThreatField | string | The field for which a threat was identified. |
| ThreatFirstReportedTime | datetime | The first time the IP address or domain were identified as a threat. |
| ThreatId | string | The ID of the threat or malware identified in the audit activity. |
| ThreatIpAddr | string | An IP address or Domain for which a threat was identified. |
| ThreatIsActive | bool | True if the threat identified is considered an active threat. |
| ThreatLastReportedTime | datetime | The last time the IP address or domain were identified as a threat. |
| ThreatName | string | The name of the threat or malware identified in the audit activity. |
| ThreatOriginalConfidence | string | The original confidence level of the threat identified, as reported by the reporting device. |
| ThreatOriginalRiskLevel | string | The risk level as reported by the reporting device. |
| ThreatRiskLevel | int | The risk level associated with the identified threat. The level should be a number between 0 and 100. |
| TimeGenerated | datetime | The timestamp (UTC) reflecting the time in which the event was generated. |
| Type | string | The name of the table |
| ValueType | string | The type of the old and new values.  |
