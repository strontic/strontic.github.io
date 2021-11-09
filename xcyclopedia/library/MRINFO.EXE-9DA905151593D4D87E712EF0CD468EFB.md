---
title: MRINFO.EXE | Multicast Information
excerpt: What is MRINFO.EXE?
---

# MRINFO.EXE 

* File Path: `C:\WINDOWS\SysWOW64\MRINFO.EXE`
* Description: Multicast Information

## Hashes

Type | Hash
-- | --
MD5 | `9DA905151593D4D87E712EF0CD468EFB`
SHA1 | `4D61A79844A18B6F0D75B8FE2D84F8FC820D82CA`
SHA256 | `FD6CDE67E70D511A1F1A1C3A2F469022EA498F989609831D90C0AA15427BC0AC`
SHA384 | `54B21B9DCAFF3ACAA4714319BA859961020467EA4B4F510C527CD6FDC953419521A6355121CBD0B9BBEB6BE3614BF9A6`
SHA512 | `39001E542B00460419578BD09DFCC4662B086EB17E5AAE704970915D5CB0838D07F1D3BF9F77A1588BCCA970DC778EDE1811D6D671B95461C2EF4DE90D9C5F42`
SSDEEP | `384:dSufTDILRPGWw0vNVuJXr2hi7PaLoLBcWd8W5g:dSubDIxGfJTaLoLBnv`
IMP | `7D973A1A6FDC7951D42858DBEBCE3C8F`
PESHA1 | `177A7C645146AC9A5EBA3D01946ED5B30D511E3B`
PE256 | `AFB1F38F789296472618EA3F15CF8D527E3663CE6459841B4AE43C5F05772165`

## Runtime Data

### Usage (stdout):
```cmhg

Usage: mrinfo [-n?] [-i address] [-t secs] [-r retries] destination
       
 -n           Display IP addresses in numeric format
 -i address   Address of local interface to send query out
 -t seconds   Timeout in seconds for IGMP queries (default = 3 seconds) 
 -r retries   Number of extra times to send the SNMP queries (default = 0)         
 -?           Print Usage
 destination  Address or name of destination


```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows | File
(RW-)   C:\Windows\SysWOW64 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\MRINFO.EXE |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mrinfo.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/fd6cde67e70d511a1f1a1c3a2f469022ea498f989609831d90c0aa15427bc0ac/detection





MIT License. Copyright (c) 2020-2021 Strontic.


