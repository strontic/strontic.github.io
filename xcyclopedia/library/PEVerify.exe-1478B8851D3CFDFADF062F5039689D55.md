---
title: PEVerify.exe | Microsoft .NET Framework PE, Metadata and IL Verification Tool
excerpt: What is PEVerify.exe?
---

# PEVerify.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\PEVerify.exe`
* Description: Microsoft .NET Framework PE, Metadata and IL Verification Tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `1478B8851D3CFDFADF062F5039689D55`
SHA1 | `0D82E2AAB97ECBC8AFE1F6B59A19EF1CAD1DCF9F`
SHA256 | `3590509830F027E2AEC29CF6AD5264546ABE7EC680C79B812F31244C3CE3B700`
SHA384 | `874A45C358CD8F126B4C3FDECD23931D232B1A117ADDB2D4524DC9111BA7051CD0F054DE3C27478745F8968570718B5D`
SHA512 | `1601A1DCEEAA379DAE0D22D79531C336559A7859A6124A15C48E4C458084DAA7814782EB5131ED1394FCC141C7A862681983FF65929F38660C140E315E78F555`
SSDEEP | `6144:5Vv4KEAupAITg7dOk20LANia2WjohLklfFrG4vho:c+EAN7dQiA8a+LkltrxZo`
IMP | `0030A2B878F02AB35902EA691F76DE68`
PESHA1 | `F0FDEC3F0A1918A8CD0FC61A61D2B78902ED90C3`
PE256 | `D6FF5E3501D4EEEE5E7919AD509BBC4A71998461EB8F7BF978BA50F4A0C7A64F`

## Runtime Data

### Usage (stdout):
```cmhg
Invalid option: --help 


Microsoft (R) .NET Framework PE Verifier.  Version  4.0.30319.0
Copyright (c) Microsoft Corporation.  All rights reserved.

Usage: PEverify <image file> [Options]


Options:
/IL           Verify only the PE structure and IL
/MD           Verify only the PE structure and MetaData
/TRANSPARENT  Verify only transparent methods
/UNIQUE       Disregard repeating error codes
/HRESULT      Display error codes in hex format
/CLOCK        Measure and report verification times
/IGNORE=<hex.code>[,<hex.code>...]  Ignore specified error codes
/IGNORE=@<file name>                Ignore error codes specified in <file name>
/QUIET        Display only file and Status. Do not display all errors.
/VERBOSE      Display additional info in IL verification error messages.
/NOLOGO       Don't display product version and copyright info.

Note: By default, MD is verified and then if there were no errors, IL is
      verified.  If /MD /IL options are specified, IL is verified even if
      there were MD verification errors.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\PEVerify.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: peverify.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/3590509830f027e2aec29cf6ad5264546abe7ec680c79b812f31244c3ce3b700/detection





MIT License. Copyright (c) 2020 Strontic.


