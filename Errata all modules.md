# AZ-500T00 All Module Errata

Updated January 2022, November and September 2021 - Labs are the same as July 2020 revision 
When starting each lab choose Yes when prompted to be visible in networks

<br>

# Module 1 Manage Identity and Access - Total lab time ~130 Minutes (3.5 hour)

<br>

## Module 1 Lab 1 – Role-Based Access Control ~30 Minutes (90) 

<br?

### Exercise 2 – Create a Junior Admins group containing the user account Isabel Garcia as its member 

<br>

Task 1: Step 1
PowerShell is now called Windows Terminal (Admin) when right clicking on the start menu.
Task 1: Step 2 
When copying and pasting command it sometimes pastes wrong, 
Ensure the command is Install-Module 

<br>

### Exercise 3 – Creating a Service Desk Group; containing the user account Dylan Williams as its member 

<br>

Task 1: Use Azure CLI to create a user account Dylan Williams 
If you encounter an error during this lab that indicates the clock is out of sync or the current time is in error, use the Settings app in the VM to synchronize the computer’s clock and then retry the step
Wait for step 1 to complete before moving on to step 2 
After running step 3 choose Edge Browser and enter your Azure tenant admin account and password 

<br>

## Module 1 Lab 2: Azure Policy ~20 Minutes (60) 

<br>

### Exercise 1 – Implementing Azure Policy 

<br>

Task 1: Create an Allowed Location policy assignment  
Step 8: The subscription will be CloudshareX (X will be a number) not an Azure subscription 

Task 2: Test the Allowed Locations policy assignment
Step 3: You will see the error as soon as you select US East.  Skip to Step 6.

<br>

## Module 1 Lab 3: Resource Manager Locks ~20 Minutes (60) 

<br>

No errata 

<br>

## Labs 4 and 5: MFA, Conditional Access and AAD Identity Protection & Privileged Identity Management (PIM) ~ 60 minutes

<br>

Before completing this lab create an outlook.com account for use in this lab.  Refer to the create an outlook.com account document in the file share.

<br>

### Exercise 1: Implement Azure MFA

<br>

Task 5: Configure Azure MFA settings.
Step 14 is a verification step Click the x to leave the page

Task 6: Validate MFA configuration
Step 8 - 10 Choose to use an email address, use the outlook.com account you created at the beginning of this lab. Open outlook.com and retrieve the code sent.

<br>

## Module 1 Lab 6: Implementing Directory Synchronization ~45 Minutes (8 hours) 

<br>

### Exercise 1

<br>

Task 1, 
Step 5: For the Add DNS TXT Record, in the Name , type @ for the Name and the ms=xxxx  value from your Custom Domain Name as the Value

<br>

### Exercise 2: Azure AD Pass-through Authentication

<br>

Task 2: Install AD Connect
Step 8: Copy the password from the Home tab in the lab.  The password in the lab instructions is incorrect.

<BR>

# Module 2 – Implement Platform Protection ~135 Minutes (180) 

<BR>

## Module 2 Lab 7 – Network Security Groups and Application Security Groups ~45 Minutes (60) 

<BR>

### Exercise 1:  Filter network traffic with a network security group using the Azure portal 

<BR>

Task 1:  Create a virtual network 
Before step 1:  Logon into the Azure portal with your global administrator account
Step 2: You may have to search for Virtual network, if you have to search then click Create 

Task 3: Create a network security group
Step 2: You may have to search for Network security group, if you have to search then click Create 

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

<BR>

## Module 2 Lab 8 – Azure Firewall ~45 Minutes (60) 

<BR>

### Exercise 1:  Deploy and test an Azure Firewall 

Task 1:  Deploy the Azure firewall 
Step 1:  When prompted:  Logon into the Azure portal with your global administrator account.  
Step 3:  Select radial button under Firewall management - Use Firewall rules (classic) to manage this firewall
Step 3:  Select Test-FW-VN from the Virtual network dropdown

Task 2:  Create a default route 
Step 2:  Click +Create
Step 5:   Search for Route Tables and select 

<BR>

## Module 2 Lab 9 – Configuring and Securing ACR and AKS ~ 45 Minutes (60) 

If the creation of the storage account fails, click on Show Advanced Settings and manually create a storage account.  Ensure you choose East US. 

### Exercise 1:  Configuring and Securing ACR and AKS 

<BR>

Task 1:  Create an Azure Container Registry 
Step 1:  When prompted:  Logon into the Azure portal with your global administrator account. 

Task 3: Create an Azure Kubernetes Service cluster
Step 6:  Do not continue until the cluster is complete

Task 4:  Give AKS permissions to access the ACR 
Step 2:   Look in your resources group to see the name of the container registry, replace <ACRuniquename> with the container name 

Task 5: Deploy an external service to AKS
Step 5: There no ellipses. Move your cursor to the upper right hand corner o the editor and left click you will see the option to save and also option to close.

<BR>

# Module 2 Additional Labs ~240 Minutes (360) 

<BR>

## Module 2 Lab 102 – VNet Peering ~45 Minutes (60) 

<BR>

### Exercise 1:  Create Virtual Networks and implement Peering 

<BR>

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

<BR>

## Module 2 Lab 103 – NVA ~75 Minutes (60) 

<BR>

### Exercise 1:  Create a route table 

<BR>

Task 1:  Route network traffic with a route table using the Azure Portal 
Before step 1:  Logon into the Azure portal with your global administrator account. 
If Route Tables does not show up as an option Search for it 

Task 6:  Create an NVA 
Step 8:  Select - “Enable with custom storage Account” 
Use the name that auto populates 

Task 11:  Turn on IP forwarding with myVmNva 
Step 4:   Does not paste correctly – change the ; to a : 

<BR>

## Module 2 Lab 104 – Azure Bastion ~30 Minutes (60) 

<BR>

### Exercise 1:  Implement Azure Bastion 

<BR>

Task 1:  Enable Azure Bastion on your subscription 
Before step 1:  Logon into the Azure portal with your global administrator account. 
If the creation of the storage account fails, click on Show Advanced Settings and manually create a storage account.  Ensure you choose East US. 
Step 4:  When running the second PowerShell command remove the word “undefined” at the end of the command 
Step 8:  Select Save not OK

Task 2:  Create a Bastion host 
Step 5:  The virtual network / subnet may take up to 10 minutes before it shows up in the drop down 

Task 3: Connect to a VM using a bastion host
Step 3:  Make sure you clear the check box "Open in a new window"


<BR>

## Module 2 Lab 105 – VM Secure Admin Access ~40 Minutes (60) 

<BR>

Task 1:  Create SSH keys with PuTTygen 
Before step 1:  Logon into the Azure portal with your global administrator account.  
Step 1:  After pasting URL remove “/undefined” from end 

<BR>

## Module 2 Lab 106 – Azure Disk Encryption ~20 Minutes (60) 

<BR>

Task 3: Encrypt the virtual machine
Step 2: You cannot configure the disk to be unencrypted, so the corresponding output will not show the same thing that the lab step shows you. This is expected, continue on.

<BR>

## Module 2 Lab 107 – VM Update Management ~40 Minutes (60) 

<BR>

### Exercise 1:  Use Azure Automation to manage Windows Updates 

<BR>

Task 1:  Enable Update Management 
Before step 1:  Logon into the Azure portal with your global administrator account. 
Step 3:  Under Operations click on Guest + host updates 
Click on “Go to Update management 

Task 5:  Configure Alerts 
Step 7:  No longer required

<BR>

# Module 3 - Secure Data and Applications ~150 Minutes (180)

<BR>

## Module 3 Lab 10 – Key Vault ~75 Minutes (60) 

Task 2:  Use PowerShell to create a Key Vault 
Before step 1:  Logon into the Azure portal with your global administrator account.  

<BR>

## Exercise 2: Create an application to demonstrate using the key vault for encryption

<BR>

Task 2: Create a policy allowing the application access to the Key Vault
Step 3:  Replace  ‘<Azure_AD_Application_Id>’ with your AP ID recorded in earlier step.  Make sure to include the ‘ at the beginning and end

Task 3:  Create an Azure SQL database 
Step 3:   You do not have permissions to create a Resource group.  Use the existing 

Task 5:  Build a Console Application to work with Encrypted Columns
        After launching Visual Studio choose not now on the sign in page
        Click start Visual Studio


<BR>

## Module 3 Lab 11 – Securing Azure SQL Database ~20 Minutes (60) 

<BR>

Task 2:  Configure Advanced Data Protection 
Before step 1:  Logon into the Azure portal with your global administrator account. 
Step 2:  On the server blade, in the Security section, click Microsoft Defender for Cloud. 
Step 5:  In the Azure Defender for SQL: Enabled at the subscription-level (Configure) parameter, click (configure).
Step 7:  Back to Microsoft Defender for Cloud blade, review Recommendations and Security incidents and alerts. 

Task 4 : Configure auditing
Step 3:  Click on Server Settings then set the Auditing switch to ON to enable auditing.


<BR>

## Module 3 Lab 12 – Securing Azure Storage ~55 Minutes (60) 

<BR>

### Exercise 1: Service endpoints and security storage 

<BR>

Task 1:  Create a virtual network 
Before step 1:  Logon into the Azure portal with your global administrator account. 
Step 2:  You may have to search for Virtual Network
Step 3:  Leave default security settings (this will choose basic DDOS) 

Task 4:  Restrict network access to a resource 
Steps do not work as written, do the following: 
Select the navigation pane in the Azure portal 
Select Storage Account 
Click on New 
Fill out the form with the information from the lab 

Task 5:  Create a file share in the storage account
Step 2:  File share is now called File service.  You may have to scroll on the Overview tab to see the link to File service.  The graphic in the lab does not match the interface. 

Task 6: Restrict network access to a subnet
Step 1:  Under Security + networking for your storage account select networking
Step 5:  Click Add, then click Save
Step 6:  Under Security + networking for your storage account select Access keys
Step 7:  Copy the Key and connection string to notepad

Task 8: Confirm access to storage account 
Step 6: In the third command replace storage-account-name with the name of your storage account leave the rest of the string 

Task 9: Confirm access is denied to storage account
Step 3:  Repeat steps 1-6 of Task 8

<BR>

# Module 4 – Manage Security Operations - Lab 13, 14 and 15 launch in a single lab environment – Total time ~135 hours (90)

<BR>

## Module 4 Lab 13 – Azure Monitor ~30 Minutes 

<BR>

Task 3: Enable the Log Analytics virtual machine extension 
Step 1: Before beginning this task, ensure that the Log Analytics Workspace deployment has completed successfully, it should take 1-2 minutes
Step 2 – if the VM is not listed, wait a few minutes and then refresh the view. It can take up to 15 minutes for the VM to appear in the list. Also, verify that the VM you created in Task 1 is Running.
Step 4 - 5: It can take a few minutes to connect.  (On 11/5/2021 this took 2.5 minutes) This is a great time to stretch & hydrate!

Task 5: View and query collected data
Step 3: Close the video in the details section of this page, and ignore the instruction to click “get started”
Step 4: Navigate to the Virtual Machines queries in the All Queries column or use Search
Step 5: It doesn’t matter which queries you run, this task is to show you VM log data being gathered. Note that some queries will have no results as not enough data has been gathered yet.

# ***** DO NOT END THE LAB!!  After completing Lab 13 use the drop down window at the top to move to lab 14  DO NOT END THE LAB!! *****

<BR>

## Module 4 Lab 14 – Security Center ~60 Minutes

<BR>

Task 1: Configure Security Center 
Step 1: You’re already logged in, you can skip this step
Step 2: Brand name change occurred. Security Center is called Microsoft Defender for Cloud now
Step 3: If you see both the subscription and the new instance that you created in Lab 13, select both of them. 
Also Step 3: After confirmation, click Install Agents
Step 4: Click the Overview blade, and then in the details pane click Enable Azure Defender
Step 7:  On the Settings blade verify that Log Analytics agent for Azure VMs is On if off turn on
Step 8:  Is on the pop up when you turn on the Log Analytics
The steps return to normal at #10. Steps 2-10 are a bit of a mess.
Step 10: In the Management section, click the Workflow Automation blade
Step 13: JFYI you can’t create a workflow automation yet because you don’t have any Logic Apps yet. You’ll create those in the next lab.
Steps 14 & 15: Skip

Task 2: Implement the Security Center recommendation 
Step 2: in the Cloud Security section, there may not be a score yet.  It can take up to 60 minutes to evaluate. Just continue with the lab.
Step 3: Click the Inventory tile

Task 3: Implement the Security Center recommendation to enable Just in time VM Access
Replace steps 1 and 2 with:
Open the Virtual Machines space
Select the VM you created earlier
In the Settings section, click the Security blade
Click the Explore just-in-time access in Defender for Cloud
If JIT does not appear as an option within 30 minutes, move on to Lab 15. It is not necessary to complete the JIT VM Access task to complete the labs.

# ***** DO NOT END THE LAB!!  After completing Lab 14 use the drop-down window at the top to move to lab 15.  Do not end the lab!! *****

<BR>

## Lab 15: Azure Sentinel ~45 Minutes

<BR>

Task 2: Configure Azure Sentinel to use the Azure Activity data connector
Step 10:  Per the note it may take anywhere from 10-30 minutes before the connector shows Connected. Please wait for it to show Connected before proceeding.

Task 4: Create a playbook
Steps 1-3: Do these tasks in the VM, not your local OS.

Task 5: Create a custom alert and configure a playbook as an automated response
Step 10: Under Alert automation, select the drop-down and check the Select all box

Task 6: Invoke an incident and review the associated actions
For Steps 1-3, disable JIT VM access for myVM using the steps in Lab 14 Task 3
Step 5: This can take several minutes to show up. Stretch & hydrate!
