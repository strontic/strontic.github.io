---
title: AtBroker.exe | Windows Assistive Technology Manager
excerpt: What is AtBroker.exe?
---

# AtBroker.exe 

* File Path: `C:\Windows\system32\AtBroker.exe`
* Description: Windows Assistive Technology Manager

## Hashes

Type | Hash
-- | --
MD5 | `22FB65036D7A01D15710A14CD70A903C`
SHA1 | `45A1BEEE176F092CDAD1384D82EFDBDD4589C41E`
SHA256 | `4D75D895625DCF95E06DB50816CEC9EF125B25FF916AF3F9CEA68CDBD2630799`
SHA384 | `014B98364A545972CCCD53619F5DBCB592F03DBF576BD35D0A5B7C28F37ADBD67E971A70853BCA89662471C1F57FBF59`
SHA512 | `C501B8B473F2C5614263B5C27F5A721B070FEEF5001A4BF1E29A8ACE54FA9FDF7755A5D52066619C3BC74CD7F0484AED38A5D1513034547348E6504F71F03515`
SSDEEP | `1536:nXtIN3Ow1nvQUfNvOI3d3M8oth+Gms2AVC3Yfx9BiXeL5Zcz5kWXFMx:ndQJBlPdc8/AVCkx/aeL5ZY5kWX6`
IMP | `EB4EAB2F36ED8FB4978A50489F965F43`
PESHA1 | `A0F462A07AE194F61A2A68F1BA2F23B7EEF1D867`
PE256 | `0BBCFC32BDF75E80F1242A1E9DEB7270023DE0108C2F7E3A5DD4BD03C342F3D4`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\system32\AtBroker.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
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

* Original Filename: ATBroker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/4d75d895625dcf95e06db50816cec9ef125b25ff916af3f9cea68cdbd2630799/detection


## Possible Misuse

*The following table contains possible examples of `AtBroker.exe` being misused. While `AtBroker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- '*\CurrentVersion\Image File Execution Options\atbroker.exe*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `Name: Atbroker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- Command: ATBroker.exe /start malware`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- Path: C:\Windows\System32\Atbroker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- Path: C:\Windows\SysWOW64\Atbroker.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Atbroker.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Atbroker.yml) | `- IOC: Unknown AT starting C:\Windows\System32\ATBroker.exe /start malware`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * App Switcher: <code>C:\Windows\System32\AtBroker.exe</code></blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


