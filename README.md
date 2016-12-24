# netcat how to

This is a simple netcat program built in Python 2.7.

In order to run it you will need to run it as a client and a server.

Example: to run the client you should run first run "python netcat.py -t localhost -p 9999" this would be the server
then run "python netcat.py -t localhost -p 9999 -c" once it starts running press CTRL-D and you will see a prompt where you can run your commands.

python is self explanatory. netcat.py is the name of the script.

-t is denoting the target

localhost is the target, it can be an IP

-p is the port 

-c is denoting that this is the client side of the netcat
