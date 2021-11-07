---
title: NisSrv.exe | Microsoft Network Realtime Inspection Service
excerpt: What is NisSrv.exe?
---

# NisSrv.exe 

* File Path: `C:\Program Files\Windows Defender\NisSrv.exe`
* Description: Microsoft Network Realtime Inspection Service

## Hashes

Type | Hash
-- | --
MD5 | `A19C36423BD32B1046781CC0B3B67F41`
SHA1 | `14E54A38697321A0547142F72192ADA6219E6160`
SHA256 | `1FE1F4B5A65AEDBBD3676959E5B10D744FABA59727F6F58DC141B5211F1F6974`
SHA384 | `B785960A4F2EE0854C582666E08428F72775D5F2B0B1CEBEF5AFAD6DD078F23586F5E109C565A25BD2311545B3BA06F3`
SHA512 | `616CD2FA8E5367B0ED4475B2E942E59412F0CA750BE02BE0494D767B68586C0155F5D43BCA9A9629CCED0DC6952EA1A0446F56248FE634A39DF35F269EA8DCAE`
SSDEEP | `49152:zITOsROxWZ+q9KCKhvO7a0DMTNYuUn89KOArxm7Kb6KvySgYneeahv3nmS7yAqA:h6SiMRYI9urj6KvySznefhv3VWNA`
IMP | `CC8925537C6EFC7F7353A89069CF5178`
PESHA1 | `9E57F35DFE7EA63D1DA6AC892F28FAAF0D6AF81E`
PE256 | `B69C31B2C847819C842858EA9765077CCDAA4EB79B2120AD0B1B29C6850BC814`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NisSrv.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.1807.16384 (WinBuild.160101.0800)
* Product Version: 4.18.1807.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/1fe1f4b5a65aedbbd3676959e5b10d744faba59727f6f58dc141b5211f1f6974/detection/


## Possible Misuse

*The following table contains possible examples of `NisSrv.exe` being misused. While `NisSrv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_reg_disable_sec_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_reg_disable_sec_services.yml) | `- '\NisSrv'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


