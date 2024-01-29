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

- Item 1 Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin

Admin Panel

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/4f3e5347-727c-4cd7-8db3-596b37d9293b) 

Agents

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/3dceebda-511a-4979-aa67-abd13efe11f5)

Roles Supreme Admin

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/2aa8dbbe-a651-46b6-813e-6c3e3e0bfa64)
![image](https://github.com/Ryanj213/post-install-config/assets/157759490/6c3b341e-9988-4bf8-9920-bd3dd9bfac30)![image](https://github.com/Ryanj213/post-install-config/assets/157759490/dda8aff7-c16f-4907-9883-31225738bbef)





- Item 2 Configure Departments
Admin Panel -> Agents -> Departments
System Administrators

Departments

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/e92ef74b-dc18-4c43-806a-27ac88e43b89)

Add New Department

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/ea570262-801a-4c24-b6e5-070e0b60beb1)




- Item 3 Configure Teams
Admin Panel -> Agents -> Teams

Add Teams

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/151385bb-f066-4dc3-af3b-b45475129f24)

Choose Support Level I, II, III

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/99eb4dc7-2572-4bf0-86b6-59a1aaa790c0)

Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/6e4c3585-5f1c-4e05-a029-c639050cbb36)


- Item 4 Configure Agents (workers)
Admin Panel -> Agents -> Add New

Jane Doe

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/b1f6c100-f238-406f-8034-3a12e2088879)

Create Agent

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/18318f57-44f4-4fc0-b583-906f2157e689)

Assign Access Settings

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/b7fa60ce-bf0d-4473-8089-b64e34524d39)

Repeat Previous Steps To Add New Agents

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/74520e29-da41-4b69-8223-8e369cf06a14)


- Item 5 Configure Users (customers)
Agent Panel -> Users -> Add New

Create New Users in Agent Panel

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/835ec730-5808-4852-997c-f60c69aaeb1b)

Karen

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/480d566e-dfa6-4d66-89c7-2b2905b33ecf)

Create New User

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/bc756132-1b93-48b4-a242-88a5e84cc654)

Repeat Above Steps For Additional Users

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/b9c9f3d5-a69b-4564-9902-3a6044afde26)

- Item 6 Configure SLA
Admin Panel -> Manage -> SLA

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/97d241cd-a118-4772-a709-55daa576a7b0)

Sev-A (1 hour, 24/7)

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/ea27a05b-305b-41ba-bccc-6a37552c63a9)

Sev-B (4 hours, 24/7)

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/c5e2b0a2-02f9-4e11-9e41-a3507712cc26)

Sev-C (8 hours, business hours) 

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/49f0f4a4-a29e-4d8f-b57a-6c3e079ea9e9)


Configure Help Topics Admin Panel -> Manage -> Help Topics Business Critical Outage Personal Computer Issues Equipment Request Password Reset

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/79870967-6c96-49da-a0f1-c0ac9b4a43b2)

![image](https://github.com/Ryanj213/post-install-config/assets/157759490/6da70521-1159-4684-aa1e-b5b61bcbed50)













