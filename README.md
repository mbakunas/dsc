# Repo to house the PowerShell desired state configuration for my other repositories
To create the zip files, use <a href="https://docs.microsoft.com/en-us/powershell/module/az.compute/publish-azvmdscconfiguration">Publish-AzVMDscConfiguration</a>.

The command for creating the zip file locally:
```powershell
Publish-AzVMDscConfiguration -ConfigurationPath .\dsc\myconfiguration.ps1 -OutputArchivePath .\dsc\myconfiguration.ps1.zip
```

In the ARM template, use https://raw.githubusercontent.com/mbakunas/dsc/master/ to download the files.