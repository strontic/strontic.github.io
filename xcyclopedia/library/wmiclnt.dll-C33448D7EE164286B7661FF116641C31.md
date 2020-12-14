---
title: wmiclnt.dll | WMI Client API
excerpt: What is wmiclnt.dll?
---

# wmiclnt.dll 

* File Path: `C:\Windows\system32\wmiclnt.dll`
* Description: WMI Client API

## Hashes

Type | Hash
-- | --
MD5 | `C33448D7EE164286B7661FF116641C31`
SHA1 | `A87B5ED293BD65F2ECF48C7CA544DD485B1D2628`
SHA256 | `C13FD6A6E23241785E09329A9368D1101DABC7F4F8EA5AE9D9852C660E293540`
SHA384 | `444594E44D9817438891B2255BB52BB74A82A839499D7416E476807EEFA91EBC7102FB4F7F72F110559A0340E875BFE1`
SHA512 | `C212CB33FCA8EDA6DC60C770A39DE71EFACF6095885F5272F3F882D61D057B966975744C9AED3F0AE0298BB31FC0B031195722B6E0CB94814C251AE695C4F9B5`
SSDEEP | `768:skWNxLuwhmAqXim/HPepSKz8/Ixuzpw3/lXS+6k4lYUsgwqHWf+uWP1krfj:sJpuemAqXimnepZz8guzpw3/ZS+6nlYP`
IMP | `B48FE7A7A13036C7EFE1B88D7408A6F3`
PESHA1 | `6216C78D19E6CDA0A950D7546E45709C7108BFB9`
PE256 | `D0191F2EC0B9BCF5B7E72A0F79F45AB91ED8C1A30F48B5B2B426ABBF5319B110`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WmiQuerySingleInstanceA` | 20 | Exported Function
`WmiQuerySingleInstanceMultipleA` | 21 | Exported Function
`WmiQuerySingleInstanceMultipleW` | 22 | Exported Function
`WmiQueryGuidInformation` | 19 | Exported Function
`WmiQueryAllDataMultipleA` | 16 | Exported Function
`WmiQueryAllDataMultipleW` | 17 | Exported Function
`WmiQueryAllDataW` | 18 | Exported Function
`WmiSetSingleInstanceW` | 27 | Exported Function
`WmiSetSingleItemA` | 28 | Exported Function
`WmiSetSingleItemW` | 29 | Exported Function
`WmiSetSingleInstanceA` | 26 | Exported Function
`WmiQuerySingleInstanceW` | 23 | Exported Function
`WmiReceiveNotificationsA` | 24 | Exported Function
`WmiReceiveNotificationsW` | 25 | Exported Function
`WmiQueryAllDataA` | 15 | Exported Function
`WmiExecuteMethodA` | 5 | Exported Function
`WmiExecuteMethodW` | 6 | Exported Function
`WmiFileHandleToInstanceNameA` | 7 | Exported Function
`WmiEnumerateGuids` | 4 | Exported Function
`WmiCloseBlock` | 1 | Exported Function
`WmiDevInstToInstanceNameA` | 2 | Exported Function
`WmiDevInstToInstanceNameW` | 3 | Exported Function
`WmiNotificationRegistrationA` | 12 | Exported Function
`WmiNotificationRegistrationW` | 13 | Exported Function
`WmiOpenBlock` | 14 | Exported Function
`WmiMofEnumerateResourcesW` | 11 | Exported Function
`WmiFileHandleToInstanceNameW` | 8 | Exported Function
`WmiFreeBuffer` | 9 | Exported Function
`WmiMofEnumerateResourcesA` | 10 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmiclnt.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/c13fd6a6e23241785e09329a9368d1101dabc7f4f8ea5ae9d9852c660e293540/detection/


## Possible Misuse

*The following table contains possible examples of `wmiclnt.dll` being misused. While `wmiclnt.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\wmiclnt.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


