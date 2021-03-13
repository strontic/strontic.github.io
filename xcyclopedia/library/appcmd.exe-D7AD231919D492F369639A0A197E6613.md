---
title: appcmd.exe | Application Server Command Line Admin Tool
excerpt: What is appcmd.exe?
---

# appcmd.exe 

* File Path: `C:\windows\system32\inetsrv\appcmd.exe`
* Description: Application Server Command Line Admin Tool

## Hashes

Type | Hash
-- | --
MD5 | `D7AD231919D492F369639A0A197E6613`
SHA1 | `2751E792D2A2AA66D31BAE904FB441D8A6951F05`
SHA256 | `9AD840CBB21E4AC99F0D3C5000F01D94FB94CFEEF1D3E81CC9F50A7F23518A50`
SHA384 | `33DE9F6B9326EBBA3587E3A7A2CD4C35288429D24A656F20D192D0DE05D6B171C2B392A658C45D36D5BF05D36AD878FC`
SHA512 | `AA8DA4C74CFB173DBBB6A5199AB9FC60582823205058F28ECED51B7BA4042F93FA44EA6A83631728ADA6DFE23D0606EAB6C6838690A2670DB5EC9439F2243084`
SSDEEP | `3072:t/uvKywEK0Ps81m0K4W3PYFU0CF82/ZF2U1hM:MvPw8Ps8a4WV0a`

## Signature

* Status: The file C:\windows\system32\inetsrv\appcmd.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: appcmd.exe.mui
* Product Name: Internet Information Services
* Company Name: Microsoft Corporation
* File Version: 8.5.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 8.5.9600.16384
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `appcmd.exe` being misused. While `appcmd.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_iss_module_install.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_iss_module_install.yml) | `- '*\APPCMD.EXE install module /name:*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | C:\Windows\System32\inetsrv\appcmd.exe set config "#{website_name}" /section:httplogging /dontLog:true | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | if(Test-Path "C:\Windows\System32\inetsrv\appcmd.exe"){ | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | C:\Windows\System32\inetsrv\appcmd.exe set config "#{website_name}" /section:httplogging /dontLog:false *>$null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) | $x2 = "$PoolPasswordCmd = 'c:\\windows\\system32\\inetsrv\\appcmd.exe list apppool" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | $s1 = "iex \"$Env:SystemRoot\\System32\\inetsrv\\appcmd.exe list vdir /text:vdir.name\" \| % { " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | $s2 = "iex \"$Env:SystemRoot\\System32\\inetsrv\\appcmd.exe list apppools /text:name\" \| % { " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | $s4 = "C:\\Windows\\System32\\InetSRV\\appcmd.exe list vdir /text:physicalpath \| " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | $s5 = "if (Test-Path  (\"$Env:SystemRoot\\System32\\inetsrv\\appcmd.exe\"))" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | $s6 = "if (Test-Path  (\"$Env:SystemRoot\\System32\\InetSRV\\appcmd.exe\")) {" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


