<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>
<p>
To create a ticket as an end user, type localhost/osTicket/ into the address bar & select "Open a New Ticket". The user will input their contact info & choose a help topic. After selecting the topic they will have space to provide information about the issue.
<p>
<img src="https://imgur.com/C9EfaWP.png" height="80%" width="80%">
<img src="https://imgur.com/peZb2uU.png" height="80%" width="80%">
<p>
Upon login to the Agent Panel (localhost/osTicket/scp/login.php) you will see the tickets assigned to that Agent. If not, you may have to log back in as an admin and reset the agent's permissions and departments.
</p>
<img src="https://imgur.com/Wvcy1J3.png" height="80%" width="80%">
<p>
<p>
After opening the ticket, the Agent assigned to it has the ability to manage the Status, Priority, Department, Assignment, and SLA level. 
<img src="https://imgur.com/FzqB0Jw.png" height="80%" width="80%">
</p>
<p>
Agents can send messages back to the person who opened the ticket to keep them updated & close the ticket once the issue has been resolved. Once the ticket is resolved it will move from the Agent's Open folder to the Closed folder.
</p>
<img src="https://imgur.com/DeeJRsP.png" height="80%" width="80%">
<img src="https://imgur.com/hIebffh.png" height="80%" width="80%">
<br />

<p>
<img src="https://i.imgur.com/hp1qPsS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/8qgRGDt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If the item is resolved, the agent will respond with news to the user and close the ticket. Even if the ticket is not resolved, the agent will send a progress update.
</p>
<br />
