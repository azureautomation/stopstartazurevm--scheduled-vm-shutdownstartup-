Stop-Start-AzureVM (Scheduled VM Shutdown/Startup)
==================================================

            

DESCRIPTION


This PowerShell Workflow runbook connects to Azure using an Automation Credential and Starts/Stops a VM/a list of VMs/All VMs in a Subscription in-parallel. You can attach a recurring schedule to this runbook to run it at a specific time.


REQUIRED


1. SubscriptionId - parameter that allows scoping VMs to a particular  Subscription.


3. **AzureVMList - **parameter to input the VM/VMList Name - seperated by (,)


2. **Action - **Parameter to perform the action. **Stop
**- to stop the Azure Virtual Machine; **Start **- to start the Azure Virtual Machine


NOTES:


1. **AzureCredential **- Is added as an credential under Shared Resources at the Automation Account level.


 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
