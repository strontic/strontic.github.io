---
title: wdigest.dll | Microsoft Digest Access
excerpt: What is wdigest.dll?
---

# wdigest.dll 

* File Path: `C:\Windows\SysWOW64\wdigest.dll`
* Description: Microsoft Digest Access

## Hashes

Type | Hash
-- | --
MD5 | `83B7BE67B3678B1A3A8D7B4C0E35E594`
SHA1 | `D496D41B225A28709D080AF3742B1142CA9E3FC0`
SHA256 | `841151520A712B366096F1C60B8633D4A8EABCAC259A2A9B28515446061E9B6D`
SHA384 | `FAA051A0CD5AF09E8FE532892832EA586A9943BA7D285085D6B55A90EACA1569A31F930785FCBA4623418F1ED79A7477`
SHA512 | `563622D19B86150C1D91A45774551A59C1036003A2EE172DCE33FF82C50136397E5323AD6663EE1BDB38E31146B227F54C288353B61B6822AA4C651A3FBF4DC4`
SSDEEP | `3072:YpoFVwELVGIHytU+zmdR8ro36UBE+R1n5BG61dVoO5FXTS0Xq4++G5qrCO7i9CyC:LZGIHytDsRr66pvn5B3NSjZ+GRO9yHi`
IMP | `A88F636C534596C3AF8FDB6796567861`
PESHA1 | `C94EF523C1A69B1141106F506F0CEC47B1022EE7`
PE256 | `116D1571A09ACB8383D7B933E549DE172AB4544C137917B3D7888CDDB0B79936`

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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/841151520a712b366096f1c60b8633d4a8eabcac259a2a9b28515446061e9b6d/detection/


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


