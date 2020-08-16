---
title: wordpad.exe | Windows Wordpad Application
---

# wordpad.exe 

* File Path: `C:\Program Files\Windows NT\Accessories\wordpad.exe`
* Description: Windows Wordpad Application

## Screenshot

![wordpad.exe](screenshots/wordpad.exe-34B557ACE63A6AF3EC4B02B4A9EC46AF-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `34B557ACE63A6AF3EC4B02B4A9EC46AF`
SHA1 | `75FF51EB39733E7C57C62FCB577026DA750E4F5C`
SHA256 | `D14682453AE07F4204E17A3DCF53367BBF3E2AF85088BF513FD728328CA8B275`
SHA384 | `3CF8D8684EF9F22D15A1588AEBCA197207777C5CEA10961A5E739AFDDC5246592FF4A6E9607CBCB8B2631C5CCB57FC91`
SHA512 | `437D2FB0F2537797775AF57C3BB078D943B2D501380E2507CD9FDD3B32DE2B3A328D9C757D1A01A1F7E89A135B7B5F03060BDF2E4F79A032FB1408567644B941`
SSDEEP | `24576:jfDp09QRTnY86ytmZuQuhU5nL5Z2FxvNEYr8oSUGeP9PDkjjqXN:jfDLTnJQu65nsxvWCXSZeP9PDk3C`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WORDPAD.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows NT\Accessories\wordpad.exe](wordpad.exe-61173FF6ABB1C40E3D3B580126FC5F66.md) | 60

## Possible Misuse

*The following table contains possible examples of `wordpad.exe` being misused. While `wordpad.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_burning_umbrella.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_burning_umbrella.yar) |       $s1 = "Wordpad.Document.1\\shell\\open\\command\\" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) |       $s3 = "Accessories\\wordpad.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


