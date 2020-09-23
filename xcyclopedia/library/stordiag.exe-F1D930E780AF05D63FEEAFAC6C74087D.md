---
title: stordiag.exe |  
excerpt: What is stordiag.exe?
---

# stordiag.exe 

* File Path: `C:\WINDOWS\SysWOW64\stordiag.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `F1D930E780AF05D63FEEAFAC6C74087D`
SHA1 | `BB9799F1BC6A8150E92AAE0CFD1567CF3F9791E6`
SHA256 | `04785B45F5E89CF98A45F917948826B63D2F9BC155D291544626F5B8B9C01318`
SHA384 | `9EA05ECB07EF83DACE376562B7DF4DF4C51E9AC4563D3C6E85F9B5283BF6C74E7687F57FA283E3CF35D3CCB3A0FE9702`
SHA512 | `9DA186715EC3CC372CDDB4E00DFC4537F9B011D099A720FCBE65C3F2D92C38FF197E06405713B04083112C1A48CFB577DB147661A09989183106AFC1F60A02DA`
SSDEEP | `1536:n6dFZKXt4SeKT/DSsdj9hf5+VIsWvbJWE4KAhUfbKU:KFZpSeK6MkWpvbJWE4nQbKU`

## Runtime Data

### Usage (stdout):
```cmhg

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
conhost.exe fltMC.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: stordiag.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1
* Product Version: 10.0.18362.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\stordiag.exe](stordiag.exe-90A922FDB190D75111DBE5A741EE0510.md) | 91




MIT License. Copyright (c) 2020 Strontic.


