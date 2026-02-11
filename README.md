# MULTITHREADED-CHAT-APPLICATION

**COMPANY** : CODTECH IT SOLUTIONS

**NAME** : MHASKE PRANAY SURESH

**INTERN ID** : CTIS3600

**DOMAIN** : JAVA PROGRAMMING

**BATCH DURATION** : 4 WEEKS

**MENTOR NAME** : NEELA SANTOSH

# ENTER DESCRIPTION OF TASK PERFORMED NOT LESS THAN 500 WORDS

In this task, a multithreaded client-server chat application was developed using Java Socket Programming. The objective of the task was to implement real-time communication between multiple clients through a centralized server. The system follows a client-server architecture where the server listens for incoming client connections and manages communication among connected users.

The server was implemented using the ServerSocket class to establish a listening port. When a client connects, the server accepts the connection using a Socket object and creates a separate thread to handle that specific client. Multithreading was implemented using the Runnable interface and Thread class, allowing multiple clients to communicate simultaneously without interrupting each other. Each client connection is managed by a dedicated ClientHandler class, ensuring independent message processing.

On the client side, a socket connection is established with the server using the server’s IP address and port number. The client application uses input and output streams to send messages to the server and receive messages from other clients. A separate receiving thread is implemented in the client program to continuously listen for incoming messages while allowing the user to send messages concurrently.

The server broadcasts messages received from one client to all other connected clients, enabling group chat functionality. Proper handling of client connection, disconnection, and resource closing was implemented to ensure stability. This task demonstrates practical implementation of networking concepts, multithreading, inter-process communication, and real-time data exchange using Java.

# OUTPUT OF THE TASK


