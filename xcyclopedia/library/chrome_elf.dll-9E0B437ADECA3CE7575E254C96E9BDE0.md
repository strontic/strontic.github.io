---
title: chrome_elf.dll | Chromium
excerpt: What is chrome_elf.dll?
---

# chrome_elf.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\chrome_elf.dll`
* Description: Chromium

## Hashes

Type | Hash
-- | --
MD5 | `9E0B437ADECA3CE7575E254C96E9BDE0`
SHA1 | `6FCB5E4CAAD0617EAC59942277E659C0CDD63CB4`
SHA256 | `26B64D37E4C2E2576020F6488054C8D3EBDC28EF9472D2542E1DFCEC2CBE5F26`
SHA384 | `DCA42E99B3BAA162277446428FF2CF52F7DDC63D2765FBF2AE0C08EE9B9E16C49B747956A0A0C308C1B6CFEB6E7FEF56`
SHA512 | `44EDDF14D549A776CCA0C0E62451C2F8B698F569A0E4508E2296CF7BF4E5608C308F096B7485AF8E4952B4A0FF19852337A5ECC28F3D73F7178314BF396DAA8D`
SSDEEP | `12288:mSAnhGkThJ9P7pvVigKiB4bMrbmW9b0uA59emnw6xHjN9Rd+nw9P:mSAnhGkThJ9hNYWY9GSn`
IMP | `FD842E3E65FB1210C45DF2380260206D`
PESHA1 | `D375DEB7A169203B2584D8344E621D93F9CAA7D1`
PE256 | `F2EDB8F34B05DF62E05AA640E6797B34D77814B67860682AB15EB1D58A49A6F3`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`IsBlacklistInitialized` | 17 | Exported Function
`IsCrashReportingEnabledImpl` | 18 | Exported Function
`RegisterLogNotification` | 19 | Exported Function
`GetUniqueBlockedModulesCount` | 14 | Exported Function
`GetUserDataDirectoryThunk` | 15 | Exported Function
`InjectDumpForHungInput_ExportThunk` | 16 | Exported Function
`RequestSingleCrashUpload_ExportThunk` | 20 | Exported Function
`SignalChromeElf` | 24 | Exported Function
`SignalInitializeCrashReporting` | 25 | Exported Function
`SuccessfullyBlocked` | 26 | Exported Function
`SetCrashKeyValueImpl` | 21 | Exported Function
`SetMetricsClientId` | 22 | Exported Function
`SetUploadConsent_ExportThunk` | 23 | Exported Function
`DisableHook` | 4 | Exported Function
`DrainLog` | 5 | Exported Function
`DumpHungProcessWithPtype_ExportThunk` | 6 | Exported Function
`AddDllToBlacklist` | 1 | Exported Function
`ClearReportsBetween_ExportThunk` | 2 | Exported Function
`CrashForException_ExportThunk` | 3 | Exported Function
`DumpProcessWithoutCrash` | 7 | Exported Function
`GetCrashReports_ExportThunk` | 10 | Exported Function
`GetHandleVerifier` | 12 | Exported Function
`GetInstallDetailsPayload` | 13 | Exported Function
`GetApplyHookResult` | 8 | Exported Function
`GetBlockedModulesCount` | 9 | Exported Function
`GetCrashpadDatabasePath_ExportThunk` | 11 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `59C5C9F46EA82C4C743981566B64BD6C`
* Thumbprint: `475DAEE5A6CC149389EFDE176DEA526C627D203A`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA - G2, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Cisco Systems Inc., O=Cisco Systems Inc., L=San Jose, S=California, C=US

## File Metadata

* Original Filename: chrome_elf.dll
* Product Name: Chromium
* Company Name: The Chromium Authors
* File Version: 76.0.3809.87
* Product Version: 76.0.3809.87
* Language: English (United States)
* Legal Copyright: Copyright 2019 The Chromium Authors. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/26b64d37e4c2e2576020f6488054c8d3ebdc28ef9472d2542e1dfcec2cbe5f26/detection/

## Possible Misuse

*The following table contains possible examples of `chrome_elf.dll` being misused. While `chrome_elf.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_fireball.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_fireball.yar) | rule chrome_elf { | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_fireball.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_fireball.yar) | description = "Detects Fireball malware - file chrome_elf.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


