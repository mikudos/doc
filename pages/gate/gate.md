---
layout: child_page
subtitle: SocketIo-Gate-Server
collectionName: Gate
collectionColor: blue
permalink: /gate/socketio-gate/
---

#### SocketIo gate server is the gate, witch all socket.IO client connect to. It handle all connections and transfer socket.IO events as requests to the backend GRPC service. Gate server build currently with 5 part up.

## Menu

-   [Authentication service](#authentication-service)
-   [Chat service](#chat-service)
-   [Json-Rpc service](#json-rpc-service)
-   [Message-Pusher service](#message-pusher-service)
-   [Duplex-Stream service](#duplex-stream-serice)

---

-   ### Authentication service

    Standalone SocketIo Gate Server. We provide easy to used implementation for JSON-RPC, Chat-Service, Duplex Grpc call management.

    [Details](socketio-gate/)

-   ### Chat service

    Chat service provide a fast way for developer to build a extensible chat service. with help of socket.io redis plugin, Chat service can be easily expansion horizontaly.

-   ### Json-Rpc service

    Json-Rpc

-   ### Message-Pusher service

    Message pusher service

-   ### Duplex-Stream service

    Duplex stream servcie
