---
title: CompMgmtLauncher.exe | Computer Management Snapin Launcher
excerpt: What is CompMgmtLauncher.exe?
---

# CompMgmtLauncher.exe 

* File Path: `C:\Windows\system32\CompMgmtLauncher.exe`
* Description: Computer Management Snapin Launcher

## Hashes

Type | Hash
-- | --
MD5 | `28317A51B8F874BCF5220872269FEC2C`
SHA1 | `D26DF3B03D41FE5BA7854A04FCE7EAD17A32661B`
SHA256 | `4352BE6FDB79A4552AE9D41A088F0B6FB16E36686FAC2A69F2AB863972AD53C1`
SHA384 | `48FF12D5EEF474D8D0E89E918403ACDAB03F3D5A816D28E17B934235F506D09BA2FB4C74C8B5242EA720A4ACD3E6AF33`
SHA512 | `CFB1DA18B1FAA715E2A1B0D61D346A7E0ED0FD8DCD916D6044BFDC8B1DC6C1B1D5C716A624E5FC08E835A108E60838383642C93B36807E3B25ADD0FE5E8E11A6`
SSDEEP | `1536:9DeNdNKcJaVlpAjzfldyCKPu1oT1ldlOo+vi6Uf:BHcJazmjTldyCut1ldco+Q`

## Runtime Data

### Child Processes:
ServerManager.exe

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CompMgmtLauncher.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-E0861FA9E0A4B441C6A11405D12D0C30.md) | 35
[C:\Windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-ED3867E805501925E10070A1430E13DF.md) | 32
[C:\windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-EF0DB115967BFB1996403434AA3C9D7E.md) | 33
[C:\Windows\system32\CompMgmtLauncher.exe](CompMgmtLauncher.exe-FF9690925244473ECC4C2E5B535B8599.md) | 33
[C:\Windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-984C9F7202A43577C2A3D52A1300FFE7.md) | 33
[C:\Windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-CA3A931A56D4B2429A39871131964101.md) | 30
[C:\windows\system32\ServerManagerLauncher.exe](ServerManagerLauncher.exe-CF83A07EECB55210ADAA65EF8B4C75D8.md) | 36

## Possible Misuse

*The following table contains possible examples of `CompMgmtLauncher.exe` being misused. While `CompMgmtLauncher.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [win_apt_invisimole_uac_bypass.yml](https://github.com/eset/malware-ioc/blob/master/invisimole/sigma/win_apt_invisimole_uac_bypass.yml) | `- '\CompMgmtLauncher.exe'`{:.highlight .language-yaml} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


