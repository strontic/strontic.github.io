---
title: wimserv.exe | Wimfltr v2 extractor
excerpt: What is wimserv.exe?
---

# wimserv.exe 

* File Path: `C:\windows\system32\wimserv.exe`
* Description: Wimfltr v2 extractor

## Hashes

Type | Hash
-- | --
MD5 | `EBA3354A8A905D42E722A342AAE18AF8`
SHA1 | `360A84FFDFAF3FA91AE494F2B25B5CBC86D1039C`
SHA256 | `A7DC774C8139D791B75DE5E9F2BD44B67E8B1AB906DC41A9294E7C7649832907`
SHA384 | `7B456F82C4E6EE30325A04FB568C2C32B20355FD04FFA1D4AAE74BB12E4105207906F294DBC76915C035DC359F2FA84C`
SHA512 | `8D6B3BE5F9BA2221ED8C42CFEDAF3E35AD017370CC68D3E551EE01C49FFB0DB1C3F1FDF1DDAB17A79A39A53A2E8D9B6B0573ABDD1894EA7CE10990EEFF1ACF25`
SSDEEP | `12288:CYaV6eJuJkSZKNs04xFFwlCdimJgm8fmaY7HqcRX7g/eTb:CYaVTIwNs0mFFwlCdzYfDY7H3TTb`

## Signature

* Status: The file C:\windows\system32\wimserv.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: extractr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.19622 (winblue_ltsb.200111-0600)
* Product Version: 6.3.9600.19622
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `wimserv.exe` being misused. While `wimserv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\wimserv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


