---
title: sdiagnhost.exe | Scripted Diagnostics Native Host
---

# sdiagnhost.exe 

* File Path: `C:\windows\system32\sdiagnhost.exe`
* Description: Scripted Diagnostics Native Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9BB47FC39CB24A16A0AB0302960645BA`
SHA1 | `8963ED884F78D263A039A9A68719840412ED30AD`
SHA256 | `50A816FE57195376AD30AEEC2EA7968936A706508E26299302F30366CC7FF3A4`
SHA384 | `3D48D1810E0ADF70CE8DEC34A387E63A1F3AB8C83822A989D7A4F94B374A4CCFB67814537087802392B08DA048689FBE`
SHA512 | `BC4EBE417272BFDAAF85D073C7D598C8B7DB74CF26FC220AE1AE247DF08F6D30D804D16BDE4AE12D2CDA1039F3BABF877EEB7469C6DD29CE3CC77B0382BB097B`
SSDEEP | `384:9NaPLsFWEjuhHKkTy8YBFMHgrQMylq1MIHGcMXgva/HRlsvfyxKil8WG7DW:bsL0W7gkzy/Wd/HPsnaKim`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdiagnhost.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\sdiagnhost.exe](sdiagnhost.exe-4946EEFDBC08E0BAD98033137502FAA6.md) | 30
[C:\WINDOWS\system32\sdiagnhost.exe](sdiagnhost.exe-6458634E67F8AE415A0A871953C04F06.md) | 74
[C:\Windows\system32\sdiagnhost.exe](sdiagnhost.exe-6A21B1893DDE94CB87BA56111375888A.md) | 36

## Possible Misuse

*The following table contains possible examples of `sdiagnhost.exe` being misused. While `sdiagnhost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `            - '\WINDOWS\System32\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `            - '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `            - '*\sdiagnhost.exe'  # https://twitter.com/gN3mes1s/status/1206874118282448897` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


