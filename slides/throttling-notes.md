###Problem
Load on a cloud application typically varies over time based on the number of active users or the types of activities they are performing.

###Solution
System should monitor how it is using resources so that, when usage exceeds some system-defined threshold, it can throttle requests from one or more users to enable the system to continue functioning.

####Notes
  * The system may be obliged to meet an agreed level of service, and such failure could be unacceptable.
  * <https://msdn.microsoft.com/en-us/library/dn589798.aspx>

note:
Auto-scaling with __provisioning is not instantaneous__
