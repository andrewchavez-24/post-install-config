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

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>

<p>
Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin
</p>
<br />

![Screen Shot 2025-03-07 at 9 29 23 AM](https://github.com/user-attachments/assets/987273ab-65b0-480c-ad6e-00e5f13b7f07)


<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins
</p>
<br />

![Screen Shot 2025-03-07 at 9 31 35 AM](https://github.com/user-attachments/assets/b59a284a-6d71-48f8-9668-b70afe3d42a9)


<p>
Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking
</p>
<br />

![Screen Shot 2025-03-07 at 9 34 02 AM](https://github.com/user-attachments/assets/d879884d-7fd2-4220-97ac-899c6f50e4b6)


<p>
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 
</p>
<br />

![Screen Shot 2025-03-07 at 9 35 28 AM](https://github.com/user-attachments/assets/062bc273-b7af-4077-bfc5-2d9c52889669)

<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)
</p>
<br />

![Screen Shot 2025-03-07 at 9 40 46 AM](https://github.com/user-attachments/assets/e1e7be63-e307-4979-830e-d3406cd19066)

<p>
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
</p>
<br />

![Screen Shot 2025-03-07 at 9 59 35 AM](https://github.com/user-attachments/assets/e664a1f7-bfc7-4cbf-afbe-629ad8d81bd1)

<p>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
</p>
<br />

![Screen Shot 2025-03-07 at 9 59 35 AM](https://github.com/user-attachments/assets/7e6f065d-cbad-48dd-80aa-8ba2dd4fc798)

<p>
Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
</p>
<br />

![Screen Shot 2025-03-07 at 10 25 32 AM](https://github.com/user-attachments/assets/5414af91-6ea3-411c-949e-3ba62ba964fe)


