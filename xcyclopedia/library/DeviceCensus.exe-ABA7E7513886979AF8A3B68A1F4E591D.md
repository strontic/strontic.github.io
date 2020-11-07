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
MD5 | `ABA7E7513886979AF8A3B68A1F4E591D`
SHA1 | `A94E7B939A8A1007F6719503BE54A09F64801AC7`
SHA256 | `AFD0D80A782E9392664CA32811055B958BD4D373F4F2BA52BFA8F7FE9C893190`
SHA384 | `C17CC639144ADFCF68DEE0B8E98F82AFAC4F94E71651838090E22B4D87050D0F190E6F4107B17385DEB7FADD8F37EA51`
SHA512 | `009BC8CC1F65585642813222884D2BE1882C0A09981DC4CC947925FEDEDAB9F8368DC19A1E9BF012477C68826B961134E96B90AE01DED6535A1F3F8AB1AC42DA`
SSDEEP | `384:1hbaEPVaYmPw5gyLjuCrHGOl2R3qj37nec/gWJXn7fRUWbgWPc32Kr6wDDBRJNSk:LmEsxwGPcrl08Cc/giXn7nSdr6wD1PSA`
IMP | `69755EB5A4F06F0B816F7B23B33E44E8`
PESHA1 | `6522AD1A8757A9F38761C7E46AFCE10B8A2FF8F2`
PE256 | `FAE15D42944FDAE6A68B1E5A83CCB5055F781C909009C3F44CAA668D4BA36E23`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\dcntel.dll |
C:\Windows\system32\DeviceCensus.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |


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

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/afd0d80a782e9392664ca32811055b958bd4d373f4f2ba52bfa8f7fe9c893190/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\6bea57fb-8dfb-4177-9ae8-42e8b3529933_RuntimeDeviceInstall.dll](6bea57fb-8dfb-4177-9ae8-42e8b3529933_RuntimeDeviceInstall.dll-513E16B14C2E8DE6AEA439153A9733FD.md) | 32
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-D1B722A188C84E5059765FA87E8C5F32.md) | 86
[C:\Windows\system32\LocationFrameworkPS.dll](LocationFrameworkPS.dll-FBF3B3CCC037AD1D9FC36C28D0E29A25.md) | 32
[C:\Windows\system32\migwiz\migres.dll](migres.dll-E937B164DC2D2A03490AC3EB9D5875B2.md) | 25
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-09C06B0224F439DF8666CF7B411B7B1C.md) | 27
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-BD3FC089F0D20F1D9172EA5CD41B2CA8.md) | 32
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-C64357854C5214AC178B78EF1A17042F.md) | 29
[C:\Windows\system32\WerEnc.dll](WerEnc.dll-57896D83DAD20250B3878747AB6115F6.md) | 30
[C:\Windows\SystemApps\MicrosoftWindows.UndockedDevKit_cw5n1h2txyewy\UndockedDevKit.exe](UndockedDevKit.exe-C1FD0D396683E3F59646E4CEC2A55A85.md) | 29
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-F290D12F0351B56708B3DF1EC26CB45B.md) | 29
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-6F3C9485F8F97AC04C8E43EF4463A68C.md) | 32
[C:\Windows\SysWOW64\ResourcePolicyClient.dll](ResourcePolicyClient.dll-AA11A4DDE5147A0EEBB147140A1AD6EF.md) | 36
[C:\Windows\SysWOW64\WerEnc.dll](WerEnc.dll-F4C2183256B20B62EBD7C9397F0C5D85.md) | 29

## Possible Misuse

*The following table contains possible examples of `DeviceCensus.exe` being misused. While `DeviceCensus.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\DeviceCensus.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


