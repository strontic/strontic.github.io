---
title: IKEEXT.DLL | IKE extension
excerpt: What is IKEEXT.DLL?
---

# IKEEXT.DLL 

* File Path: `C:\Windows\system32\IKEEXT.DLL`
* Description: IKE extension

## Hashes

Type | Hash
-- | --
MD5 | `C4EC5E470272E9F9A715299F8B79AF30`
SHA1 | `0FFD33D03746D11434271129F81814E343F20209`
SHA256 | `7DFC9886D4767518333C59F0D17DB2C7D030C67C83D0EF091998F05AF629A583`
SHA384 | `F61DBC633F68530275C9DA1467D947FCB0BB8933FE0F7DFDE604108287E06F786B94EA46F5A63BD3EFCFF5162F41FE53`
SHA512 | `FE8BC8177809E35264514B3467EE645881ABF26643134C5290A5C625BEE6138707DF7110F5B789CDB7920FF8DD288B549A51C5EBD5BA62FAA392A44F97B8BBE8`
SSDEEP | `24576:4QLgjwCzuWwhX3tsB7gleczHL58v3wECUra2Yw:4QgjwCzuWwhX3tsB7UeczHL58fwE1ras`
IMP | `5F4ED01EE151EDCADD082F7507B9694D`
PESHA1 | `BA24C99B96BE657B9290816420996A3083D81BE8`
PE256 | `0396585B1B641CCCF5DA9F73BD9120BFE9C4229B19022492A4B8C79E05B8378A`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SvchostPushServiceGlobals` | 2 | Exported Function
`IkeServiceMain` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IKEEXT.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/7dfc9886d4767518333c59f0d17db2c7d030c67c83d0ef091998f05af629a583/detection/


## Possible Misuse

*The following table contains possible examples of `IKEEXT.DLL` being misused. While `IKEEXT.DLL` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_svchost_dll_search_order_hijack.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_svchost_dll_search_order_hijack.yml) | `description: IKEEXT and SessionEnv service, as they call LoadLibrary on files that do not exist within C:\Windows\System32\ by default. An attacker can place their` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


