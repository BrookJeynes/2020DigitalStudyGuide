# Network Transmission Details 
 
[Really helpful comic](https://jvns.ca/networking-zine.pdf) that covers most of these areas and explains difficult concepts simply.




## Latency
Usually measured in milliseconds, latency is the  time it takes for data or a request to go from the source to the destination. Latency depends on the type of Network, the type of packets being transferred.

Latency can either be measured as the **Round Trip Time (RTT)** or the **Time to First Byte (TTFB)**:

**RTT** is defined as the amount of time it takes a packet to get from the client to the server and back.

**TTFB** is the amount of time it takes for the server to receive the first byte of data when the client sends a request.


## Jitter
The deviation from true periodicity of a presumably periodic signal, often in relation to a reference clock signal. In clock recovery applications it is called timing jitter. Jitter may be caused by electromagnetic interference and crosstalk with carriers of other signals. Jitter can cause a display monitor to flicker, affect the performance of processors in personal computers, introduce clicks or other undesired effects in audio signals, and cause loss of transmitted data between network devices. The amount of tolerable jitter depends on the affected application.

## Protocols
A protocol is is a system of rules that allow two or more entities of a communications system to transmit information via any kind of variation of a physical quantity. The protocol defines the rules, syntax, semantics and synchronisation of communication and possible error recovery methods. Protocols may be implemented by hardware, software, or a combination of both.
 
### List of common protocols
**HTTP:** HyperText Transfer Protocol is used for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web.

**HTTPS:** ... Secure is an extension of HTTP used for secure communication over networks. HTTPS is encrypted using TLS(Transport Layer Security). You can tell when your browser is communicating over HTTPS by the usually green lock icon in the address bar.Most browsers also display a warning to the user when visiting a site that contains a mixture of encrypted and unencrypted content.

**FTP:** File Transfer Protocol is used for the transfer of computer files between a client and server on a computer network. FTP users may authenticate themselves with a clear-text sign-in protocol, normally in the form of a username and password, but can connect anonymously if the server is configured to allow it. For secure transmission that protects the username and password, and encrypts the content, FTP is often secured with SSL/TLS (FTPS).  Setting up an FTP control connection is quite slow due to the round-trip delays of sending all of the required commands and awaiting responses, so it is customary to bring up a control connection and hold it open for multiple file transfers rather than drop and re-establish the session afresh each time. In contrast, HTTP originally dropped the connection after each transfer because doing so was so cheap. 

**VPN:** A **Virtual Private Network** extends a private network across a public network and enables users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network. Applications running across a VPN may therefore benefit from the functionality, security, and management of the private network. Encryption is a common, although not an inherent, part of a VPN connection.




# References
* 2020 Guide to Network Latency (2020). Retrieved 3 September 2020, from   [https://www.dnsstuff.com/network-latency](https://www.dnsstuff.com/network-latency)

* Communication Protocol (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/Communication_protocol](https://en.wikipedia.org/wiki/Communication_protocol)

* HTTPS (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/HTTPS](https://en.wikipedia.org/wiki/HTTP)

* HTTP (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/HTTP](https://en.wikipedia.org/wiki/HTTP)

* FTP (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/FTP](https://en.wikipedia.org/wiki/FTP)

* Jitter (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/Jitter](https://en.wikipedia.org/wiki/Jitter)

* VPN (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/VPN](https://en.wikipedia.org/wiki/VPN)


