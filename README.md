# chocolatey-on-windows-10
<--!
https://virgool.io/@dariush-tasdighi/%D9%8A%DA%A9-package-manager-%D9%81%D9%88%D9%82-%D8%A7%D9%84%D8%B9%D8%A7%D8%AF%D9%87-%D8%A8%D8%B1%D8%A7%DB%8C-windows-felwbfuzmblw
-->
### Contents
1. [Introduction](#Introduction)
2. [Commands](#Commands)
## Introduction
Chocolatey is a package manager for Windows that allows you to easily install, upgrade, and uninstall software packages on your system. With Chocolatey, you can:

1. Install and manage software packages from a central repository.
2. Automate the installation and configuration of software packages.
3. Keep your software up-to-date with the latest releases and security patches.
4. Manage multiple installations and configurations of software packages on multiple systems.
5. Create your own packages and repositories to distribute software within your organization.
6. Integrate Chocolatey with other tools and scripts to streamline your workflows.
#### install Chocolatey on Windows 10 by following these steps:
1. Open the Windows Start menu and search for "PowerShell".
2. Right-click on Windows PowerShell and select "Run as administrator".
3. Copy and paste the following command into the PowerShell window and press Enter:
```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
4. Once the installation is complete, you can test if Chocolatey is installed correctly by running the command choco in PowerShell. If the command returns a list of available commands, then Chocolatey is installed correctly.

## Commands
* Help
```
choco --help
choco -h
```
* Search
```
choco search [PackageName]
```
* Install 
```
choco install [PackageName]
```

