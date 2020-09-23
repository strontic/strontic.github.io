---
title: wuauclt.exe | Windows Update
excerpt: What is wuauclt.exe?
---

# wuauclt.exe 

* File Path: `C:\windows\system32\wuauclt.exe`
* Description: Windows Update

## Hashes

Type | Hash
-- | --
MD5 | `96712975BEC3BA3D244B2C0D02B42A7A`
SHA1 | `EBE9EAB10D63B7AE87B89C9FBFDA7D28CC4DBC7D`
SHA256 | `4D781547BB37E50919D6A8598277DC9DE7DD5ED4378CBAF87CDA98E48587E31E`
SHA384 | `1934E377D82739DAAC4D639F0B00B6F37785408A57607E64D5CAC91442DC04E81311FEF58B258790F043FC64C07D80ED`
SHA512 | `483151B76DCB28D9840C6A01D5DCD620B20F01B3695244E8DF5D199266DA4C7A67B783C610E5D7EC3B8036588CE894CE0510923EB77AAD4485D723B7A61ACAC5`
SSDEEP | `3072:htEamiH8qJPhtIijg1PeBhehkJCyTqCoTa5:8GJptIijgsBhZJf97`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wuauclt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 7.9.9600.19670 (winblue_ltsb.200307-0600)
* Product Version: 7.9.9600.19670
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `wuauclt.exe` being misused. While `wuauclt.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_putterpanda.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_putterpanda.yar) | $x0 = "WUAUCLT.EXE" fullword wide /* PEStudio Blacklist: strings */ /* score: '20.01' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


