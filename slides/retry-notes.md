###Problem
Temporary faults can occur in your own or others services and are not uncommon.

###Solution
Application detects a failure when it attempts to send a request to a remote service, and trys again.

####Notes
  * Period between retries should be chosen as to spread requests evenly amount instances.
  * Requests sent to different services can be subject to different policies and strategies.
  * <https://msdn.microsoft.com/en-us/library/dn589788.aspx>

note:
service might be getting an unexpected high number of requests and __busy__  
mitigate __single point of failures__.
__parameterize__ policies.