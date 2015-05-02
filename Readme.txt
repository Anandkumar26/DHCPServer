PROTOCOL:TCP/IP protocol

TO GET IP:

1.Client sends IPREQ message
2.Server responds with an IP address
3.Client sends ACK message or NACK message
4.If NACK message received then IP address is returned back to POOL.

TO RELEASE IP:

1.Client sends IPREL message
2.Server responds with an OK message
3.Client sends IP address
4.Server sends ACK or NACK message, if NACK message is sent then IP was 
not returned back to pool
