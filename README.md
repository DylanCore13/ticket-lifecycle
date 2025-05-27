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
  User Karen creates a ticket due to her having a problem with an issue of a website/application/service. She'll have to describe whats wrong and label the serverity of the problem.
</p>


<p align="center">
<img src="https://i.imgur.com/G7Ak6uI.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/UdiPc1s.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>



- Sign in to osTicket as an Agent, remember we created jane.doe in the previous tutorial; log in with those credentials
   
  Select the ticket we created with Karen.
  
  

 ![image](https://github.com/user-attachments/assets/48cd3a80-92b9-4e4b-9c4f-ed5e4359710f)



 - The priority here is an EMERGENCY, since mobile online banking down this can lead to losses in revenue for the company or possibly worse. 
 - This was assigned to agent "Jane Doe"
 - SLA Plan: SEV-A !!!
      - Business impacting, major critical incident
 - Department: System Administrators 
      - Sys Admins responsible for mobile banking infrastructure
 - Response text box: Coordinating with Sys Admin Team to bring mobile banking back online.
    - Select Post Reply


<p align="center">
<img src="https://i.imgur.com/Du3kmui.png" height="80%" width="80%" alt="Azure Free Account"/> <img src="https://i.imgur.com/yg9TXep.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>


- On the back end, Jane is working with the Systems Administrative Team to resolve the issue. 


     
- Once the issue is resolved, head back to the ticket and update the end user.
  - Response text box: Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up. 
  - Ticket Status: Resolved
- Select Post Reply
- Since it has been resolved, the ticket should now be on the Closed tab.

<p align="center">
<img src="https://i.imgur.com/et8h651.png" height="80%" width="80%" alt="Azure Free Account"/> <img src="https://i.imgur.com/TUo3T0Q.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>



