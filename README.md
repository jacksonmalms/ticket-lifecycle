<p align="center">
<img src="https://www.synaxiom.com/wp-content/uploads/2016/06/osticket.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. If you haven't already completed the installation/setup and configuration, go ahead and go back to my previous tutorial linked below.</p>

- [osTicket: Prerequisites and Installation](https://github.com/jacksonmalms/osticket-prereqs) (The end of this will lead you to the next tutorial, and from that next one, to here.)

Side note: this one is going to be super short, it is really to just get you started so you can do some practice on your own. Oh, and don't forget to delete your resources in Azure or at least turn off the VM so you don't get any extra charges.</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket
- HeidiSQL

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>High Level List of Steps</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Visual Walkthrough</h2>

<p>
<img src="https://i.imgur.com/F9pNEtR.png"/>
</p>
<p>
First, in the VM go to http://localhost/osTicket/ and open a new ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/JRuHkIc.png"/>
</p>
<p>
Now choose either Ken or Karen, a help topic, create whatever summary and description that you'd like, and then create the ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/o92b2CF.png"/>
</p>
<p>
Now go to http://localhost/osTicket/scp/login.php in your VMs browser and go to the Agent Panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/HWxKoFu.png"/>
</p>
<p>
Now set the SLA to SEV-B and assign the ticket to an agent or the admin user.
</p>
<br />

<p>
<img src="https://i.imgur.com/pqUE1tr.png"/>
</p>
<p>
Then respond to the ticket with any response you want and decide if the ticket should remain open or resolved if you implemented a solution and fixed the issue. Then just continue to practice making up/creating tickets and working through them as many times as you want!
  
Congrats, you've made it through all three of my osTicket tutorials/labs! Also, don't forget to clean up your resources in Azure or turn off your VM so you don't incur extra charges.
