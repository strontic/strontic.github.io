---
title: msdtc.exe | Microsoft Distributed Transaction Coordinator Service
excerpt: What is msdtc.exe?
---

# msdtc.exe 

* File Path: `C:\Windows\system32\msdtc.exe`
* Description: Microsoft Distributed Transaction Coordinator Service

## Hashes

Type | Hash
-- | --
MD5 | `2EF846AC66E181BE820B513DBC15B5D2`
SHA1 | `8B4786EB9D864FC78BD99432AE0C78F887049461`
SHA256 | `EDFE71025C352D0DABEC7B9506C5945BB0EC11F8DB540DB8CB1116C2EA1648A8`
SHA384 | `BA601A97F69630626939298014FFCD764B0CF4D936A02814145BA18EE4A5EFCD55F699EDD2ECFDD5BC551C4548F65BE3`
SHA512 | `2587ACD723F515EB8FA1DD7016647079FD7AF2A1C32F92FF344766803D524D9820BEBAF21DAA3B3D3556D2DB8AB956A8A1682EAA46ABB9B04A4C8E1E21321BDC`
SSDEEP | `1536:vOKf3ewElEA4yattFzRFZzi1A0a4qDLZAQcEzok3E8vroH3S7NtiXE/Lc:GNlOxzvv7fcmEAkyXiqc`
IMP | `51BA43624008AF885335F88516CA2AD3`
PESHA1 | `A8A8101BC18379F31B40513A68B4834E7AC3D5EC`
PE256 | `22EA120BB10C430E58DB1EBC6BD51710705C1180C0E0182082FA90088662F410`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\system32\CLUSAPI.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\CRYPTSP.dll |
C:\Windows\system32\DNSAPI.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\msdtc.exe |
C:\Windows\system32\MSDTCLOG.dll |
C:\Windows\system32\MSDTCPRX.dll |
C:\Windows\system32\MSDTCTM.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\MSWSOCK.dll |
C:\Windows\system32\MTXCLU.DLL |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\RESUTILS.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\system32\WINMM.dll |
C:\Windows\System32\WS2_32.dll |
C:\Windows\system32\XOLEHLP.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSDTC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 2001.12.10941.16384 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/edfe71025c352d0dabec7b9506c5945bb0ec11f8db540db8cb1116c2ea1648a8/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\msdtc.exe](msdtc.exe-308F08347923DEEDE7BC03EC7D485841.md) | 63
[C:\Windows\system32\msdtc.exe](msdtc.exe-7215CE218BDEAD41B708F098258CF972.md) | 66
[C:\windows\system32\msdtc.exe](msdtc.exe-915747E010A9414B069173284A9B93F4.md) | 65
[C:\WINDOWS\system32\msdtc.exe](msdtc.exe-DC59FE37CFF118B6DAC426FE9923B32C.md) | 68

## Possible Misuse

*The following table contains possible examples of `msdtc.exe` being misused. While `msdtc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [image_load_pingback_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/image_load_pingback_backdoor.yml) | `Image\|endswith: 'msdtc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_pingback_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_pingback_backdoor.yml) | `- 'msdtc'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_lazarus_session_highjack.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_lazarus_session_highjack.yml) | `- '\msdtc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [2021_T2](https://github.com/eset/malware-ioc/blob/master/quarterly_reports/2021_T2/README.adoc) | `Msdtc`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


