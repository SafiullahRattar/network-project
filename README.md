# network-project
An interactive messaging network between server and client

Project Details:

-Client has two threads. A read and write thread that works in parallel.
-You can receive message even when one client is writing a message.
-The server when receives a message, it categorizes it as a “command” or a “normal message”. The “command” is a message followed by “/”
-Implemented four commands in the program: Block, Unblock, Sleep, Quit, Change Name
Client is implemented as a class on server side. It has a name, string and an array of blocked clients. 
The above-mentioned array stores the blocked clients. All clients receive the message except the ones that client has blocked.

