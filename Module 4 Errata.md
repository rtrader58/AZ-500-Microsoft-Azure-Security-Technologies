# AZ-500T00 Module 4 Labs Errata (2020 revision) 

Updated November and September 2021 - Labs are the same as July 2020 revision 
When starting each lab choose Yes when prompted to be visible in networks

<br>

# Module 4 – Manage Security Operations - Lab 13, 14 and 15 launch in a single lab environment – Total time ~135 hours (90)

<br>

## Module 4 Lab 13 – Azure Monitor ~30 Minutes 

<br>

Task 1: Deploy an Azure virtual machine 
No errata

Task 2: Create a Log Analytics workspace
No errata

Task 3: Enable the Log Analytics virtual machine extension 
Step 1: Before beginning this task, ensure that the Log Analytics Workspace deployment has completed successfully, it should take 1-2 minutes
Step 2 – if the VM is not listed, wait a few minutes and then refresh the view. It can take up to 15 minutes for the VM to appear in the list. Also, verify that the VM you created in Task 1 is Running.
Step 4 - 5: It can take a few minutes to connect.  (On 11/5/2021 this took 2.5 minutes) This is a great time to stretch & hydrate!

Task 4:  Collect virtual machine event and performance data
No errata

Task 5: View and query collected data
Step 3: Close the video in the details section of this page, and ignore the instruction to click “get started”
Step 4: Navigate to the Virtual Machines queries in the All Queries column or use Search
Step 5: It doesn’t matter which queries you run, this task is to show you VM log data being gathered. Note that some queries will have no results as not enough data has been gathered yet.

## ***** DO NOT END THE LAB!!  After completing Lab 13 use the drop down window at the top to move to lab 14, and scroll up to Task 1: Azure Security Center.  DO NOT END THE LAB!! *****

<br>

## Module 4 Lab 14 – Security Center ~60 Minutes

<br>

Task 1: Configure Security Center 
Step 1: You’re already logged in, you can skip this step
Step 2: Brand name change occurred. Security Center is called Microsoft Defender for Cloud now
Step 3: Select both the subscription and the new instance that you created in Lab 13. After confirmation, click Install Agents.
Step 4: Click the Overview blade, and then in the details pane click Enable Azure Defender
step 7:  On the Settings blade verify that Log Analytics agent for Azure VMs is On if off turn on
Step 8:  Is on the pop up when you turn on the log Analytics
The steps return to normal at #10. Steps 2-10 are a bit of a mess.
Step 10: In the Management section, click the Workflow Automation blade
Step 13: JFYI you can’t create a workflow automation yet because you don’t have any Logic Apps yet. You’ll create those in the next lab.
Steps 14 & 15: Skip

Task 2: Implement the Security Center recommendation 
Step 2: in the Cloud Security section, there may not be a score yet.  It can take up to 60 minutes to evaluate. Just continue with the lab.
Step 3: Click the Inventory tile

Task 3: Implement the Security Center recommendation to enable Just in time VM Access
Replace steps 1 and 2 with:
a.	Open the Virtual Machines space
b.	Select the VM you created earlier
c.	In the Settings section, click the Security blade
d.	Click the Explore just-in-time access in Defender for Cloud

## ***** DO NOT END THE LAB!!  After completing Lab 14 use the drop-down window at the top to move to lab 15.  Do not end the lab!! *****

<br>

## Lab 15: Azure Sentinel ~45 Minutes

<br>

Task 1: On-board Azure Sentinel
No errata

Task 2: Configure Azure Sentinel to use the Azure Activity data connector
Step 10:  Per the note it may take 5-10 minutes before the connector shows Connected. Please wait for it to show Connected before proceeding.

Task 3: Create a rule that uses the Azure Activity data connector.
No errata

Task 4: Create a playbook
Steps 1-3: Do these tasks in the VM, not your local OS.

Task 5: Create a custom alert and configure a playbook as an automated response
Step 10: Under Alert automation, select the drop-down and check the Select all box

Task 6: Invoke an incident and review the associated actions
For Steps 1-3, disable JIT VM access for myVM using the steps in Lab 14 Task 3
Step 5: This can take several minutes to show up. Stretch & hydrate!
