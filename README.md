# Distributed Whiteboard

A whiteboard implemented in Java. The whiteboard has a server (the person who creates the whiteboard) and a number of clients that have usernames and passwords to use the whiteboard.

To create the whiteboard, the client uses the following commands in a terminal:

<i>java CreateWhiteBoard -a [IP address] -p [port number] -n [username] </i>


To join a session, a client enters the following commands in the terminal:

<i>java JoinWhiteBoard -a [IP address] -p [port number] -n [username] </i>

