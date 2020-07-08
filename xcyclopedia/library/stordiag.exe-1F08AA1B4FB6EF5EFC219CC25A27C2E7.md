---
title: stordiag.exe |  
---

# stordiag.exe 

* File Path: `C:\windows\SysWOW64\stordiag.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `1F08AA1B4FB6EF5EFC219CC25A27C2E7`
SHA1 | `C049D4B5AAC6C736ADEFB1FC243E7F9538D923A0`
SHA256 | `D706DC037C51B48E412E6CA00129FC34F06830C27260A5D84F7D30D61237E980`
SHA384 | `EEC1A09610AAF32BB8E2A5EA47294B9AD14F1723B912D125DED85FD4F5E65D9CA5814A185DD1CC4DCB891A849230494A`
SHA512 | `47514CFDC13281FFE3FFBF3C53EC55BC53F3DACD96DEC6AFA58AC8B064FC2D144BBE4B744161E172A102FAD2C44CDB3B58962C0DAF7CF6F1A417F1B28660D05F`
SSDEEP | `1536:LSXiToaguRN2LT0SA6Tny2esoOCrcLbJWE4KWh+fbyJ:OXBagGA0SAGy8/bJWE4t2byJ`

## Runtime Data

### Usage (stdout):
```Batchfile

Collects storage and filesystem diagnostic logs and outputs them to a folder.

StorDiag [-collectEtw] [-out <PATH>]
-collectEtw           Collect a 30-second long ETW trace if run from an elevated session
-collectPerf          Collect disk performance counters
-checkFSConsistency   Checks for the consistency of the NTFS file system
-diagnostic           outputs a storage diagnostic report
-bootdiag             output boot sectors of the disk
-driverdiag           output avaliable storport and storahci logs
-out <PATH>           Specify the output path. If not specified, logs are saved to %TEMP%\StorDiag



```

### Child Processes:
conhost.exe systeminfo.exe

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: stordiag.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1
* Product Version: 10.0.17763.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\stordiag.exe](stordiag.exe-EA1A603CE352708C94C964508034E010.md) | 90




MIT License. Copyright (c) 2020 Strontic.


