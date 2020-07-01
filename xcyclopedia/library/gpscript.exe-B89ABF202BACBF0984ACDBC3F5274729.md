---
title: gpscript.exe | Group Policy Script Application
---

# gpscript.exe 

* File Path: `C:\windows\SysWOW64\gpscript.exe`
* Description: Group Policy Script Application
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B89ABF202BACBF0984ACDBC3F5274729`
SHA1 | `337FF28806A6D8E20C9892AE3A9E8265A60CD93E`
SHA256 | `4D6B2E5242862760CB9D4B848DF760CD3A5A011DD59A5C633EC966D32D1D6EA2`
SHA384 | `D9302795CB0CA13D2B95F0246FB910B3AD7D3E4A9DFD139695353E8C43CB677EFB38BEC266C496FBAE572F0BDA3BA550`
SHA512 | `A57F38D9F132352D57608CCA9F51F64677A472CE644253C1EF91BB94BC6B9A6839B3602BC2BC85B3A68AA258D27371331394F56EFB1D8A3C11F166BA4EB3FDD3`
SSDEEP | `768:Q8oplU+Bk3yO2i/9cSwJz4LK4drFbE16/BSAl2ln8031udT/ZGRnxK:+++Bk3d1cS6z43FgE/BSAj031udThGRn`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GPSCRIPT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `gpscript.exe` being misused. While `gpscript.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `Name: Gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `  - Command: Gpscript /logon` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `  - Command: Gpscript /startup` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `  - Path: C:\Windows\System32\gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `  - Path: C:\Windows\SysWOW64\gpscript.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | ` - IOC: Execution of Gpscript.exe after logon` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Gpscript.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Gpscript.yml) | `  - Link: https://oddvar.moe/2018/04/27/gpscript-exe-another-lolbin-to-the-list/` | 



MIT License. Copyright (c) 2020 Strontic.


