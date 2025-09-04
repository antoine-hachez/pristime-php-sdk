# # Shift

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**start_datetime** | **\DateTime** | Beginning of the time period (inclusive). This exact moment is included in the period. Must be rounded to the nearest minute for scheduling precision. |
**end_datetime** | **\DateTime** | End of the time period (exclusive). This exact moment is NOT included in the period, allowing periods to be adjacent without overlap. Must be rounded to the nearest minute. |
**timezone** | **string** | Timezone for interpreting start_datetime and end_datetime |
**id** | **string** |  | [optional]
**label** | **string** |  | [optional]
**revenues** | [**\PristimePhpSdk\Model\ShiftRevenues**](ShiftRevenues.md) |  | [optional]
**revenue** | **int** | Additional fixed revenue value for this specific shift, added to calculated hourly revenues. | [optional] [default to 0]
**breaks** | [**\PristimePhpSdk\Model\Period[]**](Period.md) | Unpaid break periods during the shift (lunch, rest breaks). Breaks are subtracted from total shift duration to calculate actual work time. Must be entirely within the shift timeframe. | [optional]
**tags** | **string[]** | Descriptive labels for the shift type, location, or characteristics. Used to match shifts with demand requirements. | [optional]
**required_skills** | **string[]** | Skills, certifications, or qualifications that a worker must possess to be assigned to this shift. Workers without these skills will be ineligible. | [optional]
**assignment** | [**\PristimePhpSdk\Model\ShiftAssignment**](ShiftAssignment.md) |  | [optional]
**preceding_shift_id** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
