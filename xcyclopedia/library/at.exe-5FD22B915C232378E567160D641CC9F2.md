---
title: at.exe | Schedule service command line interface
excerpt: What is at.exe?
---

# at.exe 

* File Path: `C:\windows\system32\at.exe`
* Description: Schedule service command line interface

## Hashes

Type | Hash
-- | --
MD5 | `5FD22B915C232378E567160D641CC9F2`
SHA1 | `AB2909A696991B728F42FFB616C77D8CA4A1A798`
SHA256 | `488E74E2026D03F21B33F470C23B3DE2F466643186C2E06AE7B4883CC2E59377`
SHA384 | `AEEC553FCD0BE20665C6A0EC09241C6149EC8F5250F6D6F7FEA752D83139A9AEBD8A5E83AC8EFB8E13D42999AF476EFE`
SHA512 | `AC59CE4FE3770DF0FA2DF2AB8C8801EA1A6D4B2C280863E376138CADFBC5287AE67A10634D50DDD9D64B16C6F6D7FFB7AEFE3156FE87DC7E862754E7745EE2BF`
SSDEEP | `768:kMd5AsU2AN1nPPh1592eqYHPBzRQL+pI+8K:HfMVP5172sPrW5+8`

## Signature

* Status: The file C:\windows\system32\at.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: AT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `at.exe` being misused. While `at.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [zeek_smb_converted_win_atsvc_task.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/zeek/zeek_smb_converted_win_atsvc_task.yml) | `description: Detects remote task creation via at.exe or API interacting with ATSVC namedpipe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_atsvc_task.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_atsvc_task.yml) | `description: Detects remote task creation via at.exe or API interacting with ATSVC namedpipe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_interactive_at.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_interactive_at.yml) | `Image\|endswith: '\at.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_interactive_at.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_interactive_at.yml) | `- Unlikely (at.exe deprecated as of Windows 8)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- at.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [At.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/At.yml) | `Name: At.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [At.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/At.yml) | `- Command: C:\Windows\System32\at.exe at 09:00 /interactive /every:m,t,w,th,f,s,su C:\Windows\System32\revshell.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [At.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/At.yml) | `- Path: C:\WINDOWS\System32\At.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [At.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/At.yml) | `- Path: C:\WINDOWS\SysWOW64\At.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [At.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/At.yml) | `- Link: https://www.secureworks.com/blog/where-you-at-indicators-of-lateral-movement-using-at-exe-on-windows-7-systems`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: At.exe Scheduled task [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: At.exe Scheduled task [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.002/T1053.002.md) | <blockquote>Adversaries may abuse the <code>at.exe</code> utility to perform task scheduling for initial or recurring execution of malicious code. The [at](https://attack.mitre.org/software/S0110) utility exists as an executable within Windows for scheduling tasks at a specified time and date. Using [at](https://attack.mitre.org/software/S0110) requires that the Task Scheduler service be running, and the user to be logged on as a member of the local Administrators group.  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.002/T1053.002.md) | An adversary may use <code>at.exe</code> in Windows environments to execute programs at system startup or on a scheduled basis for persistence. [at](https://attack.mitre.org/software/S0110) can also be abused to conduct remote Execution as part of Lateral Movement and or to run a process under the context of a specified account (such as SYSTEM). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.002/T1053.002.md) | Note: The <code>at.exe</code> command line utility has been deprecated in current versions of Windows in favor of <code>schtasks</code>.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.002/T1053.002.md) | - [Atomic Test #1 - At.exe Scheduled task](#atomic-test-1---atexe-scheduled-task) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.002/T1053.002.md) | ## Atomic Test #1 - At.exe Scheduled task | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.002/T1053.002.md) | Upon successful execution, cmd.exe will spawn at.exe and create a scheduled task that will spawn cmd at a specific time. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | The deprecated [at](https://attack.mitre.org/software/S0110) utility could also be abused by adversaries (ex: [At (Windows)](https://attack.mitre.org/techniques/T1053/002)), though <code>at.exe</code> can not access tasks created with <code>schtasks</code> or the Control Panel. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## at

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Schedules commands and programs to run on a computer at a specified time and date. You can use **at** only when the Schedule service is running. Used without parameters, **at** lists scheduled commands. You must be a member of the local Administrators group to run this command.

### Syntax

```
at [\computername] [[id] [/delete] | /delete [/yes]]
at [\computername] <time> [/interactive] [/every:date[,...] | /next:date[,...]] <command>
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `\<computername\>` | Specifies a remote computer. If you omit this parameter, **at** schedules the commands and programs on the local computer. |
| `<id>` | Specifies the identification number assigned to a scheduled command. |
| /delete | Cancels a scheduled command. If you omit *ID*, all of the scheduled commands on the computer are canceled. |
| /yes | Answers yes to all queries from the system when you delete scheduled events. |
| `<time>` | Specifies the time when you want to run the command. time is expressed as Hours:Minutes in 24-hour notation (that is, 00:00 (midnight) through 23:59). |
| interactive | Allows *command* to interact with the desktop of the user who is logged on at the time *Command* runs. |
| every: | Runs *command* on every specified day or days of the week or month (for example, every Thursday, or the third day of every month). |
| `<date>` | Specifies the date when you want to run the command. You can specify one or more days of the week (that is, type **M**,**T**,**W**,**Th**,**F**,**S**,**Su**) or one or more days of the month (that is, type 1 through 31). Separate multiple date entries with commas. If you omit *date*, **at** uses the current day of the month. |
| next: | Runs *command*  on the next occurrence of the day (for example, next Thursday). |
| `<command>` | Specifies the Windows command, program (that is, .exe or .com file), or batch program (that is, .bat or .cmd file) that you want to run. When the command requires a path as an argument, use the absolute path (that is, the entire path beginning with the drive letter). If the command is on a remote computer, specify Universal Naming Convention (UNC) notation for the server and share name, rather than a remote drive letter. |
| /? | Displays help at the command prompt. |

#### Remarks

- This command doesn't automatically load cmd.exe before running commands. If you're not running an executable (.exe) file, you must explicitly load cmd.exe at the beginning of the command as follows:

    ```
    cmd /c dir > c:\test.out
    ```

- If using this command without command-line options, scheduled tasks appear in a table formatted similar to the following:

    ```
    Status  ID   Day        time        Command Line
    OK      1    Each F     4:30 PM     net send group leads status due
    OK      2    Each M     12:00 AM    chkstor > check.file
    OK      3    Each F     11:59 PM    backup2.bat
    ```

- If including an identification number (*ID*) with this command, only information for a single entry appears in a format similar to the following:

    ```
    Task ID: 1
    Status: OK
    Schedule: Each  F
    Time of Day: 4:30 PM
    Command: net send group leads status due
    ```

- After you schedule a command, especially a command that has command-line options, check that the command syntax is correct by typing **at** without any command-line options. If the information in the **Command Line** column is wrong, delete the command and retype it. If it's still incorrect, retype the command using fewer command-line options.

- Commands scheduled with **at** run as background processes. Output is not displayed on the computer screen. To redirect output to a file, use the redirection symbol `>`. If you redirect output to a file, you need to use the escape symbol `^` before the redirection symbol, whether you are using **at** at the command line or in a batch file. For example, to redirect output to *output.txt*, type:

    ```
    at 14:45 c:\test.bat ^>c:\output.txt
    ```

    The current directory for the executing command is the systemroot folder.

- If you change the system time after you schedule a command to run, synchronize the **at** scheduler with the revised system time by typing **at** without command-line options.

- Scheduled commands are stored in the registry. As a result, you don't lose scheduled tasks if you restart the Schedule service.

- Do not use a redirected drive for scheduled jobs that access the network. The Schedule service might not be able to access the redirected drive, or the redirected drive might not be present if a different user is logged on at the time the scheduled task runs. Instead, use UNC paths for scheduled jobs. For example:

    ```
    at 1:00pm my_backup \\server\share
    ```

    Do not use the following syntax, where **x:** is a connection made by the user:

    ```
    at 1:00pm my_backup x:
    ```

    If you schedule an **at** command that uses a drive letter to connect to a shared directory, include an **at** command to disconnect the drive when you are finished using the drive. If the drive is not disconnected, the assigned drive letter won't be available at the command prompt.

- By default, tasks scheduled using this command will stop after 72 hours. You can modify the registry to change this default value.

    **To modify the registry**

    > [!Caution]
    > Incorrectly editing the registry may severely damage your system. Before making changes to the registry, you should back up any valued data on the computer.

    1. Start the registry editor (regedit.exe).

    2. Locate and click the following key in the registry: `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Schedule`

    3. On the **Edit** menu, click **Add Value**, and then add the following registry values:

        - **Value Name.** atTaskMaxHours

        - **Data type.** reg_DWOrd

        - **Radix.** Decimal

        - **Value Data:** 0. A value of **0** in the **Value Data** field indicates no limit and doesn't not stop. Values from 1 through 99 indicates the number of hours.

- You can use the Scheduled Tasks folder to view or modify the settings of a task that was created by using this command. When you schedule a task using this command, the task is listed in the Scheduled Tasks folder, with a name such as the following:**at3478**. However, if you modify a task through the Scheduled Tasks folder, it's upgraded to a normal scheduled task. The task is no longer visible to the **at** command, and the at account setting no longer applies to it. You must explicitly enter a user account and password for the task.

### Examples

To display a list of commands scheduled on the Marketing server, type:

```
at \\marketing
```

To learn more about a command with the identification number 3 on the Corp server, type:

```
at \\corp 3
```

To schedule a net share command to run on the Corp server at 8:00 A.M. and redirect the listing to the Maintenance server, in the Reports shared directory, and the Corp.txt file, type:

```
at \\corp 08:00 cmd /c net share reports=d:\marketing\reports >> \\maintenance\reports\corp.txt
```

To back up the hard drive of the Marketing server to a tape drive at midnight every five days, create a batch program called Archive.cmd, which contains the backup commands, and then schedule the batch program to run, type:

```
at \\marketing 00:00 /every:5,10,15,20,25,30 archive
```

To cancel all commands scheduled on the current server, clear the **at** schedule information as follows:

```
at /delete
```

To run a command that is not an executable (.exe) file, precede the command with **cmd /c** to load cmd.exe as follows:

```
cmd /c dir > c:\test.out
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [schtasks](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/schtasks.md). Another command-line scheduling tool.

---



MIT License. Copyright (c) 2020-2021 Strontic.


