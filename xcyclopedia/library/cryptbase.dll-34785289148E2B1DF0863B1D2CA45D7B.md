---
title: cryptbase.dll | Base cryptographic API DLL
excerpt: What is cryptbase.dll?
---

# cryptbase.dll 

* File Path: `C:\Windows\system32\cryptbase.dll`
* Description: Base cryptographic API DLL

## Hashes

Type | Hash
-- | --
MD5 | `34785289148E2B1DF0863B1D2CA45D7B`
SHA1 | `9FD570887B8EAAD6CC4F040E3281717F2ECB35DF`
SHA256 | `36DFA707D432FF6950D23A3DC72FF50401B4B59059279C2B808FB735683C29E2`
SHA384 | `B6F884E0A8D2293F37CA29A5AEE4CA568DE542483CE389328ED463A079E0AC1D02A791A7E022D02C11E9FC0FE3EC0D87`
SHA512 | `AE616B80AE5A901DECBAC79F70E63ACAC2081A951BE1771449C8E64587501B14400A7D3E21C152D6D64149E884D41D5516515A844893ACD6BCDCD4494E458D61`
SSDEEP | `384:lNPotYaw+ZNsdfm+bgmLUi/j+YkkUBTcLyuKRXWHIW1wVyDBRJ2yGNGw6lx2+tRq:lNPgz9ZNqu+lwcGuKR0/wI1P2yGYptRq`
IMP | `947563122A564336B8FE403CBB94531C`
PESHA1 | `D621406946D0542683ABA9C28CEAA413F432BFE7`
PE256 | `808A146380EFFE790A322FCD78A98B1DADBA3449129465567D6F2AA189296331`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SystemFunction034` | 8 | Exported Function
`SystemFunction029` | 7 | Exported Function
`SystemFunction036` | 9 | Exported Function
`SystemFunction041` | 11 | Exported Function
`SystemFunction040` | 10 | Exported Function
`SystemFunction028` | 6 | Exported Function
`SystemFunction002` | 2 | Exported Function
`SystemFunction001` | 1 | Exported Function
`SystemFunction003` | 3 | Exported Function
`SystemFunction005` | 5 | Exported Function
`SystemFunction004` | 4 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cryptbase.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/36dfa707d432ff6950d23a3dc72ff50401b4b59059279c2b808fb735683c29e2/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\downlevel\api-ms-win-core-shutdown-l1-1-0.dll](api-ms-win-core-shutdown-l1-1-0.dll-B8D35A179B531F7732F7C5AAA7DEA32C.md) | 35
[C:\Windows\system32\downlevel\api-ms-win-core-sysinfo-l1-2-0.dll](api-ms-win-core-sysinfo-l1-2-0.dll-D8BF60CD8EC0CC0232EE443A034B49BA.md) | 41
[C:\Windows\system32\downlevel\api-ms-win-core-sysinfo-l1-2-1.dll](api-ms-win-core-sysinfo-l1-2-1.dll-500F177F56CC956C9517474639CA0D0F.md) | 36
[C:\Windows\system32\downlevel\API-MS-Win-devices-config-L1-1-0.dll](API-MS-Win-devices-config-L1-1-0.dll-F28F2198F08EDDB451C81923F367B4F4.md) | 41
[C:\Windows\system32\downlevel\API-MS-Win-Eventing-ClassicProvider-L1-1-0.dll](API-MS-Win-Eventing-ClassicProvider-L1-1-0.dll-78347669C5ECAFDD950B5FEEA248AA3F.md) | 38
[C:\Windows\system32\downlevel\API-MS-Win-security-lsapolicy-l1-1-0.dll](API-MS-Win-security-lsapolicy-l1-1-0.dll-09519536C526AC37CC4E403E78FC1689.md) | 38
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-heap-l1-1-0.dll](api-ms-win-core-heap-l1-1-0.dll-378B68E38537632FB3337B2CF38EB4E1.md) | 36
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-threadpool-legacy-l1-1-0.dll](api-ms-win-core-threadpool-legacy-l1-1-0.dll-3A68A61A683B3F8616CD3BF5CC576234.md) | 35
[C:\Windows\SysWOW64\dsrole.dll](dsrole.dll-C57961BC20A1DC15D28E8F75D9FCF3B0.md) | 36
[C:\Windows\SysWOW64\nsi.dll](nsi.dll-DBD708765E62C0DD5574E3EA4C7D4517.md) | 43

## Possible Misuse

*The following table contains possible examples of `cryptbase.dll` being misused. While `cryptbase.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $c4 = "\\sysprep\\CRYPTBASE.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_netwire_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_netwire_rat.yar) | $s3 = "CRYPTBASE" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s1 = "C:\\WINDOWS\\system32\\sysprep\\cryptbase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s2 = "C:\\Windows\\SysNative\\sysprep\\cryptbase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s2 = "C:\\Windows\\system32\\sysprep\\cryptbase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s3 = "\\CryptBase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s2 = "CryptBase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_win_plugx.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_win_plugx.yar) | $s3 = "l%s\\sysprep\\CRYPTBASE.DLL" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_win_plugx.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_win_plugx.yar) | $s5 = "CRYPTBASE.DLL" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s5 = "CRYPTBASE.dll" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s6 = "loadFrom=\"%systemroot%\\system32\\sysprep\\cryptbase.DLL\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s4 = "System32\\migwiz\\CRYPTBASE.dll" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


