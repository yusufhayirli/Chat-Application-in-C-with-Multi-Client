# Chat Application in C with Multi Client

Here is a simple chat application built in C. There are two components as - <b>server.c</b> and <b>client.c</b>. Application uses multithreading to handle with multiple clients. There can be up to 100 clients in a server as default. Clients will chat and server can watch their messages with their names. 

# Run the program
- $ make Makefile compile
- $ ./server (PortNumber)
- $ ./client (PortNumber) in another Terminal and Enter name 
- $ ./client (PortNumber) in another Terminal and Enter name 
- $ ...
