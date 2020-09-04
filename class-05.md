# Class 5 reading notes

### Linux DNS Server

**Reading**
* [DNS Made Easy: What is DNS](https://dnsmadeeasy.com/support/what-is-dns/)
* [Ubuntu Server: A cheat sheet](https://www.techrepublic.com/article/ubuntu-server-the-smart-persons-guide/)

DNS servers are "distributed all around the world. These nameservers are called the root nameservers and instead of storing every domain ever, they store the locations of the TLD (top level domains)."

There are a lot of steps to go through (see below notes on video), but it all happens in milliseconds!

Ubuntu server is an open source platform - a "server operating system, developed by Canonical and open source programmers around the world, that works with nearly any hardware or virtualization platform. It can serve up websites, file shares, and containers, as well as expand your company offerings with an incredible cloud presence."

"In 2015, it was reported that Ubuntu was twice as prevalent on Amazon Cloud services as all other operating systems combined."

Microsoft uses Ubuntu Server images in its Azure platform.

You can use it for:
* Websites
* FTP
* Email server
* File and print server
* Development platform
* Container deployment
* Cloud services
* Database server

"Ubuntu Server now supports ZFS (a file system with built-in snapshot capabilities) and includes the first production release of Data Plane Development Kit (DPDK), which is a set of libraries and drivers for fast packet processing."

INTERESTING - even though it's open source, you can purchase enterprise-grade support.

**Video**
* [How a DNS Server (Domain Name System) works.](https://www.youtube.com/watch?v=mpQZVYPuDGU)

Humans identify with names, not numbers...so networking engineers developed Domain Name System (DNS). DNS will resolve a name to a number b/c the only thing computers know is numbers.

DNS works like a phone book! You look up the NAME first, then the computer (DNS) will give you the number.

Steps
1. Type in yahoo.com
2. Computer will send a query to the resolver server (ISP) if it can't find it in its cache memory.
3. If ISP can't find it, it will send it to the top of the hierarchy - the root server. (There are 13 sets around the world operated by 12 different organizations).
4. When the root server receives the query, it can send the resolver to the right place (TLD - top level domain) for the .com domain.
5. The TLD stores all the domains (.net, .com, etc)
6. TLD will then direct the query to the authoritative name servers for the IP address.
7. Resolver will tell your computer the answer (and store it in it's cache memory)



**Additional Resources**
* [What Is DNS? How DNS Works](https://www.cloudflare.com/learning/dns/what-is-dns/)
* [Understanding How DNS Works in Depth](https://www.youtube.com/watch?v=T-eghY-9WdE)