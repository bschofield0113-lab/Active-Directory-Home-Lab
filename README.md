# Active Directory Testing Environment (Home Lab)

A hands-on Active Directory Domain Services lab built in VMware to simulate a real-world Windows domain environment. This project demonstrates core identity and access management skills.

## Overview

Designed and deployed an Active Directory Domain Services testing environment using VMware. The lab includes a Windows Server 2025 domain controller and a domain-joined Windows 11 client, providing practical experience with:

- Identity management
- User and group administration
- Domain controller configuration
- Domain-joined client management

## Objectives

- Build a functional Windows domain for testing user lifecycle management and Group Policy
- Practice secure domain controller setup and basic administrative tasks
- Join client computers to the domain to create a realistic multi-machine environment
- Create a reusable lab for future troubleshooting, scripting, and security experiments

## Technologies & Tools

| Technology              | Purpose                          |
|-------------------------|----------------------------------|
| VMware Workstation      | Virtualization platform          |
| Windows Server 2025     | Domain Controller (evaluation)   |
| Windows 11 Enterprise   | Domain-joined client             |
| Active Directory Domain Services | Identity & access management |

## Implementation Steps

1. Created a new virtual machine in VMware and attached the Windows Server 2025 ISO
2. Completed the installation of Windows Server 2025
3. Logged in with the built-in Administrator account and configured a strong password
4. Installed and configured Active Directory Domain Services, promoting the server to a domain controller
5. Populated the domain with sample users, security groups, and organizational units representing different departments (IT, HR, Finance, Sales)
6. Set up a Windows 11 virtual machine
7. Joined the Windows 11 PC to the Active Directory domain
8. Verified the computer object successfully appeared in Active Directory and confirmed domain membership

## Key Skills Demonstrated

- Virtual machine creation and management
- Windows Server installation and initial hardening
- Active Directory Domain Services installation and domain promotion
- User, group, and Organizational Unit (OU) management
- Domain-joining client computers
- Basic identity and access administration
- Multi-machine lab environment configuration

## Lab Screenshots

| Screenshot | Description |
|------------|-------------|
| ![AD Installed](images/ad-installed.png) | Active Directory installed on Windows Server 2025 running on VMware |
| ![Domain Structure](images.md/domain-structure.png) | Domain populated with Groups, Departments, and Users |
| ![User Properties](images.md/user-properties.png) | User properties showing group and department membership |
| ![Password Reset](images.md/password-reset.png) | Password reset performed on a user account |
| ![Domain Join](images.md/domain-join.png) | Windows 11 client successfully joined to the domain |
| ![Computer Object](images.md/computer-object.png) | Computer object visible in Active Directory Users and Computers |

## Results

Successfully established a working domain controller with a populated directory structure and a domain-joined Windows 11 client. The environment is fully functional and ready for further testing, including:

## Future Enhancements

- Apply and test Group Policy Objects (GPOs)
- Automate user and group creation with PowerShell
- Implement fine-grained password policies
- Add additional client machines and test multi-user scenarios
- Configure basic monitoring or logging

## License

This project is for educational and portfolio purposes.
