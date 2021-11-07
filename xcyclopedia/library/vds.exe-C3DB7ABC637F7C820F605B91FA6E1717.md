---
title: vds.exe | Virtual Disk Service
excerpt: What is vds.exe?
---

# vds.exe 

* File Path: `C:\Windows\system32\vds.exe`
* Description: Virtual Disk Service

## Hashes

Type | Hash
-- | --
MD5 | `C3DB7ABC637F7C820F605B91FA6E1717`
SHA1 | `5A494165A180868545C68E3C78B5C85BA39ADECF`
SHA256 | `D10944C16053504739AF3F1F2620FA652B2191622E826199AA69F19467AA494D`
SHA384 | `05C17B8A32C59637D1B553F64D5B7BA138A9C62CEC1894D3890DBE23029AC6C47EEB30A4DC4D670E9387AC8DF289391C`
SHA512 | `32048CA57F4C2815BB64832B437B9B6D4AACBD9F2378DFEAC52D16464A5C356BDA17ECFBD6A00C5C2844F264B772ABBF161BD3F15654BCE4270F60DA0C19E630`
SSDEEP | `6144:nWLjMCM2hvStTF/yHS53CJv7GYnZmzGrQ5zBGDvZvYV4Fn9N3x/VVo3bn/GTq0:WLQZb3C97GYnZMv5zBcKY93MD3`
IMP | `4A3C9169FCD22D57CCAE48D36854D00F`
PESHA1 | `3429F26FBEBD5BCD19FC3F4679130A814758C762`
PE256 | `F2BFA22BBEEC8F0C2A6A4662EC8843A4522E76A3CCE497D2A000947536C2A992`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\vds.exe |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vds.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d10944c16053504739af3f1f2620fa652b2191622e826199aa69f19467aa494d/detection


## Possible Misuse

*The following table contains possible examples of `vds.exe` being misused. While `vds.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\vds.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


