# CheckmarxAllInOneInstallation
All In One Installation Script for PoCs

Run PowerShell in Admin Mode:

```
PS > $ScriptFromGitHub = Invoke-WebRequest https://raw.githubusercontent.com/jbrotsos/CheckmarxAllInOneInstallation/master/CheckmarxPoCSetup.ps1 -zipPass xxxxxx
PS > Invoke-Expression $($ScriptFromGitHub.Content)
```

