---
title: sendmail.dll | Send Mail
excerpt: What is sendmail.dll?
---

# sendmail.dll 

* File Path: `C:\Windows\SysWOW64\sendmail.dll`
* Description: Send Mail

## Hashes

Type | Hash
-- | --
MD5 | `E61DF91EA2D03348445F3DCC51E209A4`
SHA1 | `A790CF4F0EBF7352A36DDD3E6C0996FCF4CA5979`
SHA256 | `1D4C35D31C9C0CA4F96F20DFE9EBCDDDD186EAB5B326ADE52BE7BE458EB51BF4`
SHA384 | `F5A94FB5BF560AE3E35B1EBB17DA5A6C76B5B06CC5A2ABCFC5504ABCA4EC97D54E2ADC06F995586A0982FDEC01B7C937`
SHA512 | `BC936A6F3A4CE08B237B71B15B44BB7F77B1D72300DE754C637C19D62C9B503C8B79520ACA82979F863196E9DC07BAC1CCAFFE2A0F50BFD5A9625F0216F5113B`
SSDEEP | `1536:ayxPg+JNhhbe9HK1z/8VAt1IufSeRpJ1hg2xLpJoaZ+KyvU4LNcle:1g+bhM418Vy6+SeRpJ1h7J52txcle`
IMP | `7309B0213E2393B449B3C25ACCBC1D71`
PESHA1 | `6FBA8EAF3E799F3F6082B0CD01C7DC8449D063D8`
PE256 | `F5AA328CE1F3A01DCFE164B156147CA440EB2D76E86386D60534DBF44CB0AD7C`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllGetClassObject` | 2 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SENDMAIL.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/1d4c35d31c9c0ca4f96f20dfe9ebcdddd186eab5b326ade52be7be458eb51bf4/detection/


## Possible Misuse

*The following table contains possible examples of `sendmail.dll` being misused. While `sendmail.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'sendmail -osendmail;chmod +x sendmail'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'wget http*; chmod +x /tmp/sendmail'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'chmod 700 fp sendmail pt'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'chmod 700 sendmail'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'chmod 0700 sendmail'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- '/usr/bin/wget http*sendmail;chmod +x sendmail;'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | rule sendmail { | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | description = "Webshells Auto-generated - file sendmail.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


