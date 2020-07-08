---
title: wusa.exe | Windows Update Standalone Installer
---

# wusa.exe 

* File Path: `C:\windows\system32\wusa.exe`
* Description: Windows Update Standalone Installer

## Screenshot

![wusa.exe](screenshots/wusa.exe-6C81724C47077509C4CC874E34008FC3-2.png)

## Hashes

Type | Hash
-- | --
MD5 | `59701FE9C8BA85BCEB73A9B1B3E8E1C4`
SHA1 | `41C0812B0BE63153F3B68EA76C8B985D69DDCFBB`
SHA256 | `E0438C5594A4EEB8515518989EE3A773581F414273B857B885D2201F66A95B06`
SHA384 | `8CF139BA0B9ADF180448ED29660BCE78D19D6BB8FE55CF52104CD5C83B1FB8FC3D9FE61364A3C80D39D765B13E55CC39`
SHA512 | `197279F4F762D2746E5D67FEC5B94CD569647B9BEB79B0A6069C20A1D4C2DD36808F8B546CD8F0E7E515D744F05654D9D704C3FBD8ECA951F6B4A8E16BAB8C8A`
SSDEEP | `3072:SjomFcaF4iHSd5bqcoENXK6JRAqs4xjw8m1IRpR9/BRMp3cKAArDZz4N9GhbkUNJ:Sj9FjuiebqcoMHxM8cg9wpxyN90vE`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wusa.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\PkgMgr.exe](PkgMgr.exe-16C0DDFCE82A53516E634F691689EBB6.md) | 43
[C:\windows\system32\PkgMgr.exe](PkgMgr.exe-B212B2FE6910AF8B2068F2FF2242204F.md) | 36
[C:\Windows\system32\PkgMgr.exe](PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10.md) | 43
[C:\Windows\system32\PkgMgr.exe](PkgMgr.exe-DDE0B63F2E276B969C9C1E6983990CB2.md) | 43
[C:\windows\system32\wextract.exe](wextract.exe-4B9C652BD0FD95A9E6123913C35519D6.md) | 43
[C:\Windows\system32\wextract.exe](wextract.exe-56E501E3E49CFDE55EB1CAABE6913E45.md) | 43
[C:\Windows\system32\wextract.exe](wextract.exe-91243AFCF25E3A7705CAAA03492996B7.md) | 44
[C:\WINDOWS\system32\wextract.exe](wextract.exe-A740582789B3622EAAA53D2D31955363.md) | 43
[C:\Windows\system32\wextract.exe](wextract.exe-EF82872F2141313EF07C49405145DF3B.md) | 41
[C:\WINDOWS\system32\wusa.exe](wusa.exe-7E8AE39BE13B6F0A7CAD480B7148123F.md) | 58
[C:\windows\system32\wusa.exe](wusa.exe-8930570F7F76840334962EFC6C173438.md) | 50
[C:\Windows\system32\wusa.exe](wusa.exe-8A0B789F779802881EEAC4F99532A35C.md) | 44
[C:\Windows\system32\wusa.exe](wusa.exe-E7A1BF42A43A9031533768B393D5673A.md) | 47
[C:\WINDOWS\SysWOW64\wextract.exe](wextract.exe-3035914DF08E473A10745C662047A63D.md) | 40
[C:\Windows\SysWOW64\wextract.exe](wextract.exe-330C79E31445B8A75F18EB503BC07029.md) | 44
[C:\Windows\SysWOW64\wextract.exe](wextract.exe-7CD5F431EA58317F3B2E582F2D1DDFE9.md) | 40
[C:\windows\SysWOW64\wextract.exe](wextract.exe-A66A88FFE53BBB9DDAACE0110A8232EC.md) | 47
[C:\Windows\SysWOW64\wextract.exe](wextract.exe-B9CC7E24DB7DE2E75678761B1D8BAC3E.md) | 40
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-18DE1F2C1BC5B1AFE3A66DD973C69411.md) | 43
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-6C81724C47077509C4CC874E34008FC3.md) | 46
[C:\Windows\SysWOW64\wusa.exe](wusa.exe-A60D32269A6A6E7BFDC50E22A70B8F54.md) | 40
[C:\WINDOWS\SysWOW64\wusa.exe](wusa.exe-C46BE74BD433DD95952142967E3F1F9A.md) | 38
[C:\windows\SysWOW64\wusa.exe](wusa.exe-F3EF56F76D69361022B47EF1E6201644.md) | 41

## Possible Misuse

*The following table contains possible examples of `wusa.exe` being misused. While `wusa.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) |       $s5 = "wusa.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) |       $s4 = "wusa.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


