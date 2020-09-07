---
title: bcdedit.exe | Boot Configuration Data Editor
---

# bcdedit.exe 

* File Path: `C:\windows\system32\bcdedit.exe`
* Description: Boot Configuration Data Editor

## Hashes

Type | Hash
-- | --
MD5 | `D5F797FC4D5434EB677A09C143962231`
SHA1 | `FF829D4F431715B27547E862A9D4D65764E5C35E`
SHA256 | `85A43C95BC60213353BE0960CC2947B8F458B6470C683FE18F35E0469C47D2D1`
SHA384 | `F7A33EE386436669C413EA476E125472EA67D92909B7F8F1A3BE37032496BC86925E648982F08E9E43A1111CD947EF6E`
SHA512 | `188DBF3DD6EB171FF60634FEAC855D1DF1801230BF96C06D39BFE1196AADA4385F9BA4BDC48FDBBD8A31E7C8A60F5A6F9999E91E95199B33001CC76C858AAC80`
SSDEEP | `3072:322q+HRw3etMbIFb9qYRDsxc8XDwHLFIEf9Ox2tV0uRhdNV/ysXo3HD62xKe1P/z:3K3etM8FbvDsxlz+5l0m`

## Signature

* Status: The file C:\windows\system32\bcdedit.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: bcdedit.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `bcdedit.exe` being misused. While `bcdedit.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_bootconf_mod.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bootconf_mod.yml) | `description: Identifies use of the bcdedit command to delete boot configuration data. This tactic is sometimes used as by malware or an attacker as a destructive` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bootconf_mod.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bootconf_mod.yml) | `        Image\|endswith: \bcdedit.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `            - '*bcdedit /set {default} recoveryenabled no*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_bcdedit.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_bcdedit.yml) | `description: Detects, possibly, malicious unauthorized usage of bcdedit.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_bcdedit.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_bcdedit.yml) | `    - https://docs.microsoft.com/en-us/windows-hardware/drivers/devtest/bcdedit--set` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_bcdedit.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_bcdedit.yml) | `        Image: '*\bcdedit.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | * <code>bcdedit.exe</code> can be used to disable automatic Windows recovery features by modifying boot configuration data - <code>bcdedit.exe /set {default} bootstatuspolicy ignoreallfailures & bcdedit /set {default} recoveryenabled no</code></blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | bcdedit.exe /set {default} bootstatuspolicy ignoreallfailures | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | bcdedit.exe /set {default} recoveryenabled no | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | bcdedit.exe /set {default} bootstatuspolicy DisplayAllFailures >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | bcdedit.exe /set {default} recoveryenabled yes >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_olympic_destroyer.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_olympic_destroyer.yar) |       $x1 = "/set {default} bootstatuspolicy ignoreallfailures & bcdedit /set {default} recoveryenabled no" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turbo_campaign.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turbo_campaign.yar) |       $sc_1 = "bcdedit -set testsigning" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## bcdedit

Boot Configuration Data (BCD) files provide a store that is used to describe boot applications and boot application settings. The objects and elements in the store effectively replace Boot.ini.

BCDEdit is a command-line tool for managing BCD stores. It can be used for a variety of purposes, including creating new stores, modifying existing stores, adding boot menu parameters, and so on. BCDEdit serves essentially the same purpose as Bootcfg.exe on earlier versions of Windows, but with two major improvements:

- Exposes a wider range of boot parameters than Bootcfg.exe.

- Has improved scripting support.

> [!NOTE]
> Administrative privileges are required to use BCDEdit to modify BCD.

BCDEdit is the primary tool for editing the boot configuration of Windows Vista and later versions of Windows. It is included with the Windows Vista distribution in the %WINDIR%\System32 folder.

BCDEdit is limited to the standard data types and is designed primarily to perform single common changes to BCD. For more complex operations or nonstandard data types, consider using the BCD Windows Management Instrumentation (WMI) application programming interface (API) to create more powerful and flexible custom tools.

### Syntax

```
bcdedit /command [<argument1>] [<argument2>] ...
```

#### Parameters

#### General BCDEdit Command-Line Options

| Option | Description |
| ------ | ----------- |
| /? | Displays a list of BCDEdit commands. Running this command without an argument displays a summary of the available commands. To display detailed help for a particular command, run **bcdedit /?** `<command>`, where `<command>` is the name of the command you are searching for more information about. For example, **bcdedit /? createstore** displays detailed help for the Createstore command. |

##### Parameters that Operate on a Store

| Option | Description |
| ------ | ----------- |
| /createstore | Creates a new empty boot configuration data store. The created store is not a system store. |
| /export | Exports the contents of the system store into a file. This file can be used later to restore the state of the system store. This command is valid only for the system store. |
| /import | Restores the state of the system store by using a backup data file previously generated by using the **/export** option. This command deletes any existing entries in the system store before the import takes place. This command is valid only for the system store. |
| /store | This option can be used with most BCDedit commands to specify the store to be used. If this option is not specified, then BCDEdit operates on the system store. Running the **bcdedit /store** command by itself is equivalent to running the **bcdedit /enum active** command. |

##### Parameters that Operate on Entries in a Store

| Parameter | Description |
| ------ | ----------- |
| /copy | Makes a copy of a specified boot entry in the same system store. |
| /create | Creates a new entry in the boot configuration data store. If a well-known identifier is specified, then the **/application**, **/inherit**, and **/device** parameters cannot be specified. If an identifier is not specified or not well known, an **/application**, **/inherit**, or **/device** option must be specified. |
| /delete | Deletes an element from a specified entry. |

##### Parameters that Operate on Entry Options

| Parameter | Description |
| ------ | ----------- |
| /deletevalue | Deletes a specified element from a boot entry. |
| /set | Sets an entry option value. |

##### Parameters that Control Output

| Parameter | Description |
| ------ | ----------- |
| /enum | Lists entries in a store. The **/enum** option is the default value for BCEdit, so running the **bcdedit** command without parameters is equivalent to running the **bcdedit /enum active** command. |
| /v | Verbose mode. Usually, any well-known entry identifiers are represented by their friendly shorthand form. Specifying **/v** as a command-line option displays all identifiers in full. Running the **bcdedit /v** command by itself is equivalent to running the **bcdedit /enum active /v** command. |

##### Parameters that Control the Boot Manager

| Parameter | Description |
| ------ | ----------- |
| /bootsequence | Specifies a one-time display order to be used for the next boot. This command is similar to the **/displayorder** option, except that it is used only the next time the computer starts. Afterwards, the computer reverts to the original display order. |
| /default | Specifies the default entry that the boot manager selects when the timeout expires. |
| /displayorder | Specifies the display order that the boot manager uses when displaying boot parameters to a user. |
| /timeout | Specifies the time to wait, in seconds, before the boot manager selects the default entry. |
| /toolsdisplayorder | Specifies the display order for the boot manager to use when displaying the **Tools** menu. |

##### Parameters that Control Emergency Management Services

| Parameter | Description |
| ------ | ----------- |
| /bootems | Enables or disables Emergency Management Services (EMS) for the specified entry. |
| /ems | Enables or disables EMS for the specified operating system boot entry. |
| /emssettings | Sets the global EMS settings for the computer. **/emssettings** does not enable or disable EMS for any particular boot entry. |

##### Parameters that Control Debugging

| Parameter | Description |
| ------ | ----------- |
| /bootdebug | Enables or disables the boot debugger for a specified boot entry. Although this command works for any boot entry, it is effective only for boot applications. |
| /dbgsettings | Specifies or displays the global debugger settings for the system. This command does not enablepose. To set an individual global debugger setting, use the **bcdedit /set** `<dbgsettings> <type> <value>` command. |
| /debug | Enables or disables the kernel debugger for a specified boot entry. |

### Additional References

For examples of how to use BCDEdit, see the [BCDEdit Options Reference](/windows-hardware/drivers/devtest/bcd-boot-options-reference) article.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


