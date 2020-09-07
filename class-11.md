# Class 11 reading notes

### Azure Cloud Administration

**Reading**
* [What is Microsoft Azure?](https://www.howtogeek.com/337961/what-is-microsoft-azure/)
* [Azure AD Identity and Access Management](https://docs.microsoft.com/en-us/azure/architecture/framework/security/identity)

> "Microsoft Azure is a cloud computing service that works similarly to Amazon Web Services (AWS) and the Google Cloud Platform."

Instead of running your own hardware, you pay to access someone else's (usually massive) computing resources - usually in a pay-as-you-go/use type of scenario.  Microsoft Azure (formerly Windows Azure) can support a plethora of apps, virtual machines, file storage, databases, and provide bandwidth.

"In cloud-focused architecture, identity provides the basis of a large percentage of security assurances. While legacy IT infrastructure often heavily relied on firewalls and network security solutions at the internet egress points for protection against outside threats, these controls are less effective in cloud architectures with shared services being accessed across cloud provider networks or the internet."

When you are not in control of all the devices and firewalls, etc., identity and access management becomes your main tool for security and organizational access. 

"A single authoritative source for identities increases clarity and consistency for all roles in IT and Security."

"Consistency of identities across cloud and on-premises will reduce human errors and resulting security risk."

Don't include external partners in your company directory, utilize a cloud identity service instead to maintain integrity. 

***"Don’t synchronize accounts with the highest privilege access to on premises resources as you synchronize your enterprise identity systems with cloud directories."***

