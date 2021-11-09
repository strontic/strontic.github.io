---
title: credwiz.exe | Credential Backup and Restore Wizard
excerpt: What is credwiz.exe?
---

# credwiz.exe 

* File Path: `C:\WINDOWS\system32\credwiz.exe`
* Description: Credential Backup and Restore Wizard

## Screenshot

![credwiz.exe](screenshots/credwiz.exe-A6001253D5FD839243DB624A2735F188-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `17EE62A136D2EAAF0B09D05B9F2E3259`
SHA1 | `0C317D0D099898478E3ED61C8D9064F8C1412C0D`
SHA256 | `191E5C8244E8B46C8A3394C05AA8D3F58596A62438F6481208B0FDBFDC0DF9C6`
SHA384 | `544D40942697AFC4FAE7977D05F3709C2BD56B586A2051D5BCE422B6ACDF8F76D425DEAC2392B2A95B1FD3F640D35313`
SHA512 | `B5753002E41357FBFECF4A66A91BDC5CDAD22E3731A5B5F294B808C69EEA73504F7C38358A015FA8692C67C722F691E4E1D0CF2DA8BD39CF41F022EA432933C9`
SSDEEP | `768:A5thaDZCWEZ32Vno+T+JgxtbRtB5JIFDgEVbW7UzUmZjta:A5thaDZCWEF4GeT4gEVbW0UmZjt`
IMP | `5C1347E346D7307E39B1CE7105402C7B`
PESHA1 | `8877FE87A173AB0695724D9BFD0E0AC6411FE96B`
PE256 | `2ECD5CB01E069733C292B0FF9A04661CB96FDCD873ACDA1DCA8F347A4138568B`

## Runtime Data

### Window Title:
Stored User Names and Passwords

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\credwiz.exe.mui | File
(R-D)   C:\Windows\System32\en-US\oleaccrc.dll.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(R-D)   C:\Windows\WinSxS\amd64_microsoft.windows.c..-controls.resources_6595b64144ccf1df_6.0.22000.1_en-us_6b887e04d8b70b4e\comctl32.dll.mui | File
(RW-)   C:\Windows\System32 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.c..-controls.resources_6595b64144ccf1df_6.0.22000.1_en-us_6b887e04d8b70b4e | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.22000.120_none_9d947278b86cc467 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\Windows\Theme1077709572 | Section
\Windows\Theme3461253685 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\ADVAPI32.dll |
C:\WINDOWS\system32\credwiz.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: credwiz.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/191e5c8244e8b46c8a3394c05aa8d3f58596a62438f6481208b0fdbfdc0df9c6/detection


## Possible Misuse

*The following table contains possible examples of `credwiz.exe` being misused. While `credwiz.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [badiis.yar](https://github.com/eset/malware-ioc/blob/master/badiis/badiis.yar) | `$s8 = "C:\\Windows\\System32\\credwiz.exe" ascii wide`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


