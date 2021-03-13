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
MD5 | `1F50EF577639002F59FC1D3FB0D23973`
SHA1 | `8714B1B883D08FFB750AAE72FEFF1C72EA661E61`
SHA256 | `154316C8E1FE282655A3DF44F5AF3B0C5F0ECC37449EFF4B3EAD44FB7414D468`
SHA384 | `72FB0863C6D4A3580EDBAE96D5AE4FB22933468D2BD1C61B2A47F64A62AF9824C270EAD7F915B2C2443DE5142C4433B3`
SHA512 | `C898F36A017528BD43D47608F35624F70FE87641CA1A37143799EEEB9ECBE5BB4FC7D7A7EB10EBE716EC0B81B2B6CED6427678457967B0B397F2C9C93DA7F4D2`
SSDEEP | `1536:mXeOfHS56N5D1x+qykhcdsl0VKTQIdeIwx/yvWxO2VokIdCKP3:op5D1I9kWdYA/yvWxOAHKv`
IMP | `D4D98ACF3243E0C97C83C6548571A44E`
PESHA1 | `E46D876406D73511F6668F0DC0B359CAE49410BB`
PE256 | `10CF857D4D3FDB3C9CBA91A5B7FAF1B96301E6F6C632CAF80F122B375F61356A`

## Runtime Data

### Loaded Modules:

Path |
-- |
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


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RuntimeBroker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/61
* VirusTotal Link: https://www.virustotal.com/gui/file/154316c8e1fe282655a3df44f5af3b0c5f0ecc37449eff4b3ead44fb7414d468/detection/


## Possible Misuse

*The following table contains possible examples of `RuntimeBroker.exe` being misused. While `RuntimeBroker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\RuntimeBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\runtimebroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\RuntimeBroker.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


