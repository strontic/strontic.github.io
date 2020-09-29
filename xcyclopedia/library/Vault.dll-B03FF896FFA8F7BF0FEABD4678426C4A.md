---
title: Vault.dll | Windows vault Control Panel
excerpt: What is Vault.dll?
---

# Vault.dll 

* File Path: `C:\Windows\SysWOW64\Vault.dll`
* Description: Windows vault Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `B03FF896FFA8F7BF0FEABD4678426C4A`
SHA1 | `22CE36DD14518015DD823ED91454A6558190E464`
SHA256 | `CF9B852302EE8CE6B191C23F17E5F84B58A11BE78534ECF01854A56325ECC671`
SHA384 | `183FBF17338339269424D64B5D234233D33C0DB97459A3D5E394F79306EC5543B06B5D5AD67BC2C381634D02FD815036`
SHA512 | `920AEE332117D938033E01504554EF93A84032E6E5BA3187E93C56EF4F3428527601C0815F00F8CC38345369667F731EA7BB378F64A59CE87548E3C6F9AF85B2`
SSDEEP | `6144:USsDVa0fRKe2rxcFYJuNfREloCqX7jp4VDUhId8E0nysYLpQP:USsDw0fRLCuNfRrCeuV4hIEnpYL6P`
IMP | `9D5E2758AE15101231B46D711BD6662F`
PESHA1 | `6F2AB9773D25ACA9D307546E2DA82AD277CF6279`
PE256 | `6142E1B1C3D1E6E131822B14F05156F2B543F2A9069A6680FAEFE91CF7EB6BCA`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x1000e5b0 | 0x0000e5b0
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x1000e710 | 0x0000e710


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Vault.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/cf9b852302ee8ce6b191c23f17e5f84b58a11be78534ecf01854a56325ecc671/detection/


## Possible Misuse

*The following table contains possible examples of `Vault.dll` being misused. While `Vault.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `vault` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555.001/T1555.001.md) | To manage their credentials, users have to use additional credentials to access their keychain. If an adversary knows the credentials for the login keychain, then they can get access to all the other credentials stored in this vault. (Citation: External to DA, the OS X Way) By default, the passphrase for the keychain is the user’s logon credentials.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


