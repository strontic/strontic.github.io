---
title: MoUsoCoreWorker.exe | MoUSO Core Worker Process
excerpt: What is MoUsoCoreWorker.exe?
---

# MoUsoCoreWorker.exe 

* File Path: `C:\Windows\system32\MoUsoCoreWorker.exe`
* Description: MoUSO Core Worker Process

## Hashes

Type | Hash
-- | --
MD5 | `3EBF79D6BDDE4D6D566E460E11CBC497`
SHA1 | `B23A4B75408B417BD15BA3B029AFDCCA38A66D38`
SHA256 | `A4414D96BD4BA8E42656966171F2A78A7AE9F1D0700CDD04B0801C1DDAE38AC6`
SHA384 | `212525D83E5B02ABB2064A444F53786C3B46D1B8CFF2F60F92682385E8D35125CD2A044795DADAE64249F620D2581283`
SHA512 | `002DD7D3E948DD33EE0A5F4D9AB2A843433B1CC7F0F7A2D16BBCFF2BA01B8F42BB229156A77ACD95D71DBBDECF885E120BCD87900791390F48561F24E0981030`
SSDEEP | `24576:eXF1XqblSgUYKSy30vXbzSntzDRNhATmFPxtsG3Cp:GpqwnRvR/ATmhtC`
IMP | `39233DDAE71CD9D2B0CA5AA6FDD61054`
PESHA1 | `80285CC1EE43DD47009458C18CC194D3D738EE3B`
PE256 | `38C54805231D005D7308F81C688252AB829AE6B796C0A3544F451D86B1808512`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\system32\Cabinet.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\SYSTEM32\cryptsp.dll |
C:\Windows\system32\DMCmnUtils.dll |
C:\Windows\system32\dmiso8601utils.dll |
C:\Windows\system32\IPHLPAPI.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MoUsoCoreWorker.exe |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\system32\msvcp110_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\SYSTEM32\powrprof.dll |
C:\Windows\system32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\UMPDC.dll |
C:\Windows\system32\UpdatePolicy.dll |
C:\Windows\system32\winsqlite3.dll |
C:\Windows\System32\WINTRUST.dll |
C:\Windows\system32\XmlLite.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MoUSOCoreWorker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.610 (WinBuild.160101.0800)
* Product Version: 10.0.19041.610
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/a4414d96bd4ba8e42656966171f2a78a7ae9f1d0700cdd04b0801c1ddae38ac6/detection


## Possible Misuse

*The following table contains possible examples of `MoUsoCoreWorker.exe` being misused. While `MoUsoCoreWorker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\MoUsoCoreWorker.exe'  # c:\windows\System32\MoUsoCoreWorker.exe on win10 20H04 at least`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


