Building a Chat App - Intro to WebSockets
https://www.youtube.com/watch?v=J8xReLuBNPY
https://github.com/gitdagray/build-chat-app


GitHub repo:
git@github.com:nirgluzman/WebSocket-ChatApp.git


Overview
https://javascript.info/websocket


WebSocket origin restriction (CORS)
The protections provided by CORS don't apply to WebSockets.
https://learn.microsoft.com/en-us/aspnet/core/fundamentals/websockets?view=aspnetcore-8.0


Node.js WebSocket library
https://www.npmjs.com/package/ws

WebSocketServer emits the following events:
* connection: event emitted when a client establishes a new WebSocket connection with the server. 
* headers: event emitted when a client sends its HTTP headers during the WebSocket handshake process. 
* listening: event emitted when the WebSocket server starts listening for incoming connections on the specified port. 
* close: event emitted when the WebSocket server is closed, either gracefully or due to an error. 
* error: event emitted when an error occurs during the WebSocket server operation, such as a network error or a client connection error.

Once the socket is created, there are totally 4 events:
https://javascript.info/websocket
* open – connection established
* message – data received
* error – websocket error
* close – connection closed
