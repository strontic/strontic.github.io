
# stordiag.exe 

* File Path: `C:\WINDOWS\system32\stordiag.exe`
* Description:  
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `90A922FDB190D75111DBE5A741EE0510`
SHA1 | `728132E27C24796A7C29A927FF56414E4D66C547`
SHA256 | `3BC839B933D9C40A8B8D25B415C1037BA4A47009BF3C4E3A3D4C26554B7D4898`
SHA384 | `56C87BF0397F07D106F8CDEAFBA7BE0584E04909598C9C656F69249A23A548BE935276CB17F022BD6012E4BDBF85DDC0`
SHA415 | `5F4A9DD8A99F197793FBBB00D6AA32AF93BFF90F2E52381FCF9C2FCA4F00AEDB44ADF3F627FB3D14D9960FDD31CB863F3BE7B6C051C129969C7D8B792D6F3D8B`
SSDEEP | `1536:D6dFZKXt4SeKT/DSsdj9hf5+VIsWzbJWE4KAhUfb3M:mFZpSeK6MkWpzbJWE4nQb3M`

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
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
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

MIT License. Copyright (c) 2020 Strontic.


