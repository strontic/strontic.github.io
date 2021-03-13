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
MD5 | `CBF4F868E857AB7E4817B7E3D70D2C88`
SHA1 | `CAD26985D73070C6CFC05ED79CDA22E1DAC4B5C3`
SHA256 | `55B144D3BDD0C14FF810FA295CA79E08A1E418EE3BB46EAB78982EEB0BB7816F`
SHA384 | `39979B65CAB17BDCF1F14686B6B498006B3D4F4C67FEA936FC01ACF67D926E2EAF88A4684747C9E3CA3D9C7C8A2EE064`
SHA512 | `AF3FF9ACCED9A52C18E2560D278651E1F266D101D674EEFC91EF50FCC293052A4C82BDB69A1CBF9344DC6872A1461A0716BFF22690D183E86EF5859352207D60`
SSDEEP | `12288:EShVuOWudUdWi6MiVA/NNxssBUDOo5DaHZFU:5hViuKdWMwA/j6AUyo5DaU`
IMP | `356C5FB039EB7424A518F132A23D3232`
PESHA1 | `014706757B58F7CC9E2D82EBAAC8E7C3E46B66C4`
PE256 | `6210CB17011D8F6DC5A4DE022918B08CBD37091B378E86877FD634B431118DFF`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/55b144d3bdd0c14ff810fa295ca79e08a1e418ee3bb46eab78982eeb0bb7816f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\audiodg.exe](audiodg.exe-8BBBC4F638F4822D97AA3297DE8D6F64.md) | 41

## Possible Misuse

*The following table contains possible examples of `audiodg.exe` being misused. While `audiodg.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


