<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Example of ticket lifecycle in osTicket](https://www.youtube.com/watch?v=uuxrH9l4ugM) by Shalim Razzak

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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The **Intake** stage begins when a user submits a ticket through the osTicket web portal, email, or agent-created tickets on behalf of users. Users access the osTicket client portal (e.g., http://yourdomain.com/support) and fill out a ticket form, providing details such as their name, email, issue category, and a description of the problem. Upon submission, osTicket automatically generates a unique ticket number and assigns the ticket to the appropriate department based on predefined help topics or routing rules. Agents can view new tickets in the osTicket dashboard under the "Open Tickets" queue. Email notifications are sent to both the user and relevant agents, ensuring visibility of the new ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the **Assignment and Communication** stage, an agent or team lead reviews the ticket in the osTicket dashboard and assigns it to the appropriate agent or team based on expertise or workload. This is done by navigating to the ticket, selecting "Assign To," and choosing an agent or department. Agents communicate with the user through the ticket's internal thread, posting replies that are emailed to the user or viewable in the client portal. Internal notes can be added for agent-only collaboration. osTicket’s SLA (Service Level Agreement) settings may trigger alerts if the ticket remains unassigned or unresolved beyond a set time, ensuring timely action. Users can respond via email or the portal, and all interactions are logged in the ticket history.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
During the **Working the Issue** and **Resolution** stages, the assigned agent investigates the reported issue, using the ticket details and any follow-up communication with the user. The agent may update the ticket status (e.g., "In Progress") and post internal notes or replies to document progress. For example, if the ticket involves a software issue, the agent might replicate the problem, apply a fix, or escalate to a higher-tier team. Once resolved, the agent posts a final reply to the user, detailing the solution, and closes the ticket via the "Close" option in osTicket. If the user responds with further issues, the ticket can be reopened. Closed tickets are archived but remain accessible in the "Closed Tickets" queue for reference or reporting.
</p>
<br />
