###Problem
Data store hosted by a single server may be subject to limitations such as storage space, bandwidth, computing resources and location.

###Solution
Divide the data store into horizontal partitions or _shards_. Each shard has the same schema, but holds its own distinct subset of the data.

####Notes
  * Scaling vertically may postpone the effects of some of these limitations.
  * <https://msdn.microsoft.com/en-us/library/dn589797.aspx>

note: 
To ensure optimal performance and scalability, it is important to __split the data in a way that is appropriate__ for the types of queries the application performs  
