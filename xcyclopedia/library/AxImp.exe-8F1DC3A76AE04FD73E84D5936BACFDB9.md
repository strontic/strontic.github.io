---
title: AxImp.exe | .NET Framework Windows forms ActiveX conversion utility
excerpt: What is AxImp.exe?
---

# AxImp.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\AxImp.exe`
* Description: .NET Framework Windows forms ActiveX conversion utility
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `8F1DC3A76AE04FD73E84D5936BACFDB9`
SHA1 | `80F75DC9E3937F71D47CC6A064021BAEFA33BCA4`
SHA256 | `23701485B9493F9C1BAEABD7E4F3D80D4DD5D6FA9BB0D3A9050690977E07312B`
SHA384 | `491A0EF773EF5F0447B8C8F1A4069D55D1E5F2D5565E06F9F470F059813CC72E9337E1633BEAC6047749C056E95F3BAE`
SHA512 | `37E0584E0FBE7A89260F3159B262292EDE3458BEEB065AC5BB31040864171811CC82034019F0F7C4E3BEDBA4CC65AD6A2B028E35D5AABA30F87A970C2DCB2914`
SSDEEP | `768:X3Iqp37aFC9l/3SXwXdv5yIyd6Iq8zf7bwG/5OECQ2qWqx8v4D:X/p8glPSX6dBy90aAG/5OECbqaAD`
PESHA1 | `2CBFB4FCE1FDC4CA32FE6BFE838CDA614D5095AA`
PE256 | `121C937ACCDCA0CF6BC296E00E941562D3E295C44EC91927BD0742A177F8865B`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET ActiveX Control to Windows Forms Assembly Generator 
[Microsoft .Net Framework, Version 4.8.4084.0]
Copyright (C) Microsoft Corporation.  All rights reserved.


Generates a Windows Forms Control that wraps ActiveX controls defined in the given OcxName.

Usage:
   AxImp OcxName [Options]
Options:
   /out:FileName            File name of assembly to be produced
   /publickey:FileName      File containing strong name public key
   /keyfile:FileName        File containing strong name key pair
   /keycontainer:FileName   Key container holding strong name key pair
   /delaysign               Force strong name delay signing
                            Used with /keyfile, /keycontainer or /publickey
   /source                  Generate C# source code for Windows Forms wrapper
   /rcw:FileName            Assembly to use for Runtime Callable Wrapper rather than generating new one.
                            Multiple instances of this option may be specified. Current directory is used
                            as a root for relative paths
   /ignoreregisteredocx     version of 'OcxName' library supplied on the command line is used to generate
                             the Windows Forms wrapper, if this type library is registered on the machine,
                            then the registered version is ignored
   /nologo                  Prevents AxImp from displaying logo
   /silent                  Prevents AxImp from displaying success message
   /verbose                 Displays extra information
   /? or /help              Display this usage message

```

### Usage (stderr):
```cmhg
AxImp Error: Unknown option: /-help

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\AxImp.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AxImp.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/23701485b9493f9c1baeabd7e4f3d80d4dd5d6fa9bb0d3a9050690977e07312b/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\AxImp.exe](AxImp.exe-5675F2BA7A604C31FDA0BD75488BEC85.md) | 74




MIT License. Copyright (c) 2020-2021 Strontic.


