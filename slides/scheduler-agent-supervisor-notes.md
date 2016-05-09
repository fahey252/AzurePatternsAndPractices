###Problem
Perform tasks that comprise a number of steps, some of which may fail.

###Solution
Restore the system to a consistent state and ensure integrity of the entire end-to-end operation.

####Notes
  * __Scheduler__: Arranges for the individual steps that comprise the overall task.
  * __Agent__: Contains logic that makes calls to a remote service.
  * __Supervisor__: Monitors the status of the steps in the task being performed by the Scheduler.
  * <https://msdn.microsoft.com/en-us/library/dn589780.aspx>