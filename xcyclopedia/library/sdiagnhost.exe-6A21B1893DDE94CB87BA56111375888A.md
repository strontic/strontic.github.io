---
title: sdiagnhost.exe | Scripted Diagnostics Native Host
---

# sdiagnhost.exe 

* File Path: `C:\Windows\system32\sdiagnhost.exe`
* Description: Scripted Diagnostics Native Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6A21B1893DDE94CB87BA56111375888A`
SHA1 | `540745F1CE67423A156069218680B9DA873B4778`
SHA256 | `761815301A00D0B3A7BB4959A5004B623C55009CE701C6E867C96F468DC1323A`
SHA384 | `4A7C83879CB0A023C98E7908A706B88D4B44C8CA3253884A0A9E030CD5CFEDFA821DF4D2A9A4FB4B79AC2AEFCE08B35C`
SHA512 | `AB4261F78EABC4EFD9ECA0240C147F69A17DBFFAE0486420AA2396A1C1260F82889D060FC4D3D4959AD84C23E65BD1C0AFA8F3328B4497B14391439ECF5CAC08`
SSDEEP | `384:bJwNWEgA6slYA8AGoZesJ1MYEFu8BNtbFTpUHGcMXgvaNS/uoJwJsL4BxKilsWh2:dwNW764o/+b7rHNS/uLs8KiR`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdiagnhost.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\sdiagnhost.exe](sdiagnhost.exe-6458634E67F8AE415A0A871953C04F06.md) | 35

## Possible Misuse

*The following table contains possible examples of `sdiagnhost.exe` being misused. While `sdiagnhost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `            - '*\sdiagnhost.exe'  # https://twitter.com/gN3mes1s/status/1206874118282448897` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_in_memory_powershell.yml) | `            - '\WINDOWS\System32\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


