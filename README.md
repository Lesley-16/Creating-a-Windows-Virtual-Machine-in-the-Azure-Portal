# Creating-a-Windows-Virtual-Machine-in-the-Azure-Portal
## Project Overview
This project demonstrates how to create and configure a Windows Virtual Machine (VM) using the Microsoft Azure Portal. It covers the full setup process including selecting a VM image, configuring size and networking, installing necessary software, and connecting to the VM remotely using Remote Desktop Protocol (RDP).

## What is needed
-	Microsoft Azure account
-	Basic understanding of cloud computing
-	Remote Desktop client (e.g., Windows RDP)

## Steps Taken
### 1. Select VM Image
- Chose a Windows Server image from the Azure Marketplace.
### 2. Configure VM Size
-	Selected a VM size based on performance and cost requirements (e.g., Standard B1s(1 vcpu, 1 GiB memory)).
### 3.	Set Up Networking
-	Created a virtual network and subnet.
-	Configured Network Security Group (NSG) to allow RDP (port 3389).
### 4.	Install Software
-	Installed IIS Web Server or other required software after VM provisioning.
### 5.	Connect via RDP
-	Used the public IP address and credentials to connect to the VM using Remote Desktop.

### 6. Activate auto-shutdown
- On VM, scroll to "Operations", and click "Auto-shutdown".
- Set Status to "On", choose your shutdown time, and select your time zone.
- Optionally, enter an email address for shutdown notifications, then click "Save".

 ## Technologies Used
- Microsoft Azure Portal
-	Windows Server
-	Remote Desktop Protocol (RDP)
-	IIS Web Server



