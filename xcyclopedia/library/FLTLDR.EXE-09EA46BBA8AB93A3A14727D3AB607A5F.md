---
title: FLTLDR.EXE | Microsoft Filter Loader
excerpt: What is FLTLDR.EXE?
---

# FLTLDR.EXE 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesCommonX86\Microsoft Shared\OFFICE16\FLTLDR.EXE`
* Description: Microsoft Filter Loader

## Hashes

Type | Hash
-- | --
MD5 | `09EA46BBA8AB93A3A14727D3AB607A5F`
SHA1 | `CC3918F3D738E484A4301426CCCD8F9451C26598`
SHA256 | `E01B57219524BC8864C587543B3CC3954F608FC118CFD327916E92F6774BFBE5`
SHA384 | `B850B9F5F15E5128546C3EB4474625AAE97DA4447A52FCAE7954D8C53A459BE4FD46ABEF5BDA6E18C6F60B0C26208D2F`
SHA512 | `075B09E56BC9FE2A52210901582A3960877222CF8398C3444D29EE99B1ECEC8DD5AE2B15EDB0F94F486363298A1B7E05FD71B682AC02AB8733413298EF104AB6`
SSDEEP | `6144:NzvRsmfIZoa3nFb6+Ef6SIHhvlHerF6Rw4XoBIJWQc7BPMJMGVKM75/uV:NzvR7IZF6nmvlHCOXoeQFPMWkKx`
IMP | `105349187086ED5ACDEE180D663B1EE3`
PESHA1 | `9AF9021E0470E9531C02187CC0396D841BAD5807`
PE256 | `C10C2BCEFA23D610AF7DAEA7A976310E3EBE8F8A11CD48E94D9DB6286320C9D8`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesCommonX86\Microsoft Shared\OFFICE16\FLTLDR.EXE |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fltldr.exe
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20474
* Product Version: 16.0.12527.20474
* Language: Language Neutral
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/e01b57219524bc8864c587543b3cc3954f608fc118cfd327916e92f6774bfbe5/detection/


## Possible Misuse

*The following table contains possible examples of `FLTLDR.EXE` being misused. While `FLTLDR.EXE` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2017_0261.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2017_0261.yml) | `description: Detects Winword starting uncommon sub process FLTLDR.exe as used in exploits for CVE-2017-0261 and CVE-2017-0262` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2017_0261.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2017_0261.yml) | `Image: '*\FLTLDR.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


