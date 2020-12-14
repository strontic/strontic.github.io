---
title: Dism.exe | Dism Image Servicing Utility
excerpt: What is Dism.exe?
---

# Dism.exe 

* File Path: `C:\WINDOWS\SysWOW64\Dism.exe`
* Description: Dism Image Servicing Utility

## Hashes

Type | Hash
-- | --
MD5 | `9AD098446DE98C9CB454B7B007929374`
SHA1 | `2D0F6544F6021A27A2E07FB149443515AD55FD12`
SHA256 | `6E8EBF5EC6999883B82B9B41FCD53A4266B236E86CB41FBC450A3B7C64E708C0`
SHA384 | `317C478C445BADA4B51994C511DE8C95B8988CE22A8E53278C2E1F1E7F0929744F334847E9E43D53FAFF0DC8A53EB655`
SHA512 | `CF0EA288CFB4690012BAF03C4810E6758B602CBAD5EF80802D3BC18EB7283E86072BBB9CBE35F5A8EAACE64006BEDF59A94F116D3853F87D1A50F7CF2DF72B06`
SSDEEP | `3072:kJd77RF5S/krWIVkZi4qMxmbO0Q0xJOOZ9HCdq0V1x2qMllVr0gGdD:glF5MkrWDsxQEJrEq03x2rrNG`

## Runtime Data

### Usage (stdout):
```cmhg

Error: 740

Elevated permissions are required to run DISM. 
Use an elevated command prompt to complete these tasks.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DISM.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `Dism.exe` being misused. While `Dism.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\Dism.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


