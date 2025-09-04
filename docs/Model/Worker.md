# # Worker

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Your system&#39;s unique identifier for this worker (e.g., employee ID, database primary key). |
**name** | **string** | Worker&#39;s display name for scheduling interfaces and reports. |
**min_break_duration** | [**\PristimeSdk\PristimeSdk\Model\MinBreakDuration**](MinBreakDuration.md) |  | [optional]
**max_consecutive_workdays** | [**\PristimeSdk\PristimeSdk\Model\MaxConsecutiveWorkdays**](MaxConsecutiveWorkdays.md) |  | [optional]
**balances** | [**\PristimeSdk\PristimeSdk\Model\Balances**](Balances.md) |  | [optional]
**periods** | [**\PristimeSdk\PristimeSdk\Model\PeriodContract[]**](PeriodContract.md) | Contract periods defining work expectations, time limits, and labor rules for different date ranges. | [optional]
**availability** | [**\PristimeSdk\PristimeSdk\Model\Availability**](Availability.md) |  | [optional]
**costs** | [**\PristimeSdk\PristimeSdk\Model\WorkerCost**](WorkerCost.md) |  | [optional]
**revenues** | [**\PristimeSdk\PristimeSdk\Model\WorkerRevenue**](WorkerRevenue.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
