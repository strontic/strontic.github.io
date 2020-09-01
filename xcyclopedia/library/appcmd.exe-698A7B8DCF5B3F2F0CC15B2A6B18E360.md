---
title: appcmd.exe | Application Server Command Line Admin Tool
---

# appcmd.exe 

* File Path: `C:\Windows\system32\inetsrv\appcmd.exe`
* Description: Application Server Command Line Admin Tool

## Hashes

Type | Hash
-- | --
MD5 | `698A7B8DCF5B3F2F0CC15B2A6B18E360`
SHA1 | `FCD71B4916276D196F460B0A976EFBB8ADF3EC63`
SHA256 | `429BC84BABE1387ABF59EEFB0B225A1F5317FDB1D3F29995DBD5604E78B3AC33`
SHA384 | `2BD82FD4F7FA4EBE6EA86BD3B47007FFD7B9112BA74E44F603800DA3E0D5F0150A70ECE49A0C44EBF80EDE9B7CB65D61`
SHA512 | `52FAC7A7AEDF942164942E8F74D39E1C67DA91208889EDEB5F8783C7F2DCF574FF7A71CE257C01BE63641545D2D0707D52DF8F621456906B13180CC22D69FE83`
SSDEEP | `1536:rzc/N8pKKbblNVh0x7ryf4SMwEyFgKkQx5YkUz82/ZF2on8XZj:ra8Eq3amZVEyyKzxikUz82/ZF2o8Xl`

## Runtime Data

### Usage (stdout):
```Batchfile
General purpose IIS command line administration tool.

APPCMD (command) (object-type) <identifier> </parameter1:value1 ...>

Supported object types:

  SITE      Administration of virtual sites
  APP       Administration of applications
  VDIR      Administration of virtual directories
  APPPOOL   Administration of application pools
  CONFIG    Administration of general configuration sections
  WP        Administration of worker processes
  REQUEST   Administration of HTTP requests
  MODULE    Administration of server modules
  BACKUP    Administration of server configuration backups
  TRACE     Working with failed request trace logs
  BINDING   Object for working with SSL bindings

(To list commands supported by each object use /?, e.g. 'appcmd.exe site /?')

General parameters:

/?               Display context-sensitive help message.

/text<:value>    Generate output in text format (default).
                 /text:* shows all object properties in detail view.
                 /text:<attribute> shows the value of the specified
                 attribute for each object.
/xml             Generate output in XML format.
                 Use this to produce output that can be sent to another
                 command running in /in mode.
/in or -         Read and operate on XML input from standard input.
                 Use this to operate on input produced by another
                 command running in /xml mode.
/config<:*>      Show configuration for displayed objects.
                 /config:* also includes inherited configuration.
/metadata        Show configuration metadata when displaying configuration.

/commit          Set config path where configuration changes are saved.
                 Can specify either a specific configuration path, "site",
                 "app", "parent", or "url" to save to the appropriate portion
                 of the path being edited by the command, "apphost", "webroot",
                 or "machine" for the corresponding configuration level.
/apphostconfig   Specify an alternate applicationHost.config file to edit.
/debug           Show debugging information for command execution.

Use "!" to escape parameters that have same names as the general parameters,
like "/!debug:value" to set a config property named "debug".

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\inetsrv\appcmd.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: appcmd.exe.mui
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\inetsrv\appcmd.exe](appcmd.exe-055B2B09409F980BF9B5A3969D01E5B2.md) | 35

## Possible Misuse

*The following table contains possible examples of `appcmd.exe` being misused. While `appcmd.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_iss_module_install.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_iss_module_install.yml) | `            - '*\APPCMD.EXE install module /name:*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | C:\Windows\System32\inetsrv\appcmd.exe set config "#{website_name}" /section:httplogging /dontLog:true | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | if(Test-Path "C:\Windows\System32\inetsrv\appcmd.exe"){ | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) |   C:\Windows\System32\inetsrv\appcmd.exe set config "#{website_name}" /section:httplogging /dontLog:false *>$null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) |       $x2 = "$PoolPasswordCmd = 'c:\\windows\\system32\\inetsrv\\appcmd.exe list apppool" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | 		$s1 = "iex \"$Env:SystemRoot\\System32\\inetsrv\\appcmd.exe list vdir /text:vdir.name\" \| % { " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | 		$s2 = "iex \"$Env:SystemRoot\\System32\\inetsrv\\appcmd.exe list apppools /text:name\" \| % { " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | 		$s4 = "C:\\Windows\\System32\\InetSRV\\appcmd.exe list vdir /text:physicalpath \| " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | 		$s5 = "if (Test-Path  (\"$Env:SystemRoot\\System32\\inetsrv\\appcmd.exe\"))" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | 		$s6 = "if (Test-Path  (\"$Env:SystemRoot\\System32\\InetSRV\\appcmd.exe\")) {" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


