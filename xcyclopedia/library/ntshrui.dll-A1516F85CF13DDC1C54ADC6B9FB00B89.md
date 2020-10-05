---
title: ntshrui.dll | Shell extensions for sharing
excerpt: What is ntshrui.dll?
---

# ntshrui.dll 

* File Path: `C:\Windows\SysWOW64\ntshrui.dll`
* Description: Shell extensions for sharing

## Hashes

Type | Hash
-- | --
MD5 | `A1516F85CF13DDC1C54ADC6B9FB00B89`
SHA1 | `446EC83894C198CDC72AF883134AEC5048F247B3`
SHA256 | `1538E9E2E075265DA414FAC4FFB918C8CCCA01DBD3C1A79CE8BC344CE7959A14`
SHA384 | `BE10CA711709795D1A5FD5648467375311A86FBC6FAE5EB317DA2D466E5E6845B6B5F43CED1D64C01DB4B2658A8D71F4`
SHA512 | `1337B02C767FBDEBA5145DEBDBB33EA53170CE49ECFFEC1776893EB04DC2D6A3E51C6F8EDFC0115D803CE4F822C7CB1DDA0C458B52693050828C473A8F22728F`
SSDEEP | `6144:rLJOzkD9XsGz0agH8vtQKdP8MntXdGavqdvMR3mFfLnsa4J+m1y+CW6M50PTKze:4kD9pYKF8IdDqdvI3mFDzV+NkTK`
IMP | `C567F15D689121BDA2466DBBE5B5041F`
PESHA1 | `112C34A3A903E8AA95D8B79584F213E744840E52`
PE256 | `6FCE92696F9B56489DFC0E0272969DCAAA8325873A402CEEFB5B2C3D8BFFD84F`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`IsPathShared` | 11 | Exported Function
`IsFolderPrivateForUser` | 10 | Exported Function
`GetNetResourceFromLocalPathW` | 9 | Exported Function
`IsPathSharedA` | 12 | Exported Function
`ShowShareFolderUI` | 15 | Exported Function
`SetFolderPermissionsForSharing` | 14 | Exported Function
`IsPathSharedW` | 13 | Exported Function
`GetNetResourceFromLocalPathA` | 8 | Exported Function
`DllGetClassObject` | 3 | Exported Function
`DllCanUnloadNow` | 2 | Exported Function
`CanShareFolder` | 1 | Exported Function
`GetLocalPathFromNetResource` | 4 | Exported Function
`GetNetResourceFromLocalPath` | 7 | Exported Function
`GetLocalPathFromNetResourceW` | 6 | Exported Function
`GetLocalPathFromNetResourceA` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ntshrui.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/1538e9e2e075265da414fac4ffb918c8ccca01dbd3c1a79ce8bc344ce7959a14/detection/


## Possible Misuse

*The following table contains possible examples of `ntshrui.dll` being misused. While `ntshrui.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [groundbait](https://github.com/eset/malware-ioc/blob/master/groundbait/README.adoc) | `- `%WINDIR%\ntshrui.dll`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


