---
title: MoUsoCoreWorker.exe | MoUSO Core Worker Process
excerpt: What is MoUsoCoreWorker.exe?
---

# MoUsoCoreWorker.exe 

* File Path: `C:\Windows\system32\MoUsoCoreWorker.exe`
* Description: MoUSO Core Worker Process

## Hashes

Type | Hash
-- | --
MD5 | `66D5E472CAC7AD32561F891AACDC71D9`
SHA1 | `F3DA6968A419685023BB46D00B47ED343047FE5A`
SHA256 | `22AFA24D1A010B9465897BD8657FF34F27EFEC9EF0AA919EB3F211F1C1026948`
SHA384 | `6525625D72DFB029FC4C327048D28C35CDFFD1C227C592230E127F76E1F7E485455A1364FC2E598C04ED9DF9843969F0`
SHA512 | `FC6153E8BA6C5DBEBE2EC90903803B1D32E1EE08AE26DBA5FE285E92DE7AB157C07DC73107C7F3E630A6FCE29C84C6DC00791E337C5EC4764E9A0FA05FB13E2D`
SSDEEP | `24576:aZJvYqhVusESiktB0KL0PcQFGH0pyPGgLipKQsG3WTs:EgqazJB00MPGdpDtW`
IMP | `39233DDAE71CD9D2B0CA5AA6FDD61054`
PESHA1 | `4EF7DFA80D44EBC484A6939678465571E027AEE6`
PE256 | `A008E3448A4196FE5F5D0763C639A422EF36F607D0AB719169E80236BBC96100`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\system32\dmiso8601utils.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MoUsoCoreWorker.exe |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MoUSOCoreWorker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.662 (WinBuild.160101.0800)
* Product Version: 10.0.19041.662
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/22afa24d1a010b9465897bd8657ff34f27efec9ef0aa919eb3f211f1c1026948/detection


## Possible Misuse

*The following table contains possible examples of `MoUsoCoreWorker.exe` being misused. While `MoUsoCoreWorker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\MoUsoCoreWorker.exe'  # c:\windows\System32\MoUsoCoreWorker.exe on win10 20H04 at least`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


