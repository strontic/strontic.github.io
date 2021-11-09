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
MD5 | `DC59FE37CFF118B6DAC426FE9923B32C`
SHA1 | `8A272FFC41CBD7E26EE59C204D18D472BB24E352`
SHA256 | `8DDC6D67A14B549946D103F2A5E7B1EB23C68BB6E7B8ECBC192365C7323EC458`
SHA384 | `DA444AF915A0B91CD980FC705A0908D9445422718A90FDAB46A1A956F90F67E793DCB9AA489CA1549BA520EB1A33DECB`
SHA512 | `3E5E3A16008E510172A5D97DF8A5D1F0FC5330837A1A5C0D53E3D02B32075C468F1DA39768A9F3152693603E3D6B736478F88936BDA82372FEAC5279828DD8AE`
SSDEEP | `1536:jpfIniVRD81jmGX8q15ZkMH1A0a4qDLZAQcEzok3E8vroH3S7NtiXE/Lk:zVFNzqBkfv7fcmEAkyXiqk`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSDTC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 2001.12.10941.16384 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\msdtc.exe](msdtc.exe-2EF846AC66E181BE820B513DBC15B5D2.md) | 68
[C:\Windows\system32\msdtc.exe](msdtc.exe-308F08347923DEEDE7BC03EC7D485841.md) | 71
[C:\Windows\system32\msdtc.exe](msdtc.exe-7215CE218BDEAD41B708F098258CF972.md) | 75
[C:\windows\system32\msdtc.exe](msdtc.exe-915747E010A9414B069173284A9B93F4.md) | 66
[C:\WINDOWS\system32\msdtc.exe](msdtc.exe-ED13DCE3E438FD8BD3DAEC15460C42A0.md) | 66

## Possible Misuse

*The following table contains possible examples of `msdtc.exe` being misused. While `msdtc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [image_load_pingback_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/image_load_pingback_backdoor.yml) | `Image\|endswith: 'msdtc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_pingback_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_pingback_backdoor.yml) | `- 'msdtc'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_lazarus_session_highjack.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_lazarus_session_highjack.yml) | `- '\msdtc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [2021_T2](https://github.com/eset/malware-ioc/blob/master/quarterly_reports/2021_T2/README.adoc) | `Msdtc`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


