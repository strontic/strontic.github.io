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
MD5 | `0C4B3D8C6E8DF52A58A19D306A8F1712`
SHA1 | `2FC6DD677C7F786977DC6C8F84911C02BBE74338`
SHA256 | `36B6C08C86514A332CBDDE4B908AC0E045DD92309EF564DEBD3825CA55316CD2`
SHA384 | `5EF24B9C3CAF38963C685475A6FB989EC2B4A60C09EA7040AED2E6AF68E9F4C332E0E43CE0001DA40A55AF67AFF533B3`
SHA512 | `7FCD23BE4B02F36892A7A0BE6A6AC5D682CE4354B1C1FFF0E70046D7A371A0F56AAB67F08844B2BAD7FE91A6EB150CB5B939CDA0895BBA9A8D033F09B57A9E46`
SSDEEP | `24576:oUM9HgdVoa2Q/Bd7twtlbFRspx9+GJTZoXoqRp7zAR:oH6H/Bxmlb7sbrBO4qHE`
IMP | `9F99F14179075A92847CE4E8C8A1B987`
PESHA1 | `6123891024F1E1375705B656168DB9B5CDB58BAA`
PE256 | `0806712BB551B3FB1AD9BB66E25CD183D587C56D44530E0BC818AC2B90A447E5`

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

### Child Processes:
csrss.exe winlogon.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\system32\ClipUp.exe |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\CRYPTSP.dll |
C:\Windows\system32\CRYPTXML.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\ncrypt.dll |
C:\Windows\system32\NTASN1.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\webservices.dll |


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
* File Version: 10.0.17763.1432 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1432
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/36b6c08c86514a332cbdde4b908ac0e045dd92309ef564debd3825ca55316cd2/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ClipUp.exe](ClipUp.exe-8C441F89861BB35A143BB78BCFC2C208.md) | 90




MIT License. Copyright (c) 2020-2021 Strontic.


