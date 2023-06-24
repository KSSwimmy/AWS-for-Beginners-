# AWS-for-Beginners-
Life in the cloud ☁️

---

# IT FUNDAMENTALS 


### CLIENT SERVER COMPUTING

Examples: 
- phones
- laptops/notebooks
- desktops

#### Basic Architecture of a Computer

1. **Central Processing Unit (CPU)** : The processor that actually preforms processing data.

2. **Random Access Memory (RAM)** : This is non persistent storage. It has really high preformance and it's used for keeping data that the actual CPU and computer operating system need to access quickly. 

3. **Hard Disk Drives (HDD) or Solid State Driver SD** : This is where files and videos are stored and can be stored for a long periods of time. You *shouldn't* lose them.

4. **Network Interface Cards (NICs)** : Connects you to the internet or other computers on a network. 

#### Measurements for Components  

1. **CPU** - typically measured in gigahertz (GHz - Billions of Cycles per second)
2. **RAM** - Gigabytes (GB)
3. **Hard Disk** - Gigabytes (GB)
4. **Network Interface Card** - Megabytes per second. Gigabytes per second. Measured in terms of its performance, how much data it can actually transmit and receive over a network, and that's usually megabits per second or gigabits per second.

#### Servers Vs Desktops/Laptops 

Servers are a little bit more behind the scenes for most people.

There are different types of servers that serve different purposes. 
- Web servers
- Email servers 

Inside the server, the inside components are pretty much identical to a CPU the difference is servers are designed so that many users can connect to them. 

Server Hardware Build 
- Hardware is more specialized 
- Much higher prices compared to desktops and laptops 
- Includes redundancy 

#### Clients and Servers 

Desktops, phones, and tablet devices. There are laptops, and then there are  devices which are installed in cars, washing machines, and manufacturing equipment.

And each of these client devices is able to communicate over a network to a server.

And the servers are running in the cloud and they offer services such as applications and processing of data and data storage.

Client devices are connected over a network such as the Internet, and they can be connected through a wired connection, a wireless connection, or a cellular network.

Sometimes we call the internet the cloud which is cloud networking. 

Cloud computing is the servers in the data center. 

#### Connecting to Servers 

_**Q: How does the computer find the web server on the internet?**_

_A: the client application finds the server by its IP address._

when the user enters something like Amazon.com into their browser, a answer comes back from a DNS server with an IP address. And that address is used by the computer to connect to the web server.

##### HTTP Protocol

the protocol after connecting to the IP address is the Hypertext Transfer Protocol HTTP, and that uses a specific port.

Think of a port as a door into the server.

#### Server to Server Connectivity 

example, application servers will often need to store information in a database.

So here in this example, the protocol for MySQL is being used and that uses a free, free zero six

so the application server can connect to the database server using a specific protocol and port and

then store information in the database.

---

## Storage - Block vs File vs Object

---

There are 3 key types of storage systems
1. **Block Base Storage System:** Examples, hard disk drives or solid state drives - And what that means is your operating system, Windows or Linux, actually sees a hard disk drive, so it sees a drive on which you can create a volume and then you can partition that volume.

For example, there could be a 1000 gigabytes volume and we could then partition that so we could

say, I want to create a C drive with 800 gigabytes and a D drive with 200 gigabytes.
2. **Network Attached Storage:** connecting using a network interface card, you're going over a network and then you're accessing a network attached storage server. **Example:** network attached drives and that could be a corporate shared directory. The operating system sees a file system that is mapped to a local drive letter. A file based storage system.
3. **Object Storage Systems:** user might upload an object using a web browser. 
So rather than using, for instance, a file management system like Windows Explorer, they're using

a web browser and uploading an object to a container on the internet somewhere.

Uses the HTTP protocol Uses REST API

So objects can be files, videos, images, pretty much anything that you any kind of file type that you may want to upload.

---

## IP Addresses and DNS 

### What is and IPv4 (IP version 4) address? 

IP Addresses are address that computers use to communicate with each other

If there's a computer somewhere on a network and that computer wants to connect to the web server, they might use a browser. 

When the user enters the url (uniform resource locater which is also a DNS address)A DNS server is used to map the domain name, such as Amazon.com the IP address that's associated with the server.

#### What happen when I enter a domain name into the browser?

The domain name communicates to the DNS server. Once it communicates and knows what the IP address is it can then communicate directly with the web server using the IP address.

### Structure of an IPv4 Address

`192.168.0.1`

The dots in between the numbers stands for **Dotted Decimal Notation** and each part of the address is a _binary octet_.

#### What is a binary octet mean? 

Octet means that eight, eight bits.

There are eight bits which are either a one or zero.

From left to right they have different values.

Now the most significant bit on the left has a value of 128, and the least significant bit on the right

has a value of one.

The **subnet mask** is used to define the network and the host ID. 

#### Networks and hosts

On a Network they will have different host IDs and the same Network ID.

##### See visual example in the slide

#### Private IP Addresses 

There are private IP addresses that aren't accessible over the internet. 

---
### Bandwidth and Latency

**Bandwidth** is the rate of data transfer for a fixed period of time, measured in gigabits per second (Gbps).

The larger the bandwidth the thicker the pipe. It's the width of the communication band.

Latency is the amount of time it takes to send the data from one point to another, and it's measured. Either in microseconds or milliseconds.

Latency is essentially the delay. How long is it going to take to send some data from the left here to the computer on the right here.

The quantity of data that you actually have in the channel, that is the bandwidth.

We think about distance being the biggest factor in terms of latency. 

---

### Networking - Routers, Switches, and Firewalls

A **switch** is often known as a layer two device. It just has some intelligence on how to send communications between computers within a individual network.

***So how can a computer in the subnet on the right hand side here connect to the subnet on the left or vice versa?***

Well, for that you need a **router.**

A router is known as a layer free device and that simply means that it's able to understand network numbers.

**Firewalls** are used for security and we can place them in various different places in our network.

Applying security at various different layers in our network is a security best practice. (See slide 38 for example {Layer table})

---

### API (Application Programming Interface)

**So what is an API?**

API is often known as a RESTful API and REST stands for Representational State Transfer and it uses the HTTP protocol, the very same protocol we use for browsing the internet from a web browser on our computer.

APIs can then connect to various backend services like websites and application servers and databases.

---

# Section 4 Cloud Computing Concepts 

### Legacy IT/Traditional  

Data center building
• Data center security
• Physical IT hardware
• Software licensing costs
• Maintenance contracts
• Power
• Internet connectivity
• Staff wages (design, build,
operations, maintenance) 

---

### What is Cloud Computing? Well-known examples 

1. Gmail
2. Dropbox 
3. Sealsforce 

- You don't own or manage the infrastructure on which the service runs.
- Cloud services are offered on a subscription/consumption model
-  Service scales as demand changes

---




