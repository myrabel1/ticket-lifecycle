# ticket-lifecycle<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img width="1240" height="475" alt="image" src="https://github.com/user-attachments/assets/bb7a82d1-d80e-47cd-b21b-51563a492fc7" />

</p>
<p>
As the agent "Myra", this ticket basically states that osTicket has just been installed. What's useful to note on this subsequent tickets is the time it was created. This will become useful when numerous tickets are received of similar levels of priority. If all tickets are 'normal' in priority, observing the time limits guesswork which tickets should be done first. Otherwise, severity levels take priority.
<br />

<p>
<img width="956" height="886" alt="image" src="https://github.com/user-attachments/assets/227fef0d-136b-4829-9085-fd35607d9f3d" />

</p>
<p>
This tickt shows that an end user has created a ticket stating the 'online system is down'. Initially, an employee (agent / Johnnie), received this ticket and because he only had "read-only" access, he was only able to write an internal office comment stating "Johnnie was here". When the admin Susie logged in, she was able to elevate Johnnie's permissions and he was then able to make appropriate changes to the ticket. Change Priority from normal to emergency, SLA from default to Sev-A, Help Topic from general inquiry to business critical. Finally, he was able to escalate this ticket to Susie Smith in SysAdmins (administrator) who was able to investigate the cause of and resolve this ticket in a timely manner per the SLA requirements.
</p>
<br />

<p>
<img width="836" height="747" alt="image" src="https://github.com/user-attachments/assets/861d75eb-acb1-42a0-9686-07b079deabb7" />

</p>
<p>
osTickets are widely used as a way to submit problems. End users (customers) can submit them for a variety of reasons and agents are the ones to manage and resolve the tickets. Agents can submit tickets on behalf of endusers. This is a helpful way to track tickets and to keep endusers updated on the progress of their issue. osTickets are user friendly with tabs that help monitor the lifecycle of a ticket until it's been resolved.
</p>
<br />
