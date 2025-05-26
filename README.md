# ticket-lifecycle
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



<br />


<p>
  User Ken creates a ticket due to him having a problem with an issue of a website/application/service. He'll have to describe whats wrong and label the serverity of the problem.
</p>


<p align="center">
<img src="https://i.imgur.com/G7Ak6uI.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/UdiPc1s.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 2: Assignment and Communication</h3>

- Sign in to osTicket as an Agent
  - We created jane.doe in the previous tutorial; log in with those credentials. 
  - Select the ticket we created in Step 1.
  
  
<p align="center">
<img src="https://i.imgur.com/sDgzS36.png" height="80%" width="80%" alt="Azure Free Account"/> 
</p>


 - Priority: Emergency. 
      - Mobile online banking down can lead to losses in revenue for the company. 
 - Assigned to: Jane Doe
 - SLA Plan: SEV-A 
      - Business impacting, critical incident
 - Department: System Administrators 
      - Sys Admins responsible for mobile banking infrastructure
 - Response text box: Coordinating with Sys Admin Team to bring mobile banking back online.
    - Select Post Reply


<p align="center">
<img src="https://i.imgur.com/Du3kmui.png" height="80%" width="80%" alt="Azure Free Account"/> <img src="https://i.imgur.com/yg9TXep.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>

<h3>Stage 3: Working the Issue</h3>

- On the back end, Jane is working with the Systems Administrative Team to resolve the issue. 


<h3>Stage 4: Resolution</h3>
     
- Once the issue is resolved, head back to the ticket and update the end user.
  - Response text box: Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up. 
  - Ticket Status: Resolved
- Select Post Reply
- Since it has been resolved, the ticket should now be on the Closed tab.

<p align="center">
<img src="https://i.imgur.com/et8h651.png" height="80%" width="80%" alt="Azure Free Account"/> <img src="https://i.imgur.com/TUo3T0Q.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>


🎉Congratulations! You have created and resolved your first ticket! You have completed the third and final part of this three-part osTicket Install/Configuration/Ticket-Creation tutorial series.🎉
  



<p>
  Agent John Doe logs in and sees this is Sev-A emergency ticket and has to reassign ticket to a System Administrator.
  He also makes sure to leave a proper message:
</p>

![image](https://github.com/user-attachments/assets/a4edfbc9-3a87-4de1-8528-cdb814110e5c)

<br />
<p>
  System Administrator agent Jane Doe logs in:
</p>
<p>
  <img src="https://i.imgur.com/i61WQKi.jpg" height="75%" width="100%" alt="Sys admin agent login"/>
</p>
<p>
  Agent Jane works the issue and communicates back to agent John.
</p>
<p>
  She also makes sure to switch the status of the issue from open to resolved:
</p>
<p>
  <img src="https://i.imgur.com/DYPJufr.png" height="75%" width="100%" alt="Working the issue"/>
</p>
<br />
<br />

<br />
<p>
  Support agent John sees in his portal that System Administrator agent Jane has left him a message and that the ticket is now closed:>
</p>
<p>
  <img src="https://i.imgur.com/kRpUysm.png" height="75%" width="100%" alt="Working the issue"/>
</p>
<br />
<br />
<p>
  This was a very simplistic scenario of the creation of a ticket by a user, how the ticket is assigned and displays the communication of a ticket between agents; subsequently resulting in a resolution.
</p>
<p>
  There are additional scenarios that can also happen while a ticket is being assessed. A ticket can either be reassigned to a different department, escalated in severeity level, or needs to be both reassigned to a more qualified agent/department to handle the issue, depending on business impacts.
</p>
<p>
  I hope this tutorial helps you understand and have a better general overview of a life-cycle of a ticket. Help desk agents can expect to regularly deal with anywere between 10 to 100 tickets during their day depeneding on the company size.
</p>
