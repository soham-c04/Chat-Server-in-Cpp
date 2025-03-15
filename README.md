# Chat-Server-in-Cpp
Made by :
1. Adarsh Dhakar
2. Avik Sarkar
3. Debargha Nath
4. Soham Chakraborty  

[Link to Original Project](https://github.com/adarshdhakar/cn_lab_sheet5/tree/main)

### Starting the Server
```
g++ server.cpp -o server
./server [SOCKET NO.]
```

### Starting the Client
```
g++ client.cpp -o client
./client [SERVER PORT] [SOCKET NO.]
```

## How to Use
1. Enter your name
2. By default your messages will be sent to "everyone".
3. If you specifically want to send messages to a particular subset of users -  
   `$[Name1,Name2,...] Message`  
   Incorrect user_names will be omitted automatically.
4. To list all the rooms with their users -  
   `/rooms`
5. To join an existing room -  
   `/room [Room Name]`  
   Note that if there was no room previously created with that given name, a new room will be created.  
6. To leave a room -  
   `/leave`   
7. To leave the Chat Server -  
   `exit`
8. Staying inactive for more than 2 minutes will result in you being kicked/banned from the server.
9. No. of active clients will be displayed each time someone joins or exits the server, along with the name of user who joined/left.
