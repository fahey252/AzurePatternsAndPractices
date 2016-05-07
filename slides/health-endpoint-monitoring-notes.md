###Problem
You do not have full control of the hosting environment. Services typically depend on other services provided by platform others.

###Solution
Implement health monitoring by sending requests to an endpoint. Do a __check__ and then __analysis__ of the result.

####Notes
  * Functional checks that external tools can access through exposed endpoints at regular intervals.
  * Validating the response code, response time, expired SSL certificates, etc.
  * <https://msdn.microsoft.com/en-us/library/dn589789.aspx>