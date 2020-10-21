---
title: TCPSVCS.EXE | TCP/IP Services Application
excerpt: What is TCPSVCS.EXE?
---

# TCPSVCS.EXE 

* File Path: `C:\Windows\SysWOW64\TCPSVCS.EXE`
* Description: TCP/IP Services Application

## Hashes

Type | Hash
-- | --
MD5 | `24299886198E801C7D428FC30C95E9C5`
SHA1 | `E132698D6E20B41AD8F839094CD9DDA7370F4E00`
SHA256 | `B2268460262B8587C8ACD530A5EDD7FB5D13CF41640D8BCF02A2EA213882FAB4`
SHA384 | `B8070597F6926BFEC5206B1E2F1EF3B7FFF865A6F3B1C230145A946492F438C170B6C1A24A335B22AD33F9EA95540E65`
SHA512 | `114D097595E3302B00698B8429F2758BDCBFC7F5DEB540C1C3A3134A89AAF8CCFC4C6AF8D19793E4ABC8B2459BC46C219110164FE2B3EA425BD8FAB61EFBED9D`
SSDEEP | `192:EF0o+tFS+H3I3Ou4vt2bvCpeXL6//1PKcW5/Wh:EF0oe4+XaR412DCM6//QcW5/Wh`
IMP | `7EC53FBE050A90703B67A98FCB8BCFCC`
PESHA1 | `229A8CFDED64AC7D199E3C0C7283AD8C1BDD5409`
PE256 | `46D3D27ECEFF7F3027CED91C11663EF609AF3B816B926BFC2CDB9B1D6375FA31`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\TCPSVCS.EXE |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TCPSVCS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/b2268460262b8587c8acd530a5edd7fb5d13cf41640d8bcf02a2ea213882fab4/detection/


## Possible Misuse

*The following table contains possible examples of `TCPSVCS.EXE` being misused. While `TCPSVCS.EXE` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s2 = "tcpsvcs.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


