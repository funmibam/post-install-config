# osTicket Configuration Project

This project outlines the configuration and setup process for the osTicket system, an open-source help desk and ticketing software. The configuration includes settings for agents, users, departments, roles, and service level agreements (SLAs).

## Project Overview

This guide walks through the steps required to configure osTicket for efficient support ticket management, including:

- Creating different roles for agents and users
- Configuring departments and teams for ticket visibility and assignment
- Setting up Service Level Agreements (SLAs) to prioritize tickets
- Managing help topics to streamline ticket creation by users

### Access URLs

- **Admin/Analyst Login Page:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- **End Users osTicket URL:** [http://localhost/osTicket](http://localhost/osTicket)

---

## Configuration Steps

### 1. Agent Panel vs Admin Panel

Here's a screenshot of the Admin Panel:


<img width="717" alt="Screenshot 2024-10-14 175528" src="https://github.com/user-attachments/assets/f8a8c453-edcb-4ee5-8b49-8b552ac09302">


---

### 2. Configure Roles

Roles define permissions for agents.

Navigate to:  
`Admin Panel -> Agents -> Roles`

Example Role:
- **Supreme Admin**

Here’s an example of the **Roles** configuration screen:



<img width="721" alt="Screenshot 2024-10-14 174416" src="https://github.com/user-attachments/assets/fc7ae89a-1bcf-4d8f-8e48-9888338a34cf">


---










<img width="719" alt="image" src="https://github.com/user-attachments/assets/3afde1af-349e-4afa-9ea3-869378a59e9d">




---












<img width="718" alt="Annotation 2024-10-29 200531" src="https://github.com/user-attachments/assets/4468a36c-4a5f-4710-9a64-b2e74f21c0b5">


---


---

### 3. Configure Departments

Departments control ticket visibility for agents. For example, a help desk department vs a sysadmin team.

Navigate to:  
`Admin Panel -> Agents -> Departments`

Example Departments:
- **SysAdmins** (for system administrators)

Here’s a screenshot of the Departments page:


<img width="718" alt="Screenshot 2024-10-14 174708" src="https://github.com/user-attachments/assets/ca705008-d07d-43fc-a162-bbe0f1fffc38">




---









<img width="718" alt="image" src="https://github.com/user-attachments/assets/4426e8ee-2741-44c2-bd70-ff39b5dc7ae1">










---









<img width="719" alt="Annotation 2024-10-29 203009" src="https://github.com/user-attachments/assets/cf4eadc3-6951-4b81-9142-7e0bb5159cc5">





---

### More Configuration Steps...

## License

This project uses [osTicket](http://osticket.com/) under its respective open-source license.
