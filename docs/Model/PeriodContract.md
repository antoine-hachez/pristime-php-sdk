# # PeriodContract

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**start_date** | **\DateTime** | First date (inclusive) of the contract period. All period-level rules and limits begin applying from this date. |
**end_date** | **\DateTime** | Last date (inclusive) of the contract period. All period-level rules and limits stop applying after this date. |
**time_constraints** | [**\PristimeSdk\Model\PeriodTimeConstraints**](PeriodTimeConstraints.md) |  | [optional]
**day_constraints** | [**\PristimeSdk\Model\PeriodDayConstraints**](PeriodDayConstraints.md) |  | [optional]
**days** | [**array<string,\PristimeSdk\Model\DayContract>**](DayContract.md) |  | [optional]
**costs** | [**\PristimeSdk\Model\PeriodCosts**](PeriodCosts.md) |  | [optional]
**flextime_factor** | **int** | Factor by which the flextime is multiplied before being added to the flextime_balance. | [optional] [default to 1]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
