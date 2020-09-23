---
title: syskey.exe | SAM Lock Tool
excerpt: What is syskey.exe?
---

# syskey.exe 

* File Path: `C:\windows\SysWOW64\syskey.exe`
* Description: SAM Lock Tool

## Screenshot

![syskey.exe](screenshots/syskey.exe-8D00177CA1D11D9A61CBF6F0D2F0420B-3.png)

## Hashes

Type | Hash
-- | --
MD5 | `C72F56AC33E9F1204528020CD0840A5A`
SHA1 | `7AEE703C88A41F257D2A3AABEB9FE68999D86B51`
SHA256 | `ED1F857082E575E1D2426ADB2416DE6172BC993174DCC95801FC3516C451D96D`
SHA384 | `69E69FC5F0FB4B8D79F88DF4258AABC2F5854AB1661D72794B9BE81CF16062412232AC9B0E3A8A8DCB8ECEE969C40785`
SHA512 | `E02853A09F38B705ECAD0CF330476E1D3F1F9DA62C7E1924D1C61C3FABB7164C4D774F23BA9F13F333EC1DE43722D8D9BB18C0B406BB7627BE704B76C252955C`
SSDEEP | `384:OiRkpseHdT7BHMI/W/PKjlXfoEXmq4O3q5X1GwU1KC1Q1XWTxWx:rS2+IgWE2qfq5X1GwI`

## Signature

* Status: The file C:\windows\SysWOW64\syskey.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: samlock.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\syskey.exe](syskey.exe-EFDF337667EB0516CC325BA74A7F9411.md) | 29

## Possible Misuse

*The following table contains possible examples of `syskey.exe` being misused. While `syskey.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- 'reg SAVE HKLM\SAM'  # save registry SAM - syskey extraction` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_syskey_registry_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_syskey_registry_access.yml) | `title: SysKey Registry Keys Access` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_syskey_registry_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_syskey_registry_access.yml) | `description: Detects handle requests and access operations to specific registry keys to calculate the SysKey` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | description      = "LSA dump programe (bootkey/syskey) - pwdump and others" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


