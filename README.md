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

![Admin Panel Screenshot](images/admin-panel.png)

---

### 2. Configure Roles

Roles define permissions for agents.

Navigate to:  
`Admin Panel -> Agents -> Roles`

Example Role:
- **Supreme Admin**

Here’s an example of the **Roles** configuration screen:

![Roles Screenshot](images/roles-config.png)

---

### 3. Configure Departments

Departments control ticket visibility for agents. For example, a help desk department vs a sysadmin team.

Navigate to:  
`Admin Panel -> Agents -> Departments`

Example Departments:
- **SysAdmins** (for system administrators)

Here’s a screenshot of the Departments page:

![Departments Screenshot](images/departments.png)

---

### More Configuration Steps...

## License

This project uses [osTicket](http://osticket.com/) under its respective open-source license.
