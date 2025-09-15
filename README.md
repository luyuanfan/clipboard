# clipboard

tryin to sync clipboards between devices (linux, mac, mainly). 

can start by looking at 
1. how airdrop works
2. where are clipboard data buffered
3. how to encrypt messages

## brainstorm

how will i run the program?? does it have to be installed on all devices in the share network? i feel like yeah if anyone leaves the other ones should still be able to share things. 

i think lots of python functions supports getting clipboard content.

problem!!! then get the curr IP address of the devices (but ip addresses **change**, so idk how to keep track of that yet?)

then just establish connection are share the content.

appntly routers are only involved when two devices from different networks want to communicate so we don't care about routers.

## answers

1. how airdop works
the thing about airdrop is that it auto detects surrounding devices, in our case we don't gaf about that.

it does use wifi to establish connection 

2. where are clipboard data buffered
should be a easy thing

3. how to encrypt messages
can make pub/priv key pairs ig? 

or try to find a stable library somewhere out there. 

4. establish connection
can ask user to log the ip address of the devices in network. then whenever a copy is done, store it, make connection to everyone, and store it in their clipboard buffer. 