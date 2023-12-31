<h2>☄ Microsoft Sentinel (SIEM) Azure Lab with Cloud-based Honeypot </h2>
<br />

This repo is for the scripts used in the [<b>🔷Microsoft Sentinel (SIEM) Azure Lab</b>](https://tektsunami.com/alabsentinel.html) , you can read more about it on my website where I explain step-by-step how to implement all the tools necessary. <br />
The scripts are made with <b>KQL</b> (query language to be used in Azure on the Log Analytics Workspace and Microsoft Sentinel dashbaord) and with <b>Powershell</b> (to be used in the Virtual Machine). <br /> <br />

In this lab I've created a vulnerable and exposed (to pretty much anything) Windows Virtual Machine in Azure, aka Honeypot, then I've displayed (by using various Azure tools and log extractions) all the attempted brute force attacks towards my Virtual Machine on a world map. <br /> <br />

I let the Virtual Machine run defenseless for less than 1 hour, and yet all these attacks happened. If you let it run for 24 hours or more, you'll probably see thousands upon thousands of attempts. It truly makes you understand how important security is with anything you do or have on the internet.

<br />
<h3>🔶 Experience gained: </h3>

- Detection of threats, Analysis of logs and Prevention with SIEM systems. <br />
- Configuration and Deployment of Azure tools: <b>Azure Virtual Machines, Log Analytics Workspace and Azure Sentinel</b>. <br />
- Management of Windows Security Event logs and Event Viewer. <br />
- KQL to create queries to be used with Azure tools. <br />

<br />

<h3>🗺 Microsoft Sentinel live attacks Map: </h3>  <br />

![map-image](labsentinel10.png)
