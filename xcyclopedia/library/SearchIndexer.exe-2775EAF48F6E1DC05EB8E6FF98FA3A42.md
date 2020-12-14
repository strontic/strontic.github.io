---
title: SearchIndexer.exe | Microsoft Windows Search Indexer
excerpt: What is SearchIndexer.exe?
---

# SearchIndexer.exe 

* File Path: `C:\Windows\system32\SearchIndexer.exe`
* Description: Microsoft Windows Search Indexer

## Hashes

Type | Hash
-- | --
MD5 | `2775EAF48F6E1DC05EB8E6FF98FA3A42`
SHA1 | `83E542E5A0C93F181253274C2C127327B007594F`
SHA256 | `63B92D3657EC7E81AD3A8AD8ECA83C456752EB654715518732DA1ADC9C4241AD`
SHA384 | `AC76CB3D00EB6CF4134F170D363DF0D7C7D59D0A0679FC0578A43AB975FC34627FD4E8AAFD9A439B0CAD9F3D21922E26`
SHA512 | `EFD925A538E3CA7F338A648638FBF272BF3D2D0A1E01300CDC913D5752DA3D70C3DB8605D51799AD4C974383A240AA4819A3581C143FDE6E08603506048DC211`
SSDEEP | `24576:SCbwO4J2bdDUVXCmovWffrR7h8OYbKh74:SCbh4Z0vQrX8/bKh`
IMP | `A1B3FB608C2CC985C3A5D8A82E356A6F`
PESHA1 | `36F1F9A180BF440051D4E86E404CF8CFC3125036`
PE256 | `6714D2212BD29E2D5139286D83EDA1AEB411405D62383159810B64A4DD697FEC`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MSSRCH.DLL |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\SearchIndexer.exe |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\system32\TQUERY.DLL |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SearchIndexer.exe.mui
* Product Name: Windows Search
* Company Name: Microsoft Corporation
* File Version: 7.0.19041.1 (WinBuild.160101.0800)
* Product Version: 7.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/63b92d3657ec7e81ad3a8ad8eca83c456752eb654715518732da1adc9c4241ad/detection


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


