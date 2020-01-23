---
layout: single
title: "Network protocols"
---

In the real world, protocol often refers to a code of conduct or a form of etiquette. People follow certain rules of behaviour, ceremony etc. They also have to know what is expected of them in any particular situation to ensure communication wihout conflicts. The same requirements are expected when they interact with people from other countries and cultures, making sure that they do not offend anybody due to unfamiliarity of local customs. In simple words - protocols are some kind of unwritten rules of society.

All in all, social networking and networking in context of computers are very similar. They define set of rules and procedures that enable devices and systems to communicate. Despite that PCs and laptops do not have to worry about making a faux pas, they strictly have to ensure that all the devices on the network are in agreement about how to communicate with each other.

> Protocol is set of rules, algorithms, messages and other defined mechanisms which are governing communication between entities at the same working surface (like OSI layers). For example, Transmission Control Protocol (TCP) is responsible for specific way of communication on layer 4 in the OSI model. Therefore, all hosts must implement TCP to utilize it properly.

Despite above definition, term `protocol` often refers to different concepts of networking, eg: protocol suites (set of protocols), MS Windows Protocols.

Below is a list of the most popular internet protocols:

  * IP: Internet Protocol
  * FTP: File Transfer Protocol
  * SSH: Secure shell
  * SSL: Secure Sockers Layer
  * TELNET
  * SMTP: Simple Mail Transfer Protocol
  * POP3: Post Office Protocol
  * HTTP: HyperText Transfer Protocol
  * HTTPS: HyperText Transfer Protocol


In the next posts, some of the above will be described more precisely.

## Connection-Oriented and Connectionless Protocols

We can divide networking technologies based on whether or not they use a dedicated path (circuit switching, eg. telephone system) or packet-switching type (path is assigned while packets are traversing between routers). Another way which they could be differentiated has to do with whether or not they use persistent connections between them. This case is closely related to circuit vs packet-switching.

### Connection-oriented protocols

To establish connection using these protocols, there have to be some kind of handshakes. Fox example, in TCP protocol, before data is being sent, both parties exchange information about connection (three way handshake). If the connection is established, only then payload is sent. When all the packets are sent, connection is closed.

### Conectionless protocols

These protocols do not require to initiate any handshakes before data is send. One party just sends data to the receiver and do not care if the packet is delivered or not. This protocol is used in UDP, eg. for streaming videos, where establishing connections is not needed, thus faster performance is available.
