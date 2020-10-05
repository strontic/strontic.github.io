---
title: Vault.dll | Windows vault Control Panel
excerpt: What is Vault.dll?
---

# Vault.dll 

* File Path: `C:\Windows\system32\Vault.dll`
* Description: Windows vault Control Panel

## Hashes

Type | Hash
-- | --
MD5 | `1606C923179EEFDB54684CF4203AC69C`
SHA1 | `4CDAE3209D9DF6EB9B6BA72448B4670C9E73B444`
SHA256 | `E1ECCBC3845BDF5213A2FAE64BC7F0A4C5C1233333CF5716E5F198BAF19A68F5`
SHA384 | `2083EC1FBE31E53DBF55AE81CA3A448BE1F96E59B88E49645D9D6F13AEB5ADC1EA3E25C961BDE6C7FC0DE20086F2C5B4`
SHA512 | `459CA7F86DE16B5FB59399C38EAD1EA247E79E587F35862C2DC1D9FB2D638C389BE76DC9F8DBE4069BB971BA1BAE5CCA62CF766188FA2D3D2FA2A9775A5638E5`
SSDEEP | `6144:BqE/2xc8e5QpN9NI5ryDHBA9uZBHvCHah0yNC1yb:BB2XN3XDhA8ZBPUarC4b`
IMP | `C6E9CE023610E36DF2BCF9F84FBC95BD`
PESHA1 | `AF9C471380EBC4D6CC72731A45CE3760B0C8B999`
PE256 | `897994CC16DBC10686AC488947E0391EA4D63FDA86D5E16A5D4D7CF79B9C8C65`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllGetClassObject` | 2 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Vault.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/e1eccbc3845bdf5213a2fae64bc7f0a4c5c1233333cf5716e5f198baf19a68f5/detection/


## Possible Misuse

*The following table contains possible examples of `Vault.dll` being misused. While `Vault.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `vault` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555.001/T1555.001.md) | To manage their credentials, users have to use additional credentials to access their keychain. If an adversary knows the credentials for the login keychain, then they can get access to all the other credentials stored in this vault. (Citation: External to DA, the OS X Way) By default, the passphrase for the keychain is the user’s logon credentials.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


