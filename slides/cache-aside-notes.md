###Problem
Usually impractical to expect that cached data will always be completely consistent with the data in the data store.

###Solution
Load data on demand into a cache from a data store.

####Notes
  * Develop so cache is as up to date as possible, detect when cache is stale.
  * Make the modification to the data store, then invalidate the corresponding item in the cache.
  * <https://msdn.microsoft.com/en-us/library/dn589799.aspx>