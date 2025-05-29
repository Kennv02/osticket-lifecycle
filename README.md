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
<img src="https://github.com/user-attachments/assets/17ffadc0-571e-4a38-823a-6272a51969af" />
</p>
<p>
In the final segment of the osticket system process, the final portion of the procedure will focus on Ticket Lifecycle examples from creating a ticket, assigning severity of ticket, priority, and assigned agent to working the issue and resolving the ticket. 

- To begin creating a ticket as a user, go to the following - http://localhost/osTicket and begin creating the ticket as it will be submitted to the osticket system for an agent to assist with the ticket.
- Follow the prompt and fill it out before attempting to create the ticket. I used karen as the user and used fake personal information
- In the help topic section: There is a dropdown list of different help topics to choose from and assessing which topic is well suited for the issue on hand can give agents/admin a brief understanding of what the issue may be before resolving the ticket
- Create the ticket once information is entered.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/62b8218f-b8f5-4001-939e-fd89371eb0ab" />
</p>
<p>
This section provides an overview of the ticket from the agent/admin(s) perspective. As noted in the top sction of the ticket, the ticket is "open" which indicates it is unresolved and awaiting attention. See explanation of the headers below: 

  - Priority: Indicates the urgency of the ticket
  - Department: What department the ticket is assigned to.
  - Date: When the ticket was submitted.
  - Source: How the ticket was submitted by the user (Please note, users can submit a ticket through various ways. Some of the most common are: Web, Mobile, In person)
  - Assigned to: The agent/admin assigned to the ticket. It is currently unassigned and will be assigned to an agent.
  - SLA(Service Level Agreement): The severity of the ticket to which how fast the ticket is addressed depends in the SLA level.
  - Due date: When the ticket is expected to be resolved.

The ticket thread will give you an overview of the ticket history along with messages from user and agents. Essentially, this ticket showcases how the incident is logged and displays how impactful the incident is. 

The bottom thread displays how responses are coordinated across the staff. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/a2f49176-6532-45de-928b-dea4a5ebdf97" />
</p>
<p>
In addition to the message thread, I had agent "John Doe" assigned to the ticket to resolve the incident. John states the online banking portal issue has a wide impact on employees and customers. Because the incident has a wide impact, the agent John asseses the ticket and changes the SLA to Sev-A (1 hour grace period) 

- Let's reiterate SLA Plans.
- Sev-A is high priority (1 hour grace period)
- Sev-B is standard priorty (4 hours grace period) The ticket could alsd be subject to Sev-B if only a select number of employees had issues accessing the banking portal.
- Sev-C is low priority (24 hour grace period) The ticket could be considered low priority if only one individual was affected.

We can also see in the example shown that John updated the help topic to properly categorize the issue.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/50038bf6-5f05-4382-a138-8db14a9ca8a9"/>

</p>
<p>
<img src="https://github.com/user-attachments/assets/a883d346-3f0c-4da1-8db0-7dad3f892dcf" />
</p>

<p>
The images above displays how to change the following and by clicking on the cursor:

- SLA
- Help Topics
- Priority

This can also be done to other tabs in the Top Box of the osticket system.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/c64f6e45-2a3e-4c3a-a14c-c4e1da51fb99" />

In the message thread, John elaborates and briefly provides an overview of the ticket, and he escalates it to the Online Banking Department.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/00b6d0f1-473a-4bcc-a755-73ad66d1a042"

To escalate the ticket and assign it to the proper department and agent, go to:

- Assigned To -> Teams -> Assignee

The ticket is now assigned to the Online Banking team and Jane Doe will be the agent working on the ticket.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/62ceaea1-88dd-4ac8-863b-571a682d4674"

Considering Jane is the agent assigned to the ticket, Jane will have to log in to the admin portal to work on the ticket. Log out of the admin account from the current admin and log back in using Jane or your specified agents credentials.
</p>

<p> 
<img src="https://github.com/user-attachments/assets/f5fcd8bd-a462-4eac-8beb-8f964db618bb"

Logged in as Jane, we can assume that Jane successfully worked on the ticket andd posted a response detailing the root of the issue. It weas noted that the root cause of the issue was the recent update. The vendor was notified and are pending a fix. 
The response will get posted and Jane may close the ticket and changed the status from Open to Resolved. 
</p>

<p></p>
See below: 
<img src="https://github.com/user-attachments/assets/d216da43-4d71-4a7b-890e-c3228b36c65d"
</p>

</p>
