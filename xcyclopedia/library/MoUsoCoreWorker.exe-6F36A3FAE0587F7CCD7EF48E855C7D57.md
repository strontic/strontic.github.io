---
title: MoUsoCoreWorker.exe | MoUSO Core Worker Process
excerpt: What is MoUsoCoreWorker.exe?
---

# MoUsoCoreWorker.exe 

* File Path: `C:\Windows\system32\MoUsoCoreWorker.exe`
* Description: MoUSO Core Worker Process

## Hashes

Type | Hash
-- | --
MD5 | `6F36A3FAE0587F7CCD7EF48E855C7D57`
SHA1 | `8B2479BFA3A98A7E660AB588F9EE27ADE6C9D9C7`
SHA256 | `F278E748B6FFDF95038CAE2F17F8F99F556B42F22CBF53B6BFC5FEA16FC9A46D`
SHA384 | `0E1408441E1C5C6DC17B8591283AB3B3AE559082AE072529A9D6C6D73AE9D0D857E3DDDF689816EAEE69D49F6C952B38`
SHA512 | `D6413B847C6159B7D75E861BDD0484D5F71291800E5315EC543D5F4DC6B8118ED966A1035CF0B3F0AF2765C4F1A97AF1BE08C76CA3150A7867C5733E6B479306`
SSDEEP | `24576:zZt9KkvnUcCLX7picmIQpvhnno7eQ0pmdh3oEw2tZG3pv5uA:d1vnDKXH+Keodh3oIupU`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MoUSOCoreWorker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.329 (WinBuild.160101.0800)
* Product Version: 10.0.19041.329
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `MoUsoCoreWorker.exe` being misused. While `MoUsoCoreWorker.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\MoUsoCoreWorker.exe'  # c:\windows\System32\MoUsoCoreWorker.exe on win10 20H04 at least` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


