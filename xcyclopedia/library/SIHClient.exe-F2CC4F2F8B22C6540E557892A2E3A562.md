---
title: SIHClient.exe | SIH Client
excerpt: What is SIHClient.exe?
---

# SIHClient.exe 

* File Path: `C:\Windows\system32\SIHClient.exe`
* Description: SIH Client

## Hashes

Type | Hash
-- | --
MD5 | `F2CC4F2F8B22C6540E557892A2E3A562`
SHA1 | `4EDB06BC51EE0EA2050C6087FC8FA164D3C8A63A`
SHA256 | `A167B3DE2DF58AB035602223DAF33FC807F01FBE901EDC7BD1913B43D5172541`
SHA384 | `42565CA51F7BF19903565E2BA204BD702A17AD8587A2E0ABE0ADA6F01D3AC93BE63ECB407022F037ADE414B7471194B4`
SHA512 | `3AD341046431B9439668E6A66C4E8ADDC895E05755D2F082BA2B6E1D958B7EBD9E8ED620ABF4AB4AFFD92753A7210930F53F0601DF446CAA4EBE84DA4B45886D`
SSDEEP | `6144:KOCUtmYAGr1TgnkQ+4Vx2f8hOAvj3aWzl49IT90edT+ZQb6fnA6RFFMTi5Ci:VCUvKECNvbaOUaZ+rA6fyTACi`
IMP | `69863607D629D2AA5AB89B0D5A4AD9A1`
PESHA1 | `22E296E8E73CD2FAA2652CF33A9DC6C74C09092C`
PE256 | `5D83F8C576143DC88F93D9A896130BF20389F471A6AA0FF80AAE079D36E82E8F`

## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihclient.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/a167b3de2df58ab035602223daf33fc807f01fbe901edc7bd1913b43d5172541/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\SIHClient.exe](SIHClient.exe-1A2203911DB977B17D378E2B2CC21E25.md) | 91

## Possible Misuse

*The following table contains possible examples of `SIHClient.exe` being misused. While `SIHClient.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\SIHClient.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


