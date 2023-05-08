<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This overview tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Adding Roles
- Permissions
- Configure Departments
- Teams
- creating tickets/ users
- Agents
- Configuring SLA
- Help Topics

<h2>Configuration Steps</h2>

</p>
<p>
First we wil Enter to the VM (Virtual Mashine) login to your osTicket, lets create a new role. for that go to "Admin Panel>Agents>Roles" and "add new role ".
  add the name, and set your permissions how you want them. images below
</p>
<br />

<p>
<img src="https://i.imgur.com/q2z1b4S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/1LOv953.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Creating deparments is important to better manage your activities on osTicket. now lets configure a department, let go to "Admin Panel>Agents>Deparments"
click on "Add New Department" name it "System Administrators" Than "create department". images below.
</p>
<br />

<p>
<img src="https://i.imgur.com/6yscLD9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

 Now lets create a team. we will stay in "Admin Panel" go to "Agents>Teams" and "Add New Team". Name the team, add Agent. images below.
</p>
<br />

<p>
<img src="https://i.imgur.com/yHawZnt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

  
Lets allow anyone to create a ticket to submit. go to " Settings>Users" uncheck "Required Registration & login to create tickets" images below
  
  
<p>
<img src="https://i.imgur.com/YWCQS9n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

Configuring Agents, select "Agents" still in "Admin Panel" and "Add New Agent" on agent select their primary department and give it a role add as many agents you need. images below.

<p>
<img src="https://i.imgur.com/mwVFulr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/7833VvB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

Configuring users, users are the ticket owners. to do this, go to "Agent Panel>Users>Add Users" images below.

<p>
<img src="https://i.imgur.com/8TJpHlV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

Configuring SLA, configuring the rules of actions on tickets depending on severity. lets go back to "Admin Panel" than go to "Manage" & "SLA" create as need it. images below.

<p>
<img src="https://i.imgur.com/iL9Te72.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

Configuring help desk topics, this is to help the end user select their tech related issue. images below.

<p>
<img src="https://i.imgur.com/DjKXqkv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

You made it! Thank you for taking the time to follow along!
