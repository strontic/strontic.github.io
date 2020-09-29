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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`bool __cdecl container::ShutdownAppContainer(void * __ptr64)` | 14 (0xe) | Exported Function | 0x000000018000e360 | 0x0000e360
`WcSetRegistryFlushState` | 30 (0x1e) | Exported Function | 0x000000018000d1f0 | 0x0000d1f0
`WcReleaseContainerTerminationNotification` | 29 (0x1d) | Exported Function | 0x000000018002cb20 | 0x0002cb20
`WcRegisterForContainerTerminationNotification` | 28 (0x1c) | Exported Function | 0x000000018002caf0 | 0x0002caf0
`WcLaunchContainer` | 27 (0x1b) | Exported Function | 0x000000018000d1b0 | 0x0000d1b0
`WcLaunchApplicationContainer` | 26 (0x1a) | Exported Function | 0x000000018000d180 | 0x0000d180
`WcIsContainerQuiescent` | 25 (0x19) | Exported Function | 0x000000018000d150 | 0x0000d150
`WcGetContainerRegistryRootPath` | 24 (0x18) | Exported Function | 0x000000018000cfb0 | 0x0000cfb0
`WcGetContainerObjectRootPath` | 23 (0x17) | Exported Function | 0x000000018000d090 | 0x0000d090
`WcGetContainerIdentifier` | 22 (0x16) | Exported Function | 0x000000018000cf80 | 0x0000cf80
`WcGetComRegistryRoot` | 21 (0x15) | Exported Function | 0x000000018000cf50 | 0x0000cf50
`WcDestroyDescription` | 20 (0x14) | Exported Function | 0x0000000180022650 | 0x00022650
`WcCreateDescriptionFromXml` | 19 (0x13) | Exported Function | 0x0000000180022240 | 0x00022240
`WcCreateContainer` | 18 (0x12) | Exported Function | 0x000000018000cf20 | 0x0000cf20
`WcCleanupContainer` | 17 (0x11) | Exported Function | 0x000000018000cf00 | 0x0000cf00
`WcAddRuntimeVirtualKeysToContainer` | 16 (0x10) | Exported Function | 0x000000018000d1d0 | 0x0000d1d0
`void __cdecl container::WaitForContainerTerminationNotification(struct _WC_CONTAINER_NOTIFICATION * __ptr64)` | 15 (0xf) | Exported Function | 0x000000018002d010 | 0x0002d010
`void __cdecl container::SetRegistryFlushState(void * __ptr64,unsigned char)` | 13 (0xd) | Exported Function | 0x000000018000e230 | 0x0000e230
`void __cdecl container::ReleaseContainerTerminationNotification(struct _WC_CONTAINER_NOTIFICATION * __ptr64)` | 12 (0xc) | Exported Function | 0x000000018002ce20 | 0x0002ce20
`void __cdecl container::LaunchContainer(void * __ptr64)` | 10 (0xa) | Exported Function | 0x000000018000df90 | 0x0000df90
`void __cdecl container::GetRegistryRootPath(void * __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > const & __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)` | 7 (0x7) | Exported Function | 0x000000018000e800 | 0x0000e800
`void __cdecl container::GetContainerObjectRootPath(void * __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)` | 6 (0x6) | Exported Function | 0x000000018000e890 | 0x0000e890
`void __cdecl container::CreateContainer(void * __ptr64,struct container::DefinitionFile::Container const & __ptr64,bool,void * __ptr64)` | 3 (0x3) | Exported Function | 0x000000018000d3a0 | 0x0000d3a0
`void __cdecl container::CleanupContainer(void * __ptr64,unsigned short const * __ptr64)` | 2 (0x2) | Exported Function | 0x000000018000d240 | 0x0000d240
`void __cdecl container::AddRuntimeVirtualKeysToContainer(void * __ptr64,unsigned long,struct _WC_VKEY_INFO * __ptr64)` | 1 (0x1) | Exported Function | 0x000000018000e4e0 | 0x0000e4e0
`void * __ptr64 __cdecl container::LaunchApplicationContainer(void * __ptr64,unsigned short const * __ptr64,unsigned long)` | 9 (0x9) | Exported Function | 0x000000018000db00 | 0x0000db00
`void * __ptr64 __cdecl container::GetComRegistryRoot(void * __ptr64)` | 4 (0x4) | Exported Function | 0x000000018000e4c0 | 0x0000e4c0
`unsigned char __cdecl container::IsContainerQuiescent(void * __ptr64)` | 8 (0x8) | Exported Function | 0x000000018000da70 | 0x0000da70
`struct _WC_CONTAINER_NOTIFICATION * __ptr64 __cdecl container::RegisterForContainerTerminationNotification(void * __ptr64,void (__cdecl*)(void * __ptr64,enum _WC_CONTAINER_TERMINATION_REASON,struct _WC_CONTAINER_NOTIFICATION * __ptr64,void * __ptr64),void * __ptr64)` | 11 (0xb) | Exported Function | 0x000000018002cb70 | 0x0002cb70
`class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > __cdecl container::GetContainerIdentifierString(void * __ptr64)` | 5 (0x5) | Exported Function | 0x000000018000e7a0 | 0x0000e7a0
`WcShutdownAppContainer` | 31 (0x1f) | Exported Function | 0x000000018000d210 | 0x0000d210
`WcWaitForContainerTerminationNotification` | 32 (0x20) | Exported Function | 0x000000018002cb40 | 0x0002cb40


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


