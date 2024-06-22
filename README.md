# Networking!

![image](https://github.com/ShanmukaRS25/Networking/assets/164605613/0e3d99a7-6255-4f2d-ab61-4990a05edc76)


### 1. **Socket Programming**

**TCP Client-Server Example**: This pair of Python scripts demonstrates the creation of a basic TCP/IP communication channel. The server script sets up a socket, binds it to a specific port, and listens for incoming client connections. Upon establishing a connection, it receives data in small chunks and echoes the data back to the client. The client script connects to the server, sends a message, and waits to receive the echoed message back, illustrating a simple echo server-client interaction.

### 2. **HTTP Request Handling**

**Simple HTTP Server**: This script leverages Python's built-in `http.server` module to create a basic HTTP server that serves files from the current directory on port 8000. It demonstrates how to set up a simple web server that can handle HTTP requests and serve static content.

**HTTP Client Using Requests**: This script uses the `requests` library to perform an HTTP GET request to the GitHub API. It retrieves and displays the status code, headers, and content of the response, demonstrating how to interact with web APIs and handle HTTP responses.

### 3. **Ping Implementation Using ICMP**

**Ping Tool**: This script simulates the `ping` command to test the reachability of a network host (`google.com`). It uses the `subprocess` module to execute the `ping` command appropriate to the operating system, showcasing a basic network diagnostic tool.

### 4. **DNS Lookup**

**DNS Query**: This script performs a DNS lookup to resolve a domain name (`www.example.com`) to its corresponding IP address using Python's `socket` library. It illustrates how to obtain IP addresses for domain names through DNS resolution.

### 5. **Simple Chat Application**

**UDP Chat Server and Client**: These scripts create a basic UDP chat application. The server listens for messages from clients on a specific port, echoes them back, and prints them to the console. The client sends messages to the server and prints the responses, demonstrating a simple UDP-based messaging system.

### 6. **Multithreaded Server**

**Multithreaded TCP Server**: This script sets up a TCP server that can handle multiple client connections simultaneously using threading. Each client connection is managed in a separate thread, allowing concurrent processing of multiple clients, illustrating a scalable server design.

### 7. **HTTP REST API**

**Flask API Server**: This script creates a RESTful API using Flask. It sets up endpoints to manage a simple in-memory database of users, allowing retrieval and creation of user records through GET and POST requests. This example demonstrates the basics of building and handling RESTful APIs.
