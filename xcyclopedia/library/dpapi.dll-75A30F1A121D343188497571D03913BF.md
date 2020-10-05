---
title: dpapi.dll | Data Protection API
excerpt: What is dpapi.dll?
---

# dpapi.dll 

* File Path: `C:\Windows\SysWOW64\dpapi.dll`
* Description: Data Protection API

## Hashes

Type | Hash
-- | --
MD5 | `75A30F1A121D343188497571D03913BF`
SHA1 | `45CB62A8E454BEF4C8B76132A283AA9CA702BB86`
SHA256 | `3A9CFE948EBD9B4315B19B27CAC1B93181A90CD992129DCB6EE32503F8BF57FA`
SHA384 | `7AE909A53100F7B562361F4B8A4CBA698E9AE090DE2C75AFAE01C0FF0039017D01B569EA03CFF0E4E7CFF56AD6418619`
SHA512 | `F61B3D9A6D62AE8CB390B5C8AE97314B2BDEB2E3D51ABD2FEA6CFC8ADFA453FE3D45F8000BE15BD20F469CFBBAC15201BC5F42EC85FD6506C4A1894AA50A1212`
SSDEEP | `192:xOS3uudlcXa9NcyOO2L+Lg1ES3SAfU+EcNWMHwWCVWdPH:xd6XayiUz3SAfUMWMHwWCVWdP`
IMP | `CDAC1DB4215AC1D17520C1DE9681D5AC`
PESHA1 | `1B99747807BB4BE4226B2D5B0C3FD1F202490B99`
PE256 | `66DA5299C01D867481B434A8FCFFB31478150AC8A6614502C31973E804CB7DD0`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`CryptUnprotectMemory` | 5 | Exported Function
`CryptUpdateProtectedState` | 6 | Exported Function
`iCryptIdentifyProtection` | 7 | Exported Function
`CryptUnprotectDataNoUI` | 4 | Exported Function
`CryptProtectDataNoUI` | 1 | Exported Function
`CryptProtectMemory` | 2 | Exported Function
`CryptResetMachineCredentials` | 3 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dpapi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/3a9cfe948ebd9b4315b19b27cac1b93181a90cd992129dcb6ee32503f8bf57fa/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\dpapi.dll](dpapi.dll-BC3EF1D4F109A82BDFE085604B822517.md) | 32

## Possible Misuse

*The following table contains possible examples of `dpapi.dll` being misused. While `dpapi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_dpapi_domain_backupkey_extraction.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_dpapi_domain_backupkey_extraction.yml) | `title: DPAPI Domain Backup Key Extraction` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dpapi_domain_backupkey_extraction.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_dpapi_domain_backupkey_extraction.yml) | `description: Detects tools extracting LSA secret DPAPI domain backup key from Domain Controllers` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dpapi_domain_masterkey_backup_attempt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_dpapi_domain_masterkey_backup_attempt.yml) | `title: DPAPI Domain Master Key Backup Attempt` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dpapi_domain_masterkey_backup_attempt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_dpapi_domain_masterkey_backup_attempt.yml) | `description: Detects anyone attempting a backup for the DPAPI Master Key. This events gets generated at the source and not the Domain Controller.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_protected_storage_service_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_protected_storage_service_access.yml) | `description: Detects access to a protected_storage service over the network. Potential abuse of DPAPI to extract domain backup keys from Domain Controllers` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mimikatz_command_line.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mimikatz_command_line.yml) | `- dpapi` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mimikatz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mimikatz.yar) | $s14 = "sekurlsa::dpapi" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


