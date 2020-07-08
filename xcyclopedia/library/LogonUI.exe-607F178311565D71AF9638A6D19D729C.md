---
title: LogonUI.exe | Windows Logon User Interface Host
---

# LogonUI.exe 

* File Path: `C:\windows\system32\LogonUI.exe`
* Description: Windows Logon User Interface Host

## Hashes

Type | Hash
-- | --
MD5 | `607F178311565D71AF9638A6D19D729C`
SHA1 | `707A83603472EF72AAC181778FBF47EF76EB5DAD`
SHA256 | `997C0E69C490770815DD64189AD2F59F8309AD266981BFC5D70A728DD174D19C`
SHA384 | `0AB044962DD74A603135DC7B3E5DE4042CC5368691C473E2FF68D3228EDC5EEE667BB57060899C0E285819274603DC03`
SHA512 | `1537488E962119E600E97A5E78A54701546D4B9F66EF2CBFE9C8D9537092F51EBB0A954B487AF9CEDC0801E6CC405DB90E4D49436FA0311ED75588FCED094617`
SSDEEP | `192:Y4Q5QD3rAMw3PDtu+WalQp0nunmbpEQrpQDoeKY0U1XlGWmUW:7YQD3rAMdGlFAgSSpuoehgWmUW`

## Signature

* Status: The file C:\windows\system32\LogonUI.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: logonui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `LogonUI.exe` being misused. While `LogonUI.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_seaduke_unit42.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_seaduke_unit42.yar) | 		$s2 = "LogonUI.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


