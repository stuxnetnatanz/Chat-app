Chat App
A multiroom, multiclient chat app build using UNIX Domain Sockets. The application is a console based application. The project is developed in C/C++ language and can be executed on a single stand-alone UNIX machine across a network using loop back address concept.

Server
Concurrent server using fork() system call
Binary files used for database
Client
User authentication
Switch account or chatroom
Send personal message
Prerequisite
Your shell profile must export "COLUMNS" environment variable. Or to add (say in your bash profile) run

$ echo "export COLUMNS">>~/.bashrc
$ source .bashrc
Download and run
$ git clone https://github.com/stuxnetnatanz/chat_app.git
$ cd chat_server
$ make
# Server
$ ./server
# Client
$ ./client 5555 127.0.0.1
