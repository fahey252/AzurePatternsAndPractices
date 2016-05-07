###Problem
In a distributed environment, unexpected events may cause resources to break and try to rectify themselves continously.

###Solution
Quickly accept that the operation has failed and handle this failure accordingly (backoff logic or stop trying).

####Notes
  * Prevent an application repeatedly trying to execute an operation that is likely to fail.
  * Can enable an application to detect whether the fault has been resolved.
  * <https://msdn.microsoft.com/en-us/library/dn589784.aspx>

note:
__proxy for operations__ that may fail.
proxy should __monitor recent failures__ that have occurred  
Usually partners with the __Retry Pattern__.

