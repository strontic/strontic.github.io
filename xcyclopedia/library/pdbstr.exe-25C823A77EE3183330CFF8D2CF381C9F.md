---
title: pdbstr.exe | Microsoft Stream Utility
excerpt: What is pdbstr.exe?
---

# pdbstr.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\srcsrv\pdbstr.exe`
* Description: Microsoft Stream Utility

## Hashes

Type | Hash
-- | --
MD5 | `25C823A77EE3183330CFF8D2CF381C9F`
SHA1 | `5AC3BCAF9140C1D374F91DE3C1658FD0E4D7D445`
SHA256 | `B7CF928B4C48CAA6B39097AE8A27AEC9565C99EE8BC9190C3D97C7AF107E88CC`
SHA384 | `DC521F3C3A7531AEDCB1262896CFBB3163C2E5289D689B6BA82D6B09FF90394957ECE68CA8C2B39035C26773EC3688E2`
SHA512 | `C100DE1607958468B16EBEC377832E244EAE40664B0BC6701760D432F817EB5CA7F44681F08B602AF22B822CB3B1C532C98080212342F07C882A8809CCD7F474`
SSDEEP | `12288:CNjFhNL1uWDlVtIk3w5UeOTIjV/omLa3CepeF0RMIMq8qujfQpXt+H1DWbQmeKR:OhYWRIk3wjZgpeF0Rlz+HFWbQmeKR`
IMP | `146F88594791252355248F736B945F0C`
PESHA1 | `D223265652834A091209AB2906CDCD14DFF04FAD`
PE256 | `085CF89CC710BE5DE270835FCABE5653856F003137864E4BD99106AF4819FA61`

## Runtime Data

### Usage (stdout):
```cmhg
pdbstr -r/w -p:PdbFileName -i:StreamFileName -s:StreamName
       -r/w indicates whether to read or write the stream
       -p   name of PDB
       -s   name of stream in the PDB
       -i   input text file containing stream to write to PDB (in write mode)
       -i   output text file for writing contents of PDB stream (in read mode)

```

### Usage (stderr):
```cmhg
Error while parsing arguments. Usage:
pdbstr -r/w -p:PdbFileName -i:StreamFileName -s:StreamName

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\srcsrv\pdbstr.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pdbstr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


