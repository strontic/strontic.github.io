---
title: container.dll | Windows Containers
excerpt: What is container.dll?
---

# container.dll 

* File Path: `C:\Windows\SysWOW64\container.dll`
* Description: Windows Containers

## Hashes

Type | Hash
-- | --
MD5 | `C259DD10A8EA13A92F822DDBCB9F1E97`
SHA1 | `7FE16DA6CEAAFC6BEDB61BF2D2B6279616753B21`
SHA256 | `BBDFBA0AE806E43A3A37B87323A96F3115EE46EF0AA6794273B20D0CB06EF333`
SHA384 | `5175DAB95B5073D1A2E4E8822C0421F192B4384501CFA920FE7BE4C88F942C1EC2959B41ADDAB74F8A5141724B45FD13`
SHA512 | `0E9687088B911750B1B90C0476651AE37A661385551257584F48F3440AA9D45498EFD0D4CAA67603692A40D0F80A1CAB3DE7B0ADB20F26326EDCF55BCD09002A`
SSDEEP | `3072:2tyo7NPKEuepLcfLYVB9cnxq+6WuEd2WQSgRNf6/YAW96AUKo:2H7VB3l9VB9oo+6pi2Wt8igAW96AJ`
IMP | `202B54AEA5D993FA856ABC5822BBF96E`
PESHA1 | `5699B79484EF0B5A8E828FA6BD728C3E0E634D9D`
PE256 | `34E39CE57B3C942C03E4AB698E59C1A7949468D84BF9BD55C5F02519A1BAB7B1`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`container::GetComRegistryRoot` | 4 | Exported Function
`container::IsContainerQuiescent` | 8 | Exported Function
`container::AddRuntimeVirtualKeysToContainer` | 1 | Exported Function
`container::LaunchApplicationContainer` | 9 | Exported Function
`container::ShutdownAppContainer` | 14 | Exported Function
`_WcWaitForContainerTerminationNotification@4` | 32 | Exported Function
`container::RegisterForContainerTerminationNotification` | 11 | Exported Function
`container::GetContainerIdentifierString` | 5 | Exported Function
`container::ReleaseContainerTerminationNotification` | 12 | Exported Function
`container::LaunchContainer` | 10 | Exported Function
`container::WaitForContainerTerminationNotification` | 15 | Exported Function
`container::SetRegistryFlushState` | 13 | Exported Function
`DefinitionFile::Container` | 3 | Exported Function
`container::CleanupContainer` | 2 | Exported Function
`std::allocator` | 7 | Exported Function
`std::allocator` | 6 | Exported Function
`_WcGetComRegistryRoot@8` | 21 | Exported Function
`_WcDestroyDescription@4` | 20 | Exported Function
`_WcGetContainerObjectRootPath@12` | 23 | Exported Function
`_WcGetContainerIdentifier@8` | 22 | Exported Function
`_WcCleanupContainer@8` | 17 | Exported Function
`_WcAddRuntimeVirtualKeysToContainer@12` | 16 | Exported Function
`_WcCreateDescriptionFromXml@8` | 19 | Exported Function
`_WcCreateContainer@16` | 18 | Exported Function
`_WcReleaseContainerTerminationNotification@4` | 29 | Exported Function
`_WcRegisterForContainerTerminationNotification@16` | 28 | Exported Function
`_WcShutdownAppContainer@4` | 31 | Exported Function
`_WcSetRegistryFlushState@8` | 30 | Exported Function
`_WcIsContainerQuiescent@8` | 25 | Exported Function
`_WcGetContainerRegistryRootPath@16` | 24 | Exported Function
`_WcLaunchContainer@4` | 27 | Exported Function
`_WcLaunchApplicationContainer@16` | 26 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: container.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.292 (WinBuild.160101.0800)
* Product Version: 10.0.19041.292
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/bbdfba0ae806e43a3a37b87323a96f3115ee46ef0aa6794273b20d0cb06ef333/detection/


## Possible Misuse

*The following table contains possible examples of `container.dll` being misused. While `container.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [turla-outlook.yar](https://github.com/eset/malware-ioc/blob/master/turla/turla-outlook.yar) | `$s17 = "cmd container" ascii wide` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-05-01/Atomic_Friday.md) | Resolved Collection Methods: Group, Sessions, Trusts, ACL, ObjectProps, LocalGroups, SPNTargets, Container | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - T1525 Implant Container Image [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - T1525 Implant Container Image [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/linux-matrix.md) | \|  \|  \| Implant Container Image [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Trap](../../T1546.005/T1546.005.md) \| [HISTCONTROL](../../T1562.003/T1562.003.md) \| Steal Application Access Token [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [System Information Discovery](../../T1082/T1082.md) \|  \| [Screen Capture](../../T1113/T1113.md) \|  \| Multi-Stage Channels [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Stored Data Manipulation [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| Implant Container Image [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Launch Daemon](../../T1543.004/T1543.004.md) \| Extra Window Memory Injection [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Steal Web Session Cookie [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | if (!(Test-Path C:\Users\Public\Libraries\yanki -PathType Container)) { | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_project_sauron.yara](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_project_sauron.yara) | description = "Rule to detect ProjectSauron samples encrypted container" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s5 = "A new key container has been created." | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


