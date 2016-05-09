###Problem
App server must handle requests to download static content. This absorbs processing cycles that could often be put to better use.

###Solution
Locate some of an application’s resources and static pages in a storage service. The cost for cloud-hosted storage is typically much less than for compute instances.

####Notes
  * Secure resources that are not intended to be available to anonymous users.
  * <https://msdn.microsoft.com/en-us/library/dn589776.aspx>

note: 
__Save money__ minimize the requirement for compute instances.
