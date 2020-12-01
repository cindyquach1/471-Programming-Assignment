# 471-Programming-Assignment

Cindy Quach

Justin Nguyen - 

Ryan Teoh - teohr@csu.fullerton.edu

Ivan Tu - ivanstar@csu.fullerton.edu

Marco Botello - marco.botello@csu.fullerton.edu

Language used - Python2

Instructions for running the program:

1. Run the file 'sendfileserv.py' using the command 'python2 sendfileserv.py ' with your desired port number (e.g. 'python2 sendfileserv.py 3002'). This will start the server with the desired port.
2. Run the file 'sendfilecli.py' using the command 'python2 sendfilecli.py ' with your desired server and port number (e.g. 'python2 sendfilecli.py localhost 3002). This will start the client and have it connect to the server. During testing, we used 'localhost' as the server. The client will then display 'ftp> '. This means that the client is waiting for a command from the user.
3. Type in one of the available commands (get, put, ls, quit) 3a. The 'get' command and the 'put' command require that the user puts a file name after the command. For example, 'get file.txt' 3b. The 'ls' command will return the files in the server. It will post it on both the server and the client. 3c. The 'quit' command will close both the client and the server
4. When done, use the 'quit' command to exit the client and server.
