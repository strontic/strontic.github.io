---
title: wkssvc.dll | Workstation Service DLL
excerpt: What is wkssvc.dll?
---

# wkssvc.dll 

* File Path: `C:\Windows\system32\wkssvc.dll`
* Description: Workstation Service DLL

## Hashes

Type | Hash
-- | --
MD5 | `5ADCB62320EEAAC526F8E464BEAC3D17`
SHA1 | `5A7C04136F46DE2E11D5C08B2E373255438C74A2`
SHA256 | `297B48E02834E4460C52CF181DC03D6FC2B9698A2537BFD60DD933F3EEA86C68`
SHA384 | `F7B6682405026989F059DBA1A715367C05BD9971D7328BA107CA7C8F51D43072747597C8BA77CA4F6361161EC6F8222E`
SHA512 | `EE021DB85E38F3FCAE24C81A3E826737B9382FB58C7881823B48FF303DAEBC2046B82CFBAAC238F7B1E555B9AF0719BBCAD691EF1E2546EECEAE47173A2BC44B`
SSDEEP | `6144:4IeLkccJQ2lDg1MV+UTmmaXNf5ErTJuNjz47uebYiW42sW4jVDF1en88u6Z:41CQ2lDVV+UTTa9Aciq8`
IMP | `F940CEA55552803E9F89D01E35D01030`
PESHA1 | `3A641374EA2FB6091DF3EAED150464C92AB980AC`
PE256 | `44FBAF437426D594BE24A41C33AD55E5D5E2847B6A97ABD330D7BC5F7B4E76CB`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SvchostPushServiceGlobals` | 2 | Exported Function
`ServiceMain` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WKSSVC.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/297b48e02834e4460c52cf181dc03d6fc2b9698a2537bfd60dd933f3eea86c68/detection/


## Possible Misuse

*The following table contains possible examples of `wkssvc.dll` being misused. While `wkssvc.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [zeek_smb_converted_win_lm_namedpipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/zeek/zeek_smb_converted_win_lm_namedpipe.yml) | `- 'wkssvc'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lm_namedpipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_lm_namedpipe.yml) | `- 'wkssvc'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


