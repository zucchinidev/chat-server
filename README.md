# chat-server

A simple chat server that lets several users broadcast textual messages to
each other through TCP connections.

Execute the server

```bash
./server
```


* Connect a client
```bash
$ ./client
 
You are 127.0.0.1:39062
127.0.0.1:39066 has arrived
127.0.0.1:39066: Hello Golang!!!

```

* Connect another client

```bash
$ ./client
 
You are 127.0.0.1:39066
Hello Golang!!!
127.0.0.1:39066: Hello Golang!!!


```