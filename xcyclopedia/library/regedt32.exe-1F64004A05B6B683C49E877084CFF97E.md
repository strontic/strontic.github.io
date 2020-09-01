---
title: regedt32.exe | Registry Editor Utility
---

# regedt32.exe 

* File Path: `C:\Windows\SysWOW64\regedt32.exe`
* Description: Registry Editor Utility

## Hashes

Type | Hash
-- | --
MD5 | `1F64004A05B6B683C49E877084CFF97E`
SHA1 | `FFA8C1F38BC6E162B586AB71D53A3D04689DD50D`
SHA256 | `D575C86DD61B1B45314B2015A31A700E4636437F1B1738E60725119D68982603`
SHA384 | `E3F7EF2291E0BCABCD9965A486C877B35896697310596214B4272A9C8A32B37E59A41C776C3D7B1D408C4F6E0C7BE8CB`
SHA512 | `E3999CE0320A78877FB5B5D11D63770DE79DA29AACE754B0F13D126468E228F817AF1D766F4832F2989EA102E11E9D425256900CED5378A8225F77BBE0E1DFA9`
SSDEEP | `96:BQP6yb6/tfZO0ac95Ep2zyIRoVoxsDGjs0KtAtUFo3NVRrDJFMVW9EWaZhHWwD5L:BpCC39E2RowGAtUFo3NVRbEWQxWqF`

## Runtime Data

### Child Processes:
regedit.exe

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\regedt32.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: regedt32.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\regedt32.exe](regedt32.exe-6E243D43D411D8C7384883376A1F54E3.md) | 68

## Possible Misuse

*The following table contains possible examples of `regedt32.exe` being misused. While `regedt32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) |       $a3 = "regedt32.exe" wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


