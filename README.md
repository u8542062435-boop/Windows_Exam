# Windows Server — Users, Groups & OUs

> Managing Organizational Units, Groups, and Users through Active Directory Users and Computers (ADUC).

---

## Table of Contents

1. [Opening the Management Tool](#1-opening-the-management-tool)
2. [Creating Organizational Units](#2-creating-organizational-units)
3. [OU Configuration](#3-ou-configuration)
4. [Groups and Users inside an OU](#4-groups-and-users-inside-an-ou)
5. [Creating Groups](#5-creating-groups)
6. [Group Scope Reference](#6-group-scope-reference)
7. [Creating Users](#7-creating-users)
8. [User-specific Settings](#8-user-specific-settings)
9. [Disabling an Account](#9-disabling-an-account)

---

## 1. Opening the Management Tool

To create Users, OUs and Groups within the domain, open the **Active Directory Users and Computers (ADUC)** tool.

![ADUC Tool](https://github.com/user-attachments/assets/3dcbd442-6d40-45d9-85fd-7e0a66c31a4c)

---

## 2. Creating Organizational Units

Start by creating the **Organizational Units (OUs)** — they will serve as containers to organize groups and users.

![Create OU](https://github.com/user-attachments/assets/8c145926-71a9-4614-9ac8-64f8ee489377)

---

## 3. OU Configuration

Only a name is required to create an OU — minimal configuration needed.

![OU Settings](https://github.com/user-attachments/assets/d505b46a-1878-42f3-83eb-27f6d7f6f062)

---

## 4. Groups and Users inside an OU

Once the OUs are created, both **Groups** and **Users** can be added inside them.

![Groups and Users](https://github.com/user-attachments/assets/0d82d397-f095-49c3-b008-86fd59d59d42)

---

## 5. Creating Groups

When creating a group, two key properties must be defined: **Scope** and **Type**.



<img width="435" height="372" alt="imatge" src="https://github.com/user-attachments/assets/32ae650a-acfe-49f4-96f5-63380b90d852" />


---

## 6. Group Scope Reference
For this task, each group had a specific compatibility requirement:
| Group | Scope | Type | Requirement | Reason |
|---|---|---|---|---|
| **Grupo_Direccion** | Global | Security | Compatible with Windows Server 2000 | Global groups exist since Windows 2000, offering maximum legacy compatibility. Members can only come from the same domain, but the group is visible across the entire forest. |
| **Grupo_Mantenimiento** | Domain Local | Security | Only accessible from this domain | Domain Local groups can only be assigned to resources within their own domain. They accept members from any domain in the forest, but their scope is strictly local. |
| **Grupo_Laboratorio** | Universal | Security | Accessible from all domains | Universal groups are stored in the Global Catalog and are visible and usable across all domains in the AD forest. |

---

## 7. Creating Users

When adding a user, fill in the required fields such as name, logon name, and password options.

![User Creation](https://github.com/user-attachments/assets/c105a9d2-0271-4734-b06b-84e4c257f0ef)

---

## 8. User-specific Settings

Individual settings can be applied per user, such as **logon hour restrictions**.  
Below are the configured settings for user **Juzo Kabuto**.

![Juzo Kabuto Settings](https://github.com/user-attachments/assets/b0a2d83c-3fca-42a3-b0ba-cc40f797cff9)

---

## 9. Disabling an Account

Accounts can be disabled directly from ADUC without deleting them.  
Here, **Pepe's account** has been disabled.

![Disable Account](https://github.com/user-attachments/assets/48af81e9-462b-465f-9541-6eea528b4561)

---




