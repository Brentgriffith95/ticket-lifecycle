# tick<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket
- HeidiSQL
<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

![Screenshot (123)](https://github.com/Brentgriffith95/ticket-lifecycle/assets/150200843/abd56205-5036-48ea-8f75-b2334666b65d)

While in the VM go to http://localhost/osTicket/ and click Open a New Ticket.

![Screenshot (125) Edit](https://github.com/Brentgriffith95/ticket-lifecycle/assets/150200843/ba02a51f-e1e3-4674-abac-d74335e40163)

Now use either of the two accounts Ben or Karen from the prvious tutorial that we created. Then choose a help topic for simulated scenario that a customer might come accross. In this simple tutorial we will be using a password reset.

![Screenshot (126) Edit](https://github.com/Brentgriffith95/ticket-lifecycle/assets/150200843/e8614e20-8608-4b6a-b073-c9ac977d56a9)

Go back to http://localhost/osTicket/scp/login.php and then click the Agent Panel


![Screenshot (127) Edit](https://github.com/Brentgriffith95/ticket-lifecycle/assets/150200843/e86dfaca-350d-4e5f-b392-aa91f3728865)

Then go the tickets panel and select the ticket we just created. Now assign the ticket to either a user or the admin. Next set SLA plan to SEV-C since it can be done on a weekday and is a low severity ticket. If the severity is greater it will have a higher priority.


![Screenshot (128) Edit](https://github.com/Brentgriffith95/ticket-lifecycle/assets/150200843/e8f28e26-6eb1-418b-b66f-3e7503239a25)

Now we will respond to the ticket and decide if we close it because it has been resolved. 
