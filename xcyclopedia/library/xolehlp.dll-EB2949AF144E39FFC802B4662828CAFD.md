---
title: xolehlp.dll | Microsoft Distributed Transaction Coordinator Helper APIs DLL
excerpt: What is xolehlp.dll?
---

# xolehlp.dll 

* File Path: `C:\Windows\system32\xolehlp.dll`
* Description: Microsoft Distributed Transaction Coordinator Helper APIs DLL

## Hashes

Type | Hash
-- | --
MD5 | `EB2949AF144E39FFC802B4662828CAFD`
SHA1 | `3799699202396CC66D02C0FD79067AF887308D41`
SHA256 | `4746E1FB132157769F865DC6064ADE1E3F17F0A8A7F59206C4DB5224CAF8EB91`
SHA384 | `AD976E9D7F4FF340DF4D41F8067C48493581DB80A847B9C0680D4D41DDFCFD5AABEC35A7171F913812BF9694BD3CA628`
SHA512 | `B3EAD5ABFB6A8D064F51BE4C85C2A094ADFF2BEF71DD39592F834349CBE64E76F8DBA26978B8D7C925EDF62C166688F1A4DA85CDC466A61A9B137A997E7F40E8`
SSDEEP | `1536:PvKvgF7+BfcuDzYFRULyBUdA9EQmthfAJ/3:nKv5UuDzYFhb9jOFAJ/3`
IMP | `D186F5CCC94176E9FAC64F51F86DC312`
PESHA1 | `26D98BAB7EA2F426B75F5123A0EB5FD193A79E42`
PE256 | `7D414079969AD835AD7EA6073022775E0E9B8CBFA6082EF4FB796E09EF6312B5`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`FreezeLocalTransactionManagers` | 8 | Exported Function
`DtcGetTransactionManagerExW` | 11 | Exported Function
`ThawLocalTransactionManagers` | 9 | Exported Function
`GetDtcLocaleResourceHandle` | 4 | Exported Function
`DtcGetTransactionManagerC` | 7 | Exported Function
`DtcGetTransactionManager` | 5 | Exported Function
`DtcGetTransactionManagerExA` | 10 | Exported Function
`DtcGetTransactionManagerEx` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: XOLEHLP.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 2001.12.10941.16384 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/4746e1fb132157769f865dc6064ade1e3f17f0a8a7f59206c4db5224caf8eb91/detection/


## Possible Misuse

*The following table contains possible examples of `xolehlp.dll` being misused. While `xolehlp.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s3 = "XOLEHLP.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


