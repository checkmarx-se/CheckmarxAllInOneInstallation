# CheckmarxAllInOneInstallation
All In One Installation Script for PoCs

# List of applications installed

* Chocolatey
* SQL Server Express
* IIS
* GIT
* dotnetcore-windowshosting
* jdk8
* jre8
* maven
* nodejs-lts
* dotnetcore-sdk
* nuget.commandline
* gradle
* python3
* sbt
* 7zip
* Notepad++
* Jenkins
* Google Chrome
* Checkmarx Plugins
* Cpp Redist: vcredist_x64.exe
* dotnet-hosting-2.1.14-win.exe
* Checkmarx Manager & Engine Server

# How to Run
Run PowerShell in Admin Mode:

```
PS > $ScriptFromGitHub = Invoke-WebRequest https://raw.githubusercontent.com/jbrotsos/CheckmarxAllInOneInstallation/master/CheckmarxPoCSetup.ps1 -zipPass xxxxxx
PS > Invoke-Expression $($ScriptFromGitHub.Content)
```

