---
title: wmiclnt.dll | WMI Client API
excerpt: What is wmiclnt.dll?
---

# wmiclnt.dll 

* File Path: `C:\Windows\SysWOW64\wmiclnt.dll`
* Description: WMI Client API

## Hashes

Type | Hash
-- | --
MD5 | `3A0762930543084DAF64E61A0CF69923`
SHA1 | `ADA71C18C8FEF33D017501632B6DF014C947FA6A`
SHA256 | `DD53D6079F8C1DAC64EC1A0BA31A99CCDB2173F455A68AD82636A5C2290580D8`
SHA384 | `F730D13EC1723C0B9257DBEBD82CD5F4A70E9AC15F27E5EC3872DCB4AE770817EC23F100D19130BB9C3C4ECF24A5088B`
SHA512 | `5771A2F1FD802366839701DB04F7D5FDEB8C66FD6BE2CB4358D6F4B144419928BE9F42835368B7B58CA09372108A8D57DCF5815FA98ACF11151ACDD7EE3FE000`
SSDEEP | `768:cCmLuwKotVsLTWyR2+z7erQ8wRK4AKpxw4lWUswIqNB7+BHsaJ:WLRltuHWUNXRxT5wUpIqNh+BHsaJ`
IMP | `C224C175C29071387DE0035776E40940`
PESHA1 | `BA97C04D6882F6E9C012D644738EF8181E0381CA`
PE256 | `C3A697AB8EBB8F496B11A511BACC451A9559E2D9EC2133389BA4C9D56A11D14A`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WmiCloseBlock` | 1 | Exported Function
`WmiSetSingleInstanceW` | 27 | Exported Function
`WmiSetSingleInstanceA` | 26 | Exported Function
`WmiReceiveNotificationsW` | 25 | Exported Function
`WmiReceiveNotificationsA` | 24 | Exported Function
`WmiQuerySingleInstanceW` | 23 | Exported Function
`WmiQuerySingleInstanceMultipleW` | 22 | Exported Function
`WmiQuerySingleInstanceMultipleA` | 21 | Exported Function
`WmiQuerySingleInstanceA` | 20 | Exported Function
`WmiQueryGuidInformation` | 19 | Exported Function
`WmiQueryAllDataW` | 18 | Exported Function
`WmiQueryAllDataMultipleW` | 17 | Exported Function
`WmiQueryAllDataMultipleA` | 16 | Exported Function
`WmiSetSingleItemA` | 28 | Exported Function
`WmiQueryAllDataA` | 15 | Exported Function
`WmiNotificationRegistrationW` | 13 | Exported Function
`WmiNotificationRegistrationA` | 12 | Exported Function
`WmiMofEnumerateResourcesW` | 11 | Exported Function
`WmiMofEnumerateResourcesA` | 10 | Exported Function
`WmiFreeBuffer` | 9 | Exported Function
`WmiFileHandleToInstanceNameW` | 8 | Exported Function
`WmiFileHandleToInstanceNameA` | 7 | Exported Function
`WmiExecuteMethodW` | 6 | Exported Function
`WmiExecuteMethodA` | 5 | Exported Function
`WmiEnumerateGuids` | 4 | Exported Function
`WmiDevInstToInstanceNameW` | 3 | Exported Function
`WmiDevInstToInstanceNameA` | 2 | Exported Function
`WmiOpenBlock` | 14 | Exported Function
`WmiSetSingleItemW` | 29 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/dd53d6079f8c1dac64ec1a0ba31a99ccdb2173f455a68ad82636a5c2290580d8/detection/


## Possible Misuse

*The following table contains possible examples of `wmiclnt.dll` being misused. While `wmiclnt.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\wmiclnt.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


