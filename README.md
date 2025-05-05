<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube/ClipChamp: How to create, work, and resolves tickets within osTicket Part1](https://youtu.be/quaTA4miodY?si=Q5tutyDnG6ZbRjpb)
- ### [YouTube/ClipChamp: How to create, work, and resolves tickets within osTicket Part2](https://youtu.be/ZmIyx3G1ufA?si=kPHdN2msppaDN8QR)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket System

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- End-User Intake
- Help Desk Agent Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
  
![Image](https://github.com/user-attachments/assets/c54fe6c9-2440-4fba-8822-1b83b9381a94)

</p>
<p>
1. Login and Overview:
  
Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php

End Users osTicket URL: http://localhost/osTicket
  
2. Admin Actions:
Change the SysAdmins Department:
Convert the SysAdmins department to a Top-Level Department.
Delete the Maintenance Department:
Permanently delete (not archive) the Maintenance Department.
  
3. End-User Actions:
Create a Ticket (End-User):
Issue: "Entire mobile/online banking system is down."
  
4. Help Desk Agent (john) Actions:
Observe Ticket Properties: After the ticket is created by the end user, as john (Help Desk Agent), you will observe the following ticket properties:
Priority
Department
SLA (Service Level Agreement)
Assigned To
Set Ticket Properties:
Priority: Sev-A (1 hour, 24/7)
Department: Online Banking Department
  
5. Attempt to Re-Observe Ticket:
After setting the properties, try to observe or modify the ticket again as john. Check if you are able to view or change the ticket after altering its properties.
  
6. Resolve Ticket as "jane":
Work on the ticket and resolve it to completion as jane.
  
This lab involves creating tickets, modifying their properties as a help desk agent, and resolving the issues by changing ticket statuses, priorities, and departments. It also includes administering certain backend tasks like adjusting department settings and deleting departments in the system.
</p>
<br />

<p>
  
![Image](https://github.com/user-attachments/assets/1aeae9bd-858c-4b9f-b4cf-0fa7182803da)

</p>
<p>
Ticket 2: Accounting Department Needs Adobe Upgrade

End-user Action: Reported that Adobe software in the accounting department is broken and needs an upgrade.

Help Desk Agent (John) Action: Observed the ticket's properties, including priority (Sev-B), department (Support), and SLA (4 hours, 24/7).

Ticket Update: John worked on the ticket, performing the necessary upgrade to Adobe software.

Resolution: The issue was resolved successfully by John.

<p>
  
![Image](https://github.com/user-attachments/assets/cd3febaa-efa2-43bd-948b-f48e4dbd4952)

</p>

Ticket 3: CFO’s Laptop Will No Longer Turn On

End-user Action: Reported that the CFO's laptop won't turn on.

Help Desk Agent (John) Action: Observed the ticket's properties, including priority (Sev-B), department (Support), and SLA (4 hours, 24/7).

Ticket Update: John worked on the ticket, troubleshooting and resolving the issue with the laptop.

Resolution: The issue was successfully fixed by John.

Both tickets were resolved by John within the defined SLA.

</p>
<br />

<p>
