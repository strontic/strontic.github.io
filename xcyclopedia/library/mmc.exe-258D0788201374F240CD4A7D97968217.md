---
title: mmc.exe | Microsoft Management Console
---

# mmc.exe 

* File Path: `C:\Windows\SysWOW64\mmc.exe`
* Description: Microsoft Management Console
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `258D0788201374F240CD4A7D97968217`
SHA1 | `BECBDEEF5D9E9A52B0BAACE184521D1F06195942`
SHA256 | `38B20E000EE8A8675881CA126FA85DAF9CE6A55EB7D990D8BB805D3AFE48D342`
SHA384 | `D230103D099A910DC3DC415E74802132955C877EA6C9BAF46CFE3FD67BB227C338D2C0C97B400D4AC9D2FA4D3BF4F1F6`
SHA512 | `0B5076F62BBF4EDDE874D143255CC9F277385DA5E11E21D49039B8A0F5107AA0FACF7B214CAE800CEDF656CD9DBB7EDFB5C66060A2CBCF301672D809F538BDDE`
SSDEEP | `24576:wthBrJrd+oG2TH2tVfoV5hmpbh0XOBIYplgGMo7wMo7DHDAOLiE:wtNrdSqWtVfoVTmpms7e7DH0OLiE`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
mmc.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mmc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\mmc.exe](mmc.exe-26F0B79F5A4797E4D06D164E650FC872.md) | 35
[C:\Windows\system32\mmc.exe](mmc.exe-9317AC7FF7ED5E614E17E49D1EB474CB.md) | 32
[C:\Windows\system32\mmc.exe](mmc.exe-C51BACB9B93CA44254BE462516C6BEE0.md) | 33
[C:\Windows\system32\mmc.exe](mmc.exe-E1328E5A4A87C376927DB685110F8D6F.md) | 35
[C:\Windows\SysWOW64\mmc.exe](mmc.exe-08CA3F1D18A0B8F55098C3940AFD088E.md) | 35
[C:\Windows\SysWOW64\mmc.exe](mmc.exe-9012E43AD3F261742257A1234A006746.md) | 30
[C:\WINDOWS\SysWOW64\mmc.exe](mmc.exe-E92C9CCE925FAF5CF45308F855F10016.md) | 29

## Possible Misuse

*The following table contains possible examples of `mmc.exe` being misused. While `mmc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc20_lateral_movement.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_mmc20_lateral_movement.yml) | `description: Detects MMC20.Application Lateral Movement; specifically looks for the spawning of the parent MMC.exe with a command line of "-Embedding" as a child of svchost.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc20_lateral_movement.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_mmc20_lateral_movement.yml) | `        Image: '*\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_user_driver_loaded.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_user_driver_loaded.yml) | `            - '*\Windows\System32\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adsi_cache_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_adsi_cache_usage.yml) | `            - 'C:\windows\system32\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_desktop_ini.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_desktop_ini.yml) | `            - 'C:\Windows\System32\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `        #   parent is mmc.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `            - '*\mmc.exe'  # dcomexec MMC` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mmc_spawn_shell.yml) | `        ParentImage: '*\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_parent.yml) | `            - '*\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_eventvwr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_eventvwr.yml) | `        Image: '*\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adsi_cache_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_susp_adsi_cache_usage.yml) | `            - 'C:\windows\system32\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_desktop_ini.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_susp_desktop_ini.yml) | `            - 'C:\Windows\System32\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_eventvwr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_uac_bypass_eventvwr.yml) | `        Image: '*\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_module_load.yml) | `            - '\mmc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Eventvwr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Eventvwr.yml) | `    Description: During startup, eventvwr.exe checks the registry value HKCU\Software\Classes\mscfile\shell\open\command for the location of mmc.exe, which is used to open the eventvwr.msc saved console file. If the location of another binary or script is added to this registry value, it will be executed as a high-integrity process without a UAC prompt being displayed to the user.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Eventvwr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Eventvwr.yml) | ` - IOC: eventvwr.exe launching child process other than mmc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mmc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mmc.yml) | `Name: Mmc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mmc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mmc.yml) | `  - Command: mmc.exe -Embedding c:\path\to\test.msc` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mmc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mmc.yml) | `  - Path: C:\Windows\System32\mmc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mmc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Mmc.yml) | `  - Path: C:\Windows\SysWOW64\mmc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wsreset.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wsreset.yml) | ` - IOC: wsreset.exe launching child process other than mmc.exe` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mmc.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.015.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.015/T1546.015.md) | START MMC.EXE EVENTVWR.MSC | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | copy "#{executable_binary}" "\\?\C:\Windows \System32\mmc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | mklink c:\testbypass.exe "\\?\C:\Windows \System32\mmc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

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
| /? | Displays help at the command prompt. |

### Remarks

- You can use environment variables to create command lines or shortcuts that don't depend on the explicit location of console files. For instance, if the path to a console file is in the system folder (for example, **mmc c:\winnt\system32\console_name.msc**), you can use the expandable data string **%systemroot%** to specify the location (**mmc%systemroot%\system32\console_name.msc**). This may be useful if you're delegating tasks to people in your organization who are working on different computers.

- When consoles are opened using the **/a** option, they're opened in author mode, regardless of their default mode. This doesn't permanently change the default mode setting for files; when you omit this option, mmc opens console files according to their default mode settings.

- After you open **mmc** or a console file in author mode, you can open any existing console by clicking **Open** on the **Console** menu.

- You can use the command line to create shortcuts for opening **mmc** and saved consoles. A command-line command works with the **Run** command on the **Start** menu, in any command-prompt window, in shortcuts, or in any batch file or program that calls the command.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


