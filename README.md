How to run
=========

Start server:

```
npm install
node server.js
```

Start client:

```
node client.js
```

You will see they are communicating.

Also you can use some other websocket clients:

```
npm install -g wscat
wscat -c ws://localhost:3000
```

Reference
=========

1. Code is from <https://github.com/theturtle32/WebSocket-Node>, but simplified. Removed the subprotocol `echo-protocol` and binary message part.
2. 
