---
title: ie4uinit.exe | IE Per-User Initialization Utility
excerpt: What is ie4uinit.exe?
---

# ie4uinit.exe 

* File Path: `C:\Windows\system32\ie4uinit.exe`
* Description: IE Per-User Initialization Utility

## Hashes

Type | Hash
-- | --
MD5 | `7B68D605B51474457D1CAFE437205213`
SHA1 | `2DAA37A12BA96B6990418460F1D30869E432F125`
SHA256 | `6F83621ED34B61CA0BBAFF5A5FD158FEECA364DE52EEC38E1CC2295A82A7BD5C`
SHA384 | `96D0EEAD8C04662AD3CB5DF188C881292FA28AED20491B039B7C269D05FA5DCAA9898988381AD63ADB74935635E06F02`
SHA512 | `616873A3BCC7A1E78441A9040FD37DFA5F6648347685C1B4198841B64F8E553F82CC28288215B6016602071F5C854D43EFFE0898C552F3A1B6D183479612264F`
SSDEEP | `6144:U3scA4efnKKCR/o6e8cnz/eXTsrqAxWl/s5ZMyQ:U8cAjKd7I7UAx+`
IMP | `AE9B039EFA096B7A0B1FD63D51F43863`
PESHA1 | `95216B359B62BFC5972BC4967FB989AC6D5B172D`
PE256 | `94DD39CB8A2DC823DBC592AE400F054C433EEC28D084076F5642C0483C17A457`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\ie4uinit.exe.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_5.82.19041.488_none_4238de57f6b64d28 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\system32\ie4uinit.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IE4UINIT.EXE.MUI
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/6f83621ed34b61ca0bbaff5a5fd158feeca364de52eec38e1cc2295a82a7bd5c/detection


## Possible Misuse

*The following table contains possible examples of `ie4uinit.exe` being misused. While `ie4uinit.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `Name: Ie4uinit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Command: ie4uinit.exe -BaseSettings` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `Description: Executes commands from a specially prepared ie4uinit.inf file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Path: c:\windows\system32\ie4uinit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Path: c:\windows\sysWOW64\ie4uinit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- IOC: ie4uinit.exe loading a inf file from outside %windir%` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`IE4UINIT.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


