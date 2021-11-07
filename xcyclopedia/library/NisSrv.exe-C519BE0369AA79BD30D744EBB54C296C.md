---
title: NisSrv.exe | Microsoft Network Realtime Inspection Service
excerpt: What is NisSrv.exe?
---

# NisSrv.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.9-0\NisSrv.exe`
* Description: Microsoft Network Realtime Inspection Service

## Hashes

Type | Hash
-- | --
MD5 | `C519BE0369AA79BD30D744EBB54C296C`
SHA1 | `4F73FA06D716DE090E7299B6B88BF9938B6479E3`
SHA256 | `7771F332FFB71B2C9668DE3C5AA14617E26D00A21C931DEB2DCE0776CA3EE02A`
SHA384 | `E54B61C87343A9D56AC3E3503E073BB049447DB325EC523D11157D334CC5068F78270E1792E668EE2F77ED9C7D0E1367`
SHA512 | `D8BB374AB42799EED413B677AEEF2097B20A0DF5BA0FFEDB8632FD4E9095EADD0E3612AEB106D423193F770383F173FE1B1B376993BEB04D404B30DF154C4AA0`
SSDEEP | `49152:ehfaICkvvT4YAhYc+wjrMsunQrBTSSy7RcbMV3AMFSl09zhXgeHibn:eKNYs8ir`
IMP | `4DECE0E26698C1D6E3536B7EDD46D8F1`
PESHA1 | `594C999E8704AA9461B1449A750C7A83C9745D4E`
PE256 | `F88F13FD89B82BA33A3E556BB3B4CB80F3B7351B1FDD44A80C187C20DCCB468F`

## Signature

* Status: Signature verified.
* Serial: `330000024A0E8AFDF15C662D2B00000000024A`
* Thumbprint: `96384A7F5F1C438F32E2454697DC6D312A74517B`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NisSrv.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.2008.9 (WinBuild.160101.0800)
* Product Version: 4.18.2008.9
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/7771f332ffb71b2c9668de3c5aa14617e26d00a21c931deb2dce0776ca3ee02a/detection/


## Possible Misuse

*The following table contains possible examples of `NisSrv.exe` being misused. While `NisSrv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_reg_disable_sec_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_reg_disable_sec_services.yml) | `- '\NisSrv'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


