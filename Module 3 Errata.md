# AZ-500T00 Module 3 Errata (2020 revision) 

Updated November and September 2021 - Labs are the same as July 2020 revision 
When starting each lab choose Yes when prompted to be visible in networks

# Module 3 - Secure Data and Applications ~150 Minutes (180)

<br>

## Module 3 Lab 10 – Key Vault ~75 Minutes (60) 

<br>

Task 2:  Use PowerShell to create a Key Vault 
Before step 1:  Logon into the Azure portal with your global administrator account.  
Exercise 2: Create an application to demonstrate using the key vault for encryption

Task 2: Create a policy allowing the application access to the Key Vault
Step 3:  Replace  ‘<Azure_AD_Application_Id>’ with your AP ID recorded in earlier step.  Make sure to include the ‘ at the beginning and end

Task 3:  Create an Azure SQL database 
Step 3:   You do not have permissions to create a Resource group.  Use the existing 

Task 5:  Build a Console Application to work with Encrypted Columns

        After launching Visual Studio choose not now on the sign in page
        Click start Visual Studio

<br>

## Module 3 Lab 11 – Securing Azure SQL Database ~20 Minutes (60) 

<br>

Task 2:  Configure Advanced Data Protection 
Before step 1:  Logon into the Azure portal with your global administrator account. 
Step 2:  On the server blade, in the Security section, click Microsoft Defender for Cloud. 
Step 5:  In the Azure Defender for SQL: Enabled at the subscription-level (Configure) parameter, click (configure).
Step 7:  Back to Microsoft Defender for Cloud blade, review Recommendations and Security incidents and alerts. 

Task 4 : Configure auditing
Step 3:  Click on Server Settings then set the Auditing switch to ON to enable auditing.

<br>

## Module 3 Lab 12 – Securing Azure Storage ~55 Minutes (60) 

<br>

### Exercise 1: Service endpoints and security storage 

<br>

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
