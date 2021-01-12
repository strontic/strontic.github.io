---
title: CorFlags.exe | Microsoft Common Language Runtime Agnostic Assembly Conversion Tool
excerpt: What is CorFlags.exe?
---

# CorFlags.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\CorFlags.exe`
* Description: Microsoft Common Language Runtime Agnostic Assembly Conversion Tool
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `EA46F177C0C1E89B3EF37A415384562A`
SHA1 | `120A4571808296FDD151D74600EA2E39C75167A1`
SHA256 | `6B4301904632B25D8E1638BF3F274251D9FF1A175B525F8E1E4B93C38BDE42E0`
SHA384 | `6562F2FC1F55474B2117009BA956D327DE58EE1DF063ECEE7C986437642F87F3DFE3C25D34BF7F6AAFEFF8F2BE4CC4F7`
SHA512 | `97A19B2912165BD10295A4DE9D341E45423C6174092A0531F21F9A61B8228796CE21CCD2D52388704B8B7B4476940468C643012C29A3E32B55B16D80D71D88DC`
SSDEEP | `6144:exlU0xp1BhhTnIrxmc7b3rdEq5tpNl0JKFh1ME8:6a0nrhhTnIrxBb32wsE8`
IMP | `2BE01F61EFE0EC9BD26A9DB134AE42E3`
PESHA1 | `A260404198C2A8273ECE7DE07C97F28250CA858A`
PE256 | `E78A1696BC7343BE281F290CFAC66BB8D54FE7A7C8DCB996A00E7F063389BD8E`

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
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\x64\CorFlags.exe |
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

* Original Filename: CorFlags.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6b4301904632b25d8e1638bf3f274251d9ff1a175b525f8e1e4b93c38bde42e0/detection





MIT License. Copyright (c) 2020 Strontic.


