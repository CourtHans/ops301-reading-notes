# Class 9 reading notes

### OSPF Routing

**Reading**
* [What is Routing?](https://www.geeksforgeeks.org/types-of-routing/)</br>
Why is OSPF dynamic routing considered easier to administer than static routing?
* [What is Open Shortest Path First (OSPF)?](https://www.metaswitch.com/knowledge-center/reference/what-is-open-shortest-path-first-ospf)

"Routing is a process which is performed by layer 3 (or network layer) devices in order to deliver the packet by choosing an optimal path from one network to another."

3 types:
1. static routing
2. default routing
3. dynamic routing

Each other various advantages and disadvantages like work/reward ratio (consider the size of your org) and degree of security.

"The OSPF protocol is a link-state routing protocol, which means that the routers exchange topology information with their nearest neighbors."

The bit advantage OSPF is the complete knowledge of topology, but it's not scalable, thus is used typically only to route traffic within a single AS.

**Video**
* [Static and Dynamic Routing - CompTIA Network+ N10-007 - 1.3](https://www.youtube.com/watch?v=YRzr56cwgCg)
* [DDoS Attack Explained](https://www.youtube.com/watch?v=ilhGh9CEIwM)

Routing sends IP packets across a network, and each router only "knows" the next step.

**Static routing** - means an admin can definte the routes manually. Pros are that it can be easier in a small network and you can avoid any overhead. It could also be considered more secure. Cons are that it's very challenging with large networks. Any drops have to be manually reconfigured.

**Dynamic routing** - the routers do the "work" and are updated in real time. Pros - no manual configurations, very scalable. Cons - router overhead/bandwidth, requires a good degree of initial configuration

**Default routing** - the "gateway of last resort" is common for a remote site that may only have one route. The router doesn't have to make any decisions. Pros - can dramatically simplify the routing process

***DDoS***
Distributed denial of service is a cyber attack on a specific server or network with the intended purpose of disrupting normal operation. It does this by flooding the the target with a constant flood of traffic. A DoS attack comes from just one source (and can be easier to pinpoint/mitigate), but a DDoS comes from multiple sources simultaneously, eating up the servers resources (CPU, bandwidth, etc.). </br>
The attacking computer usually "recruits" other computers via malware. It's a **botnet** - hundreds or thousands of computers that can be controlled like an army. These attacks can last for hours or days.</br>
These attacks could be for financial or political reasons or even just for fun.


**Additional Resources**
* [The Attack That Could Disrupt The Whole Internet - Computerphile](https://www.youtube.com/watch?v=BcDZS7iYNsA)
