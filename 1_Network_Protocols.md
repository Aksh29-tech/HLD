# Network Protocols

It defines a set of rules that enable two systems to communicate with each other over a network.

## Application Layer

### Client Server Protocol

One Way Communication, means everytime client initiate and server only responds
- HTTP: Protocol for transferring web pages over the internet.
- FTP: Protocol for transferring files between computers. It's not safe because data is not encrypted so use HTTPs.
- SMTP: Protocol for sending emails between servers. (SMTP - for sending emails, IMAP - read/accessing emails, 
POP3 - Downloads emails from the server, not used currently).
- Web Sockets: Two way communication or bidirectional communication but client can not communicate with client, so 
it's not a peer to peer.

### Peer to Peer Protocol

- WebRTC(Web Real-Time Communication): Uses UDP to transfer data.

## Transport / Network Layer

### TCP/IP

- Data divided into small data packets
- Ordering 
- Acknowledgement
- Maintains Connection

### UDP/IP

- Data divided into small data packets
- Not maintains ordering
- No Acknowledgement
- Not maintains connection
- It's fast compare to TCP/IP
- ex: video streaming etc.