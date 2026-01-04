# Active-Directory-HOMELAB

## Project Overview
Built a virtualized Windows Server 2022 enivronment with Active Directory Domain Services to simulate an enterprise IT infrastructure. This project demonstrates hands-on experience with server adminstration, user management, and security policy configuration-skills directly applicable to help desk, systems administration, and cybersecurity roles.

## Technologies Used
- **Virtualization:** Oracle VirtualBox 7.1
- **Operating System:** Windows Server 2022 Evaluation
- **Services:** Active Directory Domain Services (AD DS), DNS
- **Management Tools:** Server Manager, Active Directory Users and Computers, Group Policy Management

## Architecture
- **Domain:** homelab.local
- **Domain Controller:** DC1 (Windows Server 2022)
- **User Accounts:** Multiple test users configured with proper naming conventions
- **Group Policies:** Password complexity and security settings enforced domain-wide

## What I Built

### 1. Virtualization Setup
- Installed and configured VirtualBox on host machine
- Created virtual machine with appropriate resource allocation (4GB RAM, 2 CPUs, 50GB virtual disk)
- Successfully troubleshot ISO mounting issues during installation

### 2. Windows Server Installation & Configuration 
- Deployed Windows Server 2022 Evaluation edition
- Configured server hostname (DC1) and network settings
- Installed Active Directory Domain Services role

  ### 3. Active Directory Domain Controller Promotion
  - Promoted server to Domain Controller
  - Created new forest: homelab.local
  - Configured DNS services for domain name resolution
  - Set Directory Services Restore Mode (DSRM) password
  
 ### 4. User Account Management 
 - Created multiple user accounts following enterprise naming conventions (firstname.lastname format)
 - Configured user logon names and initial passwords
- Demonstrated understanding of password policies and user provisioning workflows

 ### 5. Group Policy Configuration - Accessed Group Policy Management Console 
 - Modified Default Domain Policy to enforce security standards:
   - **Minimum password length:** 10 characters 
   - **Password complexity requirements:** Enabled (uppercase, lowercase, numbers, symbols required)
- Documented policy changes for future reference

## Skills Demonstrated 
**Technical Skills:** 
- Windows Server administration
- Active Directory Domain Services (AD DS)
- User account provisioning and management
- Group Policy Object (GPO) configuration
- DNS configuration
- Virtualization concepts and resource management
- Technical troubleshooting and problem-solving

 **IT Operations Knowledge:**
- Understanding of domain architecture
- Enterprise authentication systems
- Security policy enforcement
- Documentation and standard operating procedures
- Help desk workflows for user account management

## 🔧 Challenges & Solutions 
**Challenge:** ISO file failed to mount properly during initial VM creation, causing "cannot find license terms" error. 

**Solution:** Removed and recreated the virtual machine, manually attached the ISO through the IDE controller in VirtualBox settings, ensuring proper configuration before boot. 
**Lesson Learned:** Attention to detail in virtualization configuration is critical. Verified file integrity (4.69 GB) and used alternative mounting methods when initial approach failed.

## 📸 Screenshots 
*Screenshots demonstrating key components:* 
- Active Directory Users and Computers console showing created user accounts
- Group Policy Management Editor with configured password policies
- Server Manager dashboard showing installed roles and features

*(Screenshots stored in `/screenshots` folder)*

## Real-World Applications
This home lab directly simulates enterprise IT environments where I would: 
- Create and manage user accounts for new employees
- Reset passwords and unlock accounts (common help desk tasks)
- Implement security policies across the organization
- Troubleshoot authentication and login issues
- Document IT procedures and configurations

 **Industries using Active Directory:** Healthcare systems, financial institutions, educational organizations, government agencies, and virtually all medium-to-large enterprises with Windows-based infrastructure. 
 
## Future Enhancements 
Planned additions to expand this lab: 
- [ ] Add client Windows 10/11 machines to the domain
- [ ] Create Organizational Units (OUs) for department-based management
- [ ] Implement additional Group Policies (desktop restrictions, software deployment)
- [ ] Configure file sharing and network drives with permission management
- [ ] Set up security groups and role-based access control
- [ ] Integrate DHCP services
- [ ] Practice disaster recovery scenarios

## What I Learned 
This project reinforced that **hands-on practice is essential** for IT roles. Reading about Active Directory in textbooks is valuable, but actually building and troubleshooting a domain controller provides practical experience that directly translates to job responsibilities. 

**Key takeaway:** Entry-level IT positions require foundational knowledge of Windows Server and Active Directory. This lab demonstrates I can perform the core tasks required in help desk and desktop support roles from day one. 

## Contact 

**Ar'Jah'Naye Spivey** 
- LinkedIn: [linkedin.com/in/aspivey22](https://linkedin.com/in/aspivey22)
- Email: sarjahnaye@gmail.com
 ---
*Project completed: January 2026* 
*Total build time: ~4 hours (including troubleshooting)*
