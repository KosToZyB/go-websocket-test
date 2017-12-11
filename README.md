# Go Websocket Test

The inspiration: http://www.jayway.com/2015/04/13/600k-concurrent-websocket-connections-on-aws-using-node-js/#comment-291225

Run server:
```
./server
```

Run client:
```
./client -connections 500 -url ws://0.0.0.0:8002/ws
```