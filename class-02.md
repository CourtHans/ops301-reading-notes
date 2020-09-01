# Class 2 reading notes

### Networking

**Reading**
* [Networking: A Complete Guide](https://www.ibm.com/cloud/learn/networking-a-complete-guide)

The main takeaway here is that there is no "best" or "right" solution. Each situation is unique and there are many configurations/solutions that can provide the proper infrastructure. Like many things in life... sometimes you have to give it your best shot and go with a little trial and error!

**LAN** connects computers in a defined physical space </br>
**WAN** can connect computers across continents (the internet is the largest example of a WAN)

"You can further define a computer network by the protocols it uses to communicate, the physical arrangement of its components, how it controls traffic, and its purpose."

**Most common types of networks**
* LAN - local area network
* WLAN - wireless local area network
* WAN - wide area network
* MAN - metropolitan area network
* PAN - personal area network
* SAN - storage area network
* CAN - campus area network
* VPN - virtual private network

***Ports***: "If you think of an IP address as comparable to the address of a hotel, then ports are the suites or room numbers within that hotel."

**CDN** - main beneift is that it makes your content delivery faster.

> "The best computer networking solution is typically a unique configuration based on your specific business type and needs."

**Videos**
* [Network Topologies](https://www.youtube.com/watch?v=zbqrNg4C98U)

Most common topology is **star topology**.
Major benefits are that if one computer failed, the others would not be affected. However, the disadvantage is that if the central hub fails, the entire network goes down (SINGLE POINT OF FAILURE).

**Ring topology** </br>
Old, and rarely used. Easy to install and troubleshoot, but if there is a SINGLE break, than all data flow would be disrupted.

**Bus topology** </br>
Old, not used much anymore. All are connected to a single cable. Advantages are that it's fairly cheap, but the cable must be terminated on both ends and there must not be ANY open connections. Signal reflection could disrupt data flow.

**Mesh topology** </br>
Lots of connections, so it handles disruption very well. The advantage is that it creates a high redundancy level; however, there's a huge amount of cabling and network cards so it can be cost prohibitive. The internet uses mesh topology.

**Wireless topology** </br>
Similar to a star topology. Wireless access point acts as a bridge.

**Ad hoc topology** </br>
Doesn't rely on any infrastructure. All devices in an ad hoc network connect in a simple peer to peer network without using a central wi-fi device. Each device is responsible for it's own security and permissions. Useful for setting up a quick network on the fly.

**Wireless mesh topology** </br>
Similar to wired mesh topology...just wireless. Can create a seamless internet system. All the access points are in constant contact with each other (redundancy).

**Additional Resources**
* [Networking Design and Best Practices](https://www.youtube.com/watch?v=sckuGYiHYRA)
* [The Ultimate Guide to Network Design](https://www.itprc.com/the-ultimate-guide-to-network-design/)