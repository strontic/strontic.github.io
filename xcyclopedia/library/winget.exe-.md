---
title: winget.exe | 
excerpt: What is winget.exe?
---

# winget.exe 

* File Path: `C:\Users\user\AppData\Local\Microsoft\WindowsApps\winget.exe`

## Hashes

Type | Hash
-- | --
MD5 | ``
SHA1 | ``
SHA256 | ``
SHA384 | ``
SHA512 | ``
SSDEEP | ``

## Runtime Data

### Usage (stdout):
```cmhg
Windows Package Manager v1.1.12663
Copyright (c) Microsoft Corporation. All rights reserved.

Argument alias was not recognized for the current command : '-help'

The winget command line utility enables installing applications and other packages from the command line.

usage: winget [<command>] [<options>]

The following commands are available:
  install    Installs the given package
  show       Shows information about a package
  source     Manage sources of packages
  search     Find and show basic info of packages
  list       Display installed packages
  upgrade    Upgrades the given package
  uninstall  Uninstalls the given package
  hash       Helper to hash installer files
  validate   Validates a manifest file
  settings   Open settings or set administrator settings
  features   Shows the status of experimental features
  export     Exports a list of the installed packages
  import     Installs all the packages in a file

For more details on a specific command, pass it the help argument. [-?]

The following options are available:
  -v,--version  Display the version of the tool
  --info        Display general info of the tool

More help can be found at: https://aka.ms/winget-command-help

```

### Loaded Modules:

Path |
-- |
C:\Program Files\WindowsApps\Microsoft.DesktopAppInstaller_1.16.12663.0_x64__8wekyb3d8bbwe\AppInstallerCLI.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000003F16206E3E7EFDA8ABE0000000003F1`
* Thumbprint: `5362FAEB842C236D05A729B7FAC85BAA1B68BDCA`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: Unknown


## Possible Misuse

*The following table contains possible examples of `winget.exe` being misused. While `winget.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbin_execution_via_winget.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lolbin_execution_via_winget.yml) | `title: Monitoring Winget For LOLbin Execution`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbin_execution_via_winget.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lolbin_execution_via_winget.yml) | `description: Adversaries can abuse winget to download payloads remotely and execute them without touching disk. Winget will be included by default in Windows 10 and is already available in Windows 10 insider programs. The manifest option enables you to install an application by passing in a YAML file directly to the client. Winget can be used to download and install exe's, msi, msix files later.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbin_execution_via_winget.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lolbin_execution_via_winget.yml) | `- https://docs.microsoft.com/en-us/windows/package-manager/winget/install#local-install`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbin_execution_via_winget.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lolbin_execution_via_winget.yml) | `- '.*(?i)winget install (--m\|-m).*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbin_execution_via_winget.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lolbin_execution_via_winget.yml) | `- Admin activity installing packages not in the official Microsoft repo. Winget probably won't be used by most users.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


