###Problem
Necessary to reconfigure the application to change specific behavior or settings while it is deployed and in use.

###Solution
Application code will respond to events that are raised by the hosting infrastructure when it detects a change to the application configuration.

####Notes
  * Depends on the features available in the application hosting environment.
  * Consider how you will roll back configuration changes that cause issues.
  * <https://msdn.microsoft.com/en-us/library/dn589785.aspx>

note:
Granularity of __logging levels__
__Polling mechanism__ that regularly checks for changes to the configuration.

