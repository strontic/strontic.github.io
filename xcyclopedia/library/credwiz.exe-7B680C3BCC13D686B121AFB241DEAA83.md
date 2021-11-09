---
title: credwiz.exe | Credential Backup and Restore Wizard
excerpt: What is credwiz.exe?
---

# credwiz.exe 

* File Path: `C:\WINDOWS\SysWOW64\credwiz.exe`
* Description: Credential Backup and Restore Wizard

## Screenshot

![credwiz.exe](screenshots/credwiz.exe-A6001253D5FD839243DB624A2735F188-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `7B680C3BCC13D686B121AFB241DEAA83`
SHA1 | `778B73E4FCC1DC33CB1A216BE3EB41A1A7BEDBC4`
SHA256 | `995587B68C4CC076FFB95B80A3592CBF7FED6E24E1DAF3137014D7713F56FB9E`
SHA384 | `E9054A31561CDF32BEADB3021431092CBDE0BC77BDD37CC9626F636A3A3D80519FD8CBB5552491F3444F43F8C3B31757`
SHA512 | `31345F9BE4D51D2765A3C93DC0B161833C989BDDD80CA785D6CBFEB7A48DC8FAA47603130311F51384E5F1E68C9AC9EB1D843332EBDF5AF435AA6841A6C51D52`
SSDEEP | `768:N1sKY8nLQOIRuwqTKchAXeo+PjZENatS4xc:N1i8nLQ63mujZENC`
IMP | `17FCC5275158ADC0F36D83472CA0B06C`
PESHA1 | `6A60124254987938B9B2A4D486E9BAE3A8B4A9E3`
PE256 | `F9154394C96F7862B7A856F99AD35C3F2EBD79654E3B222802000E26C3F12DFD`

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
(R-D)   C:\Windows\WinSxS\x86_microsoft.windows.c..-controls.resources_6595b64144ccf1df_6.0.22000.1_en-us_b335b4dbed333454\comctl32.dll.mui | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\SysWOW64 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.c..-controls.resources_6595b64144ccf1df_6.0.22000.1_en-us_b335b4dbed333454 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.22000.120_none_e541a94fcce8ed6d | File
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
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\credwiz.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: credwiz.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/995587b68c4cc076ffb95b80a3592cbf7fed6e24e1daf3137014d7713f56fb9e/detection


## Possible Misuse

*The following table contains possible examples of `credwiz.exe` being misused. While `credwiz.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [badiis.yar](https://github.com/eset/malware-ioc/blob/master/badiis/badiis.yar) | `$s8 = "C:\\Windows\\System32\\credwiz.exe" ascii wide`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


