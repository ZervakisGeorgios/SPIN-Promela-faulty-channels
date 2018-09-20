# SPIN-Promela-faulty-channels

The programme was written using the verification modeling language Promela. The programme creates for different processors and faulty channels between them. The processors can communicate in cyrcular way (A to B, B to C and so on). When a message is transmited, an ACK is sent. The programme simulates faulty channels. Therefore, there some times the packets fail to be delivered and hence no ACK is sent. In these cases, the sender sends again the same message until it receives an ACK.
