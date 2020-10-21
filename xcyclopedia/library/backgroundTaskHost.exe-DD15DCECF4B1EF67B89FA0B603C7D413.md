---
title: backgroundTaskHost.exe | Background Task Host
excerpt: What is backgroundTaskHost.exe?
---

# backgroundTaskHost.exe 

* File Path: `C:\WINDOWS\SysWOW64\backgroundTaskHost.exe`
* Description: Background Task Host

## Hashes

Type | Hash
-- | --
MD5 | `DD15DCECF4B1EF67B89FA0B603C7D413`
SHA1 | `F84AC16AEBE0C7FF5C7823394AB9DEF50FB25F8C`
SHA256 | `80898E0BA235C0B49DC7336F7079BD303302BE396CE14F05F8E2E5B969156301`
SHA384 | `13DAD2DBC5799BBD8C3B1C6C1C1FFF0B02FC904CB7F79EE9BF5F196DD184981CAF21C0AD90CBF257A4EC2EB707296225`
SHA512 | `AB8385063FD1E2DABFCCDBB57B4AE0B1D8C9568A0460B7027B7A44EAFA0BDD1696759FE7152CC8880713A46EC7411190206F59921D9F7D108D30CF056E74D6D4`
SSDEEP | `384:JB3rKpHXoQHWZWfGWNmXjDBRJ+lNFElZW:J1r0XNHWO0Xj1Pcv`

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
[C:\Program Files (x86)\Common Files\microsoft shared\Ink\TabTip32.exe](TabTip32.exe-725AAEFD55B6DEA9663EEAA04E881C0E.md) | 36
[C:\Windows\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-50D5FD1290D94D46ACCA0585311E74D5.md) | 40
[C:\WINDOWS\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-E22E7BD6B146BDE93DC48643B772D8BB.md) | 52
[C:\Windows\system32\browser_broker.exe](browser_broker.exe-C7C56DB13D5F1A2BB6DE92B8BBD22CA0.md) | 32
[C:\WINDOWS\system32\dllhost.exe](dllhost.exe-680045579134D8AD9D0400A9DBE30786.md) | 43
[C:\Windows\system32\dllhost.exe](dllhost.exe-D2AB39EA2C0FCD172751F84BDA723A97.md) | 32
[C:\Windows\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-6DD5ECC82E9118B2DE1CAE3B35550E14.md) | 41
[C:\WINDOWS\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-94C10EAE7738DA6F112A6407E8C952F8.md) | 44
[C:\Windows\system32\prproc.exe](prproc.exe-7ABD17EE7B6B0F79CD4D2F3D4B4B11C2.md) | 41
[C:\WINDOWS\system32\prproc.exe](prproc.exe-BFD6335E4F61D44CA74B627A45686106.md) | 32
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-71B9062F02950BAA4441E2FB79677E99.md) | 32
[C:\Windows\system32\SlideToShutDown.exe](SlideToShutDown.exe-2CE65A4F9A63402F38537BE59FA1689D.md) | 36
[C:\WINDOWS\system32\SlideToShutDown.exe](SlideToShutDown.exe-C428A6CE6F4424BF148AF087C0BF4B75.md) | 35
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-F8D636BD68156F0C653DBC3D69FC0F08.md) | 54
[C:\Windows\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-443AFE0E4385A46CFE2AD14890DC1FD4.md) | 29
[C:\WINDOWS\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-8E0D0D53CA176DDA94850F7A3B406408.md) | 33
[C:\WINDOWS\SysWOW64\dllhost.exe](dllhost.exe-60D0B50CFF3A0722ADC274F49FB16F14.md) | 35
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-B5A6D2FB3F4521C37D613DE52AB3467D.md) | 30

## Possible Misuse

*The following table contains possible examples of `backgroundTaskHost.exe` being misused. While `backgroundTaskHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `- BackgroundTaskHost.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


