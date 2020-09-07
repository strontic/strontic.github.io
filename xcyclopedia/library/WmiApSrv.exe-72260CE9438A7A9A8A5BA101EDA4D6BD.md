---
title: WmiApSrv.exe | WMI Performance Reverse Adapter
---

# WmiApSrv.exe 

* File Path: `C:\WINDOWS\system32\wbem\WmiApSrv.exe`
* Description: WMI Performance Reverse Adapter

## Hashes

Type | Hash
-- | --
MD5 | `72260CE9438A7A9A8A5BA101EDA4D6BD`
SHA1 | `090436B0679559CB2D5E863AD9C9135613F38D77`
SHA256 | `8A221672E37FD7F30D35B3466CA9F1A473F9A77C27A5A16C6392BCEECCAFEA6F`
SHA384 | `867153DE041EC131350804441A1BBD7696A5D69B7D8BEF9B54EAE5948DFE4A6D193E47C1DB48F20CEB5BB1B5B558739B`
SHA512 | `F671504C6824CF222BE5E3C7BB409B887176ECC6EC9D0A4D886F065345B76233DE79C7CED1F10749C1A5D26B1CA347E4AFFC70AF652604BC319279A5FF8FE107`
SSDEEP | `3072:yVuG1JcDtqbSZczNZaPT/VxACI7J02rnY3F3uU+75jX1oAp48ZFRvCcw:jGetqbSZczvkjV+PN/nMajXiAW8PRvC`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WmiApSrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `WmiApSrv.exe` being misused. While `WmiApSrv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\WmiAPsrv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


