###Problem
Application requires many tasks of various complexities that is developed as a monolithic module. Limited code reuse.

###Solution
Decompose the processing required for each stream into a set of discrete components (or filters), each of which performs a single task.

####Notes
  * Standardize the format of the data that each component receives and emits.
  * Filters are combined into a pipeline.
  * <https://msdn.microsoft.com/en-us/library/dn568100.aspx>

note:
scale independently  
__Microservices__ that can be updated/swapped out adhoc.