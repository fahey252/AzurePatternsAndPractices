###Problem
Data will be read, modified, and updated. Current state of the data with the new values may be locked by transactions.

###Solution
Handle operations on data that is driven by a sequence of events, each of which is recorded in an append-only store.

####Notes
  * Append-only store to record the full series of events that describe actions taken.
  * Data update conflicts are more likely to occur because the update operations take place on a single item of data.
  * <https://msdn.microsoft.com/en-us/library/dn589792.aspx>

note:
__Layering__  
Problems: overhead, concurrent users, no history and audit trail.  
Materialize the current state of an entity by effectively __playing back__.