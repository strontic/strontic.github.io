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
MD5 | `9CF023E59025A50A9F0481F51CE80FE7`
SHA1 | `9E37B805701CB0093C2571B016B25C73722E3F2D`
SHA256 | `127DAFA6F4B9F39191E8532BE9772B29A269F4C9DF5E78DCBF759C6F3D98B99F`
SHA384 | `DAF9BCFA6461E4EC242C5236D7B547AFCC788F148D90DE7D9F49F5C38913A513AAB71EC2F7D3D198EDFC61192B0910EE`
SHA512 | `D3C5774581E1EF0E74D4BA2868700AE1E5B1B078FBB7289592D4CDB39B71003A8E5342815AA674C2432F3DAE9AEC1488741D0CDB950764760ACC1F487ED05A14`
SSDEEP | `24576:ePixm1+2b7XxY9/Jp0hLD4NYkwWrKbMh:ePJBY7pkLwwWrKbMh`
IMP | `A1B3FB608C2CC985C3A5D8A82E356A6F`
PESHA1 | `CF67C4F2F777021015782EFF44A11BBD7AB7B1E1`
PE256 | `5817CE5EAA2038164F9B77C1C7A7B162FE55E437B405F1CCD947AEEE0C7DC4C3`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\SearchIndexer.exe |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
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

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/127dafa6f4b9f39191e8532be9772b29a269f4c9df5e78dcbf759c6f3d98b99f/detection/


## Possible Misuse

*The following table contains possible examples of `SearchIndexer.exe` being misused. While `SearchIndexer.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\searchindexer.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


