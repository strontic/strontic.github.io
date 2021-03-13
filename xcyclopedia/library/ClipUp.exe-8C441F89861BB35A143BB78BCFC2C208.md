---
title: ClipUp.exe | Client License Platform migration tool
excerpt: What is ClipUp.exe?
---

# ClipUp.exe 

* File Path: `C:\Windows\system32\ClipUp.exe`
* Description: Client License Platform migration tool

## Hashes

Type | Hash
-- | --
MD5 | `8C441F89861BB35A143BB78BCFC2C208`
SHA1 | `89971AA29AB82A636B4F4E6C2A63FD04D0AF34F8`
SHA256 | `2B72661BDD723636A0523AB07A0C23DE7AFF2EC2147B5183BFE67B0ECF1941B2`
SHA384 | `1F83AD68955D6453B2DB304DDF3A63FB8CCAF603B7AC2E8301773080B04C524B8FE0D8D895945F8614765694F67FA37C`
SHA512 | `49F139EC02284B46B566E408084B08124BD461848E7D6E73E2922AFAFB7621EEE6D5B2ABA824E252DD58A6A308FCE9ED398F750DA2CC2BB53688624AD3351C1D`
SSDEEP | `24576:yUM9HgdVoa2Q/Bd7twtlbFRspR0+GJTZoXoqRp8zAG:yH6H/Bxmlb7sbgBO4qYL`

## Runtime Data

### Usage (stdout):
```cmhg
Done.
C:\Windows\system32\ClipUp.exe Usage: 
-?/-h	This help menu
-p 	Attempts to migrate data from the legacy Windows Phone database
-o 	Attempts to migrate data from Windows Genuine Authorization blob
-altto 	[path] Optional alternative Windows Genuine Authorization blob folder location
-d 	Generate a genuine ticket for the BIOS key
-k 	[5X5 product key] Windows product key
-pfm 	[package family name] Optional package family name to look for a migratable license
-l 	[path] Optional folder of legacy Windows Store licenses
-v 	Enables optional verbose logging
-previd 	Device ID prior to hardware-related changes
[path]	Optional alternative output location for migrated data
Done.

```

### Usage (stderr):
```cmhg
Failed! Error 0x80070057.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\ClipUp.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ClipUp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1075 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1075
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ClipUp.exe](ClipUp.exe-0C4B3D8C6E8DF52A58A19D306A8F1712.md) | 90




MIT License. Copyright (c) 2020-2021 Strontic.


