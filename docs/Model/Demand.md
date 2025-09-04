# # Demand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Your system&#39;s unique identifier for this demand (e.g., department ID, location ID, event ID). |
**timezone** | **string** | Timezone for interpreting the demand time series and any automatically created shifts. Should match your local business timezone. |
**required_skills** | **string[]** | Skills, certifications, or qualifications that workers must possess to fulfill this demand. Only workers with all these skills will be considered. |
**required_tags** | **string[]** | Tags that shifts must have to count toward fulfilling this demand. Useful for matching specific shift types, locations, or characteristics. |
**label** | **string** |  | [optional]
**time_series** | **array<string,float>** | Staffing level requirements over time as change points. Each entry specifies when the required number of workers changes. Format: {timestamp: worker_count}. The last entry must be 0 to indicate demand end. | [optional]
**upper_limit_increment** | **int** |  | [optional]
**revenues** | **object** |  | [optional]
**shift_creation_settings** | [**\PristimePhpSdk\Model\ShiftCreationSettings**](ShiftCreationSettings.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
