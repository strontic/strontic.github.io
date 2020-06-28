---
title: msconfig.exe | MSCONFIG MFC APPLICATION
---

# msconfig.exe 

* File Path: `C:\Windows\system32\msconfig.exe`
* Description: MSCONFIG MFC APPLICATION
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EA390568A41C03B6327AAE1873664B45`
SHA1 | `8A21D11428FF89CA42B8A997FDB7A89A1CA12A9D`
SHA256 | `AC9B4A57BE180E2BAB2CC2718D017FE9FC806927DA69B82B0BAA229C4065ECD2`
SHA384 | `A559F2A35F1B6C23BBA46E6B44E936B37E77A6A257E1380BAAE04EB4A2730929117FC76211210DFEF6DEC0E56F6AF4DE`
SHA512 | `6E5BDB1B5BB65FCD175A3A268A63AC4C80E76B1A2E6C167551DD5BE19A5FE3F21AB5754B8B5E7A60DA7C36045352F32FC686CCE8615F153927C6D244E0C3607D`
SSDEEP | `3072:GixBrgOYNvtt4DIIsYhCx8oMFir9fUd0/HlGJRA1:GirgObIIsYYSFkUdSGJRW`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSCONFIG.EXE
* Product Name: MSCONFIG APPLICATION
* Company Name: Microsoft Windows Operating System
* File Version: 1, 0, 0, 1
* Product Version: 1, 0, 0, 1
* Language: English (United States)
* Legal Copyright: COPYRIGHT (c) Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\msconfig.exe](msconfig.exe-C39148DD0D650E2C49095237998218F2.md) | 41
[C:\WINDOWS\system32\msconfig.exe](msconfig.exe-EC284B6D1AFBBA44211F4F0C3EA44838.md) | 47

## Possible Misuse

*The following table contains possible examples of `msconfig.exe` being misused. While `msconfig.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Name: Msconfig.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `Description: MSConfig is a troubleshooting tool which is used to temporarily disable or re-enable software, device drivers or Windows services that run during startup process to help the user determine the cause of a problem with Windows` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `  - Command: Msconfig.exe -5` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `    Usecase: Code execution using Msconfig.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | `  - Path: C:\Windows\System32\msconfig.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msconfig.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msconfig.yml) | ` - IOC: msconfig.exe executing` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`msconfig.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


