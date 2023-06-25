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
<img src="https://i.imgur.com/3bwWRCm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To simulate a customer submitting a ticket to osTicket, go over to the Agent Panel as the user admin account, select Tickets and then select New Ticket. From there, an option to search for a user will appear, in which we can select the one we created in the previous part. In this case, our user is Ken Ken. After selecting a user, you can select one of the Help Topics we created before, such as Business Critical Outage. Finally, we can enter an Issue Summary, along with a description of the issue, such as the entire mobile banking system is down. Scroll down and select "Open" to open the ticket. 
</p>
<br />

<p>
<img src="https://i.imgur.com/a7n3rKm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure assingment of the newly open ticket and communicate back to the user/customer, go to Agent Panel and select Tickets. From here you can select the new ticket and assign this ticket to an agent, such as John Doe. From the picture above, you can see that along with assigning the ticket, you can select the priority, what department this ticket should go to, and SLA Plan. Since this is a Business Critical issue, the ticket's priority is set to emergency and the SLA Plan is set to SLA-A, since that is set to a 1 hour grace period along with a 24/7 time frame. 
</p>
<br />

<p>
<img src="https://i.imgur.com/MhE9cte.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Since we just assigned this ticket to John Doe, sign out of the user admin account, and sign in to John Doe's account. Once logged in, select Tickets and our created ticket should appear. Clicking on this will show a screen like the picture above, in which we can now send a message back to our user Ken to communicate that we received his ticket and are working on the issue.
</p>
<br />

<p>
<img src="https://i.imgur.com/onaY4AR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/5FiZqLE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Assuming that John and his department fixed the issue, the first picture above shows an example of a resolution response, communicating to the user that the issue has been resolved. In addition, selecting ticket status and changing it to Resolved will close the ticket once Post Reply is selected. Once this is posted, you can go back to Tickets to see that the ticket has been closed. 
</p>
<br />
