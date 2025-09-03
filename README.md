# Windows Active Directory Homelab

This project documents the design, setup, and management of a Windows Server–based Active Directory homelab.  
The lab simulates a small enterprise environment with a Domain Controller (DC), client machines, organizational units, group policies, and secure departmental file shares.

## 📂 Lab Phases

### Phase 1 – Domain Controller Setup
- Installed Windows Server, promoted it to a Domain Controller (`lab.local`).
- Configured DHCP, static IP, and DNS.
- Created and verified Active Directory roles and services.  
📸 Screenshots: [phase-01](./phase-01)

### Phase 2 – Domain Users & Groups
- Added test users (e.g., *Alice Smith*, *John Doe*).  
- Created groups (e.g., *IT_Staff*).  
- Joined a Windows 10 client to the domain.  
📸 Screenshots: [phase-02](./phase-02)

### Phase 3 – Group Policy Objects (GPOs)
- Enforced password policies.  
- Restricted Control Panel and Command Prompt for users.  
- Applied a corporate wallpaper via GPO.  
📸 Screenshots: [phase-03](./phase-03)

### Phase 4 – OU-Specific Policies
- Created OUs for departments (*IT, HR, Finance*).  
- Applied OU-specific GPOs (e.g., stricter rules for IT).  
📸 Screenshots: [phase-04](./phase-04)

### Phase 5 – File Shares
- Configured shared folders for each department.  
- Applied NTFS permissions so only department members can access their folder.  
📸 Screenshots: [phase-05](./phase-05)

## 🛠️ Skills Demonstrated
- Active Directory Domain Services (AD DS) deployment  
- DHCP & DNS configuration  
- Group Policy Object (GPO) creation and troubleshooting  
- OU design and delegation  
- NTFS permissions and network shares  
- Documentation and GitHub project organization  

## 🚀 How to Use This Lab
Anyone can replicate this lab using:  
- VirtualBox or VMware  
- Windows Server 2019/2022 ISO  
- Windows 10/11 ISO  

Follow the phase order and apply the GPOs step by step.  
