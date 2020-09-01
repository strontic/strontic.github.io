---
title: ClipUp.exe | Client License Platform migration tool
---

# ClipUp.exe 

* File Path: `C:\WINDOWS\system32\ClipUp.exe`
* Description: Client License Platform migration tool

## Hashes

Type | Hash
-- | --
MD5 | `58CFCFFBA3539E7D078B91D416684142`
SHA1 | `F2BBA798F3FA6F76271CBA6F157A8A932EE2D3B0`
SHA256 | `46467B4B06255DB1494E855207703AA3C083689490B3F7E77169E2E3DC254ED8`
SHA384 | `853C2B17C2EEEE3828EF41A1502391DA1BF0996B7661A837AE4B9A92B6AB35C5632EC61F4828659DF85C1DC301764A90`
SHA512 | `1969C99512DBB3F6E6E917EB535B9571181E31459733A3E404ED23B7AFFF4118216BF4AC754CEBB1E002D8E4DBDCBCB4595BFD9D75E4F23A2CACD7EF04021DBC`
SSDEEP | `24576:eC4vyV8xG0oNcxhMNyXP7QoG5bgTYr4UTZGxIETIRfEC:Z4vyVaG0oNWeN2LTYoz+fF`

## Runtime Data

### Usage (stdout):
```Batchfile
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
```Batchfile
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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ClipUp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.693 (WinBuild.160101.0800)
* Product Version: 10.0.18362.693
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


