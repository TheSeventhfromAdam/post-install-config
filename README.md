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

- Configure Roles
- Configure Departments
- Configure Teams
- Allow tickets to be made
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/hnw723r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/c3jx0Hb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/U212692.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/29nqNEg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/xMBaGmZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/JefGp1b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/UtQICbW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/MWFMBxU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/9wFW7w2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/dqsC1fw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1:Configure Roles: Login to http://localhost/osTicket/scp/login.php Admin Panel -> Agents -> Roles. Create Supreme Admin
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2 Configure Departments: Admin Panel -> Agents -> Departments
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3 Configure Teams: Admin Panel -> Agents -> Teams. Create Tier I and Tier II Support
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Step 4 Allow anyone to make a ticket: Admin Panel -> Settings -> User Settings. Registration NotRequired: Allow tickets to be submitted without registration
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5 Configure Agents (workers): Admin Panel -> Agents -> Add New. Make new agents Jane and John, or whatever name you prefer.
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6 Configure Users (Customers): Agent Panel -> Users -> Add New. Add Karen and Ken, or whatever name you prefer.
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7 Configure SLA: Admin Panel -> Manage -> SLA. Sev-A (1 hour, 24/7),Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours)
</p>
<br /

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 8 Configure Users Help Topics: Admin Panel -> Manage -> Help Topics. Create these topics (Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset)
</p>
<br />
