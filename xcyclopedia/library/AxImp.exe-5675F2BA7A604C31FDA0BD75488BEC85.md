---
title: AxImp.exe | .NET Framework Windows forms ActiveX conversion utility
excerpt: What is AxImp.exe?
---

# AxImp.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\AxImp.exe`
* Description: .NET Framework Windows forms ActiveX conversion utility
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `5675F2BA7A604C31FDA0BD75488BEC85`
SHA1 | `2E083C1E5306C18C8C24FE85B86E1EF43175F9B1`
SHA256 | `B9B5F16CD710DC3EF4A2DA440AD5B5AC06385E1E7187F27C6CC1EFA631A18E4E`
SHA384 | `B6EFAAAA57997752B0388A0022E0BFE52DD291038D4A3940C6492D14DD639A1BF1B0AF68B47966B22D6E2C25CB269429`
SHA512 | `EF669C8B5874EFCAF9F4D55135D5B4E56459086C13A35539A86D3E78D9C6A429198B48BC940BB2B563DAFBEAEEC3BCD06380034596DFFF4519A2F860CBC5B01A`
SSDEEP | `768:R3IqpkgaFC9l/3SXwXdv5/Iyd6Iq8zf7bwG/5OEWtJqWA/bV8Aeuko:R/p2glPSX6dB/90aAG/5OEWtnSWAeul`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `9EB7540BAA96D2DE4E51E2C16C9AD6D79A61E7ED`
PE256 | `EE3F287F7DE0AD942523B7A4A37A90D8BF8D4D8B7BEEFC279D50AADC2F5B4336`

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
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\AxImp.exe |
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

* Original Filename: AxImp.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/b9b5f16cd710dc3ef4a2da440ad5b5ac06385e1e7187f27c6cc1efa631a18e4e/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\AxImp.exe](AxImp.exe-8F1DC3A76AE04FD73E84D5936BACFDB9.md) | 74




MIT License. Copyright (c) 2020 Strontic.


