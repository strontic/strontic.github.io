---
title: ClipUp.exe | Client License Platform migration tool
---

# ClipUp.exe 

* File Path: `C:\Windows\system32\ClipUp.exe`
* Description: Client License Platform migration tool

## Hashes

Type | Hash
-- | --
MD5 | `3D3B88936ED7B4F04EB2D6528F75C975`
SHA1 | `F91A595549AF76E31DD8EC944A6153F9D3EC3BA6`
SHA256 | `6B5502BD71FC210CB75E9E4953F4CEA21BBAE7849B4A18095E5A51DE7A0797FA`
SHA384 | `E3B3645FFD22B58F4697040F6F554B266A891BE5ADC1E6C06606D7D5316A0FB3F2C46247C1581FFBC91B97D58D83B10E`
SHA512 | `9EA70AB3EAD4EF2860FD3B10EAE7E6AC5E5066870FA4F47C8C545087E62339AA747F55AC04D6240C629FB404AE969739EC983F1DD954C0A78D3A5FDF889238A9`
SSDEEP | `24576:y22rikDzqNUGWO+JlEE1RpSGyyJwrygkeH0Qpp+zw:yzVDeU5O+kJlrseRb`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
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
* File Version: 10.0.19041.84 (WinBuild.160101.0800)
* Product Version: 10.0.19041.84
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


