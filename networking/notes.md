# TCP 3-way handshake

TCP Message type:
- SYN: Used to initiate and establish a connection, synchronize sequence numbers between devices.
- ACK: Confirm to the other side that it has received the SYN
- SYN-ACK: SYN message from local device and ACK of the ealier packet.
- FIN: Used to terminate a connection.

Client                                              Server
1. ------------------------SYN-------------------->
2. <-----------------------ACK---------------------
3. ------------------------Data transfer---------->
