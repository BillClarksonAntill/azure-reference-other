---
title: Azure Monitor Logs reference - ACSCallSurvey
description: Reference for ACSCallSurvey table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 5/26/2023
---

# ACSCallSurvey

 Call survey provides information about the call surveys submitted by the participants.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- Communication Services




## Columns

| Column | Type | Description |
| --- | --- | --- |
| AudioIssues | string | Comma separated audio issues reported by the participant. |
| AudioRatingScore | int | Audio experience rated by the participant. |
| AudioRatingScoreLowerBound | int | Minimum value of the AudioRatingScore scale. |
| AudioRatingScoreThreshold | int | The AudioRatingScore greater than this value indicates better quality. |
| AudioRatingScoreUpperBound | int | Maximum value of the AudioRatingScore scale. |
| _BilledSize | real |  |
| CallId | string | The identifier of the call used to correlate. Can be used to identify correlated events between multiple tables. |
| CorrelationId | string | The ID for correlated events. This field contains the participant ID that allows call survey to be correlated with other calling logs. |
| _IsBillable | string |  |
| OperationName | string | The operation associated with log record. |
| OperationVersion | string | The API-version associated with the operation or version of the operation (if there is no API version). |
| OverallCallIssues | string | Comma separated overall issues reported by the participant. |
| OverallRatingScore | int | Overall call experience rated by the participant. |
| OverallRatingScoreLowerBound | int | Minimum value of the OverallRatingScore scale. |
| OverallRatingScoreThreshold | int | The OverallRatingScore greater than this value indicates better quality. |
| OverallRatingScoreUpperBound | int | Maximum value of the OverallRatingScore scale. |
| ParticipantId | string | ID of the participant. |
| _ResourceId | string | A unique identifier for the resource that the record is associated with |
| ScreenshareIssues | string | Comma separated screenshare issues reported by the participant. |
| ScreenshareRatingScore | int | Screenshare experience rated by the participant. |
| ScreenshareRatingScoreLowerBound | int | Minimum value of the ScreenshareRatingScore scale. |
| ScreenshareRatingScoreThreshold | int | The ScreenshareRatingScore greater than this value indicates better quality. |
| ScreenshareRatingScoreUpperBound | int | Maximum value of the ScreenshareRatingScore scale. |
| SourceSystem | string |  |
| _SubscriptionId | string | A unique identifier for the subscription that the record is associated with |
| SurveyId | string | The ID of the survey uniquely identifies the call survey. |
| TenantId | string |  |
| TimeGenerated | datetime | The timestamp (UTC) of when the log was generated. |
| Type | string | The name of the table |
| VideoIssues | string | Comma separated video issues reported by the participant. |
| VideoRatingScore | int | Video experience rated by the participant. |
| VideoRatingScoreLowerBound | int | Minimum value of the VideoRatingScore scale. |
| VideoRatingScoreThreshold | int | The VideoRatingScore greater than this value indicates better quality. |
| VideoRatingScoreUpperBound | int | Maximum value of the VideoRatingScore scale. |
