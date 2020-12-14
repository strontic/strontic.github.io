---
title: wab32.dll | Microsoft (R) Contacts DLL
excerpt: What is wab32.dll?
---

# wab32.dll 

* File Path: `C:\Program Files (x86)\Common Files\System\wab32.dll`
* Description: Microsoft (R) Contacts DLL

## Hashes

Type | Hash
-- | --
MD5 | `6872F7CF47415E5BA936F2ED8F77D8D5`
SHA1 | `ACE06FD4F8F2A394C9E4A4ED603F14195B0E36AE`
SHA256 | `397B7E02E68FF73A572101008FCD0C112D865DD13EDB6832AAE047BEE3EF4818`
SHA384 | `45CFBA2EAD51CCB0F6DE31AFB375D0A2A3239B111F00D4A9DF9EC30530477B01E36291F825277D4311B397849A972856`
SHA512 | `CE695D2EF211B3D028A3BCDB9F79AF4F0D10DF4380610659AC4468A8C46D6C584AF70CBD381882BED450799B4E5ABF813D890BC5EC571C8C626049BFDF485490`
SSDEEP | `12288:qlwYI3H18oE+TlPTpc+p1/wyYxIL7VZaJUx5X1UZanoy8cDvTx5KRZV:qlwbC6La+TwdIL7SJAWZwocAV`
IMP | `FA7C8996EEAA85C49BA32A4910F02708`
PESHA1 | `79BF8A9FF670871C204032532025EF17C1A202A9`
PE256 | `5FD933FD6EA2DEB7463012FF07623B013CA391DD62F26CBF08A182233468F920`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ShellUICommand_OnImportW` | 16 | Exported Function
`ShellUICommand_OnNewContactW` | 13 | Exported Function
`ShellUICommand_OnExportW` | 17 | Exported Function
`Ordinal9` | 9 | Exported Function
`ShellUICommand_OnEditW` | 15 | Exported Function
`WABOpen` | 2 | Exported Function
`WABOpenEx` | 4 | Exported Function
`WABCreateIProp` | 3 | Exported Function
`ShellUICommand_OnNewEmailW` | 12 | Exported Function
`ShellUICommand_OnNewGroupW` | 14 | Exported Function
`Ordinal8` | 8 | Exported Function
`Ordinal11` | 11 | Exported Function
`Ordinal22` | 22 | Exported Function
`Ordinal10` | 10 | Exported Function
`DllCanUnloadNow` | 18 | Exported Function
`DllGetClassObject` | 19 | Exported Function
`Ordinal6` | 6 | Exported Function
`Ordinal7` | 7 | Exported Function
`Ordinal5` | 5 | Exported Function
`Ordinal23` | 23 | Exported Function
`Ordinal24` | 24 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WAB32.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.388 (WinBuild.160101.0800)
* Product Version: 10.0.19041.388
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/397b7e02e68ff73a572101008fcd0c112d865dd13edb6832aae047bee3ef4818/detection/

## Possible Misuse

*The following table contains possible examples of `wab32.dll` being misused. While `wab32.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s0 = "C:\\Program Files\\Common Files\\System\\wab32" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


