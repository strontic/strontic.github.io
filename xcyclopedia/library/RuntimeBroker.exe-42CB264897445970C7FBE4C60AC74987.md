---
title: RuntimeBroker.exe | Runtime Broker
excerpt: What is RuntimeBroker.exe?
---

# RuntimeBroker.exe 

* File Path: `C:\Windows\system32\RuntimeBroker.exe`
* Description: Runtime Broker

## Hashes

Type | Hash
-- | --
MD5 | `42CB264897445970C7FBE4C60AC74987`
SHA1 | `3AF6154156D8CC1B695FB6F44993CDF83D092680`
SHA256 | `70D968B4F65C5CE471474096F8623AECD7D496E4F10C8B94C3577C8362E0ADA1`
SHA384 | `18DB1853AB7D0F515D242844C4C99D9F5F6343B4DC1C7D2DBB6B097A357F9DA9054CC5E4809225F0F991B2848299F9AA`
SHA512 | `99D048E8CC77036B021E47E6EDE75E9D4F70D1134DCDF6B010A20AB2A4D379D3E8E3393B4D83A9A5097B9AD1A5F42F4FEECF20E3073BF7E0BDA6D8D6AA30E296`
SSDEEP | `1536:hAL8w3ydlf2ggSgbeHLIloWMUlySN+vQyk6x/Q4GE/5K5/Zdxq2VLUc6fraqP2OZ:dP0glgbRlDMQq/QddxqALyOqu`
IMP | `D4D98ACF3243E0C97C83C6548571A44E`
PESHA1 | `49E1D467B4C4305B75AD0133ED1A304A486C6D49`
PE256 | `5D28BAF57043D3406097F2EB2B9998C2844258605DC671706A85B1CF441AF79C`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\powrprof.dll |
C:\Windows\system32\RMCLIENT.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\RuntimeBroker.exe |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\UMPDC.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RuntimeBroker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.546 (WinBuild.160101.0800)
* Product Version: 10.0.19041.546
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/70d968b4f65c5ce471474096f8623aecd7d496e4f10c8b94c3577c8362e0ada1/detection


## Possible Misuse

*The following table contains possible examples of `RuntimeBroker.exe` being misused. While `RuntimeBroker.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\RuntimeBroker.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\runtimebroker.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\RuntimeBroker.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


