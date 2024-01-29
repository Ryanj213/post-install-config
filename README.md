<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1 Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin

- Item 2 Configure Departments
Admin Panel -> Agents -> Departments
System Administrators

- Item 3 Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets

- Item 4 Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John

- Item 5 Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken

- Item 6 Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours) Configure Help Topics Admin Panel -> Manage -> Help Topics Business Critical Outage Personal Computer Issues Equipment Request Password Reset
