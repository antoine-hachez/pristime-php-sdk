# # Constraint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**caller_shift_ids** | **string[]** | List of shift IDs that this constraint applies to. These are the shifts that will be limited in their assignment to the specified workers. | [optional]
**caller_worker_ids** | **string[]** | List of worker IDs that this constraint applies to. These are the workers who are subject to the assignment limitation for the specified shifts. | [optional]
**max_assigned** | **int** | Maximum number of shifts (from caller_shift_ids) that can be assigned to any combination of workers (from caller_worker_ids). Use 1 for exclusive assignment, higher numbers for load distribution. | [optional] [default to 1]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
