# Windows Server — CLI Setup Guide

> Command-line walkthrough for installing and configuring Windows Server with Active Directory.

---

## Table of Contents

1. [Disk Partitioning](#1-disk-partitioning)
2. [Server Installation](#2-server-installation)
3. [Administrator Password](#3-administrator-password)
4. [Computer Name](#4-computer-name)
5. [Network Configuration](#5-network-configuration)
6. [Active Directory Installation](#6-active-directory-installation)
7. [Domain Creation](#7-domain-creation)
8. [Domain Verification](#8-domain-verification)

---

## 1. Disk Partitioning

Adjust the disk partitions before proceeding with the installation.

![Partition Setup](https://github.com/user-attachments/assets/054fbb25-04e0-4403-a065-aef654e69134)

---

## 2. Server Installation

Install the server on the second partition.

![Install on Second Partition](https://github.com/user-attachments/assets/b1ee2747-f330-409e-86b9-ecc3a742c858)

---

## 3. Administrator Password

The system will prompt you to set the **Administrator password** on first boot.

![Password Prompt](https://github.com/user-attachments/assets/b356f4e0-1bc2-44d1-bbc0-e2f09c744c35)

---

## 4. Computer Name

Rename the machine to match your naming convention using the CLI.

![Computer Name Change](https://github.com/user-attachments/assets/19effddc-7522-4bb2-8009-536e9642cb9c)

---

## 5. Network Configuration

Configure the network adapters directly from the terminal.  
Using CLI commands is the recommended approach for a **Server Core** environment.

![Network Configuration](https://github.com/user-attachments/assets/4fe4ed88-b403-4879-9d73-37eba7b88f0e)

---

## 6. Active Directory Installation

Install the **AD DS** management tools to prepare the domain environment.

![AD DS Installation](https://github.com/user-attachments/assets/75b2a3b3-21b2-406f-8da4-9336c2454b1c)

---

## 7. Domain Creation

Create the new domain using PowerShell or the `dcpromo` equivalent commands.

![Domain Creation](https://github.com/user-attachments/assets/8f87a858-52ac-4f45-8e0b-b21a7fb9955c)

---

## 8. Domain Verification

Verify that the domain has been successfully created and is responding correctly.

![Domain Verification](https://github.com/user-attachments/assets/4fc7d16c-30a0-4906-845e-2115493a6ef2)

---
