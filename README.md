# stage2-module4-task2
Tasks for structural design pattern

Written code overview
com.mjc.stage2.impl.ConnectionPool is a pool that contains all real connections created.

com.mjc.stage2.impl.RealConnection is a connection that implements the com.mjc.stage2.Connection interface and is used in connection pool.

Task: Implement proxy pattern for connection.
1. Implement interface Connection in the ProxyConnection class (com.mjc.stage2.impl)
2. The close() method should return connection to the connection pool
3. Write a reallyClose() method in the ProxyConnection class that closes the real connection.
