# Class 6 reading notes

### Windows Server

**Reading**
* [Microsoft Active Directory®: The Ultimate AD FAQ](https://jumpcloud.com/blog/active-directory-faq)

> "Developed by Microsoft in the late 1990s, AD is the world’s most well-known on-prem directory service. It is a complex platform with many practical applications..."

Active directory was introduced in 1999, and released alongside Microsoft Windows 2000 Server. It takes advantage of DNS and Lightweight Directory Access Protocol (LDAP). 

The primary users of Active Directory are the admins who "actually operate, manage, and configure AD." This typically includes the entire IT team, and may also include members of the security, DevOps, or engineering teams. However, in organizations that employ AD, every employee uses it every day to login to their machines, use apps, print, and share files.

**GPOs* - Group policy objects makes IT administration more efficient.

"A domain controller is any server that is running Active Directory Domain Services." 

"AD DS basically sets up the database of objects that serves as the foundation for AD management. AD DS isn’t the only server role associated with Active Directory, but you could argue that it’s the server role that corresponds most directly to the core functionality that people associate with AD."

"Azure AD has been designed to extend an existing Active Directory instance to the cloud." This is potentially a competitor for Amazon Cloud Services. 

***Fun fact*** - "conventional SSO arose out AD’s inability to authenticate users into web apps during the mid-2000’s."

Active Directory is *not* a server, but it does require a server in order to function. "Generally, to operate AD, you’ll need a server, a backup, data center space, and VPNs. You’ll also need an IT admin who is technically adept enough to operate AD."

The estimated lifespan for a server is about five years - fascinating. 

### Best practices
* Change the default security settings
* Utilize principles of least privilege in AD roles and groups
* Control administration privileges and limit accounts in the Domain Admins group
* Don’t use a domain controller like it’s a computer
* Patch AD regularly
* Monitor and audit AD health
* Define a naming convention at the beginning
* Clean up AD regularly
* Get your domain time right

Costs of Active Directory =</br>
servers + software + hosting + backup + security + monitoring + VPNs + IT admin + third-party SW + multi-factor authentication + governance

Most anything that Active Directory does can be done on an individual system without Active Directory - *manually* from the OS. But the key word there is manual. Active Directory is needed once an organization has reached a size where manual administration over its systems and IT resources is no longer feasible. 