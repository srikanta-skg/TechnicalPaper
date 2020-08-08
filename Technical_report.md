# Technical Paper On Firewall
## Abstract
> As there is an Increses in Demand for Connecting Various Devices Across the globe, there is a need for robust CyberSecurity to protect our devices form cyber attack which can lead to Tremendous Financial loss as well as loss of confidential data, hence by firewall we can monitor and control incomming and outgoing network traffic from a predeterminded Security Rules.

## Introduction
A Firewall can either be a Software program or a Hardware.
Firewall helps us form protecting our system from an Unauthorized Netwrok or Viruse, worms that tries to reach our system. 

Hardware Firewall is a devices that is connected to our system with untrusted internet, it is also called as network firewall which runs on network hardware. 

A Software firewall is a program to protect each and every computer from hackers. it is a Host-based firewall which control network in and out by running on a host computer.


## What is a Firewall

Firewall control and Monitors the Flow of incomming and outgoing data from our computer.

The task of firewall is to regulate flow of traffic in between computer network of diffrent trust Levels.

For Example, my local Network is zone of high trust where as the incoming network is zone of low trust. this incomming messeges are passed through firewall. firewall checks if this incomming data matches the specified security criteria, then it allows the data to pass the firewall or else it blocks the data enterning our system.

## How Firewall Works

* First generation: packet filters

>Packet filtering, workings on the basis of Allowed and Not Allowed Network permission, in which the Firewall blocks the Not Allowed network from entering our system. The not allowed sites will in included in the Firewall list.

* Second generation: stateful filters

>The Firewall notices which website we are currently using and will have a conversation list of our browsing history, if the unknown data enters our site which is not present in our conversation list that site will be blocked, this method of protection is known as **statefull Inspection.**

*  Proxy FireWall

> This method has saved many computers from hackers.
 The working of Proxy Firewall is as follows, when the request is made from computer A, this request is received from computer B (whcih acts as proxy) and the computer B sends the request to the internet, and the Internet thinks the request was made by computer B, where as computer A is safeguarded by computer B, this method of Security is called as Proxy Firewall

  ## Types of Firewall

  1. Packet Filtering Firewall

  This is the most chepest for of security, here when a user request for data from the internet, the data is split into number of packets, for Example a 400mb data is split into number of small packets of 5mb and transmitted into the network, when the data arrives the system the firewall checks for the port number and if it matches the request port id, the data packet passes the firewall, but there is a disadvantage where as each datapacket containes data payload, this payload might contain virus or be hacked.

  hence, Packet Filter is a Low Security option.

  2. Application or ProxyFire Wall

  In this method, the request from the user is made anonymous by a proxy request, the Hacker will not know how has really made the request, as the anonymity of the user is safeguarded to protect from hackers.
  The Ip address of the computer is not disclosed.

  3. Hybrid Firewall 

  This method has both Packet Filtering Firewall as well as Application firewall to enhance security.

  Hybrid firewall has Packet Firewall and Application firewall in series as a result this method has the higest secirity compared to other types of wirewall.


  ## Limitation of Firewall

  * Firewall can not completly protect us from as it does not scan every incoming data packet.

  * As the firewall is used to protech the user from unauthorized network, if the user itself attacks the internal network the firwall cannot protect the system.
  
  * A firewall is only effective if it has only one entry exit point of a network but if there exist more than one entry exit point it fais to protect.

 * Firewall do not have Anti-Malware or Anti-Vires protection, thus we need extra protection by having anti_virus software Installed on our computers.
 

## CONCLUSION
 As we have examined so far, Firewall is an essential tool to save us from Cyberattcks and to protect our data from Hackers.

 ## Links

 Reference Links
  [Wikipedia](https://en.wikipedia.org/wiki/Firewall_(computing)).
  [researchgate](https://www.researchgate.net/publication/292138198_Role_of_firewall_Technology_in_Network_Security).