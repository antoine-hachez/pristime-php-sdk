# # ShiftCreationSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**timezone** | **string** | Timezone for all automatically created shifts. Should typically match the demand&#39;s timezone and your business location. |
**break_minutes** | **int** | Duration in minutes for break periods that will be automatically added to created shifts. Breaks are unpaid time subtracted from work hours. |
**work_duration** | [**\PristimeSdk\PristimeSdk\Model\WorkDuration**](WorkDuration.md) |  |
**continuous_work_duration_before_break** | [**\PristimeSdk\PristimeSdk\Model\ContinuousWorkDurationBeforeBreak**](ContinuousWorkDurationBeforeBreak.md) |  |
**required_skills** | **string[]** | Skills, certifications, or qualifications required for workers to be assigned to created shifts. Must be a superset of the demand&#39;s required_skills. | [optional]
**tags** | **string[]** | Descriptive tags that will be applied to all created shifts. Must be a superset of the demand&#39;s required_shift_tags to ensure compatibility. | [optional]
**day_boundary_offset_minutes** | **int** | Day boundary adjustment for created shifts, useful for night shift operations. Positive values shift the day end later (e.g., +120 &#x3D; day ends at 2:00 AM). | [optional] [default to 0]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
