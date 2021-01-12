---
title: MsiTran.exe | MSI database transform tool
excerpt: What is MsiTran.exe?
---

# MsiTran.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\MsiTran.exe`
* Description: MSI database transform tool

## Hashes

Type | Hash
-- | --
MD5 | `6ACFFD6C96B748F7F38063FEC43A24D1`
SHA1 | `2C16234BDC25D7A08B7F6B02138FF6C8550858E9`
SHA256 | `A3E13515F279FD84C09F335E34D8EE2D15140007ACC4C377A9E7E9E7C02765AA`
SHA384 | `4002AE6C5078B6892FC4CB2D90DAE5A469A05216F50B52F1A68A2B456D62D43133B7B0A457BE987607C8E8C58D5FD861`
SHA512 | `1A2BE60DD6119A311A1D43ABFD6E9B479F7CC4C462DD4F92F8D119A7726BC5BAD071890DF409D8353D7645315ECD3EFC28592D8415B5BFEC04D4EFDBB662817C`
SSDEEP | `1536:sEHtCZ9BkpkUp7y2lMZo5WiGuCYPzksrDV1iaAG5a:sEHtuEdNL5WfS751iaAma`
IMP | `2966C47977779404E0D6EB3117DD103A`
PESHA1 | `DE3D95E080697F5A9D10A71839BDBA40C4E6D2D0`
PE256 | `BF8904931281DDF88219CAF18AF908A6098B7703C7C0397F96B85FF36B2F3044`

## Runtime Data

### Usage (stdout):
```cmhg
Error 1. Msi Transform Tool --- Generate and Apply Transform Files

Options for MsiTran.exe:
-g {base db} {new db} {transform} [{error/validation conditions}] -->Generate
-a {transform} {database} [{error conditions}]              -->Apply

Error Conditions:
The following errors may be suppressed when applying a transform.
To suppress an error, include the appropriate character in
{error conditions}. Conditions specified with -g are placed in
the summary information of the transform, but are not used when
applying a transform with -a.

'a': Add existing row.
'b': Delete non-existing row.
'c': Add existing table.
'd': Delete non-existing table.
'e': Modify existing row.
'f': Change codepage.

Validation Conditions:
The following validation conditions may be used to indicate when a
transform may be applied to a package. These conditions may be
specified with -g but not -a.

'g': Check upgrade code.
'l': Check language.
'p': Check platform.
'r': Check product.
's': Check major version only.
't': Check major and minor versions only.
'u': Check major, minor, and update versions.
'v': Applied database version < base database version.
'w': Applied database version <= base database version.
'x': Applied database version =  base database version.
'y': Applied database version >= base database version.
'z': Applied database version >  base database version.

Generate transform without summary info stream (conditions ignored):
'@': Suppress summary information stream generation.
-? Displays this help message.
-nologo Do not display the logo message.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\MsiTran.exe |
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

* Original Filename: msitran.exe
* Product Name: Windows Installer
* Company Name: Microsoft Corporation
* File Version: 5.0.19041.1 (WinBuild.160101.0800)
* Product Version: 5.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


