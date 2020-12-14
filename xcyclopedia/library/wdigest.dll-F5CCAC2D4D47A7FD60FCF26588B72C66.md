---
title: wdigest.dll | Microsoft Digest Access
excerpt: What is wdigest.dll?
---

# wdigest.dll 

* File Path: `C:\Windows\system32\wdigest.dll`
* Description: Microsoft Digest Access

## Hashes

Type | Hash
-- | --
MD5 | `F5CCAC2D4D47A7FD60FCF26588B72C66`
SHA1 | `4A7C1B25E888E741BDD145BF92BAF730C878991B`
SHA256 | `BAB8CB5ACDAB6CAA1AA7A09BA24436C1CA5D4250D690681C5960ADA9B2F0DCEE`
SHA384 | `F53980ED0F267A65154BA2BDE3D5892E10601BCD8C16DF1DF956F1855FC401FD4F4810D172C856F086B9C638E9439394`
SHA512 | `ACDE9B7DE1B651531A2D6E0B406A256EE14A8288B72F4C32F7E2DFE85DDD3D9D86C1C7A359FE30690C42C607CD940CEFBD94728EBB28E1F66EF8798935896459`
SSDEEP | `6144:dsB5kp6Nup5BmrKIrM4/MRwcVhcrV+le2TO:dsBOpKrKGMpOcV+842i`
IMP | `F8D88D9A3BF9BBD4F5E25177ECE786C6`
PESHA1 | `92714A9F96EA525B5BF89583E8A9C443082CD35B`
PE256 | `EAF0662A4BE3E863EAE79D0D4108061707E4F1394C6997A93FE42782060F2619`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SpUserModeInitialize` | 7 | Exported Function
`SpLsaModeInitialize` | 6 | Exported Function
`SsiCredentialsUpdateNotify` | 3 | Exported Function
`SsiCredentialsUpdateFree` | 8 | Exported Function
`SpInstanceInit` | 32 | Exported Function
`CredentialUpdateNotify` | 5 | Exported Function
`CredentialUpdateFree` | 4 | Exported Function
`SpInitialize` | 1 | Exported Function
`CredentialUpdateRegister` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WDIGEST.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.388 (WinBuild.160101.0800)
* Product Version: 10.0.19041.388
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/bab8cb5acdab6caa1aa7a09ba24436c1ca5d4250d690681c5960ada9b2f0dcee/detection/


## Possible Misuse

*The following table contains possible examples of `wdigest.dll` being misused. While `wdigest.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_chafer_mar18.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_chafer_mar18.yml) | `TargetObject: '*\Control\SecurityProviders\WDigest\UseLogonCredential'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"comment": "Wdigest chain (stage 3)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"comment": "Wdigest chain (stage 4)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"comment": "Wdigest chain (stage 5)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"comment": "Wdigest chain",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"value": "%WINDIR%\\SysWOW64\\drivers\\wdigest.dll",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"comment": "UAC bypass in Wdigest chain",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"comment": "Wdigest chain (stage 6 - RC2CL backdoor)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"comment": "Wdigest chain (stage 6 - DNS downloader)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"comment": "persistence method for Wdigest chain",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `==== Wdigest exploit chain (Stage 3)` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `==== Wdigest exploit chain (Stage 4)` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `==== Wdigest exploit chain (Stage 5)` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `==== Wdigest exploit chain` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `%WINDIR%\SysWOW64\drivers\wdigest.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `"FlashConfigEnrollee" = "shell32 ShellExec_RunDLL  "C:\Windows\SysWOW64\drivers\Rundll32.exe" "C:\Windows\SysWOW64\drivers\wdigest.dll",SpInitialize %SHELLCODE_BYTES%"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | * Wdigest: The Digest Authentication protocol is designed for use with Hypertext Transfer Protocol (HTTP) and Simple Authentication Security Layer (SASL) exchanges.(Citation: TechNet Blogs Credential Protection) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1112.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1112/T1112.md) | Additionally, open Registry Editor to view the modified entry in HKLM\SYSTEM\CurrentControlSet\Control\SecurityProviders\WDigest. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1112.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1112/T1112.md) | reg add HKLM\SYSTEM\CurrentControlSet\Control\SecurityProviders\WDigest /v UseLogonCredential /t REG_DWORD /d 1 /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1112.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1112/T1112.md) | reg add HKLM\SYSTEM\CurrentControlSet\Control\SecurityProviders\WDigest /v UseLogonCredential /t REG_DWORD /d 0 /f >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) | $s5 = "wdigest!l_LogSessList" fullword ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_dumps.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_dumps.yar) | $s2 = "wdigest.DLL" wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mimikatz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mimikatz.yar) | $s2 = "sekurlsa::wdigest" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mimikatz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mimikatz.yar) | $s4 = "wdigest :" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


