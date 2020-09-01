---
title: vcredist_x86.exe | Microsoft Visual C++ 2012 Redistributable (x86) - 11.0.61030
---

# vcredist_x86.exe 

* File Path: `C:\ProgramData\Package Cache\{00000000-0000-0000-0000-000000000000}\vcredist_x86.exe`
* Description: Microsoft Visual C++ 2012 Redistributable (x86) - 11.0.61030

## Hashes

Type | Hash
-- | --
MD5 | `1191BA2A9908EE79C0220221233E850A`
SHA1 | `F2ACD26B864B38821BA3637F8F701B8BA19C434F`
SHA256 | `4670E1ECB4B136D81148401CD71737CCF1376C772FA513A3E176B8CE8B8F982D`
SHA384 | `D77003D5234E12CDBA76C95CE1E97B88BCE9101CBDE04DE99875F0F7A00FE76C0DD8A2F629B684C2ECA7A2BF29A0C696`
SHA512 | `DA61B9BAA2F2AEDC5ECB1D664368AFFFE080F76E5D167494CEA9F8E72A03A8C2484C24A36D4042A6FD8602AB1ADC946546A83FC6A4968DFAA8955E3E3A4C2E50`
SSDEEP | `12288:LZc0IursYCYQeSnyZJiqlEbXSb9NtoqOFBqkYHp:DMYenGJiKEbXWtpOLl8`

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\VaultCmd.exe |


## Signature

* Status: Signature verified.
* Serial: `33000000B011AF0A8BD03B9FDD0001000000B0`
* Thumbprint: `108E2BA23632620C427C570B6D9DB51AC31387FE`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vcredist_x86.exe
* Product Name: Microsoft Visual C++ 2012 Redistributable (x86) - 11.0.61030
* Company Name: Microsoft Corporation
* File Version: 11.0.61030.0
* Product Version: 11.0.61030.0
* Language: English (United States)
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\ProgramData\Package Cache\{00000000-0000-0000-0000-000000000000}\vcredist_x64.exe](vcredist_x64.exe-2B48F69517044D82E1EE675B1690C08B.md) | 75

## Possible Misuse

*The following table contains possible examples of `vcredist_x86.exe` being misused. While `vcredist_x86.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1095.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1095/T1095.md) |   Start-Process (Join-Path $unzipPath "vcredist_x86.exe") | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


