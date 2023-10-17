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

- Configure Roles, Departments, and Teams
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>

![2](https://github.com/JCallerx/post-install-config/assets/143349237/bb8b5886-bb18-4c4e-a511-3e3fe50b5e11)


</p>
<p>
In this image, I configured Roles, Departments, and Teams to begin our workflow. After creating these roles I updated Agents and Users to have the corresponding permissions on their profiles. 

</p>
<br />

<p>

![Annotation 2023-09-02 141952](https://github.com/JCallerx/post-install-config/assets/143349237/0141e248-755f-423b-b48e-88d080798118)


</p>
<p>
In this portion, I reviewed and configured the SLA expectation by using the tiers below:

  - SEV-1 (1 hour, 24/7)
  - SEV-2 (4 hours, 24/7)
  - SEV-3 (8 hours, business hours)
</p>
<br />

<p>

![1](https://github.com/JCallerx/post-install-config/assets/143349237/1c72778f-177e-413c-b551-12b620dd0548)

  
</p>
<p>
Finally, I updated the Help topics to ensure we had a baseline to help users with FAQ. These topics are the following: 

  - Business Critical Outage
  - Password Reset
  - Personal Computer Issues

</p>
<br />
