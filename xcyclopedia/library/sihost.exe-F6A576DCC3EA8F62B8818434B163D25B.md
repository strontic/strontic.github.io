---
title: sihost.exe | Shell Infrastructure Host
---

# sihost.exe 

* File Path: `C:\Windows\system32\sihost.exe`
* Description: Shell Infrastructure Host

## Hashes

Type | Hash
-- | --
MD5 | `F6A576DCC3EA8F62B8818434B163D25B`
SHA1 | `A72247134CA39DA0B1F706F6B339DC912C0EE0D3`
SHA256 | `FDF2362A69C542996A8AC84B938DE62CA97AC209762171D2F8B6B543D3A966D0`
SHA384 | `0E53778852D51252DD3E83D2641C6C5C0358FEDA818487FB159F04E0937796EE6225B5BE80DC0DDCD70EDAF1B2F01792`
SHA512 | `92159635D475DC21BE9C543142C79370F3A80F9C1D8ECCBCF6D959517165FF40FE0DB59215C105406D0E0F7F8B060B3B0A67C4E3260DAAA2E0B34C13F38415E0`
SSDEEP | `3072:HoGHHEEU+WYAKG+DizpogS+qWe9AN5rytOU/:HoekV+PA/PpVSGb5rytOU`

## Runtime Data

### Child Processes:
explorer.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\Administrator\Documents | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\RPC Control\DSEC1514 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\sihost.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1075 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1075
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `sihost.exe` being misused. While `sihost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\sihost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\sihost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


