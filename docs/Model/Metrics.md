# # Metrics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**start_date** | **\DateTime** | First date included in the metrics calculation period. |
**end_date** | **\DateTime** | Last date included in the metrics calculation period. |
**profit** | **float** | Total optimization value (all revenue minus all costs). Primary measure of scheduling effectiveness and business impact. |
**partial_profit** | **float** | Core profit excluding period-closing balance adjustments. Shows operational scheduling value without accounting complexities. |
**pto_time_revenue** | **float** | Revenue generated from optimally scheduling paid time off periods. Balances worker satisfaction with operational needs. |
**assignment_revenue** | **float** | Revenue from assigning workers to shifts based on shift value and worker suitability. Core revenue from successful matches. |
**skill_revenue** | **float** | Revenue bonus from matching workers with compatible shift requirements, skills, or preferences. Rewards optimal worker-shift pairing. |
**continuity_revenue** | **float** | Revenue from maintaining consistent worker schedules and minimizing assignment changes. Values schedule stability for worker satisfaction. |
**demand_revenue** | **float** | Revenue generated from meeting staffing demand requirements. Measures success in providing adequate coverage for business needs. |
**preferred_time_revenue** | **float** | Bonus revenue from scheduling workers during their preferred time periods. Balances worker preferences with operational requirements. |
**variable_costs** | **float** | Additional operational costs incurred from scheduling decisions. Includes dynamic costs that vary with assignment patterns. |
**overtime_cost** | **float** | Premium labor costs for overtime hours beyond regular contract time. Reflects the additional expense of extended work periods. |
**has_exceeded_preferred_max_consecutive_workdays_limit_cost** | **float** | Penalty cost when workers exceed preferred maximum consecutive workdays. |
**idle_time_cost** | **float** | Cost of unproductive time gaps between worker shifts. Encourages efficient schedule compactness while respecting break requirements. |
**assignment_cost** | **float** | Base labor costs for worker assignments including wages, benefits, and administrative overhead. Core cost of workforce utilization. |
**unpreferred_time_cost** | **float** | Penalty for scheduling workers during periods they marked as unpreferred. Balances operational needs with worker satisfaction. |
**period_closing_profit** | **float** | Profit adjustment for flextime and overtime balance management at period boundaries. Handles accounting for accumulated time credits/debts. |
**flextime_balance_negative_revenue** | **float** | Revenue from workers making up time debt (negative flextime balance). Helps ensure contract hour obligations are met. |
**flextime_balance_positive_cost** | **float** | Cost of accumulated worker time credits (positive flextime balance). Represents future time-off obligations or premium payments. |
**overtime_balance_cost** | **float** | Cost associated with managing overtime balances and accumulated overtime compensation. Tracks overtime liability management. |
**assigned_time** | **float** | Total minutes of productive work time assigned to workers. Core measure of workforce utilization and operational capacity. |
**overtime** | **float** | Total minutes of overtime scheduled beyond regular contract hours. Indicates reliance on premium labor to meet demands. |
**recovered_time** | **float** | Total minutes of overtime taken as paid time off instead of cash payment. Shows flexibility in overtime compensation management. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
