---
title: vds.exe | Virtual Disk Service
excerpt: What is vds.exe?
---

# vds.exe 

* File Path: `C:\Windows\system32\vds.exe`
* Description: Virtual Disk Service

## Hashes

Type | Hash
-- | --
MD5 | `E845A556FC6574216078A02FE53189C1`
SHA1 | `EEFD84BCBB943CDD21B292FA5F5A811E3C4CC711`
SHA256 | `9CECFC7977BAA23A840F987A28813227BAB3F2DFDF1D571B51327107B5AA8CE2`
SHA384 | `D993646D5A6F5EB71A529F3CDEBB15438E7E09A189B55DCFB52253EC6A7BFC29DAA9D755E6438793E1CF14D8411F8A92`
SHA512 | `055C28953FA8CA1E7DF848EA2048CA6D02232A84C71F79DCB47820B9AAE7ABB758170DB940845CE00474A23E11D7D29AB51C6B463B9FA9643DCE9ABC868FDA47`
SSDEEP | `6144:1MPs1dwUXYhQqD2TkbqEXfYmjHc+ZDcaysxbhH/TLhmhDnlIn+i:3yQqD2ufP8+V9L4Ns`
IMP | `E2F880E899B5A451B9B030D7BCFA2EAE`
PESHA1 | `FB25BF4C73B7C3235769CB21BE9D2DD1C6A16537`
PE256 | `FC75597F41D1D0697771F34233E053703FDF8A60AC70BD97CF29CB01BC0ECFE3`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\ATL.DLL |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\OSUNINST.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SETUPAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\vds.exe |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vds.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/9cecfc7977baa23a840f987a28813227bab3f2dfdf1d571b51327107b5aa8ce2/detection/


## Possible Misuse

*The following table contains possible examples of `vds.exe` being misused. While `vds.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\vds.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


