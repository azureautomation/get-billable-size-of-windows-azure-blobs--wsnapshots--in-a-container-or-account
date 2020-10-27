Get Billable Size of Windows Azure Blobs (w/Snapshots) in a Container or Account
================================================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Data Management Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=data-management&service=all)

Description

Enumerates all blobs in either one container or one storage account and sums up all costs associated. This includes all block and page blobs, all metadata on either blobs or containers. It also includes both committed and uncommitted blocks in the case that
 a blob is partially uploaded.


The details of the calculations can be found in this post:


[http://blogs.msdn.com/b/windowsazurestorage/archive/2010/07/09/understanding-windows-azure-storage-billing-bandwidth-transactions-and-capacity.aspx](http://blogs.msdn.com/b/windowsazurestorage/archive/2010/07/09/understanding-windows-azure-storage-billing-bandwidth-transactions-and-capacity.aspx)


Note: This script requires an Azure Storage Account to run. The storage account can be specified by setting the subscription configuration. For example:


Set-AzureSubscription -SubscriptionName 'MySubscription' -CurrentStorageAccount 'MyStorageAccount'

Example
 
Scenario
You want to to calculates cost of all blobs in a container or storage account.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.18 
See Also

  *  [Windows Azure Data Management Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=data-management&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
