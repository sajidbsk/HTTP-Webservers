# HTTP-Webservers

Two simple implementations of a networking server that can handle HTTP requests from clients. Listening sockets are used to establish TCP connections in both servers. These servers are made following [Ruslan's Work](https://ruslanspivak.com/lsbaws-part1/) closely. 
```server.py``` is designed to work for any choice of Web Framework, be it Django or Flask or Pyramid. It uses  Web Server Gateway Interface (WSGI) to handle framework requests and at the same time can serve multiple client requests in parallel.
```server2.py``` is a fully functioning server that can handle multiple requests at a time from multiple clients. 
Pull requests are appreciated. For edit suggestions and modification, you can contact me at ksmahmoo@edu.uwaterloo.ca
