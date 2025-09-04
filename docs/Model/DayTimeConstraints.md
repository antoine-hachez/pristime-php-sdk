# # DayTimeConstraints

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**max_scheduled_time_minutes** | **int** | Maximum total scheduled minutes on this date including work (assigned time), PTO, and recovery time. Sets overall daily time limit regardless of activity type. |
**contractual_minutes** | **int** |  | [optional]
**min_expected_time_minutes** | **int** | Minimum guaranteed hours in minutes the worker must be paid for on this date if they&#39;re scheduled at all. | [optional] [default to 0]
**max_expected_time_minutes** | **int** | Maximum hours in minutes the worker is expected to work on this date before it becomes overtime. Sets the boundary for regular vs overtime pay. | [optional] [default to 0]
**max_overtime_minutes** | **int** | Maximum overtime hours in minutes allowed on this date. | [optional] [default to 1440]
**min_assigned_time_minutes** | **int** | Minimum productive work time in minutes that must be assigned if the worker is scheduled. | [optional] [default to 0]
**max_assigned_time_minutes** | **int** | Maximum productive work time in minutes that can be assigned on this date. Limits actual working time regardless of total scheduled time. | [optional] [default to 1440]
**max_recovered_time_minutes** | **int** | Maximum overtime recovery time in minutes that can be taken on this date. | [optional] [default to 1440]
**max_pto_time_minutes** | **int** | Maximum paid time off minutes (vacation, sick leave) that can be taken on this date. | [optional] [default to 0]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
