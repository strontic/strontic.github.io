---
title: net1.exe | Net Command
excerpt: What is net1.exe?
---

# net1.exe 

* File Path: `C:\Windows\SysWOW64\net1.exe`
* Description: Net Command

## Hashes

Type | Hash
-- | --
MD5 | `2D06D33D05E02C11DC5C5B9A671E974C`
SHA1 | `B4A2C1230227500BFA40ABFE6722AB88E97ACF5E`
SHA256 | `964722D4207CDF6C2419212E101B453A7C6DAFD3B65AC9205AAEA4D38C5514E4`
SHA384 | `B6FA912B1A0BA0B9CCB9BB7982AC72EB9F1AD5CF0DCF414C51E37537208437910F9A50C7D2B45D1B98697C07130AB983`
SHA512 | `3F4D3EFBC81DBDB27D5A8E4015B9C5A3847EF26B3525531684F4B8E5F2E959D2CBEF36F26BB429C9130A030986EFBB84AC83246A4133C46375A32C0C20663D2B`
SSDEEP | `3072:DKTO7WOip+MUEAWChg4wqPceuZS5/wNlWKiHBVjR:OTSEpGRZjuZS5/wNgKiHBhR`
IMP | `1D734F0B53689FA33F2F764B9CDCF8EE`
PESHA1 | `345B9477403C930FBF6D781034379194DB3F0FD4`
PE256 | `34B357E41777AA5DBE2FDBECBE06F51FFEC7EC68E24B6F781C1ECA772DA64E46`

## Runtime Data

### Usage (stdout):
```cmhg
The syntax of this command is:

NET HELP
command
     -or-
NET command /HELP

  Commands available are:

  NET ACCOUNTS             NET HELPMSG              NET STATISTICS
  NET COMPUTER             NET LOCALGROUP           NET STOP
  NET CONFIG               NET PAUSE                NET TIME
  NET CONTINUE             NET SESSION              NET USE
  NET FILE                 NET SHARE                NET USER
  NET GROUP                NET START                NET VIEW
  NET HELP

  NET HELP NAMES explains different types of names in NET HELP syntax lines.
  NET HELP SERVICES lists some of the services you can start.
  NET HELP SYNTAX explains how to read NET HELP syntax lines.
  NET HELP command | MORE displays Help one screen at a time.


```

### Usage (stderr):
```cmhg
The syntax of this command is:

NET
    [ ACCOUNTS | COMPUTER | CONFIG | CONTINUE | FILE | GROUP | HELP |
      HELPMSG | LOCALGROUP | PAUSE | SESSION | SHARE | START |
      STATISTICS | STOP | TIME | USE | USER | VIEW ]

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\net1.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: net1.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.546 (WinBuild.160101.0800)
* Product Version: 10.0.19041.546
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/964722d4207cdf6c2419212e101b453a7c6dafd3b65ac9205aaea4d38c5514e4/detection


## Possible Misuse

*The following table contains possible examples of `net1.exe` being misused. While `net1.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- '\net1.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_net_enum.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_net_enum.yml) | `- '\net1.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_net_user_add.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_net_user_add.yml) | `- '\net1.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_time_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_time_discovery.yml) | `- '\net1.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'net1.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\net1.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_service_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_service_execution.yml) | `- '\net1.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_service_stop.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_service_stop.yml) | `- '\net1.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_net_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_net_execution.yml) | `- '*\net1.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


