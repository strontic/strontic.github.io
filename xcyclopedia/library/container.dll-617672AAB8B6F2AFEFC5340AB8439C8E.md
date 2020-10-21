---
title: container.dll | Windows Containers
excerpt: What is container.dll?
---

# container.dll 

* File Path: `C:\Windows\system32\container.dll`
* Description: Windows Containers

## Hashes

Type | Hash
-- | --
MD5 | `617672AAB8B6F2AFEFC5340AB8439C8E`
SHA1 | `C71B15704ED9DB80FA748DDEB5ED5C249F4ED7BB`
SHA256 | `D04200EDD7DE6013727793BDD34B63E590D7A9625C4A669B78DC586B0F6181CF`
SHA384 | `283BE305E91719AB530EE0A226ADDDE17FDAB4CDD76B8FCC9F647381BF65F12AD333B6CF9D55C8339D60DF3FC3CDC260`
SHA512 | `43188DD6CC45F9022A74B949630BF944B371BC001ACF813833E835638C030C5663A53CF9F883115088CCEF29D598C6419488C9CFA1644E07C8C63E2B0C6A5EA8`
SSDEEP | `6144:AxILBhqgbtcwLnKpoBOkEZI60PZrlanmxBF5:Mgh/ZBVHllaof`
IMP | `85E45176550F91AD0A4D7551117ABBEF`
PESHA1 | `63FEA546818AA4C32F43E89A99C010F226A6AF8C`
PE256 | `0417C0CAA2744BC94589C99AE175E225E36A37FEE0DEDCE11B4B360E07B2B232`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WcGetContainerIdentifier` | 22 | Exported Function
`WcGetComRegistryRoot` | 21 | Exported Function
`WcGetContainerRegistryRootPath` | 24 | Exported Function
`WcGetContainerObjectRootPath` | 23 | Exported Function
`WcCreateContainer` | 18 | Exported Function
`WcCleanupContainer` | 17 | Exported Function
`WcDestroyDescription` | 20 | Exported Function
`WcCreateDescriptionFromXml` | 19 | Exported Function
`WcSetRegistryFlushState` | 30 | Exported Function
`WcReleaseContainerTerminationNotification` | 29 | Exported Function
`WcWaitForContainerTerminationNotification` | 32 | Exported Function
`WcShutdownAppContainer` | 31 | Exported Function
`WcLaunchApplicationContainer` | 26 | Exported Function
`WcIsContainerQuiescent` | 25 | Exported Function
`WcRegisterForContainerTerminationNotification` | 28 | Exported Function
`WcLaunchContainer` | 27 | Exported Function
`LaunchApplicationContainer` | 9 | Exported Function
`GetComRegistryRoot` | 4 | Exported Function
`CleanupContainer` | 2 | Exported Function
`AddRuntimeVirtualKeysToContainer` | 1 | Exported Function
`GetContainerIdentifierString` | 5 | Exported Function
`ShutdownAppContainer` | 14 | Exported Function
`IsContainerQuiescent` | 8 | Exported Function
`RegisterForContainerTerminationNotification` | 11 | Exported Function
`SetRegistryFlushState` | 13 | Exported Function
`ReleaseContainerTerminationNotification` | 12 | Exported Function
`WcAddRuntimeVirtualKeysToContainer` | 16 | Exported Function
`WaitForContainerTerminationNotification` | 15 | Exported Function
`allocator` | 6 | Exported Function
`Container` | 3 | Exported Function
`LaunchContainer` | 10 | Exported Function
`allocator` | 7 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/d04200edd7de6013727793bdd34b63e590d7a9625c4a669b78dc586b0f6181cf/detection/


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


