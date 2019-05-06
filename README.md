> Title: Open Systems Interconnection
> Author: Sarah Wooldridge
> Brief Summary: The purpose and content of this tutorial is to educate the reader on the Open Systems Interconnection or OSI for short. Listed below is what the OSI does, a breif history, and an explantion of the layers.
> Target Audience: The target audience of this tutorial is those interested in the topic of OSI. This content is suitable for those with some background information of computer science or information technology. 


# Open Systems Interconnection (OSI)
The Open System Interconnection model (OSI) is a conceptual framework that describes the functions of a networking system. It can also be known as the OSI Seven Layer Model.
There are 7 different abstract layers: Physical, Data Link, Network, Transport, Session, Presentation, and Application.

### History of the OSI
In 1984 the Internalional Organization for Standardization (ISO) developed a document that defined a standard for the architecture of networking systems.


### Description of OSI Layers

#### Application 
The application layer is the top layer at layer 7 in the OSI model. It is in the host layer and part of the data in the Protocoal data unit (PDU). The function is High-level APIs, inclduign resource sharing, remote file access, directory services and virutal terminals. Examples of this are: HTTP, FTP, SMTP

#### Presentation
The presentation layer is the 6th layer in the OSI model. It is in the host layer and part of the data Protocol data unit (PDU). The functions of this is translation of data between a networking service and an application; including character encoding, data comptression and encryption/decryption. Examples of this are: STP, Telnet, SNMP

#### Session
The session layer is the 5th layer in the OSI model. It is in the host layer and part of the data Protocol Data Unit (PDU). The function is managing communication sessions like continuous exchange of information in the form of multiple back-and-forth transmission between two nodes. Examples include RPC, PAP, NetBIOS

#### Transport
The trasnport layer is the 4th layer in the OSI model. It is in the host layer and part of the Segment Datagram Protocol Data Unit (PDU). It provides transparent transfer of data between end systems, or hosts, and it is responsible for end to end recovery and flow control. It ensures complete data transfer. Examples incldue SPX, TCP, UDP.

#### Network
The network layer is the 3rd layer in the OSI model. It is part of the media layer and the Packet Protocol Data Unit (PDU). The function of the network layer is structuing and managing a mutli-node network, including addressing, routing, and traffic control. Examples of this are: IP, DDP, IPX

#### Data Link
The data link layer is the 2nd layer in the OSI model. It is part of the media layer and the Frame layer in the Protocol Data Unit (PDU). Its functions are reliable transmission of data frames between two notes connected by a physical layer. It also handles error correction from the physical layer. Switches mostly operate here. Examples: Ethernet, LocalTalk, Token Ring

#### Physical
This physical layer is the 1st layer in the OSI model. It is part of the media layer and the Symbol PDU. Its functions arae transmission and reception of raw bit streams over a physical medium. This can include everything from the cable type, radio frequency link, as well as the layout of pins, voltages and other physical requirements. Examples include: Fiber Optics, Radio, Electricity

### OSI Model Acronym
7 Away - Application   
6 Pizza - Presentation  
5 Salami - Session   
4 Throw - Transport  
3 Not - Network  
2 Do - Data Link  
1 Please - Physical  

### Userful Links
Watch: [The OSI Model Demystified](https://www.youtube.com/watch?v=HEEnLZV2wGI)  
Watch: [OSI Explained in 2 minutes](https://www.youtube.com/watch?v=A_3wBgfVDZo)  
Read: <a href="https://www.networkworld.com/article/3239677/the-osi-model-explained-how-to-understand-and-remember-the-7-layer-network-model.html" target="_blank">The OSI Model Explained</a>  
Read: <a href="https://www.geeksforgeeks.org/layers-osi-model/" target="_blank">Computer Network | Layers of OSI Model</a>  
