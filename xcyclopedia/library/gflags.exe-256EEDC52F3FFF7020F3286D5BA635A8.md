---
title: gflags.exe | Microsoft NT Global Flags Manipulator
excerpt: What is gflags.exe?
---

# gflags.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\gflags.exe`
* Description: Microsoft NT Global Flags Manipulator

## Hashes

Type | Hash
-- | --
MD5 | `256EEDC52F3FFF7020F3286D5BA635A8`
SHA1 | `B04D9E1E6F458E9EAC955FCFEB2A2C0123A5DF5D`
SHA256 | `451E75D8FA831240B208001D3E23B1DC26AB9152A24701604E289CE0A444E956`
SHA384 | `74D117B3ED948AD7482C5B8E0E461E92F49FA64712B28492ACACE95644566B95F02648F326E5B7F2CC98D9350A5B1B53`
SHA512 | `67BBB865AFEC13E4F3A881ED3CAFDBCD544CCA5AC66AF95BB6798A377770D8C359ED40965FA66E50608BFDF8F0949865EABA52DC49883C8B7B13BEF6A6ADFB4F`
SSDEEP | `768:EKg0lUMWZi2meQwBPXoyPegU6x6ODSKL5b8p6zVTgs0qgWCmuVTvZ:EM+QehA764qdt8m90qDC3VTvZ`
IMP | `7E0A5BBAA33183B687A994F22C63644E`
PESHA1 | `1CC12A9F59C5170483C4B4FACECCFB852FB8FA4D`
PE256 | `A61C03B2CC42684A707D4FD09283B3500C52BF0A5406BFEBEE554F5BF25A9A14`

## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GFLAGS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 452

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/451e75d8fa831240b208001d3e23b1dc26ab9152a24701604e289ce0a444e956/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\gflags.exe](gflags.exe-8B6FDD8FEF0CABD5CC556E1BC81D0B7C.md) | 43

## Possible Misuse

*The following table contains possible examples of `gflags.exe` being misused. While `gflags.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | IFEOs can be set directly via the Registry or in Global Flags via the GFlags tool. (Citation: Microsoft GFlags Mar 2017) IFEOs are represented as <code>Debugger</code> values in the Registry under <code>HKLM\SOFTWARE{\Wow6432Node}\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\<executable></code> where <code>&lt;executable&gt;</code> is the binary on which the debugger is attached. (Citation: Microsoft Dev Blog IFEO Mar 2010) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | IFEOs can also enable an arbitrary monitor program to be launched when a specified program silently exits (i.e. is prematurely terminated by itself or a second, non kernel-mode process). (Citation: Microsoft Silent Process Exit NOV 2017) (Citation: Oddvar Moe IFEO APR 2018) Similar to debuggers, silent exit monitoring can be enabled through GFlags and/or by directly modifying IFEO and silent process exit Registry values in <code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\SilentProcessExit\</code>. (Citation: Microsoft Silent Process Exit NOV 2017) (Citation: Oddvar Moe IFEO APR 2018) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


