---
title: pvk2pfx.exe | PVK/SPC to PFX file converter
excerpt: What is pvk2pfx.exe?
---

# pvk2pfx.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\pvk2pfx.exe`
* Description: PVK/SPC to PFX file converter

## Hashes

Type | Hash
-- | --
MD5 | `6E300F27AA19FCD62D309F6622107B68`
SHA1 | `DC2C2AF0251EF2A071CA9998774BB417F538A1D5`
SHA256 | `8BE7F023BA93DF9E2BD2D210577C82BE3B619267F3F643AC0349B596E89F7035`
SHA384 | `6E3D55B6E379D82E5096D07978970397466B7715D94792B876D1B80C3A68284ED3228A44512B42172E27019A3A98AB0D`
SHA512 | `F55E55FBFD640599809E835EF5DD30D733DF18C0A35E8BE6D9D06F3801CED182463F88E70EB4638DAB55FEBBA1C022A4C029833080913CFFE126F4DE1390D992`
SSDEEP | `384:FKfOX7OXf+twNkWuPhMpzntKKTUzjf36cMD+ptjvraWLkWkKOXkwGyq4JeRlFP:AfOXyv+5BSnKUUqLGvr3qKOUC`
IMP | `DAF4A77F27D21C03E5490E485C8C787A`
PESHA1 | `E8AA8A25BFB83883C88A406F449F7012B500ACA4`
PE256 | `41BD13834C7CB1B67EC54C1E55D36CCA5F87E8023EADA1EBFAD1A39D84A065B9`

## Runtime Data

### Usage (stderr):
```cmhg

Usage:
    pvk2pfx -pvk <pvk-file> [-pi <pvk-pswd>] -spc <spc-file>
           [-pfx <pfx-file> [-po <pfx-pswd>] [-f]]

        -pvk <pvk-file>  - input PVK file name.
        -spc <spc-file>  - input SPC file name.
        -pfx <pfx-file>  - output PFX file name.
        -pi <pvk-pswd>   - PVK password.
        -po <pfx-pswd>   - PFX password; same as -pi if not given.
        -f               - force overwrite existing PFX file.

        if -pfx option is not given, an export wizard will pop up. in
        this case, options -po and -f are ignored.


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\pvk2pfx.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pvk2pfx.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\cert2spc.exe](cert2spc.exe-A725321361AAE077A560502C1E30BCD5.md) | 32
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\pvk2pfx.exe](pvk2pfx.exe-C0002840F47F992AFA351FD697491929.md) | 30
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\pvk2pfx.exe](pvk2pfx.exe-5E4F866AD2609C77862F6D1504D39180.md) | 30
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\x64\api-ms-win-crt-utility-l1-1-0.dll](api-ms-win-crt-utility-l1-1-0.dll-0FC56003FFA56CCBB9E7B4E361F8675F.md) | 33




MIT License. Copyright (c) 2020-2021 Strontic.


