# Black Hat Python

## TCP Client

- af_inet indicates an ipv4 address or hostname
- sock_stream indicates that this will be a TCP client

assumptions:

- the connection will always succeed
- server expect us to send data first
- server will always return data in a timely fashion

## TCP Server

...

## TCP Connection

```shell
$ python3 tcp_server.py
[*] Listening on 0.0.0.0:9998
[*] Accepted connection from 127.0.0.1:55518
[*] Received: GET / HTTP/1.1
Host: localhost
```
