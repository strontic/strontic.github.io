---
title: CorFlags.exe | Microsoft Common Language Runtime Agnostic Assembly Conversion Tool
excerpt: What is CorFlags.exe?
---

# CorFlags.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\CorFlags.exe`
* Description: Microsoft Common Language Runtime Agnostic Assembly Conversion Tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `01CC4822FE50180CC5D459A8B21E96D0`
SHA1 | `248A3172661ED65BD57F6D54EAC1F4FE6CFD2B7D`
SHA256 | `98AF83697D51AD5E529AD3AACFEA5717851371D45A48EAA6BA2BAB013B142A02`
SHA384 | `D5B0BF4B53BC886A1A2E73F14A096C058725441EABBDC15B3314AF9E45C7DD2E71E1D3D286D971B8CD357230ECFADAB7`
SHA512 | `04AAEA187F540498F1C721236FB12B23C50DA1CD8F97B84C9D3E0FEF2AA5A4B4198A8C24FEF4D299C51CC869509B0F950A17F05C2423F0F4235FE83E1C5CF146`
SSDEEP | `3072:3ym0jmY04me/zHPcaV1E/IN0i8xzvXTBjpt/c8ptVLUrkh425s+HK2E:rK/E/e0i8xDJpJc8Zow4Ws+HKl`
IMP | `84EDC1DB7D6233B2DC3A9D515E266A8B`
PESHA1 | `855413E51A5C6FC6CFFF42D2722C5A30C1C92AAC`
PE256 | `F48EC3B5F12E4F04819E400BFD4E54F7393DFC67B9268DBE322E01C7261067D2`

## Runtime Data

### Usage (stdout):
```cmhg
corflags : error CF000 : Invalid option (--help)

Microsoft (R) .NET Framework CorFlags Conversion Tool.  Version  4.8.4084.0
Copyright (c) Microsoft Corporation.  All rights reserved.

Usage: Corflags.exe Assembly [options]

If no options are specified, the flags for the given image are displayed.

Options:
/ILONLY+ /ILONLY-       Sets/clears the ILONLY flag
/32BITREQ+ /32BITREQ-   Sets/clears the bits indicating 32-bit x86 only
/32BITPREF+ /32BITPREF- Sets/clears the bits indicating 32-bit preferred
/UpgradeCLRHeader       Upgrade the CLR Header to version 2.5
/RevertCLRHeader        Revert the CLR Header to version 2.0
/Force                  Force an assembly update even if the image is
                        strong name signed.
                        WARNING: Updating a strong name signed assembly
                         will require the assembly to be resigned before
                         it will execute properly.
/nologo                 Prevents corflags from displaying logo

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\CorFlags.exe |
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

* Original Filename: CorFlags.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/98af83697d51ad5e529ad3aacfea5717851371d45a48eaa6ba2bab013b142a02/detection





MIT License. Copyright (c) 2020-2021 Strontic.


