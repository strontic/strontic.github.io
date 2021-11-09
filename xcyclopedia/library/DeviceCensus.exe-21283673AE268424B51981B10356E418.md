---
title: DeviceCensus.exe | Device Census
excerpt: What is DeviceCensus.exe?
---

# DeviceCensus.exe 

* File Path: `C:\WINDOWS\system32\DeviceCensus.exe`
* Description: Device Census

## Hashes

Type | Hash
-- | --
MD5 | `21283673AE268424B51981B10356E418`
SHA1 | `4568E9B5132E970FE7B08A42304E9AC459CC4103`
SHA256 | `3747338D09D623C859B48AF7784CDB95783910675857CB49E061ED805A25905D`
SHA384 | `8A08BC1234A68F6A9FBE34510D1571BC4944F66E92308FBA977EE909E946B22BA5738B0CB189968C4061AE87E3A77E76`
SHA512 | `F8EB848801256367139BE73ACF2640A138D8D65E77276FD1687CFB40A50B162FC318A87049B2D28F740F57FA1E21EB8A8F5557C546AD8B01E51BCC278B3D2466`
SSDEEP | `768:sjBw8tBWX7ZyBId2l0VTP9/gKXLrYVT1Pt:6w8tBqyOM+VR4KXLrY3Pt`
IMP | `69755EB5A4F06F0B816F7B23B33E44E8`
PESHA1 | `7116337B35565321213128CEAEFB14716EE059AA`
PE256 | `834C2ECE0E81EB27C0628B517DB4EAC745C78617F5BEAC8CCC997B2C2116F5A2`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\advapi32.dll |
C:\WINDOWS\system32\AEPIC.dll |
C:\WINDOWS\system32\bcrypt.dll |
C:\WINDOWS\SYSTEM32\cfgmgr32.dll |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\System32\CRYPT32.dll |
C:\WINDOWS\system32\dcntel.dll |
C:\WINDOWS\system32\DeviceCensus.exe |
C:\WINDOWS\system32\IPHLPAPI.DLL |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\logoncli.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\system32\ncrypt.dll |
C:\WINDOWS\system32\netutils.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\OLEAUT32.dll |
C:\WINDOWS\SYSTEM32\powrprof.dll |
C:\WINDOWS\System32\RPCRT4.dll |
C:\WINDOWS\System32\sechost.dll |
C:\WINDOWS\System32\shcore.dll |
C:\WINDOWS\system32\SspiCli.dll |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\system32\WINHTTP.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DeviceCensus.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3747338d09d623c859b48af7784cdb95783910675857cb49e061ed805a25905d/detection


## Possible Misuse

*The following table contains possible examples of `DeviceCensus.exe` being misused. While `DeviceCensus.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\DeviceCensus.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_win_reg_telemetry_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_win_reg_telemetry_persistence.yml) | `- '\system32\DeviceCensus.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


