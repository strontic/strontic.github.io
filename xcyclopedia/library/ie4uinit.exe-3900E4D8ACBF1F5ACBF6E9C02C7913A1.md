---
title: ie4uinit.exe | IE Per-User Initialization Utility
excerpt: What is ie4uinit.exe?
---

# ie4uinit.exe 

* File Path: `C:\WINDOWS\system32\ie4uinit.exe`
* Description: IE Per-User Initialization Utility

## Hashes

Type | Hash
-- | --
MD5 | `3900E4D8ACBF1F5ACBF6E9C02C7913A1`
SHA1 | `B399F1EBC839B7268A33708EFF853C5077E4BC93`
SHA256 | `7E258C54A58002C64CA0A951A48ABF754A58EBCD8CB8777E74EF76B530D13DB4`
SHA384 | `5D0D498E9B9D21B3435A018FCF787862511047A01D37119EEC14AEB6FF67AACF3FC8D6AC9775B905ED07AAE51F23F50D`
SHA512 | `882025415544DBD1B195B3856580A768D4107E386F6D5011EB3411BB2C0D6E2BF588CB1AF12959C5C340E373B5251D8365984CC1D4C005B34E0C280A9D6EF8A7`
SSDEEP | `6144:tZYpLV+rpvIpScucSCloq8wf1j4Z6bBPHislwC7TGC:tZYtCpvIpScucSC8wfQ6d/ix`
IMP | `655A7015F0262253899C020FF7A9E6C6`
PESHA1 | `F24A81CA20B8F1023E0A0BCA7401D1808DBFFEB0`
PE256 | `46E8CC10FF7C96934D8B3E7EA6B949E7327822549CCCF020F3A54FE78067D1EF`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\ie4uinit.exe.mui | File
(RW-)   C:\Windows\System32 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_5.82.22000.1_none_271a8fad6a2d1b1e | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\ADVAPI32.dll |
C:\WINDOWS\system32\ie4uinit.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IE4UINIT.EXE.MUI
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.22000.1 (WinBuild.160101.0800)
* Product Version: 11.00.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/7e258c54a58002c64ca0a951a48abf754a58ebcd8cb8777e74ef76b530d13db4/detection


## Possible Misuse

*The following table contains possible examples of `ie4uinit.exe` being misused. While `ie4uinit.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `Name: Ie4uinit.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Command: ie4uinit.exe -BaseSettings`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `Description: Executes commands from a specially prepared ie4uinit.inf file.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Path: c:\windows\system32\ie4uinit.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- Path: c:\windows\sysWOW64\ie4uinit.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ie4uinit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ie4uinit.yml) | `- IOC: ie4uinit.exe loading a inf file from outside %windir%`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`IE4UINIT.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


