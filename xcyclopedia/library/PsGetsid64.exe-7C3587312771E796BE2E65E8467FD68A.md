---
title: PsGetsid64.exe | Translates SIDs to names and vice versa
excerpt: What is PsGetsid64.exe?
---

# PsGetsid64.exe 

* File Path: `C:\SysinternalsSuite\PsGetsid64.exe`
* Description: Translates SIDs to names and vice versa

## Hashes

Type | Hash
-- | --
MD5 | `7C3587312771E796BE2E65E8467FD68A`
SHA1 | `CDB4FDB8526E6B0875B65F016F2FCB71658A5C37`
SHA256 | `952662A81384423ABF2E9D78DAD7CF8EC77D9B6C93D122B272211B3E6C7F8E49`
SHA384 | `E00E940C22FAF6D52463CD94A21867A516DC3890118E46F8B4587E9875C940868FB1C2F05E74D833CEFCA34EAF37E79E`
SHA512 | `4FBB6DDFDB7445143715E05B962B3310BE9DEE70030373622AE63F068023B5E4EFAB02F9C0FDE219CBFC30BA68F51F1ACA4B87D74AC8562F37C433CEAD22C52C`
SSDEEP | `6144:9a5e36EXPsU0TZKApHWoLbC66MKo2/1abT4eIE9G6sRTu:9we6EXafWkKz44u`
IMP | `6436C27E36FB0FAD0BDCD93AD49F3067`
PESHA1 | `40DF7B99B9283020B78B90297EFA3DF71AFA56E8`
PE256 | `540092AE17D0262E223610B692F942CAA93D393927576C31BFD135C6D44E179A`

## Runtime Data

### Usage (stdout):
```cmhg

PsGetSid v1.45 - Translates SIDs to names and vice versa
Copyright (C) 1999-2016 Mark Russinovich
Sysinternals - www.sysinternals.com


Usage: C:\SysinternalsSuite\PsGetsid64.exe [\\computer[,computer2[,...] | @file] [-u Username [-p Password]]] [account | SID]
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
C:\SysinternalsSuite\PsGetsid64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/952662a81384423abf2e9d78dad7cf8ec77d9b6c93d122b272211b3e6c7f8e49/detection/





MIT License. Copyright (c) 2020 Strontic.


