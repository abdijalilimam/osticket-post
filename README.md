
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation Setup </h1>
This shows outlines the post-install configuration of the osTicket.<br />

<h1>Enviroment</h1>
<p>
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (RDP)
</p>

<h1>Operating System</h1>
<p>
- Windows 10 (21H2)
</p>
<h1>Post Instillation and Configuration Steps </h1>
<p> - Set Departments and Roles </p>
<p> - Set Teams and allow who can create tickets </p>
<p> - Set permissions for agents/workers and users/customers</p>
<p> - Establish  SLA </p>
<p> - Configure Help Topics </p>


<p>
  Welcome! In our post instillation and Configuration we will begin by creating Roles and giving specific Agents access to everything. Depending on the organization or business needs these roles will be slightly different. To do so go to Admin panel --> Agents --> Roles. We will create a Supreme Admin. Click on "Add new role" then enter the name of the new role. 
</p>

<p>
<img width="960" alt="image" src="https://github.com/abdijalilimam/osticket-post/assets/137457871/4acda6c9-8e69-4eb5-a341-3f4dd614b2e8">
</p>

<br />

<p>
  Next, we will create a department called System Administrator to do so locate "departments" in the agent tab. You can change and do so much under the department tab you like setting emails and SLAs and much more. Certain agents are assigned to different departments depending on the organizations and the different roles as helpdesk personnel
</p>

<p>
<img width="858" alt="image" src="https://github.com/abdijalilimam/osticket-post/assets/137457871/9ca5deb0-6f56-4303-b6f6-8c26227a6ac2">\
</p>

<p>
Next, in order to have different skilled individuals to work on a specific problem we will need to create teams and this will allow for different skilled personnel to work together and get things done. To create teams go to "agents" --> teams </p>
<br />

<p>
<img width="991" alt="image" src="https://github.com/abdijalilimam/osticket-post/assets/137457871/e44ffc6e-26c0-4fc1-97b0-a05b0262428c">

</p>
<p>
In order to allow all individuals to create tickets we will need to enable it in the user setting. To do so under the admin panel click settings then click on user settings.
</p>

<p>
<img width="647" alt="image" src="https://github.com/abdijalilimam/osticket-post/assets/137457871/561c9222-e6db-4179-b7cf-0e7067369c13">
</p>

<p>
Next, we will create Agents which are the employees of the helpdesk depending on the business needs they have different roles and permissions and are able to have access to one or multiple departments. To create agents go to the admin panel and the the agents you can "add agents"
</p>

<p>
<img width="794" alt="image" src="https://github.com/abdijalilimam/osticket-post/assets/137457871/c1480b4f-f82d-4385-806c-04bd160b78b9">
</p>

<p>
  These tickets that are created and being worked on need to have a time limit depending on the priority of the ticket and the business needs because it is not logical nor reasonable to create tickets and not able to be worked and completed accurately and in a timely manner. To set some guidelines for timely management we will need to create SLAs(Service Level Agreements) and this again depends on the organizational needs. To create SLA go to admin panel --> Manage ---> SLA Plans. In this example we set Severity A or "SEV-A" to 24/7 and a hour period.
</p>

<p> <img width="676" alt="image" src="https://github.com/abdijalilimam/osticket-post/assets/137457871/854c1478-52cf-4116-a16b-afa288f5f5f9">
</p>

<p>
Lastly, we will configure and create Help topics, creating topics such as Business Critical Outage, Equipment Request, Personal Computer Issues, Password Reset, and much more depending on needs.
</p>

<p> <img width="703" alt="image" src="https://github.com/abdijalilimam/osticket-post/assets/137457871/4cb0f8de-39b8-4196-9da9-60163f9630db">
</p>

<br />
