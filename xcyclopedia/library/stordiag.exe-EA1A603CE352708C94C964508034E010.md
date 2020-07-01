---
title: stordiag.exe |  
---

# stordiag.exe 

* File Path: `C:\windows\system32\stordiag.exe`
* Description:  
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EA1A603CE352708C94C964508034E010`
SHA1 | `2E8AA7B1EBDFDD6DDB487D69B8C0B46699F7C9B2`
SHA256 | `DDC1C81667A942F91F25E18EAF3AFC453F7FE3A4CC4140CBA82FB49732011536`
SHA384 | `310263FC7606CF4954127D403EAD35A0995A3E2E9C10FB2E09E84B4A85EE4592285631E509E958111A5AC06988F362CF`
SHA512 | `A573335D8AE94B842E45E0913A81806B658E78D57E426D428A97A6918FEB7CEE4F2D2BF1EA3F5829464F3425524B036A69A548ED0BEACA92836FBB01A567DC87`
SSDEEP | `1536:dSXiToaguRN2LT0SA6Tny2esoOCd+LbJWE4KWh+fbN0:QXBagGA0SAGy8jbJWE4t2bN0`

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

### Usage (stderr):
```Batchfile

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
[C:\Windows\SysWOW64\stordiag.exe](stordiag.exe-1F08AA1B4FB6EF5EFC219CC25A27C2E7.md) | 90




MIT License. Copyright (c) 2020 Strontic.


