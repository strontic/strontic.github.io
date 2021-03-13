---
title: backgroundTaskHost.exe | Background Task Host
excerpt: What is backgroundTaskHost.exe?
---

# backgroundTaskHost.exe 

* File Path: `C:\WINDOWS\system32\backgroundTaskHost.exe`
* Description: Background Task Host

## Hashes

Type | Hash
-- | --
MD5 | `E22E7BD6B146BDE93DC48643B772D8BB`
SHA1 | `DC27F57A3BA5D13B476B1FD0872B8972744A01F8`
SHA256 | `74B3323405CDFB85CFC9D5C1CD29C816C80361DF154801E44F14863C9058906E`
SHA384 | `3C814427ED7AA87C36BC08CD58636E7ED6955777EE51D6BB1CD590242759BEA2C18DF411B39209CD9DFAD9F61177E541`
SHA512 | `3587CCFFE80892E156927A0950F2F9E2DCA43DEE5F5BB6CA83F42337D8C698749644E0EDE3433CF72B6ED166991FA72EE63C57BD1A41CF1C35346B19A7FA7969`
SSDEEP | `384:K7uKvWPKpX7b7+qIJeQH4TWfGWBmXjDBRJ+lY1lxwM:K7Z+U6fLH4QQXj1P+0`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: backgroundTaskHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Common Files\microsoft shared\Ink\TabTip32.exe](TabTip32.exe-725AAEFD55B6DEA9663EEAA04E881C0E.md) | 38
[C:\Windows\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-50D5FD1290D94D46ACCA0585311E74D5.md) | 35
[C:\Windows\system32\browser_broker.exe](browser_broker.exe-C7C56DB13D5F1A2BB6DE92B8BBD22CA0.md) | 33
[C:\WINDOWS\system32\dllhost.exe](dllhost.exe-680045579134D8AD9D0400A9DBE30786.md) | 35
[C:\Windows\system32\dllhost.exe](dllhost.exe-D2AB39EA2C0FCD172751F84BDA723A97.md) | 32
[C:\Windows\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-6DD5ECC82E9118B2DE1CAE3B35550E14.md) | 33
[C:\WINDOWS\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-94C10EAE7738DA6F112A6407E8C952F8.md) | 43
[C:\Windows\system32\prproc.exe](prproc.exe-7ABD17EE7B6B0F79CD4D2F3D4B4B11C2.md) | 35
[C:\WINDOWS\system32\prproc.exe](prproc.exe-BFD6335E4F61D44CA74B627A45686106.md) | 43
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-71B9062F02950BAA4441E2FB79677E99.md) | 38
[C:\Windows\system32\SlideToShutDown.exe](SlideToShutDown.exe-2CE65A4F9A63402F38537BE59FA1689D.md) | 35
[C:\WINDOWS\system32\SlideToShutDown.exe](SlideToShutDown.exe-C428A6CE6F4424BF148AF087C0BF4B75.md) | 32
[C:\WINDOWS\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-DD15DCECF4B1EF67B89FA0B603C7D413.md) | 52
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-F8D636BD68156F0C653DBC3D69FC0F08.md) | 40
[C:\Windows\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-443AFE0E4385A46CFE2AD14890DC1FD4.md) | 33
[C:\WINDOWS\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-8E0D0D53CA176DDA94850F7A3B406408.md) | 32
[C:\WINDOWS\SysWOW64\dllhost.exe](dllhost.exe-60D0B50CFF3A0722ADC274F49FB16F14.md) | 30
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-B5A6D2FB3F4521C37D613DE52AB3467D.md) | 30

## Possible Misuse

*The following table contains possible examples of `backgroundTaskHost.exe` being misused. While `backgroundTaskHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_abusing_azure_browser_sso.yml) | `- BackgroundTaskHost.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


