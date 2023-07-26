# Networking Notes

## Communication links
They transmit data from one place to another.

There are many types of communication links. They are made up of different types of physyical media, including:

* Coaxial cable
* Copper wire
* Optical fiber
* Radio spectrum

## Packet switch
They take a packet arriving on one of its **incoming** communication links and forward that packet on one of its **outgoing** communication links.

The two most prominent types of packet switches are:

* Routers (typically used in the network core)
* Link-layer switches (typically used in access networks)

Both types forward packets towards their ultimate destinations.

## Analogies in packet-switched networks

* Packets = analogous to trucks
* Communication links = analogous to highways and roads
* Packet switches = analogous to intersections
* End systems = analogous to buildings

A truck takes a path through the transportation network, the same way a packet takes a path through a computer network.

## Types of ISPs

* Residential ISPs (local cable or telephone companies)
* Corporate ISPs
* University ISPs
* ISPs that provide WiFi access in airports, hotels, coffee shops, etc. (public places)
* Cellulare data ISPs, providing mobile access to our smartphones and other devices

Each ISP is in itself a network of packet switches and communication links.

These lower-tier ISPs are interconnected through national & international upper-tier ISPs, such as:

* Level 3 Communications
* AT&T
* Sprint
* NTT

An upper-tier ISP has high-speed routers interconnected with high-speed fiber-optic links.

## Protocols
End systems, packets switches, & other pieces of the Internet run protocols that control the sending/receiving of information.

The two most important protocols:

* Transmission Control Protocol (TCP)
* Internet Protocol (IP)
    * Specifies the format of the packets that are sent and received

The Internet's principal protocols are collectively known as **TCP/IP**.

The Internet Engineering Task Force (IETF) developped these protocols, as well as Internet standards.

The IETF standards documents are called requests for comments (RFCs - of which there are currently more than 7,000). They define protocols such as:

* TCP
* IP
* HTTP (Hypertext Transfer Protocol - for the Web)
* SMTP (Simply Mail Transfer Protocol - for e-mail)

