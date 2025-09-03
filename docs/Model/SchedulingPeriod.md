# # SchedulingPeriod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**start_date** | **\DateTime** | First date to include in the scheduling optimization (inclusive). |
**end_date** | **\DateTime** | Last date to include in the scheduling optimization (inclusive). |
**timezone** | **string** | Primary timezone for the schedule. |
**day_boundary_offset_minutes** | **int** | Shifts the day boundary for night shift scheduling. Positive values (e.g., +120) move the day end to 02:00, so shifts starting before 02:00 belong to the previous calendar day. Useful for 24/7 operations. | [optional] [default to 0]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
