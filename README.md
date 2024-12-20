<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<background color green>

<h1>osTicket - Post-Install Configuration</h1>
The work demonstrated outlines the post-install configuration of the open-source help desk ticketing system osTicket, and the work behind it.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure agents (workers)
- Configure users (customers)
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/N0kcVLC.png" height="80%" width="80%">
</p>
<p>
 I have successfully configured a new department within the osTicket system specifically for SysAdmins. This department is set to an active status, indicating that it is currently operational for handling tickets.  The setup includes system defaults for Service Level Agreements (SLAs) and scheduling, optimizing response times and ticket handling efficiency. 
</p>
<br />

<p>
<img src="https://i.imgur.com/KEsc0y1.png" height="80%" width="80%">
</p>
<p>
The setup allows for detailed specification of the ticket’s attributes, including priority, department assignment, and the related service level agreement (SLA). The form is designed to capture essential information from the user, ensuring a clear and concise ticket submission. Features like auto-response and alert settings are also configurable, allowing for automated communication upon ticket creation and updates.
</p>
<br />

<p>
<img src="https://i.imgur.com/TQaCtXW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
in this phot ive just created another general ticket, with a low SLA level of severity for a request for general dekstop help.
</p>
<br />
