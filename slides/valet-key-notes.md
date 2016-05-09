###Problem
Application will handle the movement of the data. This approach absorbs valuable resources such as compute, memory, and bandwidth.

###Solution
Restrict access to the data store’s public connection and provide the client with a key or token that the data store itself can validate.

####Notes
  * Once the client has a connection to the data store for direct access, the application cannot act as the gatekeeper.
  * <https://msdn.microsoft.com/en-us/library/dn568102.aspx>

note: 
provides __time-limited access__ to specific resources and allows only __predefined operations__ such as reading and writing to storage or queues
