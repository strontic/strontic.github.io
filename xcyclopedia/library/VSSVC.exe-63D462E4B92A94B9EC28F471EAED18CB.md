---
title: VSSVC.exe | Microsoft Volume Shadow Copy Service
excerpt: What is VSSVC.exe?
---

# VSSVC.exe 

* File Path: `C:\WINDOWS\system32\VSSVC.exe`
* Description: Microsoft Volume Shadow Copy Service

## Hashes

Type | Hash
-- | --
MD5 | `63D462E4B92A94B9EC28F471EAED18CB`
SHA1 | `3D5ADEB34E1324EC939E155AB91C969031EF83EF`
SHA256 | `5185EF79C627A10B72B5C37728410C223D648CB20E9CFA47677F7E97062FCAF2`
SHA384 | `E16C7BFF7998B036CE2244B8334D3A1878E162CEB271B020C2D46D1A251CF77798122A8842B8FDFF4AA3D0C0E19FE3A3`
SHA512 | `8EA6E709D966D1D2C81613DB861662255A014D8CA3DEC924C2014C9F47FD99AB39BC4AB38E57E8E2E9D980C3776B241D15EB470524181D9D40DA05543F6BEADA`
SSDEEP | `24576:1k9XqC3eDGfcNwpmVvatQ4XRHzFhyPJ9w6:e9XqCuDMcNImVvyXRncJK6`
IMP | `93C089C8EE9E20F6226E43FA4349854A`
PESHA1 | `D36ED37EC55A9887ED0E2EC215BDC24306BAF7F7`
PE256 | `EF50A2E6887B74D306D32658C6403FB165092077608798C43A09A2AB6702A8CA`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\VSSVC.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VSSVC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/5185ef79c627a10b72b5c37728410c223d648cb20e9cfa47677f7e97062fcaf2/detection


## Possible Misuse

*The following table contains possible examples of `VSSVC.exe` being misused. While `VSSVC.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_vssaudit_secevent_source_registration.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_vssaudit_secevent_source_registration.yml) | `- Legitimate use of VSSVC. Maybe backup operations. It would usually be done by C:\Windows\System32\VSSVC.exe.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\vssvc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- '\vssvc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\vssvc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


