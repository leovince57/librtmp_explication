# rtmp
This file is mainly used for more fine-grained parsing of [rtmp file](../src/rtmpdump/librtmp/rtmp.c) methods.

## RTMP_Init

## RTMP_SetupURL
This function parse more more than rtmp url. \
An example character string suitable for use with RTMP_SetupURL():
```
rtmp://flashserver:1935/ondemand/thefile swfUrl=http://flashserver/player.swf swfVfy=1
```

## RTMP_Connect
Flow Chart![](../files/RTMP_Connect.png)
1. add_addr_info: assign value to sockaddr_in from RTMP.Link,init a socket address;
2. RTMP_Connect0: init a socket, establish socket connection.Then do SocksNegotiate;
3. RTMP_Connect1: handshake
