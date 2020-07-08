---
title: LogonUI.exe | Windows Logon User Interface Host
---

# LogonUI.exe 

* File Path: `C:\Windows\system32\LogonUI.exe`
* Description: Windows Logon User Interface Host

## Hashes

Type | Hash
-- | --
MD5 | `893144FE49AA16124B5BD3034E79BBC6`
SHA1 | `FBF39A288FC46CBF0620CFD297395A8FB4FBCDAD`
SHA256 | `CF01E46C146699F6C0E3DD447043F59BC9438DBBCB9563AF6C60EBC6D82727F2`
SHA384 | `AD04C11ECD7D65D4C50FDCFF26BBA66F60D0F929C624FC85A706456C142036EBB4E3E40AD75EE9CA407E614EEE741517`
SHA512 | `C921EE3786717AC1F9E1981E35494F33D26D153AFB335C52219830261F84155383D5AC9FF0EA1D7F3F6913B28C878CE6B5EA350F60ED9A9BF1AC006596FD4C68`
SSDEEP | `192:yecuhBM44rbhVsO3XKtK3NyeiKQ2pxeILJJQYSlid3slZiU4ltWIUW:HVhq4Ih6U3NRXpxLLJGYWi2ZcnWIUW`

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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `LogonUI.exe` being misused. While `LogonUI.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_seaduke_unit42.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_seaduke_unit42.yar) | 		$s2 = "LogonUI.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


