---
title: PEVerify.exe | Microsoft .NET Framework PE, Metadata and IL Verification Tool
excerpt: What is PEVerify.exe?
---

# PEVerify.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\PEVerify.exe`
* Description: Microsoft .NET Framework PE, Metadata and IL Verification Tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `1B735EB9E463BE009BC52F28A86F7D5D`
SHA1 | `29C167CA8FB0257003EC0A2E426CDF3AFE3F692B`
SHA256 | `6C89FC6FA70130DFF015271BFBB580BF100EAA3FC168B5BBD4B762E9CBEFD251`
SHA384 | `6E5B0EAD2269CC94FBFBD886CCEDDF2B109F6F4445B3FE56C2C36A83D5AC51506853AEA87448BA98E5EC595CDE968F82`
SHA512 | `2E33F2F02A1D1B811DF111182A26EDD13BCEBA6AC4694138890F5BB3347AF9FD5CF18C1850337220CC2026A522E26F483A3E65FD645B812C5F920C5C8532110A`
SSDEEP | `6144:xySBYI5nomXZC0kOxFnkXdr0I8sUodCZc2hx+ut6EJH2Qg:xygYWomXA0kOxFnkB0IrUod6+Qg`
IMP | `FCE4B3FCE7172B533D57FCDAA56D92DC`
PESHA1 | `C1BFD5249132400A2D93BCD924BE5A87B0F081D7`
PE256 | `67C084218E958144070384F101D15DA2C6A411D1778CFD679D205213F911AC2E`

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
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\PEVerify.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6c89fc6fa70130dff015271bfbb580bf100eaa3fc168b5bbd4b762e9cbefd251/detection





MIT License. Copyright (c) 2020 Strontic.


