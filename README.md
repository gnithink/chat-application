# chat-application

FINAL PROJECT RETROSPECTIVE


Objective:

	 Develop a chat application in C and in the process learn C programming.

Features:

	There will be a single server and many clients. All the clients join a channel named “Common” channel. The clients can communicate with all the other users in the channel.
    • Create Channel:
    
        ◦ Each client can create a new channel using the command “/join <channel name>”
    • List of Channels:
    
        ◦ Each client can see the list of created channels using the command “/list”
    • List of Users:
    
        ◦ Each client can see the list of users in a specific channel using the command “/who <channel name>”
    • Switching between channels:
    
        ◦ Each client can switch between the different different channels using the command “/switch <new channel name>”
        
    • Leaving a channels:
    
        ◦ Each client can leave a specific channel if he is a part of it using the command “/leav <channel name>”
        
    • Exit the chat:
    
        ◦ Each user can exit the chat application using the command “/exit”.
Usage:

    • Open many terminal windows. One window is for the server and the remaining windows are for the number of clients.
    • To initialize a server use the command : ./server  <server name> <port number>
    • To initialize a Client or user use the command: ./client localhost <server port number> <username or client name>



Retrospective:

    • Implementing socket programming initially was a steep learning curve. 
    • Once a simple two way communication was set up between server and client implementing each feature at a time was less challenging.
    • Overall it was a meaningful learning experience and I am more confident in programming in C.
