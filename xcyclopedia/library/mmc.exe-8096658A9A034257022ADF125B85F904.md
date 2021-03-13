---
title: mmc.exe | Microsoft Management Console
excerpt: What is mmc.exe?
---

# mmc.exe 

* File Path: `C:\windows\SysWOW64\mmc.exe`
* Description: Microsoft Management Console

## Screenshot

![mmc.exe](screenshots/mmc.exe-E1328E5A4A87C376927DB685110F8D6F-1.png)
![mmc.exe](screenshots/mmc.exe-E1328E5A4A87C376927DB685110F8D6F-4.png)

## Hashes

Type | Hash
-- | --
MD5 | `8096658A9A034257022ADF125B85F904`
SHA1 | `4847418E76AD42A05468C16161768D70FF7E8C66`
SHA256 | `9563E5438C4925884538162D4B275387E59EE5CA3B89C9576D598B3B58253E4A`
SHA384 | `93DE6ED2CBDD2D1B0AD40C61629B4F938E332763C5FB165A76930934CFBDE9A837BD03538CC7F05566BBC9A4DF3FD8D1`
SHA512 | `5D2BE4A8857F0D3F7AE7029972108CD5BDCA8BB0FB423E5259FD4C351120FB7EDA2755F65F0E0432644BD324029E00514F9756C1B7E65DB55579B1E10FDFC38C`
SSDEEP | `24576:sOyZSkxGMCGNMpSv86Hb4M83Uo8Mo7wMo7DHZCgaSaFqXO:sQk8qNMpSE6HEM83Uoa7e7DHLaLFqXO`

## Signature

* Status: The file C:\windows\SysWOW64\mmc.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: mmc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\mmc.exe](mmc.exe-26F0B79F5A4797E4D06D164E650FC872.md) | 29
[C:\windows\system32\mmc.exe](mmc.exe-3E4EAD40B4F45F956354569B75FFDEEA.md) | 36
[C:\Windows\system32\mmc.exe](mmc.exe-9317AC7FF7ED5E614E17E49D1EB474CB.md) | 36
[C:\Windows\system32\mmc.exe](mmc.exe-C51BACB9B93CA44254BE462516C6BEE0.md) | 33
[C:\Windows\system32\mmc.exe](mmc.exe-E1328E5A4A87C376927DB685110F8D6F.md) | 30
[C:\Windows\SysWOW64\mmc.exe](mmc.exe-08CA3F1D18A0B8F55098C3940AFD088E.md) | 30
[C:\Windows\SysWOW64\mmc.exe](mmc.exe-258D0788201374F240CD4A7D97968217.md) | 29
[C:\Windows\SysWOW64\mmc.exe](mmc.exe-9012E43AD3F261742257A1234A006746.md) | 27
[C:\Windows\SysWOW64\mmc.exe](mmc.exe-A40546440A81D2E36FB1F6F18AC376BC.md) | 27
[C:\WINDOWS\SysWOW64\mmc.exe](mmc.exe-E92C9CCE925FAF5CF45308F855F10016.md) | 27

## Possible Misuse

*The following table contains possible examples of `mmc.exe` being misused. While `mmc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc20_lateral_movement.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_mmc20_lateral_movement.yml) | `description: Detects MMC20.Application Lateral Movement; specifically looks for the spawning of the parent MMC.exe with a command line of "-Embedding" as a child of svchost.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc20_lateral_movement.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_mmc20_lateral_movement.yml) | `Image: '*\mmc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `- '*\Windows\System32\mmc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adsi_cache_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_adsi_cache_usage.yml) | `- 'C:\windows\system32\mmc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_desktop_ini.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_desktop_ini.yml) | `- 'C:\Windows\System32\mmc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `#   parent is mmc.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `- '*\mmc.exe'  # dcomexec MMC`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mmc_spawn_shell.yml) | `ParentImage: '*\mmc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_parent.yml) | `- '*\mmc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_eventvwr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_eventvwr.yml) | `Image: '*\mmc.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Eventvwr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Eventvwr.yml) | `Description: During startup, eventvwr.exe checks the registry value HKCU\Software\Classes\mscfile\shell\open\command for the location of mmc.exe, which is used to open the eventvwr.msc saved console file. If the location of another binary or script is added to this registry value, it will be executed as a high-integrity process without a UAC prompt being displayed to the user.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Eventvwr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Eventvwr.yml) | `- IOC: eventvwr.exe launching child process other than mmc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mmc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mmc.yml) | `Name: Mmc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mmc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mmc.yml) | `- Command: mmc.exe -Embedding c:\path\to\test.msc`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mmc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mmc.yml) | `- Path: C:\Windows\System32\mmc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mmc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mmc.yml) | `- Path: C:\Windows\SysWOW64\mmc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | `- IOC: wsreset.exe launching child process other than mmc.exe`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mmc.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | copy "#{executable_binary}" "\\?\C:\Windows \System32\mmc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | mklink c:\testbypass.exe "\\?\C:\Windows \System32\mmc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.012/T1574.012.md) | START MMC.EXE EVENTVWR.MSC | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $a5 = "taskkill /f /im mmc.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## mmc

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Using mmc command-line options, you can open a specific **mmc** console, open **mmc** in author mode, or specify that the 32-bit or 64-bit version of **mmc** is opened.

### Syntax

```
mmc <path>\<filename>.msc [/a] [/64] [/32]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<path>\<filename>.msc` | starts **mmc** and opens a saved console. You need to specify the complete path and file name for the saved console file. If you do not specify a console file, **mmc** opens a new console. |
| /a | Opens a saved console in author mode.  Used to make changes to saved consoles. |
| /64 | Opens the 64-bit version of **mmc** (mmc64). Use this option only if you are running a Microsoft 64-bit operating system and want to use a 64-bit snap-in. |
| /32 | Opens the 32-bit version of **mmc** (mmc32). When running a Microsoft 64-bit operating system, you can run 32-bit snap-ins by opening mmc with this command-line option when you have 32-bit only snap-ins. |

### Remarks

- You can use environment variables to create command lines or shortcuts that don't depend on the explicit location of console files. For instance, if the path to a console file is in the system folder (for example, **mmc c:\winnt\system32\console_name.msc**), you can use the expandable data string **%systemroot%** to specify the location (**mmc%systemroot%\system32\console_name.msc**). This may be useful if you're delegating tasks to people in your organization who are working on different computers.

- When consoles are opened using the **/a** option, they're opened in author mode, regardless of their default mode. This doesn't permanently change the default mode setting for files; when you omit this option, mmc opens console files according to their default mode settings.

- After you open **mmc** or a console file in author mode, you can open any existing console by clicking **Open** on the **Console** menu.

- You can use the command line to create shortcuts for opening **mmc** and saved consoles. A command-line command works with the **Run** command on the **Start** menu, in any command-prompt window, in shortcuts, or in any batch file or program that calls the command.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


