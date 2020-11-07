---
title: gpsvc.dll | Group Policy Client
excerpt: What is gpsvc.dll?
---

# gpsvc.dll 

* File Path: `C:\Windows\system32\gpsvc.dll`
* Description: Group Policy Client

## Hashes

Type | Hash
-- | --
MD5 | `E454D5476CCE91C0CC0A7001E0EBE353`
SHA1 | `C4D343219BDD1BDD01532285CC58E4C96D4F4848`
SHA256 | `0648AC5568B73579B827FD2C57A0F3AB248B8FA2894FB7EA9FAB0AA3B4818D5D`
SHA384 | `92E0A601B7652161E1AAC01877F4A8925C8DDBEDDFD5645EBEEDDBCFD621FC6AECA3DA5872FF77C6C881A6746519FE39`
SHA512 | `1C2AD777D8E4C4B2A18A09501B0AFFB9970C90369834580B5EF5BB8E080E2F8A9797CA49D1F29888A1121204F0224C07A4042B2FA83BAE254317A172FE062198`
SSDEEP | `24576:DTPxgvW5s+L7tB+VvJqJSm0kpnDOxSCv/jmuv0yF87u20KuAU:DTPxgvks67ls5AnDDOmuUu20KuA`
IMP | `B51B91F2CD8917E5BAF0884D20B76C4F`
PESHA1 | `50BE87F5278F7CD55E3E18189726E1B59C1251A1`
PE256 | `5C5DF73F3AE655A77A707EF342333B5B975B5A3D1B497662633701F5E8CDDB47`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 109 | Exported Function
`DllGetClassObject` | 110 | Exported Function
`GenerateRsopPolicy` | 111 | Exported Function
`GroupPolicyClientServiceMain` | 107 | Exported Function
`IsSecureCachingDisabled` | 112 | Exported Function
`ProcessGroupPolicyCompletedExInternal` | 113 | Exported Function
`ProcessGroupPolicyCompletedInternal` | 114 | Exported Function
`RsopAccessCheckByTypeInternal` | 115 | Exported Function
`RsopFileAccessCheckInternal` | 116 | Exported Function
`RsopResetPolicySettingStatusInternal` | 117 | Exported Function
`RsopSetPolicySettingStatusInternal` | 118 | Exported Function
`SvchostPushServiceGlobals` | 108 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: gpsvc.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/0648ac5568b73579b827fd2c57a0f3ab248b8fa2894fb7ea9fab0aa3b4818d5d/detection/


## Possible Misuse

*The following table contains possible examples of `gpsvc.dll` being misused. While `gpsvc.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`gpsvc.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


