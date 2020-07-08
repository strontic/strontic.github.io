---
title: stordiag.exe |  
---

# stordiag.exe 

* File Path: `C:\Windows\system32\stordiag.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `0A486DBEBEEE0BEC3D3E2F20978F53F8`
SHA1 | `7BBC1977DE11EE9324C5A4C3ACF4724882B38279`
SHA256 | `6A13DAC8BD42767DAD55D4C1ED4640F4E7F01ABB08CA05DDCDC2C348FCD6F8B3`
SHA384 | `FFBD945C22C16E612BE83BA3EDB2ABB74E69491256F8C0F529AC92A5098F0A430E1B5D6E8108BE7240A732CD3C256CFB`
SHA512 | `400ACADC345D946EF481C974856C9E3101B59D47E559790D0B161CDF05BC01E0498A45159392223240BF49EE0EA7D68189BDC24D929E7FC6532F24B496326E5B`
SSDEEP | `1536:hwYYQyn8M801RXnItvNCl/iB8KwZfbOZE4RS8JRFahdqb9BuN:6Y28M8068xfbOZE4I8JRFEYb9BuN`

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
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
[C:\Windows\SysWOW64\stordiag.exe](stordiag.exe-1F08FC87C373673944F6A7E8B18CD845.md) | 91




MIT License. Copyright (c) 2020 Strontic.


