---
title: hwrcomp.exe | Microsoft Custom Dictionary Compiler
---

# hwrcomp.exe 

* File Path: `C:\Windows\system32\hwrcomp.exe`
* Description: Microsoft Custom Dictionary Compiler

## Hashes

Type | Hash
-- | --
MD5 | `138DE62F2F6AE9249EA596A8A5F142B2`
SHA1 | `0FBCFD4BB74FD9B7567521DD0C02A1D39BB3C42F`
SHA256 | `365AD0B7CD24CB91E106B3358E9E099811BAE145338F796A92E11C4952E57787`
SHA384 | `2A599E89A0857EFD0DB5015B344CD9F28ED0600DCAB803895D12306EF5B2499B2B37D1E98B726E75C0222994435EE919`
SHA512 | `E27961F581625F7C505B075B22AF677CB93741709A7B6C70E98AF024A22F7D30C35B6BDC9C6FF5878CF4B888747DEA9C2463F9112674F75537AE2E889B249A94`
SSDEEP | `768:bT2c85/Y9R1lef/xxu2InDvov3+gnOV04chZWoz9c8o4Jg3Q3dFbcEa424by4:pz9Do/nuXr4+gny0wo9Jgg3dZcEa4Te4`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: hwrcomp [-lang <locale>]
               [-type <type>]
               [-comment <comment>]
               [-check | -o <dictfile.hwrdict>]
               <inputfile>

-check                Verify the input file
-lang <locale>        Assign this default language to the dictionary file.
                      Locale is of the form <language>-<REGION> using ISO codes
-type <type>          Assign this type to the dictionary file
-comment <comment>    Compile this comment into the dictionary file
-o <dictfile.hwrdict> Output to this file name.
                      If this option is missing, use <inputfile>.hwrdict

Examples:
hwrcomp -check mylist1.txt
  verifies file content
hwrcomp -lang en-US -type SECONDARY-DICTIONARY -o myrsrc1 mylist1.txt 
  compiles mylist1.txt into myrsrc1.hwrdict,
  assigns language 'English (US)' and type 'SECONDARY-DICTIONARY'


```

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: HWRComp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


