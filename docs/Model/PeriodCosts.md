# # PeriodCosts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**per_expected_hour** | **int** | Cost per hour of guaranteed time in the period. This discourages over-scheduling beyond minimum requirements. Set higher to prioritize cost control, lower to ensure full utilization. | [optional] [default to 0]
**per_flextime_positive_hour** | **int** | Cost per hour of positive flextime (time above contractual hours). Higher values encourage more consistent scheduling around standard contract hours rather than fluctuating weeks. | [optional] [default to 8]
**per_undertime_hour** | **int** | Small cost per hour of undertime (when scheduled time is below expected). Provides gentle pressure to meet minimum hour requirements without being too restrictive. | [optional] [default to 10]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
