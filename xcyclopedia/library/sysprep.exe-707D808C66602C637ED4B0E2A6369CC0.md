---
title: sysprep.exe | System Preparation Tool
excerpt: What is sysprep.exe?
---

# sysprep.exe 

* File Path: `C:\windows\system32\Sysprep\sysprep.exe`
* Description: System Preparation Tool

## Screenshot

![sysprep.exe](screenshots/sysprep.exe-DC3A5AB0D06F19841749657074D475CF-3.png)

## Hashes

Type | Hash
-- | --
MD5 | `707D808C66602C637ED4B0E2A6369CC0`
SHA1 | `106435723DA8F480796C3AAA8241B04C3DB35A6E`
SHA256 | `651E0B5E530E8058D27B7784F89C7839476C5342B0AE3ABF85981B6C2D0F4080`
SHA384 | `B861BD977CF391BAD51C89A5AB3E189034DDC7575A71686D8DD6F2AD6E9850D32A80646C8C744056BF2778A3D713A557`
SHA512 | `321B62FC47D5B5FBAB9506D57D338A8CDB25C342DA4246657ACAC089F64AFC98648A0F816AEDF78ABD81EE53AC78851353F2C9FFD1F783B5778C465C917791CC`
SSDEEP | `6144:8Qnw0UwaTsw0kuSofQycve0qnaK37JCDgnFIypfLMfIheXiDmhMic0f+aZLbe02u:c0UwaTYq6aK3Fy7QcZ`

## Signature

* Status: The file C:\windows\system32\Sysprep\sysprep.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: sysprep.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `sysprep.exe` being misused. While `sysprep.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sysprep_appdata.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_sysprep_appdata.yml) | `title: Sysprep on AppData Folder`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sysprep_appdata.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_sysprep_appdata.yml) | `description: Detects suspicious sysprep process start with AppData folder as target (as used by Trojan Syndicasec in Thrip report by Symantec)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sysprep_appdata.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_sysprep_appdata.yml) | `- '*\sysprep.exe *\AppData\\*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_sysprep_appdata.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_sysprep_appdata.yml) | `- sysprep.exe *\AppData\\*`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $c3 = "\\sysprep\\sysprep.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $c4 = "\\sysprep\\CRYPTBASE.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $c7 = "\\sysprep" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hellsing_kaspersky.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hellsing_kaspersky.yar) | $a9 = "C:\\Windows\\System32\\sysprep\\sysprep.exe" wide  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s1 = "C:\\WINDOWS\\system32\\sysprep\\cryptbase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s2 = "C:\\Windows\\SysNative\\sysprep\\cryptbase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s2 = "C:\\Windows\\system32\\sysprep\\cryptbase.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_win_plugx.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_win_plugx.yar) | $s3 = "l%s\\sysprep\\CRYPTBASE.DLL" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_win_plugx.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_win_plugx.yar) | $s7 = "%s\\sysprep\\sysprep.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s3 = "%systemroot%\\system32\\sysprep\\sysprep.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s4 = "/c wusa %ws /extract:%%windir%%\\system32\\sysprep" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s6 = "loadFrom=\"%systemroot%\\system32\\sysprep\\cryptbase.DLL\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


