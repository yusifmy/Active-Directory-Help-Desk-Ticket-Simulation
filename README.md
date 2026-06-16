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
** Figure 5.1 (added Sophie to Sales-shared-Access security group)**


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


# Ticket 8: Service Account Creation

## Request

A dedicated service account was required for backup software operations.
<img width="1920" height="892" alt="created service account for backup" src="https://github.com/user-attachments/assets/a859dd4c-0499-473d-814f-6225a2c94772" />

**Figure 8.1 – Service Account Creation**

## Actions Performed

* Created a new service account:

  * Username: svc_backup
* Assigned a secure password
* Configured the account with Password Never Expires
* Stored the account in the Service Accounts Organizational Unit

## Skills Demonstrated

* Service account management
* Account security configuration
* Active Directory administration

---
# Ticket 9: Finance Shared Folder Access Group

## Request
Finance department required a dedicated security group for future file share permissions.

<img width="1920" height="892" alt="created a group for finace for shared access" src="https://github.com/user-attachments/assets/efc9836d-f0c4-4986-b448-f28ae62b965d" />
**Figure 9.1 – Finance Security Group Creation**

## Actions Performed

* Created security group:

  * Finance-Share-Access
* Configured group as:

  * Global
  * Security
* Prepared group for NTFS and file share permission assignments

## Skills Demonstrated

* Security group administration
* Access control planning
* Role-based access management


---

# Ticket 10: Workstation OU Management

## Request

A workstation computer object was located in the default Computers container and needed proper organization.
<img width="1920" height="892" alt="moved PC01 from computers to workstations" src="https://github.com/user-attachments/assets/eddbdeca-4214-4023-8aa9-8f0b766e38c7" />
**Figure 10.1 – Computer Object Moved to Workstations OU**

## Actions Performed

* Located PC01 in Active Directory
* Moved the computer object into the Workstations Organizational Unit
* Verified successful relocation

## Skills Demonstrated

* Organizational Unit management
* Computer object administration
* Active Directory organization

---

# Ticket 11: Workstation Rename

## Request

The workstation naming convention required updating PC01 to SALES-PC01.
<img width="1920" height="892" alt="changed PC01 to SALES-PC01" src="https://github.com/user-attachments/assets/8fbac17c-6196-4fdb-9370-ccf30d8164b3" />
**Figure 11.1 – Workstation Renamed to SALES-PC01**

## Actions Performed

* Logged into the client workstation
* Renamed computer from PC01 to SALES-PC01
* Restarted the workstation
* Verified the updated computer object in Active Directory

## Skills Demonstrated

* Workstation administration
* Device management
* Enterprise naming standards

---

# Ticket 12: Strong Password Policy Implementation

## Request

The Security Team requested stronger password requirements across the domain.

<img width="1920" height="891" alt="created a new GPO called strong password policy" src="https://github.com/user-attachments/assets/71852ade-6a4e-4245-8a6d-cf3848c8ad02" />
**Figure 12.1 – Strong Password Policy Configuration**


## Actions Performed

Configured the Default Domain Policy with:

* Minimum Password Length: 10
* Password Complexity: Enabled
* Maximum Password Age: 90 Days
<img width="1920" height="891" alt="set pass maximum length to 90 days" src="https://github.com/user-attachments/assets/f7211cd1-f0fe-4b2c-a931-8201cba3b206" />
**Figure 12.2 - Password Maximum age to 10**

  <img width="1920" height="891" alt="set password minimum length to 10" src="https://github.com/user-attachments/assets/7bd5477a-27f5-40cb-bc63-875c99506cf8" />
  **Figure 12.3 - Password Mininum length to 10**

Validated configuration using:

```cmd
net accounts
```
<img width="1920" height="891" alt="net accounts" src="https://github.com/user-attachments/assets/2ae8c0fc-938f-40a8-8631-ff2f01760797" />
**Figure 12.2 - verified


## Skills Demonstrated

* Group Policy Management
* Password policy administration
* Active Directory security hardening


# Ticket 13: Account Lockout Policy

## Request

Security required protection against brute-force password attacks.
<img width="1920" height="891" alt="set account lockout policy to 5 attempts" src="https://github.com/user-attachments/assets/789a396e-92c0-4e41-a505-c3faa7b56de0" />
**Figure 13.1 – Account Lockout Policy Verification**


## Actions Performed

Configured the Default Domain Policy with:

* Account Lockout Threshold: 5 Attempts
* Lockout Duration: 15 Minutes
* Reset Lockout Counter: 15 Minutes
<img width="1920" height="891" alt="set account lockout duration to 15 minutes" src="https://github.com/user-attachments/assets/a450c4c0-ee03-48d4-ada8-1c42e51700ec" />
**Figure 13.2 - Lockout duration to 15 minutes**

Verified implementation using:

```cmd
net accounts
```

## Skills Demonstrated

* Account security management
* Group Policy administration
* Domain security configuration


# Ticket 14: Restrict Control Panel Access for Sales Users

## Request

Sales department users should not have access to Control Panel or Windows Settings.
<img width="1920" height="891" alt="prohibited control panel to sales ous" src="https://github.com/user-attachments/assets/d0dd71a4-58d5-4d6d-826a-7895a66304c0" />
Figure 14.1 – Control Panel Access Restricted for Sales Users**


## Actions Performed

* Created GPO:

  * Block Control Panel - Sales
* Linked policy to the Sales OU
* Enabled:

  * Prohibit access to Control Panel and PC Settings
* Updated policy using:

```cmd
gpupdate /force
```

* Logged in as Sales user (jdoe)
* Confirmed restriction message appeared


## Skills Demonstrated

* Group Policy Management
* User restrictions
* Organizational Unit targeting
* Security administration


# Ticket 15: Company Login Banner

## Request

Security required a legal warning banner before user authentication.
<img width="1920" height="891" alt="set inateractive" src="https://github.com/user-attachments/assets/da2c399c-155d-4477-a900-3c878537354c" />
**Figure 15.1 – Login Banner Displayed at Sign-In**



## Actions Performed

Created GPO:

* Company Login Banner

Configured:

Title:

```text
Authorized Use Only
```

Message:

```text
This system is for authorized users only.
Activity may be monitored and recorded.
```

Applied policy and verified appearance during user login.

## Skills Demonstrated

* Security policy administration
* Group Policy Management
---

# Technologies Used

### Server Infrastructure

* Windows Server 2022
* Active Directory Domain Services (AD DS)
* DNS Server
* Group Policy Management (GPMC)
* Active Directory Users and Computers (ADUC)

### Client Systems

* Windows 11 Enterprise
* Domain-Joined Workstation

### Virtualization

* Oracle VirtualBox
* Host-Only Networking
* Virtual Machine Management

### Identity and Access Management

* Organizational Units (OUs)
* User Accounts
* Security Groups
* Service Accounts
* Computer Objects

### Administrative Tools

* Server Manager
* Group Policy Editor
* Command Prompt
* Active Directory Administrative Tools

### Commands Utilized

```cmd
whoami
gpupdate /force
net accounts
nslookup
hostname
ipconfig /all
```

# Key Skills Developed

### Active Directory Administration

* Creating and managing Organizational Units (OUs)
* Creating and managing user accounts
* Creating and managing security groups
* Managing computer objects
* Managing service accounts
* Account lifecycle management

### Identity and Access Management (IAM)

* User provisioning
* User deprovisioning
* Group-based access control
* Password policy enforcement
* Account lockout management
* Least privilege implementation

### Group Policy Administration

* Creating and linking GPOs
* Password policy configuration
* Account lockout policy configuration
* Login banner deployment
* User restriction policies
* Organizational Unit targeting

### Desktop Support & Help Desk Skills

* Password resets
* User account unlocks
* User onboarding
* User offboarding
* Workstation management
* Login troubleshooting
* Domain authentication troubleshooting

### Windows Administration

* Domain joins
* Workstation renaming
* Device management
* Security configuration
* Policy deployment
* Administrative troubleshooting

### Networking Fundamentals

* DNS verification
* Domain name resolution
* Active Directory authentication
* Network configuration validation
* Client-server communication

### Security Operations

* Security group implementation
* Access control management
* Account security hardening
* Brute-force protection using account lockout policies
* Endpoint restriction policies
* Security policy enforcement

# Lab Outcome

This Active Directory Home Lab simulated a real-world enterprise environment consisting of a Windows Server 2022 Domain Controller and a Windows 11 domain-joined workstation.

Throughout the lab, multiple help desk and system administration scenarios were completed, including user account creation, password resets, account unlocks, security group management, workstation administration, Organizational Unit management, Group Policy deployment, and security hardening.

A total of 18 hands-on support tickets were completed to replicate common tasks performed by Help Desk Technicians, Desktop Support Specialists, IT Support Analysts, and Junior System Administrators in corporate environments.

The lab provided practical experience with Active Directory administration, Identity and Access Management (IAM), Group Policy management, Windows administration, and troubleshooting methodologies. By completing these exercises, I developed foundational enterprise IT skills directly applicable to entry-level Help Desk, Desktop Support, IT Support Specialist, and Systems Administration roles.

This project demonstrates the ability to deploy, manage, secure, and troubleshoot a Windows-based Active Directory environment while following industry-standard administrative practices.
