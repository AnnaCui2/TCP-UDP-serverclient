# TCP-UDP-serverclient
TCP server: The program will create a server socket and bind to an address. It will be in a while loop
forever to establish a connection, receive a message, determine if each integer in the message is a leap
year and sent it back then close the connection. You do not need to change anything in the code and just run the program as is. Please run the server first so the client can find the existing server.

TCP client: The program will create a client socket and connect to the server address. You will need to change the file variable to be whatever file you want to read. Then the program will read it, and send the integers to the server and print the results if each one is an integer or not. Once it has read all of them, it will close the socket.

UCP server: The program will create a server socket and bind to an address. It will be in a while loop
forever to receive a message from a client without any established connection, check if each integer in the message is a leap year and sent it back via client address. You do not need to change anything in the code and just run the program as is. Please run the server first so the client can find the existing server.

UDP client: The program will create a client socket. You will then need to change the file variable to be whatever file you want to read.Then the program will read it and send the integers to the server via server address. Then it will receive the message back from server via address and print the message then close the socket.
