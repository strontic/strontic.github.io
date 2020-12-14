---
title: MRINFO.EXE | Multicast Information
excerpt: What is MRINFO.EXE?
---

# MRINFO.EXE 

* File Path: `C:\Windows\SysWOW64\MRINFO.EXE`
* Description: Multicast Information

## Hashes

Type | Hash
-- | --
MD5 | `F664A3E4625D86FC6B389AFF416CF67F`
SHA1 | `1697129DD5541DA901E909D886983AEE01DDAC87`
SHA256 | `4E02CB071B535096151DEB19675B5544D4DA97584E782BF6993E9FD1E9B2007D`
SHA384 | `0C19E4E07ED622D274DFA3BA8A513A55C00A851D72C549890E082D028D9FC47999BD8995774A3FDD11B3B5C0E344AA47`
SHA512 | `3DB758872C66ED7BCF07D98469FFB27DDF5F749750DC4535CD61C0AE4C6D4F0A8D9670F51A8814BD3DF2AC089CD009513A606BF4867F8FE8BA0B32B45F3A0B44`
SSDEEP | `384:eDMa5ntCFWvw4aZsJke6UYRMfbP3B0We8W8:eDMIntCFcC8wVRMfLBg`
IMP | `190D14EA18A077D297455C1871A8223C`
PESHA1 | `B4581DF1C7CC32FBF12B7A3E4999F2963795BE3D`
PE256 | `03A9EE0C08F08AE4DA7B598D33DDBA4A034C5B33A0517A86D54726FC021F18F8`

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
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\MRINFO.EXE |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mrinfo.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/4e02cb071b535096151deb19675b5544d4da97584e782bf6993e9fd1e9b2007d/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\MRINFO.EXE](MRINFO.EXE-07F9C349CC3D87726F1AF79C1DC3656C.md) | 68




MIT License. Copyright (c) 2020 Strontic.


