# # ScheduleJobResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**schedule_job_id** | **string** | Unique identifier for this scheduling job. Use this ID to track job progress and retrieve results via GET /schedule-jobs/{id}. |
**status** | **string** | Current job status: &#39;running&#39; (still processing), &#39;completed&#39; (finished successfully), or &#39;failed&#39; (encountered error). |
**message** | **string** |  | [optional]
**result** | [**\OpenAPI\Client\Model\ScheduleJobResult**](ScheduleJobResult.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
