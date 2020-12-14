---
title: filemgmt.dll | Services and Shared Folders
excerpt: What is filemgmt.dll?
---

# filemgmt.dll 

* File Path: `C:\Windows\SysWOW64\filemgmt.dll`
* Description: Services and Shared Folders

## Hashes

Type | Hash
-- | --
MD5 | `760F7989FE60E07A5E2A24D8D457AB9B`
SHA1 | `5B1DA2F6EAAB514419375D65A1A7CE504D847E8D`
SHA256 | `EF5E04481B9DB138C2A6A0BC86DED9BE8C8EB367F6A44CF05D6D292793F188CB`
SHA384 | `D5B62DB0E24DC11E5A56B9CDF7E9FAB0212CC271FCEC69A9E002C584B20527EDDABA48DFA98ACA32F5F14A870038512F`
SHA512 | `8F09EBB97DFC65399295335ACD902114D71AF8FCE343890EE78C8CF696863719C044E2B3D914131096319B83E95D1764E79254459CB372D34F8EC65071739BC0`
SSDEEP | `6144:xpK68gDmZK5rVS9PQrb7kfG1+s88TnnQueaAzeKCKkf:vKwDxkkgZsNnQuqaKCzf`
IMP | `B2D8269DC2708A05CB93C0FA1734380E`
PESHA1 | `D9A4723F9F88EB8C5E6714F0BCFAF848044C71A8`
PE256 | `6E42B51956D4D3C88598E1796BFB77146DF5C0E071CDE54407BBE31D73BE6B42`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllGetClassObject` | 8 | Exported Function
`DllRegisterServer` | 9 | Exported Function
`DllUnregisterServer` | 10 | Exported Function
`CacheSettingsDlg` | 5 | Exported Function
`CacheSettingsDlg2` | 6 | Exported Function
`DllCanUnloadNow` | 7 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: filemgmt.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/ef5e04481b9db138c2a6a0bc86ded9be8c8eb367f6a44cf05d6d292793f188cb/detection/


## Possible Misuse

*The following table contains possible examples of `filemgmt.dll` being misused. While `filemgmt.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`FileMgmt.dll`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_fireeye_redteam_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_fireeye_redteam_tools.yar) | $rat5 = "rat/modules/filemgmt.(*acquire).NewCommandExecution" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


