---
title: TSTheme.exe | TSTheme Server Module
---

# TSTheme.exe 

* File Path: `C:\windows\SysWOW64\TSTheme.exe`
* Description: TSTheme Server Module

## Hashes

Type | Hash
-- | --
MD5 | `8FDA1BE0C3C4DEE89774F0D09E67DFA9`
SHA1 | `CADA3CFAF63258A28A5B17FB603A89F37F097E82`
SHA256 | `E518E9415190BC504C9E4FE8B477006D9F8CA6901B9D4888A5B09C848C5C1246`
SHA384 | `5C3AB79A4A5FED55E844638A2E889C566DF5F2E001728F521CC63ACCE655DC128BC9CAE28D3ED75549AA76A02E0E99BA`
SHA512 | `BB329283227428591F6572CB176126E1483904E1EE26EA848C3B27AFA03EF85E4C41309C0D188465FBD00133365E9568F2FC17F4AA9633174ABAE15D7EF761B9`
SSDEEP | `768:Qg4kVzTa9BiS9MokYewhPEWFye8ahBLnIBkP5OWjark:QFkVzTa9BiS+okY1s2j55OWjar`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSThemeS.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.771 (WinBuild.160101.0800)
* Product Version: 10.0.17763.771
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While `TSTheme.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\tstheme.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


