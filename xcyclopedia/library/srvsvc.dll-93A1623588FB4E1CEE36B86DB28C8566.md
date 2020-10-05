---
title: srvsvc.dll | Server Service DLL
excerpt: What is srvsvc.dll?
---

# srvsvc.dll 

* File Path: `C:\Windows\system32\srvsvc.dll`
* Description: Server Service DLL

## Hashes

Type | Hash
-- | --
MD5 | `93A1623588FB4E1CEE36B86DB28C8566`
SHA1 | `281E92A7F670172555437183492169C47466B245`
SHA256 | `EB1FD7247E8C17DA0EE0728FDA50AAFF1EA56C150739B59A6E472E3F1DF30B81`
SHA384 | `B677CD46313941B27A745123ACD5B0AAC91AF526D46E071A91F9636F6BCA2818A7DEFBF88C75B4D77ADCC26A9B2FD15D`
SHA512 | `D492BF2792A55E162F178CAC1300E26A4AA994C2A4183CBD49DEE87C319A9AE0610A3EDFECAD41440EDBC7960126C47F67E6CB3FF6B26355DA77514FDF34B2D8`
SSDEEP | `6144:NX7TMLv7Vi3vk1e2HD5b2Ur8Jb4/L5nfXXW4yhV+5F/uSqe:d7TMLzViM1e2HD5b2UgStuSq`
IMP | `450AF353A865533B55232AE1481F9985`
PESHA1 | `C1B286E2A8F2F4112EEBF7EAB01776FE90C16925`
PE256 | `6CE2B843A7822BA7BAF2B4154A7DA997820EB31FA6D3B12A0A209DBEBAD02152`

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

* Original Filename: SRVSVC.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/eb1fd7247e8c17da0ee0728fda50aaff1ea56c150739b59a6e472e3f1df30b81/detection/


## Possible Misuse

*The following table contains possible examples of `srvsvc.dll` being misused. While `srvsvc.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [zeek_smb_converted_win_lm_namedpipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/zeek/zeek_smb_converted_win_lm_namedpipe.yml) | `- 'srvsvc'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lm_namedpipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_lm_namedpipe.yml) | `- 'srvsvc'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt3_bemstour.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt3_bemstour.yar) | $smb_param_3 = "srvsvc" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


