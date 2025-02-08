<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket (Part 2 - Configuration)</h1>
I will be going through certain parts of osTicket to demonstrate its features.

<h2>Tools Used</h2>
 
 - Microsoft Azure
 - Remote Desktop
 - osTicket
 - Gmail

<h2>Operating Systems Used</h2>

 - Windows 10 Pro (22H2)

<h2>The Platforms Of osTicket</h2>

- OsTicket comes with the front-end and the back-end. The front-end is where users can create help tickets, while the back end is where all the configuration and work get done.



THE BACKEND

<img width="1703" alt="Screenshot 2025-02-03 at 22 30 08" src="https://github.com/user-attachments/assets/6e76c4b0-3e03-479e-9ecb-2d8be7c6b5d7" />


THE FRONTEND

<img width="904" alt="Screenshot 2025-02-03 at 22 33 05" src="https://github.com/user-attachments/assets/eb14d70b-36f6-442d-a5d3-c30cfaefaf15" />

<h2>THE AGENT & ADMIN PANELS</h2>
 
- Within the the backend of osTicket there is the Agent Panel and The Admin Panel.
   - The Admin panel is where everything gets set up from the creation and configuration of users, teams, departments etc.
   - The Agent panel is where tickets are viewed and attended to.
  
ADMIN PANEL
<img width="1703" alt="Screenshot 2025-02-03 at 22 30 08" src="https://github.com/user-attachments/assets/d3addab2-e05f-4f07-bd0b-ac7233ea5544" />

AGENT PANEL
<img width="1414" alt="Screenshot 2025-02-03 at 22 29 58" src="https://github.com/user-attachments/assets/8953758a-ea56-437e-b734-c222f19979ba" />

- Whenever a member of an organisation has a problem that needs to be sorted (e.g: password reset) they can put it through on their end and it will then appear within the agent panel
<img width="842" alt="Screenshot 2025-02-03 at 22 35 02" src="https://github.com/user-attachments/assets/3cc0ed18-a8a9-4e3e-91af-9267e0c3976d" />

<img width="960" alt="Screenshot 2025-02-03 at 22 35 30" src="https://github.com/user-attachments/assets/44ffefc2-6a7a-4ab7-9691-1ce6a89d155a" />

<h2>Assigning Tickets To Agents/Team Members</h2>

- Whenever a ticket has been created and appears in the agent panel you can choose who the ticket gets assigned to and that person will be in charge of resolving the issue.
<img width="1091" alt="Screenshot 2025-02-03 at 22 37 00" src="https://github.com/user-attachments/assets/c9e9f52e-97f7-47f4-9986-2571c5e51fe4" />

- You can create users to work on tickets in the admin panel.
<img width="1354" alt="Screenshot 2025-02-03 at 22 43 50" src="https://github.com/user-attachments/assets/7b81f48d-ace1-4b86-92b5-e7b79a3181a8" />

<img width="660" alt="Screenshot 2025-02-03 at 22 45 40" src="https://github.com/user-attachments/assets/c9ead4b0-3167-477a-8f18-d9dc7a3e77cd" />

<h2>Resolving Tickets</h2>

- After someone has been assigned a ticket and they have worked the ticket to completion, they have to close the ticket on their end so that everyone else can be made aware that the issue has been resolved.
<img width="1148" alt="Screenshot 2025-02-03 at 22 47 34" src="https://github.com/user-attachments/assets/2d712692-5225-475f-bcff-589ce3f5cdec" />

<img width="533" alt="Screenshot 2025-02-03 at 22 48 20" src="https://github.com/user-attachments/assets/5850120b-0cbb-4925-8bc3-b8d521ba083d" />

<img width="646" alt="Screenshot 2025-02-03 at 22 49 19" src="https://github.com/user-attachments/assets/2a4c6512-93c1-4995-9ef0-7a41db7d4ad7" />

- When the ticket has been marked as resolved it will no longer be visible on the agent panel unless you go to the closed ticket section within the agent panel.
<img width="969" alt="Screenshot 2025-02-03 at 22 49 35" src="https://github.com/user-attachments/assets/b6a9c16c-eae0-4749-a7cf-ec65413cb745" />

<h2>CAPTCHA</h2>

- Within the admin panel you can add a captcha setting to the front-end so that whenever a user creates a ticket you can be sure that the person is a verified human.
<img width="1003" alt="Screenshot 2025-02-03 at 22 58 08" src="https://github.com/user-attachments/assets/de6c4795-2218-42be-b1bf-5cf63e2f8103" />

<img width="828" alt="Screenshot 2025-02-03 at 23 02 57" src="https://github.com/user-attachments/assets/34ffea4f-d1a4-4534-b051-ade657d93f76" />

<h2>Help Topics</h2>

- User complaints/issues can fall under several categories and as a result, osTicket allows you to create custom help topics making it easier for users to convey the problems they have.
<img width="958" alt="Screenshot 2025-02-03 at 23 03 06" src="https://github.com/user-attachments/assets/29fb2a02-8b48-4ef2-a1ca-3ae9389cd129" />

<img width="958" alt="Screenshot 2025-02-03 at 23 15 39" src="https://github.com/user-attachments/assets/78008639-92e4-4faf-902d-eac9b7dbcca8" />

- You can even assign these topics to specific departments.

<img width="960" alt="Screenshot 2025-02-03 at 23 15 45" src="https://github.com/user-attachments/assets/79d8fb31-7b3f-4438-9873-efee16de95a8" />

- You can create departments in the admin panel
<img width="966" alt="Screenshot 2025-02-03 at 23 04 54" src="https://github.com/user-attachments/assets/f9f40f62-d96a-4c40-bbf1-f9600fe9a085" />

<h2>Filters</h2>

- From the admin panel you can set filters which restrict users from creating tickets if certain criteria are met or vice versa.
<img width="958" alt="Screenshot 2025-02-03 at 23 41 19" src="https://github.com/user-attachments/assets/c6e4c838-6109-42f1-b530-ed134842469d" />

<img width="958" alt="Screenshot 2025-02-03 at 23 41 05" src="https://github.com/user-attachments/assets/8e02138f-0c27-424b-847b-71fc93a74d33" />

<img width="836" alt="Screenshot 2025-02-03 at 23 44 05" src="https://github.com/user-attachments/assets/b1a4f3f3-fb4e-448d-8dbe-be936d8eb76d" />

<h2>SLAs (Service Level Agreements)</h2>

- You can create SLAs in the admin panel, and their purpose is to highlight the points in time tickets should be worked on(how many days a week or hours a day, as well as what hours during the day) and how long agents have to resolve them. The purpose of this is to highlight how much of a priority a particular issue is in case too many requests are coming in at once.

<img width="961" alt="Screenshot 2025-02-04 at 00 25 32" src="https://github.com/user-attachments/assets/55ea74b9-47a6-4f0e-b282-fc4fe5712d90" />

- When you create an SLA in the admin panel you can then assign it to a ticket.
<img width="1144" alt="Screenshot 2025-02-04 at 00 30 15" src="https://github.com/user-attachments/assets/5469277b-fcea-4d5d-ae01-d8387d595bc7" />

<h2>Emails</h2>

- You can restrict users with certain emails from creating tickets on the front end.
<img width="961" alt="Screenshot 2025-02-04 at 01 01 32" src="https://github.com/user-attachments/assets/710fd9c4-7ec3-4875-812a-966757bb87fb" />

<img width="941" alt="Screenshot 2025-02-04 at 01 02 01" src="https://github.com/user-attachments/assets/16c93c8d-e714-4507-aec8-c899d47c225d" />

<img width="841" alt="Screenshot 2025-02-04 at 01 05 48" src="https://github.com/user-attachments/assets/7ec31096-fc31-44a8-b15f-a5c02da494ce" />

- You can test outgoing emails via SMTP(Simple Mail Transfer Protocol). To enable this, you first need to add an email address and enable 2-step verification.

<img width="725" alt="Screenshot 2025-02-04 at 01 09 02" src="https://github.com/user-attachments/assets/e4f0c103-b7af-4975-a065-3d5016ce52b7" />

<img width="858" alt="Screenshot 2025-02-04 at 01 09 40" src="https://github.com/user-attachments/assets/15f8b78c-49f5-4b1f-8271-7b1f8153e837" />


- From there go to app passwords and create a custom password for osTicket.

<img width="723" alt="Screenshot 2025-02-04 at 01 09 53" src="https://github.com/user-attachments/assets/ffcff76c-0b40-4c8a-b6d2-8a972cc9e34e" />

<img width="650" alt="Screenshot 2025-02-04 at 01 10 07" src="https://github.com/user-attachments/assets/40a829d7-5c1f-406c-99dc-e39cc602f2a4" />

<img width="590" alt="Screenshot 2025-02-04 at 01 10 22" src="https://github.com/user-attachments/assets/246e1be7-0c34-4103-a9e4-a6c1b0e7f7b2" />

- After that is done, you fill in the hostname and portnumber.
<img width="957" alt="Screenshot 2025-02-04 at 01 11 09" src="https://github.com/user-attachments/assets/023e0be9-fe6f-4f1d-8278-1345cdd36e1f" />

- The new email has now been added
<img width="960" alt="Screenshot 2025-02-04 at 01 11 52" src="https://github.com/user-attachments/assets/d871f215-eeff-4c58-bcd6-7886cfbb1962" />


- You can then proceed to test if the outgoing email settings have been properly established
<img width="960" alt="Screenshot 2025-02-04 at 01 12 23" src="https://github.com/user-attachments/assets/c22b9052-7c54-4aea-943a-5da98a77a660" />

<img width="962" alt="Screenshot 2025-02-04 at 01 13 00" src="https://github.com/user-attachments/assets/646176e9-4153-41d6-bc03-ee63497c5150" />

<img width="613" alt="Screenshot 2025-02-04 at 01 13 21" src="https://github.com/user-attachments/assets/05dd9468-5349-4c9c-b1fd-765881adb03d" />

<h2>Teams</h2>

- Not only can help tickets be assigned to agents, but they can also be assigned to teams, and you can add multiple agents to a team.
<img width="959" alt="Screenshot 2025-02-04 at 01 21 52" src="https://github.com/user-attachments/assets/15b5a8ef-bc8b-4471-b37d-25ff5ddc1d9c" />

<img width="957" alt="Screenshot 2025-02-04 at 01 22 35" src="https://github.com/user-attachments/assets/ceeef7ac-38bb-4916-9548-87ee88970384" />

<img width="967" alt="Screenshot 2025-02-04 at 01 22 44" src="https://github.com/user-attachments/assets/910f9dcb-dc12-483d-b78d-d2de0814bcc2" />

<img width="647" alt="Screenshot 2025-02-04 at 01 40 56" src="https://github.com/user-attachments/assets/1b650756-12ad-4730-97d5-bdfd69120dcb" />

<h2>View Only Agents</h2>

- When creating agents in the admin panel you can restrict the amount of access they have to a ticket. In some cases, you can decide that they can only view tickets and nothing else.
<img width="962" alt="Screenshot 2025-02-04 at 01 42 46" src="https://github.com/user-attachments/assets/51c4aac0-d679-442b-8ba5-563696ccc491" />

<img width="960" alt="Screenshot 2025-02-04 at 01 43 11" src="https://github.com/user-attachments/assets/06fb2e17-b335-42a2-96e4-9b8b4bf08a01" />

- In the image below the agent Bob is unable to do anything besides looking at the ticket.
<img width="964" alt="Screenshot 2025-02-04 at 01 44 52" src="https://github.com/user-attachments/assets/0f35ece5-e218-4d3e-b394-7ff7f65ae6b2" />
