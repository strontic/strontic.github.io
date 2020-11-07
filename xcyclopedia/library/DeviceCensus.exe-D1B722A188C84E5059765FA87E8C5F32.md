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
MD5 | `D1B722A188C84E5059765FA87E8C5F32`
SHA1 | `05D74408A9899054FF5CEA5DAC98858062E3250E`
SHA256 | `1041623963E1A109B80312CBFE4DC4544CBAC478C2EB2597CA040E1C78585A3E`
SHA384 | `D6D2D21403EE174CAE34EA0ACD3F96C29E7E5B0251B4634F86E65D42922295499C1AF35F3C8E89B5B43FA816C74D0440`
SHA512 | `4EB2B33C511A6623706D3A5A87394A25D80FBDA3AB82D7C49ABB4AD4D46A495B98D7A0EFAAE8F08E11984183F02E292A7922AA5E42BCDA7CC8AA2B71F908E730`
SSDEEP | `384:3hbaEPVaYmPw5gyLjuCrHGOl2R3qj37nec/gWJXn7fRUWbgWPc3228hDBRJwzJXj:RmEsxwGPcrl08Cc/giXn7nSih1PwVEI`
IMP | `69755EB5A4F06F0B816F7B23B33E44E8`
PESHA1 | `6522AD1A8757A9F38761C7E46AFCE10B8A2FF8F2`
PE256 | `FAE15D42944FDAE6A68B1E5A83CCB5055F781C909009C3F44CAA668D4BA36E23`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\system32\dcntel.dll |
C:\Windows\system32\DeviceCensus.exe |
C:\Windows\system32\IPHLPAPI.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\logoncli.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\netutils.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\ntmarta.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\SYSTEM32\powrprof.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\WINHTTP.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DeviceCensus.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19645.1016 (WinBuild.160101.0800)
* Product Version: 10.0.19645.1016
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/1041623963e1a109b80312cbfe4dc4544cbac478c2eb2597ca040e1c78585a3e/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-ABA7E7513886979AF8A3B68A1F4E591D.md) | 86
[C:\Windows\system32\kdhvcom.dll](kdhvcom.dll-A4FAD08A4DDE0DEAE2062FAFF9DFE500.md) | 29

## Possible Misuse

*The following table contains possible examples of `DeviceCensus.exe` being misused. While `DeviceCensus.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\DeviceCensus.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


