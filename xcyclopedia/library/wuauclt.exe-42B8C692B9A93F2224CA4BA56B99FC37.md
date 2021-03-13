---
title: wuauclt.exe | Windows Update
excerpt: What is wuauclt.exe?
---

# wuauclt.exe 

* File Path: `C:\Windows\system32\wuauclt.exe`
* Description: Windows Update

## Hashes

Type | Hash
-- | --
MD5 | `42B8C692B9A93F2224CA4BA56B99FC37`
SHA1 | `1C7C8733DD0CD2F42B498E988F099EC03FC3C012`
SHA256 | `6390C42F0DD21C9611D2EB9C7929F5213A95438D4FBFE0D4EA2ADF1271F0696F`
SHA384 | `BCDBA036D6AFB89B9C4C713516048E10B6C037FB29F807F17E80C6AA3E73C406E510F75D66955A4EA0B779E782329AE0`
SHA512 | `2D69A5769B76F97AC8573BD823C91782C280704E5D1362D125F4C49D599705124FB701D95A16894252B49BB3C34D5893EC04EE135055BCD877CA769D7C72DB89`
SSDEEP | `1536:WK0T48tY6HAqCsd56ncytR7TBH5KZYacAPt:WKE48tY6H/FPAHH5AYacAl`
IMP | `B90160F88EBACE2E5AC66C36689E0BDA`
PESHA1 | `E4452CFDB3CA41C1A7B1B96905D4CFDA4E44A03C`
PE256 | `F83E184874AF59575F591061B6DC4B23E46F066E3AE66715E80BBFE838105778`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wuauclt.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wuauclt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.610 (WinBuild.160101.0800)
* Product Version: 10.0.19041.610
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/6390c42f0dd21c9611d2eb9c7929f5213a95438d4fbfe0d4ea2adf1271f0696f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-11F337850E397E473B3666AFB7AC1D44.md) | 66
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-95E303BF80AECA5A296E519C61F42427.md) | 68
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-E97B13E82F4E1ED5918A6C0466E19748.md) | 68

## Possible Misuse

*The following table contains possible examples of `wuauclt.exe` being misused. While `wuauclt.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wuauclt.yml) | `description: Detects code execution via the Windows Update client (wuauclt)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wuauclt.yml) | `- https://dtm.uk/wuauclt/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_wuauclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_wuauclt.yml) | `- '\wuauclt.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `Name: wuauclt.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Command: wuauclt.exe /UpdateDeploymentProvider <Full_Path_To_DLL> /RunHandlerComServer`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Path: C:\Windows\System32\wuauclt.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- IOC: wuauclt run with a parameter of a DLL path`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wuauclt.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wuauclt.yml) | `- Link: https://dtm.uk/wuauclt/`{:.highlight .language-yaml} | 
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $x0 = "WUAUCLT.EXE" fullword wide /* PEStudio Blacklist: strings */ /* score: '20.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


