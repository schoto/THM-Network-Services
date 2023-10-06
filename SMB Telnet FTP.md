<h1>Here we go again</h1>

What is SMB?

SMB - Server Message Block Protocol - is a client-server communication protocol used for sharing access to files, printers, serial ports and other resources on a network.

The SMB protocol is known as a response-request protocol, meaning that it transmits multiple messages between the client and server to establish a connection. Clients connect to servers using TCP/IP (actually NetBIOS over TCP/IP as specified in RFC1001 and RFC1002), NetBEUI or IPX/SPX.

How does SMB work?

![XMnru12](https://github.com/schoto/THM-Network-Services/assets/69323411/17737dba-c0d9-47e8-9487-4cb8b4b4c5fe)

Once they have established a connection, clients can then send commands (SMBs) to the server that allow them to access shares, open files, read and write files, and generally do all the sort of things that you want to do with a file system. However, in the case of SMB, these things are done over the network.

What runs SMB?

Microsoft Windows operating systems since Windows 95 have included client and server SMB protocol support. Samba, an open source server that supports the SMB protocol, was released for Unix systems.

**Questions / Answers**

What does SMB stand for?    

```server message block```

What type of protocol is SMB?    

```response-request```

What do clients connect to servers using?    

```tcp/ip```

What systems does Samba run on?

```unix```


