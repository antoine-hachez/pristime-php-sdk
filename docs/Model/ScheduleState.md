# # ScheduleState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**scheduling_period** | [**\PristimePhpSdk\Model\SchedulingPeriod**](SchedulingPeriod.md) |  |
**workers** | [**\PristimePhpSdk\Model\Worker[]**](Worker.md) | Your staff members available for shift assignment. Include their availability, skills, work constraints, and contract details. | [optional]
**shifts** | [**\PristimePhpSdk\Model\Shift[]**](Shift.md) | Work shifts to be optimized. Can include assigned and unassigned shifts. | [optional]
**demands** | [**\PristimePhpSdk\Model\Demand[]**](Demand.md) | Staffing requirements over time - specify how many workers with certain skills you need at different times. | [optional]
**config** | [**\PristimePhpSdk\Model\ScheduleJobConfig**](ScheduleJobConfig.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
