# # WorkerRevenue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**per_hour_of_negative_flextime_balance** | **int** | How much revenue is earned at the end of the period for each flex time balance negative hour | [optional] [default to 10]
**per_hour_of_pto** | **int** | How much revenue is earned for each pto time hour | [optional] [default to 1000]
**per_hour_of_preferred_period** | **int** | How much revenue is earned for each hour assigned during a preferred period | [optional] [default to 5]
**per_hour_of_skilled_work** | **array<string,int>** | Extra revenue per skill in euros per hour.         These skills are also used to determine the compatibility with shifts (shift.required_skills) and demands (demand.required_skills). | [optional]
**per_hour_of_tagged_work** | **array<string,int>** | Extra revenue per tagged work in euros per hour.         This revenue is used to make the assignment fairer towards workers that are lagging behind in the number of shifts with a specific tag. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
