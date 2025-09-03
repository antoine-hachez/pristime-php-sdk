# # Worker

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Your system&#39;s unique identifier for this worker (e.g., employee ID, database primary key). |
**name** | **string** | Worker&#39;s display name for scheduling interfaces and reports. |
**min_break_duration** | [**\OpenAPI\Client\Model\MinBreakDuration**](MinBreakDuration.md) |  | [optional]
**max_consecutive_workdays** | [**\OpenAPI\Client\Model\MaxConsecutiveWorkdays**](MaxConsecutiveWorkdays.md) |  | [optional]
**balances** | [**\OpenAPI\Client\Model\Balances**](Balances.md) |  | [optional]
**periods** | [**\OpenAPI\Client\Model\PeriodContract[]**](PeriodContract.md) | Contract periods defining work expectations, time limits, and labor rules for different date ranges. | [optional]
**availability** | [**\OpenAPI\Client\Model\Availability**](Availability.md) |  | [optional]
**costs** | [**\OpenAPI\Client\Model\WorkerCost**](WorkerCost.md) |  | [optional]
**revenues** | [**\OpenAPI\Client\Model\WorkerRevenue**](WorkerRevenue.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
