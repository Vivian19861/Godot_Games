## Networking Notes
* For low-level networking, it includes both TCP and UDP. 
* For TCP, it is reliable, ordered, but has limitations of higher latency, and it is not suitable for gaming. 
* For UDP, it is simpler, unreliable, unordered, but quicker, lower latency. Game networking mainly builds upon UDP. 
* LAN, means local area network, mainly refers to office, home or same building network. 
* Router is the device used to distribute local network to internet. 
* NAT is some technique used in Router, has functionality such as conserves IP address, enhances security and enable intenet connectivity. 
* HTTP request is also useful in gaming network, but mainly for larger data, such as downloading assets, lobbry browser, etc. 
* TLS/SSL certificates is protocl used in networking for secure connections. 
* Networking in game mainly includes setting up connection, make some configurations, and then send/receive packets, and close the connection. 
* Sockets is the endpoint for communication between two machines. It used in web servers and client for HTTP communication, gaming for real-time multiplayer interactions, messaging for chat applications, file transfer and IoT devices for communication between devices. 
* TCP stands for "transmission control protocol". 
* IP stands for "internet protocol", it is not reliable, dont know if the receiver receives the packets. 
* UDP is not reliable, since it does not have the ack reponse, so it could drop some packet, or unordered. It stands for "user datagram protocol". 
* TCP is a stream protocol, it will wait until the packet is big enough to send, so it is not suitable for gaming, because gaming need real-time response. 
* Peer-to-Peer lockstep has two disadavantages: it will wait for the slowest players; it needs to make sure all the players start at the same point. 
* Server and client model is modern for multiplayer games. 
* The modern way to improve latency(make game quicker) is to move part of the logic on Client side, then compare with the Server side to do some correction. So the player will feel the game is playing seemlessly. 