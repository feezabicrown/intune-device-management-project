# Microsoft Intune Device Management Project

## Overview
This project demonstrates the deployment and management of Windows devices using **Microsoft Intune** and **Microsoft Entra ID**.  
The goal of this project was to configure a modern endpoint management workflow, including device enrollment, policy enforcement, and automated application deployment.

A Windows 10 virtual machine hosted on **VMware vSphere** was used to simulate a corporate-managed endpoint.

---

## Technologies Used
- Microsoft Intune  
- Microsoft Entra ID (Azure AD)  
- Windows Autopilot  
- Windows 10  
- VMware vSphere  
- Microsoft Win32 Content Prep Tool  

---

## Project Scope
The following components were configured and validated in this project:

- Cloud user creation in Microsoft Entra ID  
- Device join and registration configuration  
- Intune MDM user scope configuration  
- Dynamic device group creation  
- Windows Autopilot enrollment profiles  
- Configuration and compliance policies  
- Application deployment using dynamic groups  
- Win32 application packaging (7-Zip)  

---

## Identity and Device Enrollment
Microsoft Entra ID was configured as the identity provider for users and devices.  
Device join and registration settings allow Windows devices to be onboarded and enrolled into Intune for centralized management.

Microsoft Intune was configured as the Mobile Device Management (MDM) authority to ensure enrolled devices are automatically managed.

---

## Dynamic Device Groups
Dynamic device groups were created to automatically include Windows devices based on defined rules.  
These groups were used to assign enrollment profiles, configuration policies, compliance policies, and applications.

---

## Application Deployment
Applications were deployed using Microsoft Intune and assigned to dynamic device groups.

### Win32 Application (7-Zip)
- 7-Zip was packaged using the Microsoft Intune Win32 Content Prep Tool  
- The application was uploaded as a Win32 app in Intune  
- Installation was automated and deployed to enrolled devices  

Microsoft 365 Apps were also configured and deployed through Intune.

---

## Device Provisioning
Windows Autopilot was used to automate device provisioning.  
During setup, the device was enrolled into Intune, security policies were applied, and applications were installed automatically without manual intervention.

---

## Results
- Successful device enrollment into Intune  
- Policies applied automatically  
- Applications installed during provisioning  
- Centralized management confirmed  

---

## Repository Contents
- **Microsoft Intune Device Management Project.docx** – Project documentation with screenshots and explanations

---

## Key Skills Demonstrated
- Endpoint management with Microsoft Intune  
- Identity and access management using Microsoft Entra ID  
- Automated device enrollment with Windows Autopilot  
- Dynamic group-based policy and application assignment  
- Win32 application packaging and deployment  

---

## Notes
This project was created as a hands-on lab to demonstrate practical Intune and endpoint management skills suitable for junior system administrator or cloud engineer roles.
