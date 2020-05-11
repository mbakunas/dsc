# Repo to house the PowerShell desired state configuration for my other repositories
To create the zip files, use <a href="https://docs.microsoft.com/en-us/powershell/module/az.compute/publish-azvmdscconfiguration">Publish-AzVMDscConfiguration</a>.

I'll create the zip file locally and publish it to this repo using the following command:
```powershell
Publish-AzVMDscConfiguration -ConfigurationPath .\dsc\myconfiguration.ps1 -OutputArchivePath .\dsc\myconfiguration.ps1.zip
```
