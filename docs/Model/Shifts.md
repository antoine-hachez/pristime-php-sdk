# # Shifts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provided** | [**array<string,\PristimePhpSdk\Model\ShiftAssignmentResult>**](ShiftAssignmentResult.md) | Assignment results for shifts you provided in the request, keyed by your original shift IDs. Shows which worker (if any) is now assigned to each existing shift. |
**created** | [**\PristimePhpSdk\Model\Shift[]**](Shift.md) | New shifts automatically created by the optimization algorithm to meet staffing demands. These are additional shifts beyond what you originally provided, always with assigned workers. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
