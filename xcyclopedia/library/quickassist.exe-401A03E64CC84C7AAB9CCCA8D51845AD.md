---
title: quickassist.exe | Quick Assist
excerpt: What is quickassist.exe?
---

# quickassist.exe 

* File Path: `C:\WINDOWS\SysWOW64\quickassist.exe`
* Description: Quick Assist

## Screenshot

![quickassist.exe](screenshots/quickassist.exe-39AB5ED601B0C39DCE3B7D269847C944-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `401A03E64CC84C7AAB9CCCA8D51845AD`
SHA1 | `B5EBDC66ACD0976B75BF6E6E1D8327BEF0F813C9`
SHA256 | `3B93A9391C4A945DF68DCCE87EC6239C0FBC1EB5BF95FCE698EF990BC040673C`
SHA384 | `5D035B01AE4A9AFF8CF55AA6077765ED215412A73FE57BC4D5B9F2C8D42F0F8C1612AF13EB09AA8B857E162E28BFEA81`
SHA512 | `7AC1B6ADC2B35D0364CF9B12E2931D4095CFEC33FE0570E943C1661775A3095039AC62D3BB759D5ED87DCAFD17FD0DD260B61F49B2FC88158F49AA16E003D8D8`
SSDEEP | `12288:iOuPr3STu8GrWtblX6Cl6xc5sHQNRSwoCJI/:vuPDSTu8GrWtblX6C8xc5sHQNRSwoC6`
IMP | `50DEBE5E0923E21510EFE7E47B20F981`
PESHA1 | `6B12F2CFA70E693650F1AAF58DB758ABEE83B33C`
PE256 | `DDB0B6B94BFCDA071CEB180F2C2316DE0781D6868BB559C3DD20B2F503F713DE`

## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: QuickAssist.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/3b93a9391c4a945df68dcce87ec6239c0fbc1eb5bf95fce698ef990bc040673c/detection


## Possible Misuse

*The following table contains possible examples of `quickassist.exe` being misused. While `quickassist.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) | $s1 = "QuickAssist.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) | $s4 = "name=\"QuickAssist\" " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


