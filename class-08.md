# Class 8 reading notes

### Identity Management

**Reading**
* [Active Directory 360: Fundamentals of Active Directory, Workgroups and Domains](https://www.windows-active-directory.com/fundamentals-of-active-directory-workgroups-and-domains.html)</br>
What is the benefit of AD over a peered/workgroup network?
* [Active Directory 360: The Structures and benefits or organizational units](https://www.windows-active-directory.com/the-structures-and-benefits-of-organizational-units.html)</br>
Why might an organization use organizational units?
* [Technical Documentation - Microsoft: Manage RBAC with Server Manager](https://docs.microsoft.com/en-us/windows-server/networking/technologies/ipam/manage-role-based-access-control-with-server-manager)</br>
Have a look around Microsoft’s official documentation to get an idea of processes surrounding RBAC.

Active Directory (AD) is a set of five services that run on a Windows server to manage permissions and access to network resources.

1. AD Domain Services (AD DS)
2. AD Lightweight Directory Services (AD LDS)
3. AD Federation Services (AD FS)
4. AD Certificate Services (AD CS)
5. AD Rights Management Services (AD RMS)

**Workgroups vs. domains**
A *workgroup* is a peer-to-peer network with no central authentication. With a domain set-up, all login and access requests by users are managed by a domain controller (DC) that runs AD.

There are three main benefits of using OUs:

1. Manage objects efficiently - put similar objects together in an OU
2. Deploy Group Policy Object (GPO) settings -  link specific groups to your OU for mass implementation of controls/standards
3. Delegate administrative control - distributed administrative authority. 

I suspect this third article will be really helpful for the day's lab, but not one that really lends to summary!