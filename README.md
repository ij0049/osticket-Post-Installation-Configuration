<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Setup Microsoft Azure Virtual Machine
- Install the osTicket requirements
- Install osTicket Itself
- Configuration of osTicket
- Explore osTicket as a help desk professional

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/wS3KwSL.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>

In my system, there are two main panels that I work with: the Agent Panel and the Admin Panel.

The Admin Panel is where I manage most of the configuration tasks. For example, when I need to configure roles, I go to Admin Panel -> Agents -> Roles. This is where I can set up different user roles for my team, which helps group permissions appropriately. A role like Supreme Admin would typically have access to everything, while other roles might have more restricted access based on what they need to do.

Next, when it comes to configuring departments, I go to Admin Panel -> Agents -> Departments. This is where I can control which agents see which tickets, based on the department they belong to. For instance, I might configure SysAdmins to only see certain types of tickets related to system administration tasks, while the Help Desk team can manage support-related tickets.

Then, I can also configure teams under Admin Panel -> Agents -> Teams, which lets me pull agents from different departments into one cohesive team. This is especially useful when I have specialized teams, like Online Banking, that need to collaborate on tasks across different functional areas.


</p>
<br />

<p>
<img src="https://i.imgur.com/cmfwN2S.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
If I want to allow anyone to create tickets, I go to the Admin Panel -> Settings -> User Settings. In this section, I can configure whether or not unregistered users are allowed to create tickets. If I uncheck the option that says "unregistered users can create tickets," I make it so that only registered users can submit tickets. This means that I require users to be logged in before they can create a ticket.

When it comes to configuring agents , I go to Admin Panel -> Agents -> Add New. This is where I add new agents who will be responsible for handling tickets. For example, I might add Jane to the SysAdmins department since she handles system administration tasks, and John to the Support department, as he is in charge of support-related tickets.

Finally, for configuring users , I switch to the Agent Panel -> Users -> Add New section. Here, I add users like Karen and Ken, who will be submitting tickets for assistance. These are the customers who will interact with the agents to resolve any issues they face.


</p>
<br />

<p>
<img src="https://i.imgur.com/BtsZK8I.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
When I need to configure agents, I go to Admin Panel -> Agents -> Add New. This is where I can add new agents to my system. For example, I would add Jane and assign her to the SysAdmins department because she handles all system administration tasks. Similarly, I would add John and place him in the Support department since he focuses on providing support-related assistance.

Next, I move to configure users, which I do in the Agent Panel -> Users -> Add New section. This is where I add users who will create tickets, like Karen and Ken, both of whom may need assistance with various issues.

To manage the SLA (Service Level Agreement), I go to Admin Panel -> Manage -> SLA. Here, I can define how quickly tickets need to be addressed based on severity. For example, for Sev-A, which is the most urgent level, I set a grace period of 1 hour and a 24/7 schedule to ensure tickets are handled around the clock. For Sev-B, I extend the grace period to 4 hours, with a 24/7 schedule as well. Finally, for Sev-C, which is less urgent, I set the grace period to 8 hours but limit the schedule to business hours, since it’s not as critical.

Lastly, I configure Help Topics to guide users when they create tickets. I do this in Admin Panel -> Manage -> Help Topics. I set up topics like Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other. These topics help users categorize their issues more easily when they submit tickets, making it easier for the agents to address the right issues faster.
</p>
<br />
