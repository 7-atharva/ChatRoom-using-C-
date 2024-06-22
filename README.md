# ChatRoom-using-C++
MPR on OOPs 

                          * Client Initialization:
* Clients create sockets and connect to the server on a designated port.
* Clients might send identification information and choose a chat name.
                          * Sending Messages:
* Clients compose messages and package them with sender information.
* Clients send message packets to the server using the established connection.
                          * Server as a Hub:
* The server receives messages from clients and unpacks the content.
* The server broadcasts the received message (including sender and content) to all connected clients.
                          * Client Receives and Displays:
* Clients listen for data on their connections and unpack received messages.
* Clients display the message content with the sender's chat name in the chat window.
                              *  CONCLUSION :
  
The chat application was developed using the C++ programming language, which is known for its high performance and control over system resources. The application uses socket programming to establish a connection between the client and the server, allowing users to communicate with each other in real-time. The development process was facilitated by using a text editor and a compiler, which enabled the writing, debugging, and building of the application. 
The development of the chat application provided valuable insights into the world of network programming and software development, highlighting the importance of choosing the right tools and technologies for achieving project goals efficiently and effectively.
