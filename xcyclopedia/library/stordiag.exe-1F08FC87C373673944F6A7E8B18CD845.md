---
title: stordiag.exe |  
---

# stordiag.exe 

* File Path: `C:\Windows\SysWOW64\stordiag.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `1F08FC87C373673944F6A7E8B18CD845`
SHA1 | `EB78E97DEE03DC3C2F744A408087AD79FD067219`
SHA256 | `B812162F140A347EC78756416302CBC9204EF484FEB7623C0FFF8FF7B4B3EC04`
SHA384 | `5FFFDC39EDC75FD6AB1DA10CCA1CBEAD3FAD3A90C0A6105A59BB0165B40708C4C1A177EFD88713535B7B3744A9274793`
SHA512 | `428CE4A0C9413D94EA1F9C041C6BA2282D017C6BDE36A28EC96679D439D8202A35AA7D652A78D8C710485C0006F7213E64C7D293BBA103FF3165E5298C804023`
SSDEEP | `1536:qwYYQyn8M801RXnItvNCl/iBeKiZfbOZE4RS8JRFahdqb3BuS:jY28M806enfbOZE4I8JRFEYb3BuS`

## Runtime Data

### Usage (stdout):
```Batchfile

Collects storage and filesystem diagnostic logs and outputs them to a folder.

StorDiag [-collectEtw] [-out <PATH>]
-collectEtw                  Collect a 30-second long ETW trace if run from an elevated session
-collectPerf                 Collect disk performance counters
-collectStorageBreakdown     Collect system volume used space breakdown
-checkFSConsistency          Checks for the consistency of the NTFS file system
-diagnostic                  outputs a storage diagnostic report
-bootdiag                    output boot sectors of the disk
-driverdiag                  output avaliable storport and storahci logs
-out <PATH>                  Specify the output path. If not specified, logs are saved to %TEMP%\StorDiag



```

### Child Processes:
conhost.exe systeminfo.exe

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
* File Version: 10.0.19041.1
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\stordiag.exe](stordiag.exe-0A486DBEBEEE0BEC3D3E2F20978F53F8.md) | 91




MIT License. Copyright (c) 2020 Strontic.


