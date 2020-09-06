# Topic 1: Digital methods for exchanging data

<br> <br>

# Recognise and Describe

## Encryption

* Criteria: 
	* Recognise and describe encryption and authentication strategies appropriate for securing data transmissions and their differences
  
    * features of symmetric (Data Encryption Standard — DES, Triple DES, AES — Advanced Encryption Standard, Blowfish and Twofish) and assymetric (RSA) encryption algorithms

    * how data compression, encryption and hashing are used in the storage and transfer of data

- - -
<br>

**Encryption**

Encryption is the process of scrambling data so that only the desired party can understand that information. In more technical terms it is the process of converting plain text to cipher text.


  ```
  "Hello"  --->  [encryption]  --->  "SNifgNi+uk0="
  plaintext                          ciphertext
  ```



**Compression**

Compression is the process used to reduce the storage space a file or program uses, this allowing more files to fit into the same amount of space. This process is especially useful when transferring files over the internet due to larger files taking a longer time to transfer.


**Hashing**
Hashing is the process in which an input is turned into a fixed sized value. Hashing, unlike encryption, has an output that cannot be reversed to form the key. This means that if a hacker gained access to the hashed database they could only gain access to the keys, which cant be reversed to gain the passwords. However, someone with the password can hash theirs and check it against the stored hash to gain access.


- - -


In modern time there are two main types of Cryptography algorithms used to protect our data over transfer, symmetric and asymmetric key encryption.

<br>
**Symmetric Key Encryption**

Symmetric key encryption, also known as a symmetric algorithm, is a type of encryption that uses one key to encrypt and decrypt data, a secret key, a public key and a private key. <i>"Keys are random bits that are used by the algorithm to transform the material into its encoded format and back to plain text." - ("Encryption 101", 2020)</i>. Some advantages to using symmetric key encryption include its encryption speed and efficiency for large projects with disadvantages consisting of its need to keep the secret key, this can become tricky when dealing with multiple locations.

<br><li><b>Symmetric Key Ciphers</b>

<ol>- DES: A 64 bit block cipher that uses a 56-bit key.</ol>
<ol>- Triple DES (3DES): Uses three separate 56 bit encryption keys. The message is encrypted using one key, encrypted again using a second key and further encrypted by using either a first or third key.</ol>
<ol>- AES: A variant of [the] Rijndael [block cipher], with a fixed block size of 128 bits, and a key size of 128, 192, or 256 bits. - ("Advanced Encryption Standard", 2020)</ol>
<ol>- Twofish: A symmetric block cipher which operates on 128 bit blocks and employs 16 rounds with key lengths up to 256 bits.</ol>
<ol>- Blowfish: A symmetric block cipher which operates on 64 bit blocks and employs 16 rounds with key lengths up to 448 bits and uses large key-dependant S-boxes [S-box: "<i>a basic component of symmetric key algorithms which performs substitution"</i> - ("S-box", 2020)].</ol>

</li>

<br>
**Asymmetric Key Encryption**
Asymmetric key encryption, also known as an asymmetric algorithm, is a type of encryption that uses two separate keys, with one being used to encrypt and the other to decrypt data. The key pair being referenced as a public key and private key. The public key is used to send the message and the private key being the one to decrypt said message. Some advantages to using asymmetric key encryption include its encryption extended functionality and its scalability for larger projects with its main disadvantage being the speed of the algorithm.

**<li>Asymmetric Key Ciphers**

<ol>- RSA: <i>"In RSA, the public key is generated by multiplying two large prime numbers p and q together, and the private key is generated through a different process involving p and q. A user can then distribute his public key pq, and anyone wishing to send the user a message would encrypt their message using the public key... When the user receives the encrypted message, they decrypt it using the private key and can read the original text."</i> - (Katz et al., 2020)</ol>

</li>


<br><br>

- - -


## Visual Communication

<li><i>Criteria: 

  <ol>
    - how useability principles are used to inform solution development
  </ol>
  <ol>
    - how the elements and principles of visual communication inform user interface development
   </ol>

</i></li>

- - -
<br>

**Usability Principles** <br>
There are seven main usability principles that will be focused on, hierarchy, harmony, contrast, repetition, alignment, proximity and balance. The combination of these principles help the users navigate though a webpage with ease giving them the best experience and allowing them to know how the webpage is meant to be used. These principles help visually and practically for the user with the use of colour design all the way to easy navigation for the blind (using screen readers). There are also usability elements, space, line, colour, shape, texture, tone, form, proportion and scale which aid the usability principles.

<br><li>**Usability Principles**

<ol>- Hierachy: "This principle can be used to highlight the importance of particular content and features, encouraging users to respond to important elements. When designing a web page, it can be helpful to keep in mind the natural tendency of users to assign greater importance to content at the top left of the screen, and less importance as they move from the top down and from left to right." - (School Resources, 2020)</ol>
<ol>- Harmony: "Harmony offers an interpretation of proximity to ensure components as a whole provide valuable meaning and are complementary across the interface. In a data driven context, it is not always harmonious to place certain datasets with others. Sometimes it is better to place datasets on separate screens to avoid confusion or otherwise improve the experience." - (School Resources, 2020)</ol>
<ol>- Contrast: "Contrast is what you see when you compare things that are different. Humans are wired to notice differences, and the clever use of contrast can support powerful interactions. Contrast can be achieved in simple ways by utilising elements such as colour and space, and in conjunction with other principles such as proportion and scale." - (School Resources, 2020)</ol>
<ol>- Repetition: "The principle of repetition provides predictability through the reusability of elements, and is commonly used in data-driven solutions. The repeated elements could be page constructs, sections or product layouts. This allows users to learn the user environment and predict where they will be able to source information they require." - (School Resources, 2020)</ol>
<ol>- Alignment: "Alignment is a principle of design that is conducive to how users infer information from a layout. Alignment of images, text and objects provides structure, eliminates potential haphazardness and allows the user to effectively scan information." - (School Resources, 2020)</ol>
<ol>- Proximity: "When presented with information, users will mentally group together elements that are close to each other in a space. It is suggested that many users 'clump' these into a summarised object. It is important to keep this in mind when developing a data-rich user experience. When data is placed close to other data, a relationship is often inferred based on a user's understanding of the logical layout of data. Changing the physical proximity of the data changes its potential meaning and how a user interprets it. This is an important consideration in delivering meaningful data to a user." - (School Resources, 2020)</ol>     
<ol>- Balance: "Balance in an interface refers to a sense of equilibrium and symmetry in the eyes of the user, allowing the user to effortlessly interpret the interface. Balance is sometimes informal — meaning it isn't exact, and is more of a general appreciation of perspective. Balance in a web context may mean simply that the breakdown of the page shows symmetry in relation to chunks of detail." - (School Resources, 2020)</ol>

</li>

<br>

<li>**Usability Elements**

<ol>- Space: "" - (School Resources, 2020)</ol>
<ol>- Line: "" - (School Resources, 2020)</ol>
<ol>- Colour: "" - (School Resources, 2020)</ol>
<ol>- Shape: "" - (School Resources, 2020)</ol>
<ol>- Texture: "" - (School Resources, 2020)</ol>
<ol>- Tone: "" - (School Resources, 2020)</ol>     
<ol>- Form: "" - (School Resources, 2020)</ol>
<ol>- Proportion: "" - (School Resources, 2020)</ol>
<ol>- Scale: "" - (School Resources, 2020)</ol>

</li>

- - -
<br>
<br>

# Explain
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

* What is Encryption? | Types of Encryption. Cloudflare. (2020). Retrieved 3 September 2020, from [https://www.cloudflare.com/learning/ssl/what-is-encryption/](https://www.cloudflare.com/learning/ssl/what-is-encryption/).

- Encryption 101. EDUCAUSE. (2020). Retrieved 3 September 2020, from [https://www.educause.edu/focus-areas-and-initiatives/policy-and-security/cybersecurity-program/resources/information-security-guide/toolkits/encryption-101](https://www.educause.edu/focus-areas-and-initiatives/policy-and-security/cybersecurity-program/resources/information-security-guide/toolkits/encryption-101).

* Stubbs, R. (2020). An Overview of Symmetric Encryption and the Key Lifecycle. Cryptomathic.com. Retrieved 3 September 2020, from [https://www.cryptomathic.com/news-events/blog/an-overview-of-symmetric-encryption-and-the-key-lifecycle](https://www.cryptomathic.com/news-events/blog/an-overview-of-symmetric-encryption-and-the-key-lifecycle).

* Advanced Encryption Standard. En.wikipedia.org. (2020). Retrieved 3 September 2020, from [https://en.wikipedia.org/wiki/Advanced_Encryption_Standard](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard).

* S-box. En.wikipedia.org. (2020). Retrieved 3 September 2020, from [https://en.wikipedia.org/wiki/S-box](https://en.wikipedia.org/wiki/S-box).

* Blowfish (cipher). En.wikipedia.org. (2020). Retrieved 3 September 2020, from [https://en.wikipedia.org/wiki/Blowfish_(cipher)](https://en.wikipedia.org/wiki/Blowfish_(cipher)).

* Katz, A., Ng, A., Bourg, P., William, C., Ross, E., Khim, J., & Kau, A. (2020). RSA Encryption | Brilliant Math & Science Wiki. [Brilliant.org. Retrieved 3 September 2020, from https://brilliant.org/wiki/rsa-encryption/](Brilliant.org. Retrieved 3 September 2020, from https://brilliant.org/wiki/rsa-encryption/).

* PMTEducation. (2020). OCR Computer Science A Level [Ebook] (1st ed., pp. 3-6). Retrieved 4 September 2020, from [https://pmt.physicsandmathstutor.com/download/Computer-Science/A-level/Notes/OCR/1.3-Exchanging-Data/Advanced/1.3.1.%20Compression,%20Encryption%20and%20Hashing.pdf](https://pmt.physicsandmathstutor.com/download/Computer-Science/A-level/Notes/OCR/1.3-Exchanging-Data/Advanced/1.3.1.%20Compression,%20Encryption%20and%20Hashing.pdf).

* Nielsen, J. (2020). Usability 101: Introduction to Usability. Nielsen Norman Group. Retrieved 4 September 2020, from [https://www.nngroup.com/articles/usability-101-introduction-to-usability/](https://www.nngroup.com/articles/usability-101-introduction-to-usability/).

* 2020 Guide to Network Latency (2020). Retrieved 3 September 2020, from   [https://www.dnsstuff.com/network-latency](https://www.dnsstuff.com/network-latency)

* Communication Protocol (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/Communication_protocol](https://en.wikipedia.org/wiki/Communication_protocol)

* HTTPS (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/HTTPS](https://en.wikipedia.org/wiki/HTTP)

* HTTP (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/HTTP](https://en.wikipedia.org/wiki/HTTP)

* FTP (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/FTP](https://en.wikipedia.org/wiki/FTP)

* Jitter (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/Jitter](https://en.wikipedia.org/wiki/Jitter)

* VPN (2020). Retrieved 6 September 2020, from [https://en.wikipedia.org/wiki/VPN](https://en.wikipedia.org/wiki/VPN)