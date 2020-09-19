---
title: backgroundTaskHost.exe | Background Task Host
---

# backgroundTaskHost.exe 

* File Path: `C:\Windows\system32\backgroundTaskHost.exe`
* Description: Background Task Host

## Hashes

Type | Hash
-- | --
MD5 | `0601F285DCFF75E679BD91E39B6EBDBF`
SHA1 | `8B4E7D875398E67D5277D9C8C9BFA027F9705EDC`
SHA256 | `23A80E09DAE6DB17909E81B1CA7E9BF43158BDEE69C1646125FC62E6BFE2745B`
SHA384 | `4A3D32544D52B06EE0E98CBE2694E83B2AEA205D89DCDB0642D54B7967E538752D8AF867620F839AB099AE3E0A54F270`
SHA512 | `D9400D7261F929CF0AD2B366DD6A6352D15D398789EE416D3255C0910A5A4720D9F6319FCB7334AB46514AC0F5D78672A328791C30B023944FED68CDF5FD40D3`
SSDEEP | `384:WWXMoCedanirwMOe7WhGWTlRDBRJB2GolghvJO:FXMyZOeCz1PXVJO`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: backgroundTaskHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `backgroundTaskHost.exe` being misused. While `backgroundTaskHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `- BackgroundTaskHost.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


