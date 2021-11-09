---
title: DiskSnapshot.exe | DiskSnapshot.exe
excerpt: What is DiskSnapshot.exe?
---

# DiskSnapshot.exe 

* File Path: `C:\WINDOWS\system32\DiskSnapshot.exe`
* Description: DiskSnapshot.exe

## Hashes

Type | Hash
-- | --
MD5 | `51911CCD8B138AB826FDB3A81CAD32D9`
SHA1 | `E44591F399865E4E19B53B98B6B23782FB9BE6C2`
SHA256 | `743F99DD39535FEA2EF86530E6636B20E4BAE872562D00CAAD81ACA1E8B11018`
SHA384 | `3607FF56B6925D77C849FD18B6962882D92D9C3F47B95AFEE7B697D17F2EA2C65556CCAC977A013F0FE69F07A7898E0A`
SHA512 | `F80A4C3A26EE7E6D54D1A7E72B95801E1A81B761EBB577C6A6FF6C473AD60D01E2F7CE4084943974485DFFC397BEFDF1BA6EFDB4095A7A760E46B86A9BC87101`
SSDEEP | `1536:N/BleChCSn5eCcysppzLVrb4DSN+qNJZg68bFR:N/BHhCSACw9OSN+qNXDc`
IMP | `9BE1E8D7C5D5B113AF20C778EF464358`
PESHA1 | `E88848467475DC992D069E5AAD440ED9C216F421`
PE256 | `1D2BD816312725F74876E0BF263B942CBCB0F7BCEC8399C86F0775422DC105E1`

## Runtime Data

### Usage (stderr):
```cmhg
DiskSnapshot: illegal option: --
DiskSnapshot.exe [options]
	-c write detail data to console
	-i write detail data to console (same as -c)
	-s (deprecated) summary data to console
	-u process large volumes (no limit)
	-j [config] specifies an alternate config file
	-v [volume][path] specifies volume(+path) to process, e.g. "d:" or "d:\foo" 
	-d [input-file] print encoded versions of the strings in the input file, for decoding purposes
	-e prints out escalation keywords
	-k calculate checksums for files, used to investigate duplicated on-disk content (c arg required).
	-o [output-file] write detail data to a file

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\DiskSnapshot.exe |
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

* Original Filename: DiskSnapshot.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/743f99dd39535fea2ef86530e6636b20e4bae872562d00caad81aca1e8b11018/detection





MIT License. Copyright (c) 2020-2021 Strontic.


