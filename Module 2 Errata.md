# AZ-500 Labs Errata (2020 revision) 

Updated November and September 2021 - Labs are the same as July 2020 revision 
When starting each lab choose Yes when prompted to be visible in networks

# Module 2 – Implement Platform Protection ~135 Minutes (180) 

<br>

## Module 2 Lab 7 – Network Security Groups and Application Security Groups ~45 Minutes (60) 

<br>

### Exercise 1:  Filter network traffic with a network security group using the Azure portal 

Task 1:  Create a virtual network 
Before step 1:  Logon into the Azure portal with your global administrator account

Step 2: You may have to search for Virtual network, if you have to search then click Create 
Task 3: Create a network security group

Step 2: You may have to search for virtual machine, if you have to search then click Create 
Task 6: Create virtual machines

Step 2:  Choose Windows Server 2019 Datacenter
Step 5:  Select Disable not off

Task 8: Associate network interfaces to an ASG
Step2:  Select Application security group, then select Configur the application security group

Task 9:  Test traffic filters 
Step 6:  When pasting from the lab instructions the syntax is wrong.  
	It pastes  
		mstsc /v;myVmWeb 
	It should be   
		mstsc /v:MyVmWeb 

<br>

## Module 2 Lab 8 – Azure Firewall ~45 Minutes (60) 

<br>

E### xercise 1:  Deploy and test an Azure Firewall 

Task 1:  Deploy the Azure firewall 
Step 1:  When prompted:  Logon into the Azure portal with your global administrator account.  
Step 3:  Select radial button under Firewall management - Use Firewall rules (classic) to manage this firewall
Step 3:  Select Test-FW-VN from the Virtual network dropdown

Task 2:  Create a default route 
Step 2:  Click +Create
Step 5:   Search for Route Tables and select 

<br>

## Module 2 Lab 9 – Configuring and Securing ACR and AKS ~ 45 Minutes (60) 

<br>

If the creation of the storage account fails, click on Show Advanced Settings and manually create a storage account.  Ensure you choose East US. 

### Exercise 1:  Configuring and Securing ACR and AKS 

Task 1:  Create an Azure Container Registry 
Step 1:  When prompted:  Logon into the Azure portal with your global administrator account. 

Task 3: Create an Azure Kubernetes Service cluster
Step 6:  Do not continue until the cluster is complete

Task 4:  Give AKS permissions to access the ACR 
Step 2:   Look in your resources group to see the name of the container registry, replace <ACRuniquename> with the container name 

<br>

# Module 2 Additional Labs ~240 Minutes (360) 

<br>

## Module 2 Lab 102 – VNet Peering ~45 Minutes (60) 

<br>

### Exercise 1:  Create Virtual Networks and implement Peering 

Task 1:  Create virtual networks 

Before step 1:  Logon into the Azure portal with your global administrator account. 
Step 3:  You may have to search for Virtual network, if you do click Create
Step 3:  Select Default subnet and change name to Subnet1 
Step 4:  You may have to search for Virtual network, if you do click Create
Step 4:  Select Default subnet and change name to Subnet2 

Task 2:  Peer virtual networks 

Step 3:  
		This virtual network
		Peering Link name:  myVirtualNetwork1-myVirtualNetwork2
		Remote virtual network
		Peering link name:  myVirtualNetwork2-myVirtualNetwork1
		Leave the remaining settings as default 

Task 3:  Peer virtual networks 
Step 5:   Select Disable for Boot Diagnostics when creating both VMs 

Task 4:  Communicate between VMs 
Step 7:   Does not paste correctly – change the ; to a : 
Step 10: Disregard 

<br>

## Module 2 Lab 103 – NVA ~75 Minutes (60) 

<br>

### Exercise 1:  Create a route table 

Task 1:  Route network traffic with a route table using the Azure Portal 
Before step 1:  Logon into the Azure portal with your global administrator account. 
If Route Tables does not show up as an option Search for it 

Task 6:  Create an NVA 
Step 8:  Select - “Enable with custom storage Account” 
Use the name that auto populates 

Task 11:  Turn on IP forwarding with myVmNva 
Step 4:   Does not paste correctly – change the ; to a : 

<br>

## Module 2 Lab 104 – Azure Bastion ~30 Minutes (60) 

<br>

### Exercise 1:  Implement Azure Bastion 

Task 1:  Enable Azure Bastion on your subscription 
Before step 1:  Logon into the Azure portal with your global administrator account. 
If the creation of the storage account fails, click on Show Advanced Settings and manually create a storage account.  Ensure you choose East US. 
Step 4:  When running the second PowerShell command remove the word “undefined” at the end of the command 
Step 8:  Select Save not OK

Task 2:  Create a Bastion host 
Step 5:  The virtual network / subnet may take up to 10 minutes before it shows up in the drop down 

Task 3: Connect to a VM using a bastion host
Step 3:  Make sure you clear the check box "Open in a new window"

<br>

## Module 2 Lab 105 – VM Secure Admin Access ~40 Minutes (60) 

<br>

Task 1:  Create SSH keys with PuTTygen 
Before step 1:  Logon into the Azure portal with your global administrator account.  
Step 1:  After pasting URL remove “/undefined” from end 

<br>

## Module 2 Lab 106 – Azure Disk Encryption ~20 Minutes (60) 

<br>

Task 3: Encrypt the virtual machine
Step 2: You cannot configure the disk to be unencrypted, so the corresponding output will not show the same thing that the lab step shows you. This is expected, continue on.

<br>

## Module 2 Lab 107 – VM Update Management ~40 Minutes (60) 

<br>

### Exercise 1:  Use Azure Automation to manage Windows Updates 

Task 1:  Enable Update Management 
Before step 1:  Logon into the Azure portal with your global administrator account. 
Step 3:  Under Operations click on Guest + host updates 
Click on “Go to Update management 

Task 5:  Configure Alerts 
Step 7:  No longer required
