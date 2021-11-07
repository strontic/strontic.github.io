---
title: SIHClient.exe | SIH Client
excerpt: What is SIHClient.exe?
---

# SIHClient.exe 

* File Path: `C:\Windows\system32\SIHClient.exe`
* Description: SIH Client

## Hashes

Type | Hash
-- | --
MD5 | `3AA9B1E2EACBA5A4F0E4A70C9011823F`
SHA1 | `0897B4076EC223A6F3C27D78197A615F05D0AD52`
SHA256 | `9F2FE7D4D0ADCC5603061B13D4137D9EB6B70C8237155EFA89CA1E051404E176`
SHA384 | `0AF745B27D95F97FE815A2E3C7DB8CB8A5FFC883D2B312B22B7325E6B526A6949F52D37FB4AB73A5861997CC2FF2618C`
SHA512 | `84AB7AC8DAE51C642B7300F8CE2C148B480B9F21CE2E9EFF5A9519B6B222A63F182807E8E51E9C1B62DD2000A606E7D0D54E773A2010EE0843E66089E0A86632`
SSDEEP | `6144:4DhwRtf2FuHuciopATl+dPDLjvdgWRQafx7bfWqVT+ETWzksFfTYFG/:4DqRbu/56jvevej+8AhNTkG/`
IMP | `24BEEBD601B5063268F15D87E7460043`
PESHA1 | `4197E86CA98113DDCD43E2BFC7B15542D0E42849`
PE256 | `FFEE25C557B49D990BAA628F8929E5716186A7AFDE04C92F8794DB2EE4BCDA69`

## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sihclient.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9f2fe7d4d0adcc5603061b13d4137d9eb6b70c8237155efa89ca1e051404e176/detection


## Possible Misuse

*The following table contains possible examples of `SIHClient.exe` being misused. While `SIHClient.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\SIHClient.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


