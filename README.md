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

- Configure Roles, Departments, and Teams
- Configure SLAs
- Add Users and Agents
- Configure Help Desk Topics
- Practice Creating and Closing Tickets

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/itrvCb3.png" height="80%" width="80%" alt="Logging into osTicket"/>
</p>
<p>
<b>- Navigate back to the osTicklet Website through the IIS Manager
</p>- Log into osTicket with the admin credentials from earlier</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/MnbW8ry.png" height="80%" width="80%" alt="Creating osTicket Roles"/>
</p>
<p>
<b>- Select the Roles menu tab under the Agents Tab
</p>- Click Add New Role and name the new role "Supreme Admin"
</p>- Click the Permissions Menu Tab and check to allow all the permissions in the tickets, tasks, and knowledgebase tabs
</p>- Click Add Role to create the new Supreme Admin Role</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/SzSMVCG.png" height="80%" width="80%" alt="Creating osTicket Departments"/>
</p>
<p>
<b>- In the Admin portal, select Departments under the Agents Menu Tab
</p>- Click Add New Department
</p>- Name the new department "System Administrators" and create the deparment with everything else default</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/yJqJdcj.png" height="80%" width="80%" alt="Creating osTicket Teams"/>
</p>
<p>
<b>- In the Admin portal, select Teams under the Agents Menu Tab
</p>- Click Add New Team
</p>- Name the new department "Level II Support" and add yourself under the Members tab
</p>- Click Create Team</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/4ZSp6X9.png" height="80%" width="80%" alt="Enabling Anonymous Tickets"/>
</p>
<p>
<b>- In the Admin portal, select the Settings Menu Tab
</p>- Select Users
</p>- Make sure "Require registration and login to create tickets" is unchecked to enable anonymous tickets</b>
</p>
<br />


<p>
<img src="https://i.imgur.com/CyseVMm.png" height="80%" width="80%" alt="Creating osTicket Agents"/>
</p>
<p>
<b>- In the Admin portal, select the Agents Menu Tab
</p>- Select Add New Agent
</p>- Fill in and create a new agent
</p>- Create a password for the new user and make sure "send the agent a password reset email" and "Require password change at next login" are not checked
</p>- Select the Acesss Menu Tab and select the "System Administrator" Department
</p>- Select the Teams Menu Tab and add the user to Level II support
</p>- Click Create to finish creating the agent</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/rRLoDvm.png" height="80%" width="80%" alt="Creating osTicket Users"/>
</p>
<p>
<b>- In the Agent portal, select the Agents Menu Tab
</p>- Click on Users and Add User
</p>- Fill in and create a new User</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/BAou167.png" height="80%" width="80%" alt="Creating osTicket SLAs"/>
</p>
<p>
<b>- In the Admin portal, select the Manage Menu Tab
</p>- Click on SLAs and Add New SLA Plan
</p>- Name the first SLA "Sev-A", Grace period is 1 hour, Schedule is set to 24/7
</p>- Name the second SLA "Sev-B", Grace period is 4 hour, Schedule is set to 24/7
</p>- Name the Third SLA "Sev-C", Grace period is 8 hour, Schedule is set to Business Hours</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/u3440wA.png" height="80%" width="80%" alt="Creating osTicket Users"/>
</p>
<p>
<b>- In the Admin portal, select the Manage Menu Tab
</p>- Click on Help Topics and Add New Help Topic
</p>- Create the help topics called "Business Critical Outage", "Personal Computer Issues", "Equipment Reset", "Password Reset"</b>
</p>
<br />
