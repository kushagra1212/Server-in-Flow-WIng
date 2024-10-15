# Server-in-Flow-WIng


# Creating an Server

## Overview

This documentation provides an example of how to create an HTTP server in Flow-Wing using the `Vortex` module. The server handles various HTTP requests, including GET and POST methods, and responds with appropriate content, including HTML and JSON.



https://github.com/user-attachments/assets/4d7502a9-e1de-4c20-a82b-4ffee80df2b9



## Modules Required

To create the HTTP server, you will need to bring in the following modules:

- `Vortex`: For handling HTTP requests and responses.
- `File`: For reading files from the filesystem.
- `Err`: For error handling.
- `Json`: For parsing JSON data.
- `Map`: For storing key-value pairs.

### Starting the Server:


```
FlowWing --F=main.fg -O=-O3 --server
```

## Starting the Server

- The server is initialized on port 8080.
- Routes are defined for handling specific paths and HTTP methods.
- The server starts listening for incoming requests.

## Conclusion

This example demonstrates how to create a basic HTTP server in Flow-Wing using the `Vortex` module. You can expand upon this foundation to handle more complex routing and request processing as needed.
