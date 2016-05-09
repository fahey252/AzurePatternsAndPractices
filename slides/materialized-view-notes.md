###Problem
When aggregates are needed, extract all of the data for the relevant entities in order to obtain the required information.

###Solution
Generate (in advanced) a view that _materializes_ the data in a format most suited to the required results set

####Notes
  * Data is completely disposable because it can be entirely rebuilt from the source data stores.
  * Automatically update on an appropriate schedule, or when the system detects a change to the original data.
  * <https://msdn.microsoft.com/en-us/library/dn589782.aspx>

note:
Improve performance of quering data.  
define materialize: __become actual fact__; happen.  