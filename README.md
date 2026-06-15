# Active-Directory-Help-Desk-Ticket-Simulation
## Overview

This lab simulates common Help Desk and Active Directory administration tasks performed in an enterprise environment. The objective was to gain hands-on experience with user account management, security groups, Organizational Units (OUs), and access control within a Windows Active Directory domain.

---

# Ticket 1: New Hire Onboarding

## Request

A new employee, John Doe, joined the Sales department and required a domain account.
<img width="1920" height="892" alt="John doe user created in sales (Ticket 1)" src="https://github.com/user-attachments/assets/182fac11-1810-4b82-a86e-7087ff46978a" />
Figure 1.1 (created Jdoe in sales)

<img width="1920" height="892" alt="verified jdoe is add to sales-users" src="https://github.com/user-attachments/assets/4c94cf6b-ad7d-4d62-bd1e-24b3a0833080" />
Figure 1.2 (Added Jdoe to the Sales-Users security group)

## Actions Performed

* Created a new Active Directory user account:

  * Username: jdoe
* Assigned a temporary password
* Configured the account to require a password change at first login
* Added the user to the Sales-Users security group

## Skills Demonstrated

* User account creation
* Group membership management
* New employee onboarding

---

# Ticket 2: Password Reset Request

## Request

Aisha Muhammed forgot her password and was unable to access her account.
<img width="1920" height="892" alt="Reset Aish Muhammed&#39;s password in sales" src="https://github.com/user-attachments/assets/421121a7-acc0-4f1c-8b5f-6d94697f5d11" />
Figure 2.1 (Reset Aisha's password)

<img width="1920" height="892" alt="password reset for aish completed ticket 2" src="https://github.com/user-attachments/assets/f9ec8d74-36a8-43b9-9b04-0d6ef13324ea" />
Figure 2.2 (Aisha's password Changed)


## Actions Performed

* Located the user account in Active Directory
* Reset the user's password
* Configured the account to require a password change at next login
* Verified account settings

## Skills Demonstrated

* Password administration
* User account management
* Security best practices

---


# Ticket 3: Employee Termination

## Request

HR requested immediate deactivation of a former employee's account.
<img width="1920" height="892" alt="Ticket 4 disable klee acc because he left the company" src="https://github.com/user-attachments/assets/b1eb5ba2-a51c-4251-8aea-ea31ddd2e112" />
Figure 3.1 (Deactivated Klee account because he left the company)

## Actions Performed

* Disabled the user account
* Moved the account to the Disabled Users Organizational Unit
* Verified account status

## Skills Demonstrated

* User lifecycle management
* Security administration
* Organizational Unit management

---

# Ticket 4: Department Transfer

## Request

Aisha Muhammed transferred from Sales to Marketing.
<img width="1920" height="892" alt="aisha tranfered to marketing" src="https://github.com/user-attachments/assets/e15bdfc0-9a47-4b2b-af42-3c0319eaf820" />
Figure 4.1 (Transfered Aisha to marketing)

<img width="1920" height="892" alt="added aisha to marketing security group" src="https://github.com/user-attachments/assets/b3809744-83d0-4fe5-9eb2-31a0bd3f2272" />
Figure 2.2 (Added Aisha to security Marketing-Users security group)



## Actions Performed

* Moved the user account from the Sales OU to the Marketing OU
* Removed the user from the Sales-Users group
* Added the user to the Marketing-Users group
* Verified updated group membership

## Skills Demonstrated

* Organizational Unit management
* Group administration
* Access management

---

# Ticket 5: Shared Folder Access Request

## Request

Sophie Sales required access to the Sales department shared folder.
<img width="1920" height="892" alt="added sophie to Sales-Shared" src="https://github.com/user-attachments/assets/81323ec6-8aa2-4ec7-ab42-2b3786c87a5e" />
Figure 5.1 (added Sophie to Sales-shared-Access security group)


## Actions Performed

* Added the user to the Sales-Share-Access security group
* Verified successful group membership assignment

## Skills Demonstrated

* Security group administration
* Access control management
* Resource permission assignment

---

# Ticket 6: VPN Access Request

## Request

Rachel Sales required VPN access for remote work.

<img width="1920" height="892" alt="Added Rachel to VPN users" src="https://github.com/user-attachments/assets/3ffa8ff9-8544-4114-a1f3-8afdfcaa205f" />
Figure 6.1 (Granted Rachel from sales access to VPN)

## Actions Performed

* Added the user to the VPN-Users security group
* Verified successful group membership assignment

## Skills Demonstrated

* Remote access administration
* Security group management
* User access provisioning

---


# Ticket 7: Finance User Creation
<img width="1920" height="892" alt="users robert to finace" src="https://github.com/user-attachments/assets/98fb1645-f06c-40f4-9f7b-c4bbe32eb523" />
Figure 7.1 (Created new employee Rebort and added him to Finance security group)
## Request

A new Finance employee required a domain account.

## Actions Performed

* Created a new user account:

  * Username: rfinance
* Assigned a temporary password
* Configured password change at next login
* Added the user to the Finance-Users group

## Skills Demonstrated

* User provisioning
* Group membership administration
* New employee onboarding

---

# Technologies Used

* Windows Server
* Active Directory Domain Services (AD DS)
* Active Directory Users and Computers (ADUC)
* Organizational Units (OUs)
* Security Groups
* Group Membership Management
* Windows Authentication

---

# Learning Outcomes

Through these ticket simulations, I gained practical experience with:

* Creating and managing user accounts
* Resetting passwords and unlocking accounts
* Managing Organizational Units
* Security group administration
* Access control and permissions management
* Employee onboarding and offboarding processes
* Active Directory troubleshooting
* Help Desk workflow procedures

These tasks replicate common responsibilities performed by Help Desk Technicians, Desktop Support Technicians, and Junior System Administrators in enterprise environments.
