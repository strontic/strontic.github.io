---
title: audiodg.exe | Windows Audio Device Graph Isolation 
excerpt: What is audiodg.exe?
---

# audiodg.exe 

* File Path: `C:\Windows\system32\audiodg.exe`
* Description: Windows Audio Device Graph Isolation 

## Hashes

Type | Hash
-- | --
MD5 | `E791E1D0340715D40E21D3D3C597F626`
SHA1 | `4319623AAFCF9B5AE6BB21153DCE66F6D3CFFB0F`
SHA256 | `BDBFE066F1981FE67CFB883C592DAC491EFC58B61E17042E31D3BACE8731C41F`
SHA384 | `DB0E2282F0C44C2C594353FF3EC4EA1D744C1AA3070A9CF83F22781CEEAA44924A5FFE709B44A0BB3EF6B547D7C7C496`
SHA512 | `2BADC97758AD9F019E0960CC6113F5BC69B29D4B0C356F70CFCE417ABD65541F876DBAD7173460FB3EA03BBC0B0F93E937C3B486BDBBF47F35BBD9AC89B9890B`
SSDEEP | `12288:k+R8p42ZtfKixtfPqXHJ0yBLPcgu76LKmGDZVHda:k+Rz2ZtfQHxLPccLEDrE`
IMP | `952B47AE2CBEF2B729D43731280B0997`
PESHA1 | `1FEF489F8B716FBF4BF08BEF33E3F2DF0AFE0555`
PE256 | `E19CEA57013C78FE2B342BBACDF5E0C5A5992583420D4E8FF7AC9B06EE9696BF`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\audiodg.exe |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MMDevAPI.DLL |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: audioadg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/bdbfe066f1981fe67cfb883c592dac491efc58b61e17042e31d3bace8731c41f/detection/


## Possible Misuse

*The following table contains possible examples of `audiodg.exe` being misused. While `audiodg.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


