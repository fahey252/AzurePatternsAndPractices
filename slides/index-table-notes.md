###Problem
Application might not be able to use the primary key if it needs to retrieve data based on some other field.

###Solution
Emulate secondary indexes by creating your own index(fact) tables. An index table organizes the data by a specified key.

####Notes
  * __NoSQL__ data stores used by cloud applications do not provide secondary indexes.
  * Improve query performance when an application frequently needs to retrieve data by using a key.
  * <https://msdn.microsoft.com/en-us/library/dn589791.aspx>

note: 
May require the application to fetch and __examine every record.__
