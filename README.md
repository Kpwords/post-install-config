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
- Configure Team
- Configure Agents
- Configure Users (Customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/pnYyMAC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 


<img src="https://i.imgur.com/tR7OMvB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Configure Roles:

Admin Panel -> Agents -> Roles -> Supreme Admin
</p>
<br />

<p>
<img src="https://i.imgur.com/K7FCfDv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Configure Departments: 

Admin Panel -> Agents -> Departments -> System Administrator
</p>
<br />

<p>
<img src="https://i.imgur.com/Ac1f0FT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/52UlO4Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



</p>
<p>
3. Configure Team: 

Admin Panel -> Agents -> Teams -> Level 1 Support / Level 2 Support

Make Sure "Registration Required" Is Unchecked.
</p>
<br />

<img src="https://i.imgur.com/qNOybDd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/4Eudmg1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/ifsY9Kn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/858X9p7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Configure Agents (Workers)

Admin Panel -> Agents -> Add New
</p>
<br />

<img src="https://i.imgur.com/68zf5n2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Configure Users (Customers)

Admin -> Users -> Add New
</p>
<br />

<img src="https://i.imgur.com/1q1SQsM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Configure SLA

Admin Panel -> Manage -> SLA

SEV-A (1 hour, 24/7)
SEV-B (4 hours, 24/7)
SEV-C (8 hours, Business Hours)
</p>
<br />

<img src="https://i.imgur.com/up8kxaq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Configure Help Topics

Admin Panel -> Manage -> Help Topics


-Business Critical Outage
-Personal computer Issues
-Equipment Request
-Passwords Reset
</p>
<br />

