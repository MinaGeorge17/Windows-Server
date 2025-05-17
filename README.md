# WindowsServer
This repository contains all the details and configurations of the Windows Server Project, which aims to establish a robust and functional IT infrastructure. Below is a summary of the project and its key components.
![windowsServer drawio](https://github.com/user-attachments/assets/d3a6c0e4-d950-43d3-bdb4-0662842e7de2)

## Project Overview
The Windows Server Project was designed to create a scalable and secure IT environment using Windows Server roles and functionalities. It features DNS, Web, FTP services, Active Directory, and policies to manage users and devices across multiple branches.

### Objectives:
- **Active Directory Design**: 
  - Primary Domain Controller (PDC) 
  - Child Domain Controller (Alexandria Branch) 
  - Read-Only Domain Controller (RODC)
- **Role-Based Access Control**: Restrict user access to resources using Group Policy Objects (GPOs).
- **Network Services**: Configure DNS, DHCP, WSUS, WDS, and FTP services.
- **Remote Management**: Enable and validate remote administrative access.
- **Testing and Validation**: Ensure all configurations work as intended.

## Devices and IP Address Table
| **Device**    | **IP Address**      |
|---------------|---------------------|
| SMART         | 192.168.100.1       |
| ALEX          | 192.168.100.10      |
| RODC          | 192.168.100.100     |
| WEB           | 192.168.1.1         |
| DNS           | 192.168.100.1       |
| www.web1.com  | 192.168.1.100       |
| www.web2.com  | 192.168.1.101       |

## Key Features
### DNS Server:
- Provides name resolution for clients.
- Hosts primary and secondary zones for internal websites (e.g., www.web1.com and www.web2.com).

### Web and FTP Server:
- Hosts two websites: www.web1.com and www.web2.com.
- FTP services allow secure file sharing with role-based access.

### Active Directory Policies:
- User-specific policies, such as restricted login times and permissions.
- Automatic software deployment (e.g., WinRAR).
- Customized settings like wallpapers and USB restrictions.

### Network Subnets:
- ITI.local Domain for centralized authentication.
- Alex.iti.local Child Domain for the Alexandria branch.
- Routing between subnets managed by core routers.

### RODC Policies:
- Local access and shutdown permissions.
- Password replication for specific users.

## How to Use
This repository contains:
1. Configuration files for DNS, FTP, and Web Servers.
2. Group Policy Object (GPO) templates.
3. Network design and routing details.

Feel free to clone this repository and adapt the configurations to suit your environment.

---

### Contact
For any inquiries or collaboration, reach out at minaaziz6868@gmail.com

### Document
For the full document https://drive.google.com/file/d/1miP_i7HcvyJI8G1x1e1sMrtr8dPPNh9w/view?usp=drive_link
