# Windows Server — Step-by-Step Setup Guide

> A complete walkthrough for installing and configuring Windows Server with Active Directory.

---

## Table of Contents

1. [Version Selection](#1-version-selection)
2. [Disk Partitioning](#2-disk-partitioning)
3. [Administrator Password](#3-administrator-password)
4. [Computer Name](#4-computer-name)
5. [Active Directory Installation](#5-active-directory-installation)
6. [Network Configuration](#6-network-configuration)
7. [Server Promotion](#7-server-promotion)
8. [Domain Controller](#8-domain-controller)

---

## 1. Version Selection

Choose the appropriate Windows Server edition for your environment.

![Version Selection](https://github.com/user-attachments/assets/b15007d4-235e-4535-ac6e-40db8f950bd3)

---

## 2. Disk Partitioning

Configure and edit the disk partitions before installation.

![Disk Partitioning](https://github.com/user-attachments/assets/f3aa6b97-b462-48c6-9869-3acee4ee91d9)

---

## 3. Administrator Password

Set a strong password for the built-in Administrator account.

![Administrator Password](https://github.com/user-attachments/assets/9a972304-dd0f-40f8-93cb-e05d6fe42d18)

---

## 4. Computer Name

Rename the computer to match your naming convention before joining the domain.

![Computer Name Change](https://github.com/user-attachments/assets/24624a50-54a7-4a07-9f57-78b00e2b0bce)

---

## 5. Active Directory Installation

Install the **Active Directory Domain Services (AD DS)** role and required features.

![Feature Selection](https://github.com/user-attachments/assets/5b318424-681b-4750-8e7f-02ba32cd7ea6)

![Feature Installation](https://github.com/user-attachments/assets/fb72ddd8-fccf-4502-9dd8-02d36b9f6c72)

---

## 6. Network Configuration

Assign a static IP address to ensure reliable domain communication.

![Network Settings](https://github.com/user-attachments/assets/d37d4feb-99c1-4cfd-a047-34bfd8990e5f)

---

## 7. Server Promotion

Promote the server to a **Domain Controller** using the AD DS Configuration Wizard.

![Promotion Wizard](https://github.com/user-attachments/assets/2be4e763-2530-43af-83e1-344d8ebd4e1c)

![Reboot](https://github.com/user-attachments/assets/17362f79-5472-4fe9-8798-ecc7f28023ae)

---

## 8. Domain Controller

The server has been successfully promoted to a **Domain Controller**.

![Domain Controller](https://github.com/user-attachments/assets/6535474f-0457-42d9-9621-e2c0fc9e5e81)

---


