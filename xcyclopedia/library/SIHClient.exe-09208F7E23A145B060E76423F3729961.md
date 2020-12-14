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
MD5 | `09208F7E23A145B060E76423F3729961`
SHA1 | `53E696941B2A5FA304100CD0011F9478F282DAB7`
SHA256 | `5A299F6FBE0E5ECBD1622F4ECE9C475BFCEF37DB0BD991C034597A587062E900`
SHA384 | `6C7815962E0F7D3713D3E77687B62E2B933AECCC40CB080DF5BAC8F13A9855BDC2B748AD57F2A63F4460190B21FC5203`
SHA512 | `5317B2367469CE1A6DDCB65930D23656BE59AAD0772361123C29D584C591FCB6571C87403670A7F0C149F2984F90B4BFB55405A230FC660F15CB600FE8151A24`
SSDEEP | `6144:kbSNlGA45uWSlDxFb9unjchIGCvNtwG7965YPmsT7X/+dKIIXwnUzFMT125:6SNvzs3rvDw6+tmv+vUzKTQ5`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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



## Possible Misuse

*The following table contains possible examples of `SIHClient.exe` being misused. While `SIHClient.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\SIHClient.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


