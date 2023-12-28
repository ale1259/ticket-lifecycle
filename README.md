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
   


 - First let's get into the End-user portal to create some tickets: http://localhost/osTicket/
<img src="https://i.imgur.com/Jj3C8LM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

-  To introduce a new ticket in our ticketying system we click on Open New Ticket, then in the new window we introduce the Email Address and Full Name of the user is submiting the ticket with the Help Topic of the ticket in this case we're going to use "Business Critical Outage"
  <img src="https://i.imgur.com/XKVbYXc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
- And a Issue Summary will be dislpay to write down the problem. In this example we choose a problem with the mobile banking online system 
<img src="https://i.imgur.com/KEWJZf5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- We"ll do the same with another ticket but Personal Computer Issues, for Issue Summary we put "Laptops are slow" and for the plain text "Laptops of two of our associates are slow when using the company resources"
 <img src="https://i.imgur.com/YtKqyZC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
- Next let's login back in our ticketying system as an Agent this time Jane Doe and as you can see we are able to see the tickets we just created

  <img src="https://i.imgur.com/JMBznMv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- Now we set the priority, what Department and Agent is assigned to and the SLA Plan 
 <img src="https://i.imgur.com/90falhH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- In this case we set the priority as an "Emergency", the assigned it to "Jane Doe" and to the "Systems Administrators" Department with the SLA Plan "SEV-A(1 hour, 24/7)"
 <img src="https://i.imgur.com/3OFTqbE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
- As we can see the prioriy and whothe ticket is assigned to change
 <img src="https://i.imgur.com/qxwT0pe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Go and do the same with the ticket that says "Laptops are slow" but this time assigned it to "John Doe" with the priority "High", the "Support Department" and the SLA Plan "SEV-B(4 hours, 24/7)". You can write down before posting to point out any information you want to say. 
  
 <img src="https://i.imgur.com/ZeOLW9Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 - Let's solve a ticket that was assigned to "John Doe". We log out and log in as John this time with the username of course john in this case and as we can see he can see only the ticket was assigned to him.
  <img src="https://i.imgur.com/lB89mYt.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 - Click on the ticket and see what the problem is. After the issue has been resolved you can post something like how you figured it out so you can document for future tickets. To close the ticket simply click on ticket status check resolved and Post Reply. And that's it.
  <img src="https://i.imgur.com/TQsF3YU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 


 


