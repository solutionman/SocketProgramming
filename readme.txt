
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









