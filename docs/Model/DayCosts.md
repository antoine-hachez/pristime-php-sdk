# # DayCosts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**per_expected_hour** | **int** | Cost per hour of expected work time. Used when worker has guaranteed hours that must be paid regardless of actual assignments. | [optional] [default to 0]
**per_flextime_positive_hour** | **int** | Cost per hour when worker exceeds their standard daily hours (positive flextime). Higher values discourage over-scheduling on individual days. | [optional] [default to 8]
**per_overtime_hour** | **int** | Cost per hour of overtime work beyond regular hours. Set higher to limit overtime usage to only high-value shifts. | [optional] [default to 50]
**per_assigned_hour** | **int** | Base cost per hour for any assigned shift work. Represents the fundamental cost of having a worker on duty. | [optional] [default to 0]
**per_idle_hour_between_shifts** | **int** | Cost per hour of paid idle time between shifts on the same day. Higher values encourage tighter scheduling with fewer gaps. | [optional] [default to 1]
**per_undertime_hour** | **int** | Small cost per hour when worker is scheduled less than expected. Helps ensure workers get their expected hours when possible. | [optional] [default to 10]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
