---
title: mousocoreworker.exe | MoUSO Core Worker Process
excerpt: What is mousocoreworker.exe?
---

# mousocoreworker.exe 

* File Path: `C:\WINDOWS\system32\mousocoreworker.exe`
* Description: MoUSO Core Worker Process

## Hashes

Type | Hash
-- | --
MD5 | `247911E166A49792D94B0A82CD201A61`
SHA1 | `45985AC3040A96CCBADCADF2E93359139ABE3A64`
SHA256 | `0E3F03283F8BA070498351CA3068B3B0FF54DF8275B0276BD6B26639FA04ED34`
SHA384 | `54D74BEF2D13AEA5739A934B584E9B895970AEAEAB37FE19833CD203B7143995D3C3A327006F21928CFEF9F1885CF0ED`
SHA512 | `5DCA6360117118554E2ED96A1B511E1D85C6418EB05C8B176A75F072D14A837FF3C471147F3BDEFD481ED2919CBA5E2EF62085B52DA7A5260A7CBC00ADAF2A97`
SSDEEP | `6144:ADos+dDnz88uogqvOvyf45pD04dudI4SYtJzLAyW6/Rxxv4fYHuU:HdPuWmlp0i8lSCfWsSXU`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MoUSOCoreWorker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.418 (WinBuild.160101.0800)
* Product Version: 10.0.18362.418
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `mousocoreworker.exe` being misused. While `mousocoreworker.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\MoUsoCoreWorker.exe'  # c:\windows\System32\MoUsoCoreWorker.exe on win10 20H04 at least` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


