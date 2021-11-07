---
title: winrshost.exe | Host Process for WinRM's Remote Shell plugin
excerpt: What is winrshost.exe?
---

# winrshost.exe 

* File Path: `C:\WINDOWS\SysWOW64\winrshost.exe`
* Description: Host Process for WinRM's Remote Shell plugin

## Hashes

Type | Hash
-- | --
MD5 | `6052104B17F7344A9655A3EE30365D1A`
SHA1 | `0F5605DFF843BA9F6AC693E059D3132FEBF4B0B8`
SHA256 | `C544EA4A01F1BC674D6F1A47A8D2DE6E6F849C069373EF71084C8FDB13DE5C8C`
SHA384 | `A27404355CD7040243BA3953C2788BC52FE554AB812F69ABBC964095FD5C4A3D97C83BBA92C371EE5C15E12F5C13C963`
SHA512 | `A88B62881286D941459FA0DE6FBA362B635C5CEEA9AC0849DDB956104677DFB0CB7CF1B71960BFD46E274B98053DA2EE3C7ED455BCF3EEBD708153FFAC7875CD`
SSDEEP | `384:qhPCqQ2beFNVFsTVXMg2KOUBECQTTW3ap/RXVWstEW:8qqzbCNVFsRMg2CSaKp/BF`

## Runtime Data

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winrshost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\winrshost.exe](winrshost.exe-06044E3942AB103B96307187BBD1ED93.md) | 43

## Possible Misuse

*The following table contains possible examples of `winrshost.exe` being misused. While `winrshost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\winrshost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


