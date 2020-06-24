
compile:

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






