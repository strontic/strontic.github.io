---
title: wimserv.exe | Wimfltr v2 extractor
excerpt: What is wimserv.exe?
---

# wimserv.exe 

* File Path: `C:\Windows\system32\wimserv.exe`
* Description: Wimfltr v2 extractor

## Hashes

Type | Hash
-- | --
MD5 | `7477F87C3C1D7633A0E003BE6AA01020`
SHA1 | `7D9B2B2E4D663D2A48C30B674CFCA9909E59CE05`
SHA256 | `96F67682AFF88F597BD00B999A6C62529C456EE72B3CD1F89CB7D319B5BC13E3`
SHA384 | `ADD6820883B09D5F4D6DE89209A2853C91694572FFE91ECCAB6FB6D10B7ECE7E02845EE337942497129EB96127728C0C`
SHA512 | `EDF5D8861CFE77E90151A606C8E16EF178690005590BE085A3FC334476BBADAE3483B6417E76092166F698B98F36D78A26D51D95D646660E48F54ED78D573A82`
SSDEEP | `6144:weLTl2YYPHEGWO+WGs01GGIO8PC9Pj5fRf0ibVF5AzOShYY0mBzqYKBia4jfG9J:3L0YckaoC9C9Pj5fydGRmBzq7infGr`
IMP | `D664C5CCBA7A8DE3C26390C871325E60`
PESHA1 | `2A318AA39687901A4A7B808D25A34583A350B425`
PE256 | `3E07FF69CA6C107B395104087FBFBFED16BD122631BAF6E83F1986DEDEAE9668`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcrypt.dll |
C:\Windows\system32\Cabinet.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wimserv.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: extractr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1202 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1202
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/96f67682aff88f597bd00b999a6c62529c456ee72b3cd1f89cb7d319b5bc13e3/detection


## Possible Misuse

*The following table contains possible examples of `wimserv.exe` being misused. While `wimserv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '\Windows\System32\wimserv.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


