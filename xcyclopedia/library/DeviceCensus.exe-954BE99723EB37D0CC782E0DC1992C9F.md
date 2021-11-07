---
title: DeviceCensus.exe | Device Census
excerpt: What is DeviceCensus.exe?
---

# DeviceCensus.exe 

* File Path: `C:\Windows\system32\DeviceCensus.exe`
* Description: Device Census

## Hashes

Type | Hash
-- | --
MD5 | `954BE99723EB37D0CC782E0DC1992C9F`
SHA1 | `0646F86530602A6D5980AD9D460E45F77EF46399`
SHA256 | `76490BE66E4D2EBF054C9D536B02C82A5C6BB97209F8E4CFFC69974A04FA7BD7`
SHA384 | `5ED6C797E54A6675B7F8127F6FA3B335D31C748F594335E5FB8C32B7B81BA31FF0CBF0C6F5D76A14C29AE4B73E120E73`
SHA512 | `D7DF0C6F42A3394DECC9D4E5C93FA72C8C012C246FDE3501007BB8B6289B6A855B6BDD74C305A8B8936DE8BB0A95E832CB7C99B9E690F569CADC264DA819C605`
SSDEEP | `384:chbaEPVaYmPw5gyLjuCrHGOl2R3qj37nec/gWJXn7uWEgWmc32wDBRJuKIml8FT0:OmEsxwGPcrl08Cc/giXn7UHH1PZ`
IMP | `69755EB5A4F06F0B816F7B23B33E44E8`
PESHA1 | `C00D928DF078583ECE4F9F1AAE15D1C532D8D1E6`
PE256 | `EC4CDF8D9DDE1FC1A147F17B2C2ED1924C6B928B0864C0E26A88CCF25C4C99EA`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\system32\dcntel.dll |
C:\Windows\system32\DeviceCensus.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DeviceCensus.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19645.1046 (WinBuild.160101.0800)
* Product Version: 10.0.19645.1046
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/76490be66e4d2ebf054c9d536b02c82a5c6bb97209f8e4cffc69974a04fa7bd7/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-ABA7E7513886979AF8A3B68A1F4E591D.md) | 80
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-D1B722A188C84E5059765FA87E8C5F32.md) | 79

## Possible Misuse

*The following table contains possible examples of `DeviceCensus.exe` being misused. While `DeviceCensus.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\DeviceCensus.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_win_reg_telemetry_persistence.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_win_reg_telemetry_persistence.yml) | `- '\system32\DeviceCensus.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


