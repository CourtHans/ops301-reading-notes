# Class 10 reading notes

### Linux Web Server

**Reading**
* [Barracuda: What is a DMZ Network?](https://www.barracuda.com/glossary/dmz-network)
* [Mozilla: What is a web server?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server#:~:text=On%20the%20hardware%20side%2C%20a,devices%20connected%20to%20the%20web.)

> "The goal of a DMZ is to add an extra layer of security to an organization's local area network. A protected and monitored network node that faces outside the internal network can access what is exposed in the DMZ, while the rest of the organization's network is safe behind a firewall."

A DNZ is, essentially, a protected subnetwork. Email, web servers, and DNS servers have  increased potential for attack, so they are often placed into the monitored subnetwork.

"There are numerous ways to construct a network with a DMZ. The two major methods are a single firewall (sometimes called a three-legged model), or dual firewalls."

The more secure approach involves 2 firewalls (the dual firewall method) - a frontend and backend. It's more effective, but also more costly.

"On the hardware side, a web server is a computer that stores web server software and a website's component files." " On the software side, a web server includes several parts that control how web users access hosted files."

A static web server, or stack, consists of a computer (hardware) with an HTTP server (software). </br>
A dynamic web server consists of a static web server plus extra software, most commonly an application server and a database.

You could host files on your computer, but it makes much more sense (power and availability) to host on a dedicated server.

On a web server, the HTTP server is responsible for processing and answering incoming requests.

A server can server either static or dynamic content, the latter being more complicated but offering a more impressive user experience.  


