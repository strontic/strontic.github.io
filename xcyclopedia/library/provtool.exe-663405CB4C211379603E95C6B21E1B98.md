---
title: provtool.exe | Provisioning package runtime processing tool
---

# provtool.exe 

* File Path: `C:\WINDOWS\system32\provtool.exe`
* Description: Provisioning package runtime processing tool

## Hashes

Type | Hash
-- | --
MD5 | `663405CB4C211379603E95C6B21E1B98`
SHA1 | `0F41E321FEB96B53A2A2E178C77D6FEFC29EC5A7`
SHA256 | `C4035D083053F59F6ECDBC8C804463D038F9CF7730D680B3693780D14B44A42F`
SHA384 | `FE99C562046BEF226F62BE17BA9DF177A5A44DB4830D9338E23BD3B7A7A79BD2F415264DCC5D7FE96CDD0643146C2088`
SHA512 | `E933744C12A6C41993807EAC7EE5F2EC25503E53B9E07A934BA86E3CF6C042F35D5D7A44CA341383F6876E6FECEB7654D36E6E3C974B0D572AAB378D7DEFCAD3`
SSDEEP | `1536:F5rqBynKLU3zwoktZwol60ED5ZnWRemvvrtO/kRMOTgDfZZt+qK7MI:UdUUouZll61DJstORO8DRZtUj`

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\msvcp110_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\provtool.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: provtool
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.719 (WinBuild.160101.0800)
* Product Version: 10.0.18362.719
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `provtool.exe` being misused. While `provtool.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\provtool.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


