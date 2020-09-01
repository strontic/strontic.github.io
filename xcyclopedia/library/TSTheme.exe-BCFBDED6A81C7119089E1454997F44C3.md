---
title: TSTheme.exe | TSTheme Server Module
---

# TSTheme.exe 

* File Path: `C:\Windows\SysWOW64\TSTheme.exe`
* Description: TSTheme Server Module

## Hashes

Type | Hash
-- | --
MD5 | `BCFBDED6A81C7119089E1454997F44C3`
SHA1 | `A49A0CF948155BD866D88253DA3E443086D2977A`
SHA256 | `B220104B36A01F1202EFE45BEAEEC3227927DCDAF364239CFF90724430B2BCA0`
SHA384 | `B3F089815CED2DD8BABF5B46D54C5130F38B627E03954E26C0740E85A939963D3CA1B5FA913986F00187345DBDCC4FCC`
SHA512 | `2EA9C45AB610163C78D07FF54F3278CCEEB59DAC92435619ED49481D0D9C7B011A82AF1DAEC71577F941A506486E81BA318E4E1235064855247EFA61921F3102`
SSDEEP | `768:PMoZrjHpb3tbZ5+2cSi+/pC6S9nJg+jfoghjjoiSi6nfkunHdofjaEObi:PMcrjHlgd+/peg+Loghjanfksdofjax`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\SysWOW64\TSTheme.exe |


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSThemeS.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While `TSTheme.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\tstheme.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


