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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_WcAddRuntimeVirtualKeysToContainer@12` | 16 (0x10) | Exported Function | 0x1000f230 | 0x0000f230
`void __stdcall container::ReleaseContainerTerminationNotification(struct _WC_CONTAINER_NOTIFICATION *)` | 12 (0xc) | Exported Function | 0x10023d50 | 0x00023d50
`void __stdcall container::LaunchContainer(void *)` | 10 (0xa) | Exported Function | 0x1000fbb0 | 0x0000fbb0
`void __stdcall container::GetRegistryRootPath(void *,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > const &,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)` | 7 (0x7) | Exported Function | 0x1000ff90 | 0x0000ff90
`void __stdcall container::GetContainerObjectRootPath(void *,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)` | 6 (0x6) | Exported Function | 0x1000fff0 | 0x0000fff0
`void __stdcall container::CreateContainer(void *,struct container::DefinitionFile::Container const &,bool,void *)` | 3 (0x3) | Exported Function | 0x1000f3e0 | 0x0000f3e0
`void __stdcall container::CleanupContainer(void *,unsigned short const *)` | 2 (0x2) | Exported Function | 0x1000f330 | 0x0000f330
`void __stdcall container::AddRuntimeVirtualKeysToContainer(void *,unsigned long,struct _WC_VKEY_INFO *)` | 1 (0x1) | Exported Function | 0x1000fda0 | 0x0000fda0
`void * __stdcall container::LaunchApplicationContainer(void *,unsigned short const *,unsigned long)` | 9 (0x9) | Exported Function | 0x1000f8a0 | 0x0000f8a0
`void * __stdcall container::GetComRegistryRoot(void *)` | 4 (0x4) | Exported Function | 0x1000fd70 | 0x0000fd70
`unsigned char __stdcall container::IsContainerQuiescent(void *)` | 8 (0x8) | Exported Function | 0x1000f820 | 0x0000f820
`struct _WC_CONTAINER_NOTIFICATION * __stdcall container::RegisterForContainerTerminationNotification(void *,void (__stdcall*)(void *,enum _WC_CONTAINER_TERMINATION_REASON,struct _WC_CONTAINER_NOTIFICATION *,void *),void *)` | 11 (0xb) | Exported Function | 0x10023bd0 | 0x00023bd0
`class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > __stdcall container::GetContainerIdentifierString(void *)` | 5 (0x5) | Exported Function | 0x1000ff30 | 0x0000ff30
`bool __stdcall container::ShutdownAppContainer(void *)` | 14 (0xe) | Exported Function | 0x1000fcc0 | 0x0000fcc0
`_WcWaitForContainerTerminationNotification@4` | 32 (0x20) | Exported Function | 0x10023bb0 | 0x00023bb0
`_WcShutdownAppContainer@4` | 31 (0x1f) | Exported Function | 0x1000f2d0 | 0x0000f2d0
`_WcSetRegistryFlushState@8` | 30 (0x1e) | Exported Function | 0x1000f280 | 0x0000f280
`_WcReleaseContainerTerminationNotification@4` | 29 (0x1d) | Exported Function | 0x10023b90 | 0x00023b90
`_WcRegisterForContainerTerminationNotification@16` | 28 (0x1c) | Exported Function | 0x10023b40 | 0x00023b40
`_WcLaunchContainer@4` | 27 (0x1b) | Exported Function | 0x1000f1e0 | 0x0000f1e0
`_WcLaunchApplicationContainer@16` | 26 (0x1a) | Exported Function | 0x1000f180 | 0x0000f180
`_WcIsContainerQuiescent@8` | 25 (0x19) | Exported Function | 0x1000f130 | 0x0000f130
`_WcGetContainerRegistryRootPath@16` | 24 (0x18) | Exported Function | 0x1000efc0 | 0x0000efc0
`_WcGetContainerObjectRootPath@12` | 23 (0x17) | Exported Function | 0x1000f090 | 0x0000f090
`_WcGetContainerIdentifier@8` | 22 (0x16) | Exported Function | 0x1000ef70 | 0x0000ef70
`_WcGetComRegistryRoot@8` | 21 (0x15) | Exported Function | 0x1000ef20 | 0x0000ef20
`_WcDestroyDescription@4` | 20 (0x14) | Exported Function | 0x1001cb50 | 0x0001cb50
`_WcCreateDescriptionFromXml@8` | 19 (0x13) | Exported Function | 0x1001c8f0 | 0x0001c8f0
`_WcCreateContainer@16` | 18 (0x12) | Exported Function | 0x1000eeb0 | 0x0000eeb0
`_WcCleanupContainer@8` | 17 (0x11) | Exported Function | 0x1000ee60 | 0x0000ee60
`void __stdcall container::SetRegistryFlushState(void *,unsigned char)` | 13 (0xd) | Exported Function | 0x1000fc30 | 0x0000fc30
`void __stdcall container::WaitForContainerTerminationNotification(struct _WC_CONTAINER_NOTIFICATION *)` | 15 (0xf) | Exported Function | 0x10023e70 | 0x00023e70


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


