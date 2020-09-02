# Class 3 reading notes

### Endpoint Acquisition

**Reading**
* [Endpoint Agents in Modern Environment](https://blog.rapid7.com/2018/08/22/endpoint-agents-are-necessary-for-todays-modern-environment-heres-why-part-1/)
* [Windows 10 Hardening Techniques](https://resources.infosecinstitute.com/category/certifications-training/securing-windows-ten/windows-10-hardening-techniques/)

**Video**
* [The Value of Continuous Monitoring With Agents](https://www.youtube.com/watch?v=hZc85wyxkV4)

To better integrate vulnerability management and incident detection and response programs,you can leverage endpoint agents. 

**Use cases**
* Real-time monitoring
* Remote monitoring of global assets and workers
* Monitoring of cloud and other virtual infrastructure
* Ability to take action through the agent
* Assessment that does not require credential scanning
* Limited resource impact
* Streamlined deployment options
* Interoperability

> "Hardening an operating system (OS) is one of the most important steps toward sound information security."

Hardening is reducing the attack surface that attackers have available to them.</br>
Configure your computer to ony do what you want it to do, and no more... don't leave any slack available for attackers to prey upon. </br>

Principles of **deter, deny, delay** and **detection** (hardening covers the first three)

1. Start with a secure installation
2. Clean up unwanted programs (i.e. bloatware)
3. Encryption (hard drives!)
4. Updates, patches and service packs
5. Ensure proper BIOS configuration
6. Enable the guards (device, credential, application, exploit)
7. Get rid of unneeded services
8. TURN ON WINDOWS DEFENDER
9. Group policy (fairly complex, mostly employed by organizations)
10. Ransomware protection - Virus & Threat Protection → Ransomware protection → Manage ransomware protection.
11. Secure authentication
12. Secure web browsing

These techniques are just a start, but there's no "code" to hardening... utilize the tools best for your use case.

Video highlights need for real time coverage of remote assets. </br>
Agents don't require credentials to provide critical details (useful for disparate teams and those that are reluctant to release credentials outside a closed environment).</br>
Consider the footprint that the agent will have on your devices. Things like how much CPU, RAM, disk space, network bandwidth, etc.</br>
Find an agent that plays nicely with your current configuration(s), agents with HIGH interoperability (send one out, get multiple things done).</br>
Rapid 7 uses agents that do vulnerability assessment as well as real time detection and response. 

**Additional Resources**
* [Linux, Mac and Unix File Permissions](https://stevenbarrett1984.wordpress.com/2014/02/08/linux-mac-and-unix-file-permissions-and-the-chmod-command-part-1/)
* [Operating System Hardening - CompTIA Security+ SY0-401: 3.6](https://www.youtube.com/watch?v=YSwTfealIV4)