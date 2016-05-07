###Problem
Data may be spread across an assortment of data sources held in a variety of geographic locations. Data store must be undone reliably.

###Solution
Intelligent process that takes into account any work done by concurrent instances.

####Notes
  * Application should not attempt to provide strong transactional consistency. (ACID)
  * Implement _eventual consistency_. (BASE)
  * <https://msdn.microsoft.com/en-us/library/dn589804.aspx>

note:
May involve __invoking the service again__ and performing another action that __reverses__ the effects of the first.
