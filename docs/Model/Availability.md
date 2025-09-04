# # Availability

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**unavailable_periods** | [**\PristimeSdk\Model\Period[]**](Period.md) | Time periods when worker cannot work at all (vacation, appointments, other commitments). These are hard constraints - no shifts will be assigned during these times. | [optional]
**preferred_periods** | [**\PristimeSdk\Model\Period[]**](Period.md) | Time periods when worker prefers to work (preferred hours, days off). The optimizer will prioritize assigning shifts during these times when possible. | [optional]
**unpreferred_periods** | [**\PristimeSdk\Model\Period[]**](Period.md) | Time periods when worker prefers not to work but is available if needed (late nights, early mornings). Used as last resort or penalized in optimization. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
