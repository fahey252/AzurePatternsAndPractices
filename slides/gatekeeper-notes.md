###Problem
Code that accepts requests from clients, likely to accesses storage with sensitive information. If one host compromised, other areas may be impacted.

###Solution
Decouple hosts or tasks that expose public endpoints from the code that processes requests and accesses storage.

####Notes
  * Dedicated instance that acts as a broker between clients.
  * If the Gatekeeper is compromised, the attacker does not obtain access to other credentials or keys. (Firewall-like.)
  * <https://msdn.microsoft.com/en-us/library/dn589793.aspx>