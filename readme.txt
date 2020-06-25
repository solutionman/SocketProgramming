
compile server:

gcc server.c -o server

run:

./server


check:

netstat -anp --tcp | grep server
or
netstat -anp -tcp | grep server
or
netstat -anp -tcp


another check:

telnet localhost 5000


compile client:

gcc client.c -o client

run (server already should be running):

./client 127.0.0.1


######################################

version 2:

gcc server2.c -0 server2

gcc client2.c -0 client2


./server2

./client2 127.0.0.1 5001




