---
title: audiodg.exe | Windows Audio Device Graph Isolation 
excerpt: What is audiodg.exe?
---

# audiodg.exe 

* File Path: `C:\Windows\system32\audiodg.exe`
* Description: Windows Audio Device Graph Isolation 

## Hashes

Type | Hash
-- | --
MD5 | `B40EDC28104EB97E7483E4801BA2ABC4`
SHA1 | `FFFEA65EBD6FB6B02637ADA0DA1A2C285FC66718`
SHA256 | `1ADD3048519CD7FC7AD7C1D2F6F41DADE1D87BBB0C26C5A25C20A955C20F8ABD`
SHA384 | `551CEFD17709C9782459748E61024EB8CA0C476DD7D699C760E8D1DF61058F55F8CCB12D9D1C7B539CB4648D10A51E4B`
SHA512 | `C26E0BA42D33BF24CE68991366D292DCC5F03A4666B2CB18A152313A4A11B40092D043A003ACF4D8FE1BC4781AB68F1EB28FFCDBE95627FA02A6442A7142883A`
SSDEEP | `6144:SJB2xOW9kndARb4uxLARp135tF+BlnWN/REH9nOQRY7JNBK/dT:SJBQjkndWxLy3rF6WREH9nO/J+`
IMP | `356C5FB039EB7424A518F132A23D3232`
PESHA1 | `99A5A1A023270A41942F44D749F3D11F93C5F9C6`
PE256 | `6C2052666F9B69D35792B8887A6A293948EB477083BAA62EF1D6E43B788263E7`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\audiodg.exe |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\DEVOBJ.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MMDevAPI.DLL |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: audioadg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/1add3048519cd7fc7ad7c1d2f6f41dade1d87bbb0c26c5a25c20a955c20f8abd/detection


## Possible Misuse

*The following table contains possible examples of `audiodg.exe` being misused. While `audiodg.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


