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

- Windows 10 Pro</b> (22H2) at least 2vCPUs, 8GB RAM

<h2>Post-Install Configuration Objectives</h2>

- Configuring roles, departments and teams
- Configuring agents (workers) and users (customers)
- Configuring SLAs: <b>Sev-A</b> (grace period: 1hr, schedule: 24x7), <b>Sev-B</b> (grace period: 4hr, schedule: 24x7), <b>Sev-C</b> (grace period: 8hr, schedule: business hr)
- Configuring help topics

<h2>Configuration Steps</h2>

<p>
Log into as an admin user via http://localhost/osTicket/scp then Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin
</p>
<p>
<img src="https://github.com/user-attachments/assets/987273ab-65b0-480c-ad6e-00e5f13b7f07" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br>
<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins
</p>
<p>
<img src="https://github.com/user-attachments/assets/b59a284a-6d71-48f8-9668-b70afe3d42a9" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br>
<p>
Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking
</p>
<p>
<img src="https://github.com/user-attachments/assets/d879884d-7fd2-4220-97ac-899c6f50e4b6" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br>
<p>
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 
</p>
<p>
<img src="https://github.com/user-attachments/assets/062bc273-b7af-4077-bfc5-2d9c52889669" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br>
<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)
</p>
<p>
<img src="https://github.com/user-attachments/assets/e1e7be63-e307-4979-830e-d3406cd19066" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br>
<p>
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
</p>
<p>
<img src="https://github.com/user-attachments/assets/e664a1f7-bfc7-4cbf-afbe-629ad8d81bd1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br>
<p>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
</p>
<p>
<img src="https://github.com/user-attachments/assets/7e6f065d-cbad-48dd-80aa-8ba2dd4fc798" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br>
<p>
Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
</p>
<p>
<img src="https://github.com/user-attachments/assets/5414af91-6ea3-411c-949e-3ba62ba964fe" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>osTicket Setup Complete!</h2>

<b> We've successfully set up multiple agents along with their departments, roles, and permissions. As well as, configured SLAs (Service Level Agreements), help topics, and users! osTicket is now setup for the next project where I will create and work different tickets using multiple agents and users!  </b>
<br />
<br />
</p>
