### Problem
Deploying lots of instances as part of the same application can increase runtime hosting costs and make management of the system more complex.

### Solution
Consolidate multiple tasks or operations into a single computational unit. (_Separation of Concerns_ anti-pattern).

#### Notes
  * Look for tasks that have a similar profile concerning their scalability, lifetime, and processing requirement.
  * Grouping items together allows them to scale as a unit.
  * <https://msdn.microsoft.com/en-us/library/dn589778.aspx>

note:
__Separation of Conerns__ working against you financially, complex
