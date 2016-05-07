###Problem
System may be overloaded by an influx of messages coming from the application.

###Solution
System can run multiple instances of the consumer service. Coordinated effort so work isn't duplicated.

####Notes
  * Reduces _bottlenecks_.
  * Dynamically increase or decrease the number of instances of the consumer service as the volume of messages fluctuates.
  * <https://msdn.microsoft.com/en-us/library/dn568101.aspx>