<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket-Configuration
I will be going through certain parts of osTicket to demonstrate its features.

<h2>Tools Used</h2>
 - Microsoft Azure
 - Remote Desktop
 - osTicket
 - Gmail

<h2>Operating Systems Used</h2>
 - Windows 10 Pro (22H2)

<h2>The Platforms Of osTicket</h2>
- OsTicket comes with the front-end and the back-end. The front-end is where users or agents can create help tickets, while the back end is where all the configuration and work gets done.

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

- Whenever a member of an organisation has a problem that needs to be sorted (e.g: password reset) they can put it through on their end and it will then appear in the agent panel
<img width="842" alt="Screenshot 2025-02-03 at 22 35 02" src="https://github.com/user-attachments/assets/3cc0ed18-a8a9-4e3e-91af-9267e0c3976d" />

<img width="960" alt="Screenshot 2025-02-03 at 22 35 30" src="https://github.com/user-attachments/assets/44ffefc2-6a7a-4ab7-9691-1ce6a89d155a" />

<h2>Assigning Tickets To Agents/Team Members</h2>
- Whenever a ticket has been created and appears in the agent panel you can choose who the ticket gets assigned to and that person will be in charge of resolving the issue.
<img width="1091" alt="Screenshot 2025-02-03 at 22 37 00" src="https://github.com/user-attachments/assets/c9e9f52e-97f7-47f4-9986-2571c5e51fe4" />

- You can create users to work on tickets in the admin panel.
<img width="1354" alt="Screenshot 2025-02-03 at 22 43 50" src="https://github.com/user-attachments/assets/7b81f48d-ace1-4b86-92b5-e7b79a3181a8" />

<img width="660" alt="Screenshot 2025-02-03 at 22 45 40" src="https://github.com/user-attachments/assets/c9ead4b0-3167-477a-8f18-d9dc7a3e77cd" />

<h2>Resolving Tickets</h2>
- After someone has been assigned a ticket and they have worked the ticket to completion, they have to close the ticket on their end so that other people can be made aware that the issue has been resolved.
<img width="1148" alt="Screenshot 2025-02-03 at 22 47 34" src="https://github.com/user-attachments/assets/2d712692-5225-475f-bcff-589ce3f5cdec" />

<img width="533" alt="Screenshot 2025-02-03 at 22 48 20" src="https://github.com/user-attachments/assets/5850120b-0cbb-4925-8bc3-b8d521ba083d" />

<img width="646" alt="Screenshot 2025-02-03 at 22 49 19" src="https://github.com/user-attachments/assets/2a4c6512-93c1-4995-9ef0-7a41db7d4ad7" />

- When the ticket has been marked as resolved it will no longer be visible on the agent panel unless you go to the closed ticket section in the agent panel.
<img width="969" alt="Screenshot 2025-02-03 at 22 49 35" src="https://github.com/user-attachments/assets/b6a9c16c-eae0-4749-a7cf-ec65413cb745" />

<h2>CAPTCHA</h2>
- Within the admin panel you can add a captcha setting to the ticket so that whenever a user creates a ticket you can be sure that the person is verified as human.
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
- From the admin panel you set filters which restrict users from creating tickets if certain criteria are met or are not met.
<img width="958" alt="Screenshot 2025-02-03 at 23 41 19" src="https://github.com/user-attachments/assets/c6e4c838-6109-42f1-b530-ed134842469d" />

<img width="958" alt="Screenshot 2025-02-03 at 23 41 05" src="https://github.com/user-attachments/assets/8e02138f-0c27-424b-847b-71fc93a74d33" />

<img width="836" alt="Screenshot 2025-02-03 at 23 44 05" src="https://github.com/user-attachments/assets/b1a4f3f3-fb4e-448d-8dbe-be936d8eb76d" />
