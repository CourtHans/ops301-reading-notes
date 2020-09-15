# Class 13 reading notes

### Patch Management

**Reading**
* [What is Patch Management?](https://heimdalsecurity.com/blog/patch-management/)
* [Windows Server Update Services (WSUS)](https://docs.microsoft.com/en-us/windows-server/administration/windows-server-update-services/get-started/windows-server-update-services-wsus)

**Videos**
* [Windows Server 2016 for Beginners What is WSUS](https://www.youtube.com/watch?v=D4FacqsQka8)

> ***"Bad patch management has been one of the reasons behind the largest cyber-attacks to date."***

Even though patches attempting to shore up known vulnerabilities can be released in a timely manner, if end users don't deploy those patches, malicious actors will be ready to exploit the gap in protection. An organization simply *cannot* leave patch management to chance or to the schedules of individual (often well-meaning but not expertly informed) employees. It's critical to have a top-notch patch management plan in place. A *single* unpatched device can be a gaping hole in your organization's security. That said, this is but one (critical) tool in an organization's security arsenal.

A patch is like a "bandaid" applied to software, "a piece of software code that improves an installed program."

In general, there are three categories:
1. *Feature patches* (improve software functionality and provide additional capabilities)
2. *Bug fix patches* (address certain errors found in software, preventing crashes)
3. *Security patches* (enhance security by correcting known software vulnerabilities and covering holes)

Benefits of automated patch management:
1. **Increased productivity**
2. **Full compliance**
3. **Increased security**

### WSUS

"You can use WSUS to fully manage the distribution of updates that are released through Microsoft Update to computers on your network."

"In a WSUS implementation, at least one WSUS server on your network must be able to connect to Microsoft Update to get available update information."

Update management is the process of controlling the deployment (timing, rollout, how many machines & when, whose machines) of interim software releases (and patches). This can help you maintain operational efficiency, overcome security gaps, and maintain stability. 

"The core scenarios where WSUS adds value to your business are:
* Centralized update management
* Update management automation"

"Windows Server Update Services is a built-in server role that includes the following enhancements:
* Can be added and removed by using the Server Manager
* Includes Windows PowerShell cmdlets to manage the most important administrative tasks in WSUS
*Adds SHA256 hash capability for additional security
*Provides client and server separation: versions of the Windows Update Agent (WUA) can ship independently of WSUS"

WSUS has recently enabled PowerShell commandlets.

## What is WSUS?

In short, it's a server role that allows admins to control Windows Updates within their domain.

It acquires the updates via direct downloads from Microsoft (if you have internet connectivity). OR you can download updates from another upstream WSUS server. OR you can import from files copied to your server. 

***WSUS should NEVER be installed on a Domain Controller.***

Separate out your WSUS servers so you don't expose your sensitive/proprietary data.  First, add a WSUS Server Role (again, not on a domain controller), then configure client computers with group policy. THEN organize WSUS clients into Computer Groups. Have a "test" group for updates so you can assess impact. 

**Patch Tuesday** - generally the second (sometimes the 4th) Tuesday of each month, when Microsoft releases all their updates.
