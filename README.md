<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img width="629" alt="Screen Shot 2024-07-05 at 1 34 59 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/d2a088e4-6931-4aff-b834-1810a74b8e30">


</p>
<p>
Created New role, "Supreme Admin" (Admin Panel -> Agents -> Roles -> Add New Role)

</p>
<br />

<p>
<img width="957" alt="Screen Shot 2024-07-05 at 1 37 04 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/1f46e8de-da56-44fc-8fb7-84dfddb4411d">

</p>
<p>
Created  a new Department, "System Administrators" (Admin Panel -> Agents -> Departments--> Add New Department)
</p>
<br />

<p>
<img width="958" alt="Screen Shot 2024-07-05 at 1 56 07 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/40d8109e-8679-46b0-8aac-8b2eda3b2338">


</p>
<p>
Created two new teams, "Level 1 support" and "Level 2 Support" (Admin Panel -> Agents -> Teams -> Add New Team)
</p>
<br />

<img width="949" alt="Screen Shot 2024-07-05 at 1 52 24 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/fe46b15d-e61b-419e-a447-e01f59478d3f">
</p>
<p>
Made sure that anyone can create tickets in user settings. Unchecked the box "Require Registration and login to create tickets"
</p>
<br />
</p>
<img width="966" alt="Screen Shot 2024-07-05 at 2 02 08 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/76106f94-adb2-43b0-8d81-18edfdc63ff3">
</p>
<br />
<img width="973" alt="Screen Shot 2024-07-05 at 1 36 13 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/71e951ee-7fce-4d57-912c-60c714668fea">

</p>
<p>
Created 2 new agents: "Jane Miller" and "John Martin". Agents are the internal employees who will be working to solve the tickets. (Admin Panel -> Agents -> Add New Agent)

</p>
<br />

<img width="665" alt="Screen Shot 2024-07-05 at 1 36 42 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/6a542f9f-4bdc-4aa8-9cc7-6075ec85be9d">
</p>
<br />
<img width="967" alt="Screen Shot 2024-07-05 at 1 36 33 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/80e8e475-3f03-4a8f-bef4-4a16c4663d77">
</p>
<p>
Created 2 new users (Customers): "Ken Wheeler" and "Karen Hill". (Agent Panel -> Users -> Add New User)
</p>
<br />

<img width="972" alt="Screen Shot 2024-07-05 at 1 35 17 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/db6125a5-d487-4a12-a7e9-f9cda942c6ab">

</p>
<p>
Configured SLA so that there is 3 different plans. Sev-A, Sev-B, and Sev-C. (Admin Panel -> Manage -> SLA -> Add new SLA Plan)

</p>
<br />

<img width="977" alt="Screen Shot 2024-07-05 at 1 36 52 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/f80a6baf-7189-405a-a47b-bb9ca6884ff2">
</p>
<br />
<img width="965" alt="Screen Shot 2024-07-05 at 2 20 40 PM" src="https://github.com/Bpeduru/post-install-config/assets/171273980/13b8b33e-612e-425d-aa58-fec385f152f1">



</p>
<p>
Added 4 new help topics that the customers can use to put in their tickets: Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset (Admin Panel -> Manage -> Help Topics -> Add New Help Topic)







