# # Balance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**current_minutes** | **int** | Current accumulated balance in minutes. Positive &#x3D; worker has worked more than expected, negative &#x3D; worker has worked less than expected. | [optional] [default to 0]
**min_minutes** | **int** | Minimum allowed balance in minutes (smallest value allowed). Prevents excessive time debt to workers. |
**max_minutes** | **int** | Maximum allowed balance in minutes (largest value allowed). Prevents excessive time debt from workers. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
