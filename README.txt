Change the directory to /Server/src folder

javac --release 8 Neighbour.java  BootstrapServer.java
java BootstrapServer

Change the directory to /Node/src folder and run following two commands

javac  --release 8 Neighbour.java Node.java
java Node - This command should be run more than once to start more than one node( eg: Run 5 times if you need 5 nodes)

Search command
ser Fast_and_Furious

Note: Change the server IP address in Node.java to your local machine Ip address. Before executing the commands.
