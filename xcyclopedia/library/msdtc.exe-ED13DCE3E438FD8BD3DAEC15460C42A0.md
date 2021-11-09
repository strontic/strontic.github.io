---
title: msdtc.exe | Microsoft Distributed Transaction Coordinator Service
excerpt: What is msdtc.exe?
---

# msdtc.exe 

* File Path: `C:\WINDOWS\system32\msdtc.exe`
* Description: Microsoft Distributed Transaction Coordinator Service

## Hashes

Type | Hash
-- | --
MD5 | `ED13DCE3E438FD8BD3DAEC15460C42A0`
SHA1 | `CA488ECE0B16DA800C3EA5E4B6E595DB251B716E`
SHA256 | `9F454AD0C63C4A899A6D081DE9A254A88DBB07FAC538BCDDF7ECD7F854B4360B`
SHA384 | `0BB307C3ABCF9D0F4826F66A1D2B152F1A8B008651FF7681BC4E4E506C89D9F3883C6585101E16D26F09ED79F7E66C42`
SHA512 | `535FDFDB118735A83205C64915A82CDB620D2C82FA46A229E24974CD4F75D965F6EFA58DA18631FF3246FBF8C1BECC8955F74E5089DF84071476015C444EC167`
SSDEEP | `1536:dSCi+oA2uuIZx3DLbZBGU1A0a4qDLZAQcEzok3E8vroH3S7NtiXE/L4:dYk5dBWv7fcmEAkyXiq4`
IMP | `711A55EEE886A979915C1C3ABA074AC9`
PESHA1 | `FC490B93B73D2CFA55BD8EB0CDC46309716EF5F9`
PE256 | `B476E6660C3184F3B1E8AB091B09F31D70B04E4470E8139F05A5891797D5DD03`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\msdtc.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSDTC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 2001.12.10941.16384 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9f454ad0c63c4a899a6d081de9a254a88dbb07fac538bcddf7ecd7f854b4360b/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\msdtc.exe](msdtc.exe-2EF846AC66E181BE820B513DBC15B5D2.md) | 63
[C:\Windows\system32\msdtc.exe](msdtc.exe-308F08347923DEEDE7BC03EC7D485841.md) | 65
[C:\Windows\system32\msdtc.exe](msdtc.exe-7215CE218BDEAD41B708F098258CF972.md) | 65
[C:\windows\system32\msdtc.exe](msdtc.exe-915747E010A9414B069173284A9B93F4.md) | 65
[C:\WINDOWS\system32\msdtc.exe](msdtc.exe-DC59FE37CFF118B6DAC426FE9923B32C.md) | 66

## Possible Misuse

*The following table contains possible examples of `msdtc.exe` being misused. While `msdtc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [image_load_pingback_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/image_load_pingback_backdoor.yml) | `Image\|endswith: 'msdtc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_pingback_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_pingback_backdoor.yml) | `- 'msdtc'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_lazarus_session_highjack.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_lazarus_session_highjack.yml) | `- '\msdtc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [2021_T2](https://github.com/eset/malware-ioc/blob/master/quarterly_reports/2021_T2/README.adoc) | `Msdtc`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


