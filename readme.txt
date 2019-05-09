1.进入redis-5.0.4/src目录下，打开终端输入./redis-server启动redis数据库
2.新开三个终端，其中一个终端作为服务器，另外两个作为客户端。
3.进入在gopath目录下，作为服务器的终端中输入go build -o server chatroom/server/main
4.然后./server运行服务器
5.进入在gopath目录下，作为客户端的终端中输入go build -o client chatroom/client/main
6.然后在两个作为客户端的终端中输入./client，分别运行两个客户端
