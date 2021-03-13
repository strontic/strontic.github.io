---
title: MsiCert.exe | MSI Database DigitalSignature table update
excerpt: What is MsiCert.exe?
---

# MsiCert.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\MsiCert.exe`
* Description: MSI Database DigitalSignature table update

## Hashes

Type | Hash
-- | --
MD5 | `98A65625F8151F65DEADF60A58DE2831`
SHA1 | `DAC6F7301C596BBD4DBEBFCAA57FF7B17E31FF5D`
SHA256 | `340D0E79D9C18D2445965A32DD9C18C611A03EACA104C7FB6335421F18A3CEE9`
SHA384 | `C21F43010D87F4B3317208D2CE6B487DCA8E9C7260BC1A2F00A793C9BE61E14C53895D6757E58E4ABFE8964A9192AE93`
SHA512 | `7259E41DF37670647852E6FD821FA596F94FCE913E1A796532E4179CDE317F418B06BF34C9A6F49D8DDDF6CD45ED79EF602CA6D471A284601B1FFBB03B799302`
SSDEEP | `1536:GxUmWLpC/u04jTsYh51ioJ9VF1lT45ikrCBo1cqITCcgH+l:GxDMq40iXJ9f1iWW1cqITRvl`
IMP | `2A9E8EF4B4A8386BA6D1261855062BD7`
PESHA1 | `1F09CB8BA47E5F2FB4713177E16BA9DD08053BC9`
PE256 | `4D8849C79F1EC5B934C1A778C8A9A0CDADAF177179EBACD7141AE63D4D0AAFC7`

## Runtime Data

### Usage (stdout):
```cmhg
MsiCert V 5.0
Copyright (c) Microsoft Corporation. All Rights Reserved

MsiCert will populate the MsiDigitalSignature and MsiDigitalCertificate tables
for a given Media entry and cabinet


Syntax: msicert -d {database} -m {media entry} -c {cabinet} [-h]
	 -d: the database to update
	 -m: the media entry in the Media table representing the cabinet
	 -c: the digitally signed cabinet
	 -h: (optional) include the hash of the digital signature
	 -?: display this help message
	 -nologo: do not display the logo message

The default behavior is to populate the MsiDigitalSignature
and MsiDigitalCertificate tables with the signer certificate
information from the digitally signed cabinet.  The MsiDigitalSignature
and MsiDigitalCertificate tables will be created if necessary.

```

### Child Processes:
csrss.exe wininit.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\MsiCert.exe |
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

* Original Filename: msicert.exe
* Product Name: Windows Installer
* Company Name: Microsoft Corporation
* File Version: 5.0.19041.1 (WinBuild.160101.0800)
* Product Version: 5.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


