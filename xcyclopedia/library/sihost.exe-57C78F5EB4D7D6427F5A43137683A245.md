---
title: sihost.exe | Shell Infrastructure Host
---

# sihost.exe 

* File Path: `C:\Windows\system32\sihost.exe`
* Description: Shell Infrastructure Host

## Hashes

Type | Hash
-- | --
MD5 | `57C78F5EB4D7D6427F5A43137683A245`
SHA1 | `B7F3E6395F369B98B5DD7BEE93BEAA02FFB843F0`
SHA256 | `32FABBC09CA776A819D40CF3E33A3FE44BF1DB72EA351845B20ED9FF528B64D4`
SHA384 | `63F281BBF499BB0CCE8A4C4DB8E4C685CCAFA6A311E34395A6FCD5DA518325A2F7C70BDB41947F8B0BD96495DEBF7792`
SHA512 | `660E926AB6E14C260E827F2A19C851712BEFF6550378462AC9D0DB97F20EF4B3CE8B4392A11B881BA4EC705E840D21291C5FB086384E19E26ACBC6A00DCB3D47`
SSDEEP | `1536:Go9A0bz1EEnZqKDeiF1mlu/HTrzvtOMCA+qbk5BKO4bt2BP:9Wi1EMeiFJTrzlOY+qbk5YO4kBP`

### Child Processes:
explorer.exe

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `sihost.exe` being misused. While `sihost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\sihost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\sihost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


