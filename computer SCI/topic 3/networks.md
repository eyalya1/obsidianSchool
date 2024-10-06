
### protocols
http - hyper text transfer protocol- how to transmit hyper text(html and )
tcp - transmission control protocol-how to 


#### server structures
client to servers- very stable, all data is in the hands of the server owner(easy to manage)-all data in the hands of the server owner(bad for messaging and such), if not configured correctly may overload the server.

peer to peer- very private( most data is in the hands of the clients), decentralized(no oversight) - decentralized(hard to manage), may be slow for less users 

### data transmission  

directions
>simplex: one way e.g radio broadcast.
>half-duplex: two-way but not at the same time, e.g walkie talkie
>full duplex: two-way, and at the same time, e.g telephone

Speed measure in bps(bit per second) not Bps(bytes per second)
dial-up is slow at around 56 kps
Broadband is faster - currently ~10 Mbps
WiFi -> wireless broadband but fairly short range -cons (short range, easily blocked by walls windows and such, not smart(a hub not a switch) so sniffers can pick up on communications, scales badly)

a data packet is a formatted unit of data carried on a packet- switched network. it comprises control information (header) and payload. the header contaions information about the payload, such as length destination address, the payload is the data that is to be sent

#### package switched vs circuit switched

packet switched communication
>data brocken into small packet (64 max for ip)
>packets may take totally different routes to their destination
>pakcet reassembled and sqeuenced at destination into coherent data
>example:internet
>[[package structure]]
>Advantages
>>full use of available bandwidth
>>more secure (can be encrypted)
>>devices of different speeds can communicate easily
>>Resilient to communications hardware failure (TCP routing)




circuit switched communication.
>Dedicated channel established between both parties.
>Data sent in one go, in order, and be received likewise.
>example: landline.

