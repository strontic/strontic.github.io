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
MD5 | `0BE391A5D9C5FB4DE0CD1A4B1440FF69`
SHA1 | `CA6025A1B991A367DBB790C03F86CBB46646509B`
SHA256 | `A8FD7DBF296BFD7117ACBF844ED84B0DB896524825D8A172C4D4C1272C8F4087`
SHA384 | `3D952B7D56FD2D81750655C6E494E30CD6F8160D4BF6C6383E570E2CCFCFB3C2FE45ED8B11ADE8C52A5BAED9B7AB2783`
SHA512 | `2293CF50F48265562D1F7B170DAEBF0BA66E8E7DB5027163305AF2E4176181FD8EB91AA1AA2636D04C20ABCED4D158A3F563A6626CE30F494C5BC73DC43ACB48`
SSDEEP | `24576:g22rikDzqNUGWO+JlEE1Rp2G55JwrygkeI0Q+p+z60:gzVDeU5O+kiYrseVx0`
IMP | `5DD332D22060CEB44D5347FCE1989751`
PESHA1 | `C2EDF5AFBC4E7BC893699B42B24FD01580521F06`
PE256 | `40989C3DA8E6215DDFCA6D85646C9CED7FBC5E9C3A529C2415D145BA96C29452`

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
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/a8fd7dbf296bfd7117acbf844ed84b0db896524825d8a172c4d4c1272c8f4087/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ClipUp.exe](ClipUp.exe-3D3B88936ED7B4F04EB2D6528F75C975.md) | 83




MIT License. Copyright (c) 2020 Strontic.


