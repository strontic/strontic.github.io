---
title: PsGetsid.exe | Translates SIDs to names and vice versa
excerpt: What is PsGetsid.exe?
---

# PsGetsid.exe 

* File Path: `C:\SysinternalsSuite\PsGetsid.exe`
* Description: Translates SIDs to names and vice versa

## Hashes

Type | Hash
-- | --
MD5 | `2AAF17D3C8F58DD11965ED235D7F310D`
SHA1 | `CE6412E96E60500FF1CAD292835FB56F652BA337`
SHA256 | `A9E3A0D0C90D440F5A7DA6DCE021C554822416C513E383409E80387E1556A760`
SHA384 | `DDB74C2795383119ECE550E08CF95C6B408341850E09346F0177D2B232622A6FC89EBFB0188E7CA4C236E418B7AD2A9E`
SHA512 | `47F81A0B0B8C672E330C9EFF4CF5418230C38B70A50521E339237EB11F5F25771DA487E5ABAD8F98D6802EF4FD5E89CBAAEDF15836C1B56191A625154AEFA83A`
SSDEEP | `3072:LXCv1bXfgMEofB2crxKzZUFLD6uLEHwDm8swOo1y9voWd3ZUFw7IUokfWRh33JWT:+v1bXCU7Lzhzs5cmGT8JCrW0G`
IMP | `C343A23BBB04BF335828E2F253CB7C38`
PESHA1 | `DBB9B06C6110A0D7B674DC54B364103D17F7932F`
PE256 | `170E69D98820920264B061711BBF5B44F679DFA48F299B2F3BAFDBC47E74EDA4`

## Runtime Data

### Usage (stdout):
```cmhg

PsGetSid v1.45 - Translates SIDs to names and vice versa
Copyright (C) 1999-2016 Mark Russinovich
Sysinternals - www.sysinternals.com


Usage: C:\SysinternalsSuite\PsGetsid.exe [\\computer[,computer2[,...] | @file] [-u Username [-p Password]]] [account | SID]
     -u         Specifies optional user name for login to
                remote computer.
     -p         Specifies optional password for user name. If you omit this
                you will be prompted to enter a hidden password.
     account    PsGetSid will report the SID for the specified user account
                rather than the computer.
     SID        PsGetSid will report the account for the specified SID.
     computer   Direct PsGetSid to perform the command on the remote
                computer or computers specified. If you omit the computer
                name PsGetSid runs the command on the local system, 
                and if you specify a wildcard (\\*), PsGetSid runs the
                command on all computers in the current domain.
     @file      PsGetSid will execute the command on each of the computers listed
                in the file.
     -nobanner  Do not display the startup banner and copyright message.


```

### Usage (stderr):
```cmhg
No mapping between account names and security IDs was done.
Error querying account:

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\PsGetsid.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001797C2E574E52E1CAD6000100000179`
* Thumbprint: `5EAD300DC7E4D637948ECB0ED829A072BD152E17`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PsGetSid.exe
* Product Name: Sysinternals PsGetSid
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.45
* Product Version: 1.45
* Language: English (United States)
* Legal Copyright: Copyright (C) 1999-2016 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/a9e3a0d0c90d440f5a7da6dce021c554822416c513e383409e80387e1556a760/detection/





MIT License. Copyright (c) 2020 Strontic.


