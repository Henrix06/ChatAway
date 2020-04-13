# ChatAway
A java chat app that runs from the terminal(Console App). The server and clients can run on different computers in the saame network.
There can be multiple clients connected to the server and they chat with each other.

When a user connects to the server the Admin is notified along with the users that are already on the platform.
Users are required to enter their names for identification.

HOW TO RUN
1.Locate the server class from project and specify path in terminal.
2. run with comand : java Server 8008
  - This will start server listening on port 8008
3.Locate the Client class from project files and specify path in terminal(A new window)
**N.B**Don't close the server window
4.run with comand 2. run with comand : java Client localhost 8008
 -This will notify server of a new client along with notifying other clients in server
 -Enter usernames from prompt then chat away
 
 

