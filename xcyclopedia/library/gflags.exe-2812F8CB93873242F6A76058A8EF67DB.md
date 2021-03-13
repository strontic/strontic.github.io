---
title: gflags.exe | Microsoft NT Global Flags Manipulator
excerpt: What is gflags.exe?
---

# gflags.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\gflags.exe`
* Description: Microsoft NT Global Flags Manipulator

## Hashes

Type | Hash
-- | --
MD5 | `2812F8CB93873242F6A76058A8EF67DB`
SHA1 | `6AEB207485B19A491A96044EA14D5FAA88D205F1`
SHA256 | `444EC25F2326C8E0B4111FDC7068115E2ACC397CBB7353C933E9AC13302CF9D6`
SHA384 | `70D5361C4608CF523B4D90AB2C144757DDC2BC78AD03074FB49F9126B7E6ED54EF62F7D243D38129440C4F70C002BB55`
SHA512 | `486CFADCF3EBA5130D4A679F96C3E5CA7BABA8AF25CD63215C886DEE89B860A34BBF9251A95EB6CC6356CEE170616D48AE907C58BF8B389EFFE84B32A044AFE9`
SSDEEP | `1536:0PK4gkN5DBivIbZUzY7x443ySndRfD4eRC5GCAXVcg0ycJ:9BSndRfD4eRovAFcg0ycJ`
IMP | `981942E76E9072C66057E1B72D92A0BF`
PESHA1 | `CC2EAE1964D32C8AA430B26D20B099C8A6B84966`
PE256 | `8D861C36F9F8D305A6F3BB13E9CEC98CE01C2292E2BAE845546216876B4EE8D6`

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
* Machine Type: 64-bit ARM

## File Scan

* VirusTotal Detections: 1/75
* VirusTotal Link: https://www.virustotal.com/gui/file/444ec25f2326c8e0b4111fdc7068115e2acc397cbb7353c933e9ac13302cf9d6/detection


## Possible Misuse

*The following table contains possible examples of `gflags.exe` being misused. While `gflags.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | IFEOs can be set directly via the Registry or in Global Flags via the GFlags tool. (Citation: Microsoft GFlags Mar 2017) IFEOs are represented as <code>Debugger</code> values in the Registry under <code>HKLM\SOFTWARE{\Wow6432Node}\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\<executable></code> where <code>&lt;executable&gt;</code> is the binary on which the debugger is attached. (Citation: Microsoft Dev Blog IFEO Mar 2010) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | IFEOs can also enable an arbitrary monitor program to be launched when a specified program silently exits (i.e. is prematurely terminated by itself or a second, non kernel-mode process). (Citation: Microsoft Silent Process Exit NOV 2017) (Citation: Oddvar Moe IFEO APR 2018) Similar to debuggers, silent exit monitoring can be enabled through GFlags and/or by directly modifying IFEO and silent process exit Registry values in <code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\SilentProcessExit\</code>. (Citation: Microsoft Silent Process Exit NOV 2017) (Citation: Oddvar Moe IFEO APR 2018) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


