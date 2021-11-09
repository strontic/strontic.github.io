---
title: wlanext.exe | Windows Wireless LAN 802.11 Extensibility Framework
excerpt: What is wlanext.exe?
---

# wlanext.exe 

* File Path: `C:\WINDOWS\SysWOW64\wlanext.exe`
* Description: Windows Wireless LAN 802.11 Extensibility Framework

## Hashes

Type | Hash
-- | --
MD5 | `5405D8D5127542A11D11AF93EB6C8ABC`
SHA1 | `2CD558D9692CBD8C25ED7DBD2F189B39B0A4B355`
SHA256 | `F7596065864B49DBA802E5B909C63BD448E34281A82301A2F4FF535FBC710573`
SHA384 | `6BCBDCFCE843F28451DE88B9E7E0A2F284844B8A954F7C29C742812475CF7C437C053F394CEE7021C681CEF53531E453`
SHA512 | `DE99D5574D3C85917C8E3C867A350A2C7BF535563A89A6A1E571C2F40A36F23E6F6B251D44F2E5901CACE9E90C6F2A74A6130ED553D16599A00429C00A9B980B`
SSDEEP | `768:a8bS1n7mhY+dD+4ywalZQSn/u5Kw7KurZ5V78she0up/6M89q2BT5vbWSjTvaOOO:DbVyWD+4ydnSKw7KMnRMDO1bPjTvtO`
IMP | `F88E2FC6EB401AC86C31E7507B651798`
PESHA1 | `62AD9681C85CF8F6909464BEE76F8EA5E141D897`
PE256 | `2229317F9422527D24591D12A5D1C38836275F3744CCE110A840E57AA80F7705`

## Runtime Data

### Child Processes:
RdpSa.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\wlanext.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wlanext.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/f7596065864b49dba802e5b909c63bd448e34281a82301a2f4ff535fbc710573/detection


## Possible Misuse

*The following table contains possible examples of `wlanext.exe` being misused. While `wlanext.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\wlanext.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\wlanext.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


