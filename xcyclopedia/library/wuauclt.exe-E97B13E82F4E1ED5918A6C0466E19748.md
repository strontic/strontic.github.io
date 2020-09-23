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
MD5 | `E97B13E82F4E1ED5918A6C0466E19748`
SHA1 | `9A8C8FDB5919751D0FB75C04F6A657DE7321EFC2`
SHA256 | `4EAC7348E16BD3EFE323AE3CEE6681246C6FCAB53597892EBB43C7E7450898E4`
SHA384 | `8ECCE33C9463450E1B3CE343E3913BF09E2BF8B0723C5726C16A555FBBBF0FC9649FFC9296F26EDF9BE9FA1EBBFE02F4`
SHA512 | `264E858A5B78A940EFE2F8EDF1DBC83A7D51268AE72849A5888A3F9E0AD39B84C7DF4E39014802ACF608F021223885974573C2A1AE7852CE83966BEEA025B228`
SSDEEP | `1536:eK0TzC8tY6HAqCsd56ncymh7TpkwsZYSpP4:eKE+8tY6H/FPRkLYSpA`
IMP | `B90160F88EBACE2E5AC66C36689E0BDA`
PESHA1 | `B0CF37CA7ECA0DFDD61B4AD032757F4C9A06579C`
PE256 | `EB18F7350A35291B839FAC3CD42413AADC819467642C902AF4CAD1E93383713B`

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
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wuauclt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.508 (WinBuild.160101.0800)
* Product Version: 10.0.19041.508
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/64
* VirusTotal Link: https://www.virustotal.com/gui/file/4eac7348e16bd3efe323ae3cee6681246c6fcab53597892ebb43c7e7450898e4/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-11F337850E397E473B3666AFB7AC1D44.md) | 88
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-95E303BF80AECA5A296E519C61F42427.md) | 90

## Possible Misuse

*The following table contains possible examples of `wuauclt.exe` being misused. While `wuauclt.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $x0 = "WUAUCLT.EXE" fullword wide /* PEStudio Blacklist: strings */ /* score: '20.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


