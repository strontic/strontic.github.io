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
MD5 | `F0CE4673A831198F6BDC136254680D86`
SHA1 | `18C6C11CACA4FE1574A2823D24AA098279DFC784`
SHA256 | `EDE5F911823FAE6A743E1C24DA62D0303D07FEC8A50795E8615E2B6946A7ACD4`
SHA384 | `086FE7D3156E3D133949CC9121A5E7604678726FEFBF4F5A4E73AA4D0E3587FE8FA51CB6D0A77EB65EB0DA3FF375CB0D`
SHA512 | `8456628F92F2A8BAF315AD88ACC20BE680E0939A902426EE4CC98FB0995A39A2DF53FC4ED7D5594B9C1E95B600FD43FBDFD9B22873CF058679EBDF33AF0ABDC7`
SSDEEP | `24576:sHecXLD4nZ5odcc53aEiaXjJMDzlwcGURWsFCFWjCi4OZyHGKvOgHq:s5LUZ5odz53BgwgRTFCFWjCikhv`
IMP | `4F8F44BDF9E6EDF9B44D1DF38F33C6C2`
PESHA1 | `89832886CCB6ADDCA7E2302E69E437689A19A7B2`
PE256 | `B3859DC852A6C5B175C2ACED77EA165806BAE774E3CE03FD50CB4582FAD17CCD`

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
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MoUsoCoreWorker.exe |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MoUSOCoreWorker.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1320 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1320
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/ede5f911823fae6a743e1c24da62d0303d07fec8a50795e8615e2b6946a7acd4/detection


## Possible Misuse

*The following table contains possible examples of `MoUsoCoreWorker.exe` being misused. While `MoUsoCoreWorker.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\MoUsoCoreWorker.exe'  # c:\windows\System32\MoUsoCoreWorker.exe on win10 20H04 at least`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


