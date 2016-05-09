###Problem
 Difficult to predict the volume of requests to which the service might be subjected at any given point in time.

###Solution
Introduce a queue between the task and the service as a buffer.

####Notes
  * Many solutions in the cloud involve running tasks that invoke services.
  * Queue effectively decouples the tasks from the service.
  * <https://msdn.microsoft.com/en-us/library/dn589783.aspx>

note:
__Thottling__ with third parties.  
service can handle the messages at its own pace __irrespective of the volume__ of requests from concurrent tasks.  
__control costs__ because the number of service instances deployed needs only to be __sufficient to meet average load, not peak__