# osTicket-Configuration
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Internet Information Services (IIS)
- osTicket application

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, and Teams on the osTicket platform
- Configure Agents to recieve and attend to user request
- Configure Users to log a request in ticketing system
- Configure Service Level Agreement (SLA) 
- Create a ticket and show resolution

<h2>Configuration Steps</h2>
<p>
I will start off by navigating through the OsTicket platform using the objectives above to show some of the major functions that are utilized. The first function we would look at is "Roles".

1. CONFIGURE ROLES
  
Roles are important in managing and organizing support teams effectively. They help structure permissions, responsibilities, and access to various parts of the help desk system, allowing for better workflow and security. This way, each person has the appropriate level of access, responsibility, and control over the system
</p>
<br />

<p>
<img src="https://i.imgur.com/U468XX0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To create a Role, navigate to the "Admin Panel" tab at the top right corner, go on to click on "Agents" > "Roles" > "Add New Role"
We'll call the role we are creating "Supreme User"
</p>
<br />

<p>
<img src="https://i.imgur.com/MjIH0Ge.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to "Tickets" and "Tasks" tab. For the purpose of having seamless explaination of osTicket usage, I'll assign all permissions to the role being created. (NOTE: This is not standard practice, except it is required by the organisational policies). Once that is done, click "Add role" to create the role
</p>
<br />

<p>
2. CONFIGURE DEPARTMENTS

The department to be created is the SysAdmin department. This department is responsible for managing and maintaining the IT infrastructure for an organization. They set up and maintain servers, set up and maintain user accounts, monitor cybersecurity threats, respond to IT issues and troubleshoot system problems
</p>
<br />
<p>
<img src="https://i.imgur.com/VIIrPwA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
To create a Department, navigate to "Departments" > "Add New Department"
</p>
<br />

<p>
<img src="https://i.imgur.com/Df7TECp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under settings, click on the "Parent" drop down, to select the Top-Level Department. We will select "Support" since they have a support function as apart of their role
</p>
<br />

<p>
3. CONFIGURE TEAMS
  
 Teams play a crucial role in organizing and managing ticket assignments efficiently within an organization. Teams allow multiple agents work together on tickets thereby reducing bottlenecks and ensuring faster ticket resolution. Utilizing Teams allow controlled access to tickets based on expertise and responsibility.

 The "Online Banking" team will be created.
</p>
<br />

<p>
<img src="https://i.imgur.com/faSMLLg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To create a Team, navigate to "Teams" > "Add New Team"
</p>
<br />

<p>
<img src="https://i.imgur.com/tWk1kCg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After typing in the name, you can navigate to the "Members" tab where you can assign Agents to the team as needed
</p>
<br />

<p>
4. CONFIGURE AGENTS

Agents are employees responsible for handling and resolving tickets. They are the first point of contact who interact with customers or end-users to provide support.

Two (2) agents will be created: Jane Doe(Sysadmin) and John Doe(Support). 
</p>
<br />

<p>
<img src="https://i.imgur.com/jRHPR2G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To create a New Agent, click on the "Agents" tab, and go on to click on "Add New Agent"
</p>
<br />

<p>
<img src="https://i.imgur.com/MjIH0Ge.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to "Tickets" and "Tasks" tab. For the purpose of having seamless explaination of osTicket usage, I'll assign all permissions to the role being created. (NOTE: This is not standard practice, except it is required by the organisational policies). Once that is done, click "Add role" to create the role
</p>
<br />

1. CONFIGURE ROLES
  
Roles are important in managing and organizing support teams effectively. They help structure permissions, responsibilities, and access to various parts of the help desk system, allowing for better workflow and security. This way, each person has the appropriate level of access, responsibility, and control over the system
</p>
<br />

<p>
<img src="https://i.imgur.com/U468XX0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To create a Role, navigate to the "Admin Panel" tab at the top right corner, go on to click on "Agents" > "Roles" > "Add New Role"
We'll call the role we are creating "Supreme User"
</p>
<br />

<p>
<img src="https://i.imgur.com/MjIH0Ge.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to "Tickets" and "Tasks" tab. For the purpose of having seamless explaination of osTicket usage, I'll assign all permissions to the role being created. (NOTE: This is not standard practice, except it is required by the organisational policies). Once that is done, click "Add role" to create the role
</p>
<br />

