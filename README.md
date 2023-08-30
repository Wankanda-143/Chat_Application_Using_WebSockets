
# Chat app 💬 using websockets (Nodejs, Express & Socket.io)

Embarking on the development of a chat application leveraging the power of Express and Websockets. Instead of utilizing plain Websockets, we've opted for the convenience and versatility offered by the Socket.io library. Socket.io serves as a user-friendly wrapper around Websockets, simplifying their implementation while also providing a valuable fallback mechanism.

This fallback enables communication through traditional XHR (XMLHttpRequest) requests when a WebSocket connection isn't immediately available, ensuring a seamless user experience. With Socket.io, our chat application will benefit from both the efficiency of Websockets and the resilience of fallback mechanisms.


## What is Websocket ?

WebSockets are an alternative to HTTP communication in Web Application, they offer full-duplex communication, that is, it is, bi-directional and that means the data can flow in both ways, so it can flow from client to the server and also from server to the client.



## To start setting up the project

Step 1: Clone the repo

```bash
  git clone https://github.com/Wankanda-143/Chat_Application_Using_WebSockets.git
```

Step 2: cd into the cloned repo and run

```bash
    npm install
```    

Step 3: Start the chat app (development mode)

```bash
    npm run dev
```  

Step 4: Start the chat app

```bash
    npm start
```  
