**osTicket Overview and Virtual Machine Creation**

**Part 1 Installation**

**What is osTicket?**

osTicket is a widely used and trusted open-source support ticketing system. Easily scale and streamline your customer service and drastically improve your customer's experience.

Part 1 Create a Virtual Machine in Azure

1. Create a Resource Group
2. Create a Windows 10 Virtual Machine with 2-4 Virtual CPUs.

1. When creating the VM, allow it to create a new Virtual Network(vnet).

**1 Create a Resource Group**

In browser go to: portal.azure.com \> Resource groups \> click on +Create \> go to Resource group\* name it RG-osTicket1

Region (US) East US 2 \> **Review+create \>**  **** Validation passed \> **Create.**

![1 RG osTicket1](https://github.com/TDCybersecurity/osTicket-Post-Installation-Setup/assets/142702123/7e2d0e0a-ed9c-4424-95dc-86d384fa0218)


2 Create a Windows 10 Virtual Machine with 2-4 Virtual CPUs

In search bar type virtual machines \> click Virtual machines \> Create\>  Azure virtual machine \>

| **Resource group**| **VM machine**| **Region**| **Availability options**| **Security type**| **Image**| **Size**| **Username**| **Password**|
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RG-osTicket1 | vm-osticket1 | (US) East US 2 | No infra | Standard | Windows 10 Pro 22H2 | Standard D4s v3 -4 vcpus | labusertd | labuserAzure1$ |

 I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights.

Next: Disks \> Next: Networking \> **Review + Create**
![os Ticket 2 Create](https://github.com/TDCybersecurity/osTicket-Post-Installation-Setup/assets/142702123/23f9e21e-4bd9-4bb8-ba3b-6a5424000017)



![](RackMultipart20240520-1-1pgppb_html_fa9d6f6ac9d67b67.png)

Validation passed \> **Create**  **\>** Deployment is in progress while resources are created \>

![](RackMultipart20240520-1-1pgppb_html_b6f57a30bcc8974.png)

From  Deployment is in progress to  Your deployment is complete \> Go to Resources

![](RackMultipart20240520-1-1pgppb_html_45bec60565e95185.png)

**Observe**  **Public IP**  **Address**  **40.123.36.32**  **and**  **Private**  **IP Address**  **10.0.0.4**

![](RackMultipart20240520-1-1pgppb_html_f27eeb0a27710b2f.png)
