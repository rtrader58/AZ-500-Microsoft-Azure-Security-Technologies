# AZ-500 Labs Errata   
 
Updated January 2022, November and September 2021 - Labs are the same as July 2020 revision  

When starting each lab choose Yes when prompted to be visible in networks 
 
# Module 1 – Manage Identity and Access - Total lab time ~130 Minutes (3.5 hour) 
 
## Module 1 Lab 1 – Role-Based Access Control ~30 Minutes (90)  
 
### Exercise 2 – Create a Junior Admins group containing the user account Isabel Garcia as its member  
 
Task 1: Step 1 
PowerShell is now called Windows Terminal (Admin) when right clicking on the start menu. 

Task 1: Step 2  
When copying and pasting command it sometimes pastes wrong,  
Ensure the command is Install-Module  
 
### Exercise 3 – Creating a Service Desk Group; containing the user account Dylan Williams as its member  
 
Task 1: Use Azure CLI to create a user account Dylan Williams  
If you encounter an error during this lab that indicates the clock is out of sync or the current time is in error, use the Settings app in the VM to synchronize the computer’s clock and then retry the step 
Wait for step 1 to complete before moving on to step 2  
After running step 3 choose Edge Browser and enter your Azure tenant admin account and password  

<br>

## Module 1 Lab 2: Azure Policy ~20 Minutes (60)  
 
### Exercise 1 – Implementing Azure Policy  
 
Task 1: Create an Allowed Location policy assignment   
Step 8: The subscription will be CloudshareX (X will be a number) not an Azure subscription  

Task 2: Test the Allowed Locations policy assignment 
Step 3: You will see the error as soon as you select US East.  Skip to Step 6. 
<br>
## Module 1 Lab 3: Resource Manager Locks ~20 Minutes (60)  
 
No errata  

<br>

## Labs 4 and 5: MFA, Conditional Access and AAD Identity Protection & Privileged Identity Management (PIM) ~ 60 minutes 
 
Before completing this lab create an outlook.com account for use in this lab.  Refer to the create an outlook.com account document in the file share. 

### Exercise 1: Implement Azure MFA 

Task 5: Configure Azure MFA settings. 
Step 14 is a verification step Click the x to leave the page 

Task 6: Validate MFA configuration 
Step 8 - 10 Choose to use an email address, use the outlook.com account you created at the beginning of this lab. Open outlook.com and retrieve the code sent. 

<br>

## Module 1 Lab 6: Implementing Directory Synchronization ~45 Minutes (8 hours)  
 
### Exercise 1,  

Task 1,  
Step 5: For the Add DNS TXT Record, in the Name , type @ for the Name and the ms=xxxx  value from your Custom Domain Name as the Value 

### Exercise 2: Azure AD Pass-through Authentication 
 
Task 2: Install AD Connect 
Step 8: Copy the password from the Home tab in the lab.  The password in the lab instructions is incorrect. 
