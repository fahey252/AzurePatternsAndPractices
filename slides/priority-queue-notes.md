###Problem
Message queues are typically used to delegate tasks to background processing. Some tasks are more important than others.

###Solution
Messages in the queue are automatically reordered so that messages with a higher priority will be received before those of a lower priority.

####Notes
  * Most message queue implementations support multiple consumers (Competing Consumers Pattern).
  * Can also maintain a separate queue for each priority level.
  * <https://msdn.microsoft.com/en-us/library/dn589794.aspx>

note:
__Define the priorities__ in the context of the solution  
 Identify the requirements for handling high priority items, and what other __resources must be allocated to meet these criteria__. i.e. processes within 3 seconds.    

