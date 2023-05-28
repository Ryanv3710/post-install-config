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
- Configure Departmenets
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics


<h2>Configuring Roles</h2>

<p>
<img src="https://i.imgur.com/7mUGCGy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
This & the proceeding steps are alot of rinse and repeat as you'll see. The hardest part is creating the ticketing system but after that everything is pretty simple.
<ol>
  <li>Admin Panel -> Agents -> Roles</li>
    <li>Supreme Admin</li>
   
  </ol>
</p>
<br />

<p>
<img src="https://i.imgur.com/Vqi8JRf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Permissions where you see tickets,tasks,knowledgable you can check everything in the check boxes and then proceed to create the role.
</p>
<br />

<h2>Configuring Departments</h2>
<p>
<img src="https://i.imgur.com/JNUn7ml.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<ol>
  <li>Admin Panel -> Agents -> Departments</li>
    <li>System Administrators</li>
</ol>
</p>
<br />

<h2>Configuring Teams</h2>

<p>
<img src="https://i.imgur.com/7FX9d8W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<ol>
  <li>Admin Panel -> Agents -> Teams -> Create both support teams (1,2)</li>
    <li>Level I Support</li>
  <li>Level II Support</li>
   
  </ol>
</p>
<br />


<h2>Allowing anyone to create tickets</h2>

<p>
<img src="https://i.imgur.com/XEsOri2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<ol>
  <li>Admin Panel -> Settings -> User Settings</li>
    <li>Registration Required: require registration and login to create tickets</li>

   
  </ol>
</p>
<br />


<h2>configure Agents (workers)</h2>

<p>
<img src="https://i.imgur.com/wrYjGyS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  The process is the exact same when creating John. The workers can now work on topics and have a thread that'll show what changes they have made and are documented and be able to close tickets once accomplished.
<ol>
  <li>Admin Panel -> Agents -> Add New</li>
    <li>Jane</li>
    <li>John</li>

   
  </ol>
</p>
<br />

<p>
<img src="https://i.imgur.com/ISWj2Hx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  When creating the password ensure both boxes are NOT checked.

</p>
<br />



<h2>configure Users (customers)</h2>

<p>
<img src="https://i.imgur.com/Vf2KbvN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  The users can be able to review the ticket status to see what has been done or if they need to communicate with the workers and of course create tickets. Like I mentioned in the beginning alot of this is rinse and repeat, the same process will be applied to create Ken as shown in this screenshot. 
<ol>
  <li>Agent Panel -> Agents -> Add New</li>
    <li>Karen</li>
    <li>Ken</li>

   
  </ol>
</p>
<br />

<h2>Configuring SLA</h2>

<p>
<img src="https://i.imgur.com/rEicNNy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Rinse and repeat with creating Sev-B and Sev-C, only thing your adjusting is the grace period and scheudle. This is going to be crucial for help desk so they know the severity of a problem and have guidelines based on the SLA. 
<ol>
  <li> Admin Panel -> Manage -> SLA </li>
    <li>Sev-A (1 hour, 24/7)</li>
    <li>Sev-B (4 hours, 24/7)</li>
    <li>Sev-C (8 hours, business hours)</li>

   
  </ol>
</p>
<br />


<h2>Configuring Help Topics</h2>

<p>
<img src="https://i.imgur.com/J1NG7up.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is where depending on the problem or issue will be filtered based on the help topics that can be looked back on. Same process, rinse and repeat creating the following help topics based on the screenshot. 
<ol>
  <li>Admin Panel -> Manage -> Help Topics</li>
    <li>Business Critical Outage</li>
    <li>Personal Computer Issues</li>
  <li>Equipment Request</li>
  <li>Password Reset</li>

   
  </ol>
</p>
<br />

