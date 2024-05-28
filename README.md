<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# **osTicket: 1 Introduction and Virtual Machine Setup**

# **Part 1 Installation**

## **What is osTicket?**

osTicket is a widely used and trusted open-source support ticketing system that allows you to easily scale and streamline your customer service tracking and improve your customer experience.

 **Part 1 Create a Virtual Machine in Azure**

   1. Create a Resource Group
   2. Create a Windows 10 Virtual Machine with 2-4 Virtual CPUs.
          *When creating the VM, allow it to create a new Virtual Network(vnet).*
      
 **1 Create a Resource Group**

In browser go to: portal.azure.com \> Resource groups \> click on +Create \> go to Resource group\* name it <span style="color:blue">**RG-osTicket1**

Region **(US) East US 2** \> **Review+create \>☑️ Validation passed \> **Create.**

![1 RG osTicket1](https://github.com/TDCybersecurity/osTicket-Post-Installation-Setup/assets/142702123/7e2d0e0a-ed9c-4424-95dc-86d384fa0218)


 **2 Create a Windows 10 Virtual Machine with 2-4 Virtual CPUs**

In search bar type virtual machines \> click 💻Virtual machines \> Create\> 💻Azure virtual machine \>

| **Resource group**| **VM machine**| **Region**| **Availability options**| **Security type**| **Image**| **Size**| **Username**| **Password**|
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RG-osTicket1 | vm-osticket1 | (US) East US 2 | No infra | Standard | Windows 10 Pro 22H2 | Standard D4s v3 -4 vcpus | labusertd | labuserAzure1$ |

 ☑️I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights.

Next: Disks \> Next: Networking \> **Review + Create**


![os Ticket 2 Create](https://github.com/TDCybersecurity/osTicket-Post-Installation-Setup/assets/142702123/23f9e21e-4bd9-4bb8-ba3b-6a5424000017)

Second part of the same page.

![os Ticket 2 Create2](https://github.com/TDCybersecurity/osTicket-Post-Installation-Setup/assets/142702123/15b09c2f-e298-4220-8ddd-ad34f24e4e80)


☑️Validation passed \> **Create**  **\>** Deployment is in progress while resources are created \>

![osTicket3](https://github.com/TDCybersecurity/osTicket-Post-Installation-Setup/assets/142702123/2caeb0b8-b0fe-4dcc-b41f-105f3c1c3448)

In conclusion, we have gained hands-on experience

From ◾◾◾Deployment is in progress to ✔️ Your deployment is complete \> Go to Resources

![osTicket4](https://github.com/TDCybersecurity/osTicket-Post-Installation-Setup/assets/142702123/a4a53312-0976-4169-81a2-4922e9715af2)



**Observe**  **Public IP**  **40.123.36.32** **and**  **Private IP**   **10.0.0.4**

![osTicket6](https://github.com/TDCybersecurity/osTicket-Post-Installation-Setup/assets/142702123/5491cf91-a264-4031-a4e4-8391dc72171a)


### **Congratulations! 
### **This lab demonstrates hands-on experience in configuring prerequisites and installing osTicket.**
