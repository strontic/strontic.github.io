﻿---
title: bcdedit.exe | Boot Configuration Data Editor
excerpt: What is bcdedit.exe?
---

# bcdedit.exe 

* File Path: `C:\Windows\system32\bcdedit.exe`
* Description: Boot Configuration Data Editor

## Hashes

Type | Hash
-- | --
MD5 | `38F0419E6AC1A5B7A30438426C5D03AA`
SHA1 | `05144616817F67849B4454AAD14F857EAF12FE7D`
SHA256 | `7202B952F1456DBE5C75B19BFE2B8BD37F40384007F1E51FD632EAD10F1EEACC`
SHA384 | `92220B32026C9555550157667EADC8B087B7A1A203EB5C036173AB7CCBE0743C38F0CC12F9AF3D9CCEA47ADA13F95246`
SHA512 | `6683C28E3858106DEE3AF793C531B239E21F382568048A5AADCEFC423448B05952EF97A3777CD2BC49ABD77DDF70508DF8ED6565230FB94F18755FDF23EF7D5D`
SSDEEP | `3072:f3c6plKHsrMQg0bkZ61YM+ukyvNB4bduMafEh74MeUAOREquXg7PeYhuJ/XBMhdY:Pc6pgswQgY1YM+p8NB6IfECTTfYuJ/T`

## Runtime Data

### Usage (stdout):
```cmhg

BCDEDIT - Boot Configuration Data Store Editor

The Bcdedit.exe command-line tool modifies the boot configuration data store.
The boot configuration data store contains boot configuration parameters and
controls how the operating system is booted. These parameters were previously
in the Boot.ini file (in BIOS-based operating systems) or in the nonvolatile
RAM entries (in Extensible Firmware Interface-based operating systems). You can
use Bcdedit.exe to add, delete, edit, and append entries in the boot
configuration data store.

For detailed command and option information, type bcdedit.exe /? <command>. For
example, to display detailed information about the /createstore command, type:

     bcdedit.exe /? /createstore

For an alphabetical list of topics in this help file, run "bcdedit /? TOPICS".

Commands that operate on a store
================================
/store          Used to specify a BCD store other than the current system default.
/createstore    Creates a new and empty boot configuration data store.
/export         Exports the contents of the system store to a file. This file
                can be used later to restore the state of the system store.
/import         Restores the state of the system store using a backup file
                created with the /export command.
/sysstore       Sets the system store device (only affects EFI systems, does
                not persist across reboots, and is only used in cases where
                the system store device is ambiguous).

Commands that operate on entries in a store
===========================================
/copy           Makes copies of entries in the store.
/create         Creates new entries in the store.
/delete         Deletes entries from the store.
/mirror         Creates mirror of entries in the store.

Run bcdedit /? ID for information about identifiers used by these commands.

Commands that operate on entry options
======================================
/deletevalue    Deletes entry options from the store.
/set            Sets entry option values in the store.

Run bcdedit /? TYPES for a list of datatypes used by these commands.
Run bcdedit /? FORMATS for a list of valid data formats.

Commands that control output
============================
/enum           Lists entries in the store.
/v              Command-line option that displays entry identifiers in full,
                rather than using names for well-known identifiers.
                Use /v by itself as a command to display entry identifiers
                in full for the ACTIVE type.

Running "bcdedit" by itself is equivalent to running "bcdedit /enum ACTIVE".

Commands that control the boot manager
======================================
/bootsequence   Sets the one-time boot sequence for the boot manager.
/default        Sets the default entry that the boot manager will use.
/displayorder   Sets the order in which the boot manager displays the
                multiboot menu.
/timeout        Sets the boot manager time-out value.
/toolsdisplayorder  Sets the order in which the boot manager displays
                    the tools menu.

Commands that control Emergency Management Services for a boot application
==========================================================================
/bootems        Enables or disables Emergency Management Services
                for a boot application.
/ems            Enables or disables Emergency Management Services for an
                operating system entry.
/emssettings    Sets the global Emergency Management Services parameters.

Command that control debugging
==============================
/bootdebug      Enables or disables boot debugging for a boot application.
/dbgsettings    Sets the global debugger parameters.
/debug          Enables or disables kernel debugging for an operating system
                entry.
/hypervisorsettings  Sets the hypervisor parameters.

Command that control remote event logging
=========================================
/eventsettings  Sets the global remote event logging parameters.
/event          Enables or disables remote event logging for an operating 
                system entry.


```

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bcdedit.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `bcdedit.exe` being misused. While `bcdedit.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_bootconf_mod.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bootconf_mod.yml) | `description: Identifies use of the bcdedit command to delete boot configuration data. This tactic is sometimes used as by malware or an attacker as a destructive`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_bootconf_mod.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_bootconf_mod.yml) | `Image\|endswith: \bcdedit.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_wannacry.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_wannacry.yml) | `- 'bcdedit'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_bcdedit.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_bcdedit.yml) | `description: Detects, possibly, malicious unauthorized usage of bcdedit.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_bcdedit.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_bcdedit.yml) | `- https://docs.microsoft.com/en-us/windows-hardware/drivers/devtest/bcdedit--set`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_bcdedit.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_bcdedit.yml) | `Image\|endswith: '\bcdedit.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \bcdedit.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | * <code>bcdedit.exe</code> can be used to disable automatic Windows recovery features by modifying boot configuration data - <code>bcdedit.exe /set {default} bootstatuspolicy ignoreallfailures & bcdedit /set {default} recoveryenabled no</code></blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | bcdedit.exe /set {default} bootstatuspolicy ignoreallfailures | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | bcdedit.exe /set {default} recoveryenabled no | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | bcdedit.exe /set {default} bootstatuspolicy DisplayAllFailures >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1490.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1490/T1490.md) | bcdedit.exe /set {default} recoveryenabled yes >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_olympic_destroyer.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_olympic_destroyer.yar) | $x1 = "/set {default} bootstatuspolicy ignoreallfailures & bcdedit /set {default} recoveryenabled no" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turbo_campaign.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turbo_campaign.yar) | $sc_1 = "bcdedit -set testsigning" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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
| /dbgsettings | Specifies or displays the global debugger settings for the system. This command does not enable or disable the kernel debugger; use the **/debug** option for that purpose. To set an individual global debugger setting, use the **bcdedit /set** `<dbgsettings> <type> <value>` command. |
| /debug | Enables or disables the kernel debugger for a specified boot entry. |

### Additional References

For examples of how to use BCDEdit, see the [BCDEdit Options Reference](/windows-hardware/drivers/devtest/bcd-boot-options-reference) article.

To see the notation used to indicate command-line syntax, see  [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md).

---



MIT License. Copyright (c) 2020-2021 Strontic.


