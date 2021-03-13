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
MD5 | `B23D3D91F4892DF3FA0D1E84B97E8160`
SHA1 | `66E20A912978E16B0E06F82C071134962B40A5F1`
SHA256 | `86BB2DFF3F88B2F1AB8DD2C1B6FA3CE78089791D5C446A587BA5F67CD80F7059`
SHA384 | `01372ED061D3B9684377DA0104365D3EB825D95D97FF684527B41867F187658FABD1E6454814D3C45A9B9AD6D4BEC263`
SHA512 | `EFF4D8DF7D7C27BBC16B5758C2C174F7F71D17E1C294138B6E77D7AF1E4123B1DD904248ABB320613C55805E302231BD3166B752540F14D4CBD468A68B8299C6`
SSDEEP | `24576:RvVaye5LiMW0i6dxxDyrRLUCIU6GH8kGWutsG3Cz:2yeBYd688kG5tC`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{F79646A6-8BE5-443B-A98F-AD03D667F646}.2.ver0x0000000000000001.db | Section
\Sessions\1\BaseNamedObjects\SessionImmersiveColorPreference | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\combase.dll |
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
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `MoUsoCoreWorker.exe` being misused. While `MoUsoCoreWorker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\MoUsoCoreWorker.exe'  # c:\windows\System32\MoUsoCoreWorker.exe on win10 20H04 at least`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


