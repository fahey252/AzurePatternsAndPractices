###Problem
Users may be forced to use specific (and different) credentials for applications. Complicated user management.

###Solution
Separating user authentication from the application code, and delegating authentication to a trusted identity provider.

####Notes
  * Trusted identity providers (IdP) include corporate directories, on-premises federation services and others.
  * IdP issues __security tokens__ that assert information about the authenticated user (_claims_).
  * <https://msdn.microsoft.com/en-us/library/dn589790.aspx>