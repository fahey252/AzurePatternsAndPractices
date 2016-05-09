###Problem
Multiple instances of the same task could be running simultaneously with each instance servicing a different user, overwritting others work.

###Solution
Instance is elected as leader. This instance should coordinate the actions of the other subordinate task instances.

####Notes
  * Ensures that task instances do not conflict with each other
  * <https://msdn.microsoft.com/en-us/library/dn568104.aspx>