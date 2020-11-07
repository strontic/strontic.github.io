---
title: MicrosoftEdge.exe | Microsoft Edge
excerpt: What is MicrosoftEdge.exe?
---

# MicrosoftEdge.exe 

* File Path: `C:\Windows\SystemApps\Microsoft.MicrosoftEdge_8wekyb3d8bbwe\MicrosoftEdge.exe`
* Description: Microsoft Edge

## Hashes

Type | Hash
-- | --
MD5 | `158227E21FCA62A3EA27577479C0E8B2`
SHA1 | `C2316DF0D5077059A4EAEB50269D4A9745F38FF9`
SHA256 | `E04233F34C27E0DE1E3B2A47441F79A93D84638864FC7311F0B6145F31957046`
SHA384 | `BD8E3A689B1DFBA919FBD66D426BCEEE7460E4B94EADED0705EC5E2E9701BACD0C398113E667E605F732F1EE12092A32`
SHA512 | `0A327F1112392D04CD200A703EAC705409E85B77F4A39A8B27FF1F2C5DC2129B681BCAF2963927CC394D4B373D2543354A3320AB6B3A9EA19CC7290C75007575`
SSDEEP | `98304:WtxCRZFUD2jyv6GPPlqFjKOWmY5BGuaGmHJkOMFXLI7BHLyOQZ4mSvTKo5zI1eOB:MxCRI2jyvnPlyWONY5BGua0x4rI`
IMP | `9088956C5EF1E416B52CA0AE3DD80358`
PESHA1 | `600E900029654A486F36D844A9D900AF76AAE791`
PE256 | `C7EB0F22FA3B50914803622810B33265EF8958DBDC02D36792372A578E45940C`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\apphelp.dll |
C:\Windows\System32\combase.dll |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\netutils.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\SYSTEM32\wincorlib.DLL |
C:\Windows\SYSTEM32\wkscli.dll |
C:\Windows\SystemApps\Microsoft.MicrosoftEdge_8wekyb3d8bbwe\MicrosoftEdge.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftEdge.exe
* Product Name: Microsoft Edge
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.546 (WinBuild.160101.0800)
* Product Version: 11.00.19041.546
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/e04233f34c27e0de1e3b2a47441f79a93d84638864fc7311f0b6145f31957046/detection


## Possible Misuse

*The following table contains possible examples of `MicrosoftEdge.exe` being misused. While `MicrosoftEdge.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\microsoftedge.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `- MicrosoftEdge.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1176.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1176/T1176.md) | 1. Navigate to https://microsoftedge.microsoft.com/addons/detail/fjnehcbecaggobjholekjijaaekbnlgj | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


