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
MD5 | `30858F924D2F706A63F2A0686A055BB3`
SHA1 | `25E226837944D2D9A96772639D8C11AD8C3BEB2D`
SHA256 | `976124D09BE547F08E23B8CBB8116CD95146F9E0B366DD76963055A3BB0AF2CB`
SHA384 | `1CA3F60A8BC7FA3DEF4753228DCD00106C60A04B77381806001FAD8B0DC305D3943D9522F0399DAC2662C3A720E7FEFD`
SHA512 | `917C92F57F987368EF0F27111D051A280B3F9EE2EBE0196CC1E9907D8D81D328ED4E2798B7EE6CCC967AB3789FAAE84021D4B6606EDAC2B51DF5CE51A7764BBA`
SSDEEP | `12288:/vQ+DuY3jJWEdpi4CWIDcergGEm7wQMuz7RicizvbCR2vgJowKqb4RqsUJvyM+4o:qeTri3WFQRZfz9n2m2ttUVyKCv3lNRX`
IMP | `5DD332D22060CEB44D5347FCE1989751`
PESHA1 | `615FB9CDA49AF5F6BAA5785E5A08A4ECB8DB5304`
PE256 | `0E829B1F83D1440A3DF5C55A8AF06D8D669475C1683859EC3100CA8BA4FD8F7F`

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
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ClipUp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1052 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1052
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/976124d09be547f08e23b8cbb8116cd95146f9e0b366dd76963055a3bb0af2cb/detection





MIT License. Copyright (c) 2020-2021 Strontic.


