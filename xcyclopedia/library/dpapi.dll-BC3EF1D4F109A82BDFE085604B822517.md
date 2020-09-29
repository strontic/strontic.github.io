---
title: dpapi.dll | Data Protection API
excerpt: What is dpapi.dll?
---

# dpapi.dll 

* File Path: `C:\Windows\system32\dpapi.dll`
* Description: Data Protection API

## Hashes

Type | Hash
-- | --
MD5 | `BC3EF1D4F109A82BDFE085604B822517`
SHA1 | `E594FDB145DE850541FA51A416D96EBA92AC2877`
SHA256 | `892D7846323AB7E9590B01C81E9AD037518122EF45D76F2EA94149B483EF92DE`
SHA384 | `88F67B8124B0007E5DF58BC0B7D539FB830AE04A61073DD838EC2BC7BAF7BB7CCBCF5CCD856C27C02352E25F55459D1E`
SHA512 | `9E177A4DE0965E081793B9E4CD96A5668C32DC9D5837E01B6E2E884FEC12F2AD0DBA3E5AB642DA0B193147329C6984E0AD807040CEB680651BBD32028780AA17`
SSDEEP | `192:A31Z4NWKCzI0tYZuRLFOw+M+DUjGdnHQHtfU+EcNWthviL8WCVWDt:ADiWKMvt9LFObMuSGKNfUMWtoYWCVWR`
IMP | `C591E3A4DDFE145A26EEC16DB70623B7`
PESHA1 | `8D5BCAAA72E1F59F27D690FDF577E65D29BC6E62`
PE256 | `82A3BABCAF2F501E124AD47F43887FBF0DDF6334F0E082167EB3063C76ED4A36`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CryptProtectDataNoUI` | 1 (0x1) | Exported Function | 0x0000000180001010 | 0x00001010
`CryptProtectMemory` | 2 (0x2) | Exported Function | 0x0000000180001700 | 0x00001700
`CryptResetMachineCredentials` | 3 (0x3) | Exported Function | 0x0000000180002370 | 0x00002370
`CryptUnprotectDataNoUI` | 4 (0x4) | Exported Function | 0x0000000180001360 | 0x00001360
`CryptUnprotectMemory` | 5 (0x5) | Exported Function | 0x00000001800016d0 | 0x000016d0
`CryptUpdateProtectedState` | 6 (0x6) | Exported Function | 0x0000000180002120 | 0x00002120
`iCryptIdentifyProtection` | 7 (0x7) | Exported Function | 0x0000000180001730 | 0x00001730


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/892d7846323ab7e9590b01c81e9ad037518122ef45d76f2ea94149b483ef92de/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\dpapi.dll](dpapi.dll-75A30F1A121D343188497571D03913BF.md) | 32

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


