---
title: LogonUI.exe | Windows Logon User Interface Host
excerpt: What is LogonUI.exe?
---

# LogonUI.exe 

* File Path: `C:\WINDOWS\system32\LogonUI.exe`
* Description: Windows Logon User Interface Host

## Hashes

Type | Hash
-- | --
MD5 | `DAA5CD4C86D5FCD6B3A215B34264FE78`
SHA1 | `9F0DC7C05FB0A7FEAE7709DDC039A15A423077ED`
SHA256 | `630067181FA5B2E7D9E7F50C6CECF3C3E60EEA426A7AB0125810E3337E14BAE0`
SHA384 | `AA5F18CC97B1856AE2AFF1AA59B4F779B068306FF575876DBA1E0AF1649B69981226F8C489C502F6638B653AE2CF2F81`
SHA512 | `8B5445D6BB81853CF39A1F46934B09F564406453245398F5FA194A40334145F92AE7045283F343041E0AB7C22C3ED3DAB99972F338DF67983D785AAE74D5B461`
SSDEEP | `192:sU1JmsaTvp/oNIsb+BC5zolJ8sdzpdNouZid7llW5UW:LKTv9qVKBuzoJZzpfZiJfW5UW`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: logonui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\LogonUI.exe](LogonUI.exe-33F89DD9629CB0422A2C17268376232D.md) | 60

## Possible Misuse

*The following table contains possible examples of `LogonUI.exe` being misused. While `LogonUI.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_seaduke_unit42.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_seaduke_unit42.yar) | $s2 = "LogonUI.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


