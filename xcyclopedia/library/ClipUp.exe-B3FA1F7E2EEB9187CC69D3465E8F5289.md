---
title: ClipUp.exe | Client License Platform migration tool
excerpt: What is ClipUp.exe?
---

# ClipUp.exe 

* File Path: `C:\WINDOWS\system32\ClipUp.exe`
* Description: Client License Platform migration tool

## Hashes

Type | Hash
-- | --
MD5 | `B3FA1F7E2EEB9187CC69D3465E8F5289`
SHA1 | `9876D7C7A8CF3D914315165C884A7C83676A8A6B`
SHA256 | `74170A784A59DBCDD76BFD44084306E5A48D6B72980771E9D65CC88C1A6DFF52`
SHA384 | `4BBEDE819430FC2084AEF81A75C8F47B0020BC479997C5899ACF0713E9CF1F90FBD673E89F120EDB802974066F5F57D9`
SHA512 | `C9D5E871C57D713215FF35B3B49DACBB1E748DD8840055C21E673AB3D1D0300D04D0F703B91ADA5B55FF9F5EF5DC6BE7D8021A04F83B12E1890FAB1CFA221FFB`
SSDEEP | `24576:UKUjZ/V95FF9WCHdQk4ABunSrQRnOV+jTzh9GniULSU9/2j:7UjZ/V95b0a4ABGScRnOuTfdmXEj`
IMP | `5067B792794940D056A6CCE72521AA3A`
PESHA1 | `B0FCEB4E842EA5D600FD4D67F87FC0171DC932F0`
PE256 | `24EC14BE47B9DBD8D22FBD718F454F22E0F73D8D3BBEA2F71504A60C1A40BCD6`

## Runtime Data

### Usage (stdout):
```cmhg
Done.
C:\WINDOWS\system32\ClipUp.exe Usage: 
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
C:\WINDOWS\system32\ClipUp.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ClipUp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.120 (WinBuild.160101.0800)
* Product Version: 10.0.22000.120
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/74170a784a59dbcdd76bfd44084306e5a48d6b72980771e9d65cc88c1a6dff52/detection





MIT License. Copyright (c) 2020-2021 Strontic.


