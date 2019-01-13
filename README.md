# java--simulator-of-Http-protocol
HTTP communication begins by creating a call between the server and the client using the TCP protocol on the layer
The traffic of a TCP / IP protocol continues in a series of requests and responses sent by the client and the server.

In our project, an HTTP server uses a custom port (port) to a client server when a client request
To connect to the server, the server receives the client connection and waits for the .HTTP request header
We will focus only on receiving and sending client requests, so this program can receive HTML comment or put
HTML content to or from the server respectively. This HTTP server is multithreaded so it will process a clients request
Many at the same time.
