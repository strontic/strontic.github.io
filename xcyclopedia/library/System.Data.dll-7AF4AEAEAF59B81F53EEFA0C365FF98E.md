---
title: System.Data.dll | .NET Framework
excerpt: What is System.Data.dll?
---

# System.Data.dll 

* File Path: `C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Data.dll`
* Description: .NET Framework
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `7AF4AEAEAF59B81F53EEFA0C365FF98E`
SHA1 | `1AAAF9BC3DF555DD31842B7189F428B2274B1776`
SHA256 | `93BC5129BC6799D50B0542B76AE4BFC5BB5A399E0776C514FDBE9923EDF84737`
SHA384 | `911150F9CFF7E4B8A91DD6FFA8C7707F78DED7B582D7F2D3439954163983F41F4E25EFFA6D6221DB7F91F3E0D6BF3FCF`
SHA512 | `89DD71F26C75FDFACD18330F5DDBB31DC2822B7F95748028199067D975162D8140E3C987D07530033B8C9DC691F27B9DDFD7B8975FABD69F27C024C0345180BC`
SSDEEP | `24576:Tk5enR3mYLB1gX5g7PTvN7TJ9VdBLKpagagngRhyNX3AsYN4hCmg6B5+ghg7xNxo:ZPLB1gJg7PTvN7TJ9VdBLKpagagngRh8`
IMP | `DAE02F32A21E03CE65412F6E56942DAA`
PESHA1 | `25BDA5A4F821FE9A129CC7AF70FB480807950CFE`
PE256 | `B05F19AA4F427C070AF43CD2493C27E714E853A788D04444B70F7BBE908EA271`


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: system.data.dll
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/93bc5129bc6799d50b0542b76ae4bfc5bb5a399e0776c514fdbe9923edf84737/detection


## Possible Misuse

*The following table contains possible examples of `System.Data.dll` being misused. While `System.Data.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_greenbug_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_greenbug_may20.yml) | `- 'system.Data.SqlClient.SqlDataAdapter($cmd); [void]$da.fill'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1006/T1006.md) | <blockquote>Adversaries may directly access a volume to bypass file access controls and file system monitoring. Windows allows programs to have direct access to logical volumes. Programs with direct access may read and write files directly from the drive by analyzing file system data structures. This technique bypasses Windows file access controls as well as file system monitoring tools. (Citation: Hakobyan 2009) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1082.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1082/T1082.md) | Tools such as [Systeminfo](https://attack.mitre.org/software/S0096) can be used to gather detailed system information. A breakdown of system data can also be gathered through the macOS <code>systemsetup</code> command, but it requires administrative privileges. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | <blockquote>Adversaries may delete or remove built-in operating system data and turn off services designed to aid in the recovery of a corrupted system to prevent recovery.(Citation: Talos Olympic Destroyer 2018)(Citation: FireEye WannaCry 2017) Operating systems may contain features that can help fix corrupted systems, such as a backup catalog, volume shadow copies, and automatic repair features. Adversaries may disable or delete system recovery features to augment the effects of [Data Destruction](https://attack.mitre.org/techniques/T1485) and [Data Encrypted for Impact](https://attack.mitre.org/techniques/T1486).(Citation: Talos Olympic Destroyer 2018)(Citation: FireEye WannaCry 2017) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


