---
title: forfiles.exe | ForFiles - Executes a command on selected files
excerpt: What is forfiles.exe?
---

# forfiles.exe 

* File Path: `C:\Windows\system32\forfiles.exe`
* Description: ForFiles - Executes a command on selected files

## Hashes

Type | Hash
-- | --
MD5 | `9BB67AEA5E26CB136F23F29CC48D6B9E`
SHA1 | `CABEE28F7368AAE1AC23F0713E2C330F96AF2062`
SHA256 | `9B4886F187489A190BB2C412772C1998539F086C63A4CFD72FF3B107CBC21907`
SHA384 | `52831636AFEC50A2F6FC4CBF7766F1831D513707653896695036CCCF5F51E3ED4C8CF9FE299DEA60634175D92C9BFB7C`
SHA512 | `AC1EA7BE97CADCE0ABF3B581A97B32CCEECDC5E7015704EF6A08E33D47F928AAB4758DF61EFB9856057C09D31629EA080F9525B199DAEBAA4B945338086411BB`
SSDEEP | `1536:3vFQXxbEZhhnGU3Yk8aoBgkRfnt6xCxggRL:3exAZhhnGU3Yk7kRyCxgU`
IMP | `BB3BC1A3FEF88F916302D61DDC886F80`
PESHA1 | `62B4D108996AEAD71664BEABD9CF05764594BB4F`
PE256 | `1693C3F0D4CA2B5206F11A406A2A3B17B8B8077534DAD2631454FFA4A115804F`

## Runtime Data

### Usage (stdout):
```cmhg

FORFILES [/P pathname] [/M searchmask] [/S]
         [/C command] [/D [+ | -] {MM/dd/yyyy | dd}]

Description:
    Selects a file (or set of files) and executes a 
    command on that file. This is helpful for batch jobs.

Parameter List:
    /P    pathname      Indicates the path to start searching.
                        The default folder is the current working
                        directory (.).

    /M    searchmask    Searches files according to a searchmask.
                        The default searchmask is '*' .

    /S                  Instructs forfiles to recurse into
                        subdirectories. Like "DIR /S".

    /C    command       Indicates the command to execute for each file.
                        Command strings should be wrapped in double
                        quotes. 

                        The default command is "cmd /c echo @file".

                        The following variables can be used in the
                        command string:
                        @file    - returns the name of the file.
                        @fname   - returns the file name without
                                   extension.
                        @ext     - returns only the extension of the
                                   file.
                        @path    - returns the full path of the file.
                        @relpath - returns the relative path of the
                                   file.
                        @isdir   - returns "TRUE" if a file type is
                                   a directory, and "FALSE" for files.
                        @fsize   - returns the size of the file in
                                   bytes.
                        @fdate   - returns the last modified date of the
                                   file.
                        @ftime   - returns the last modified time of the
                                   file.

                        To include special characters in the command 
                        line, use the hexadecimal code for the character
                        in 0xHH format (ex. 0x09 for tab). Internal
                        CMD.exe commands should be preceded with
                        "cmd /c".

    /D    date          Selects files with a last modified date greater
                        than or equal to (+), or less than or equal to
                        (-), the specified date using the
                        "MM/dd/yyyy" format; or selects files with a
                        last modified date greater than or equal to (+)
                        the current date plus "dd" days, or less than or
                        equal to (-) the current date minus "dd" days. A
                        valid "dd" number of days can be any number in
                        the range of 0 - 32768.
                        "+" is taken as default sign if not specified.

    /?                  Displays this help message.

Examples:
    FORFILES /?
    FORFILES  
    FORFILES /P C:\WINDOWS /S /M DNS*.* 
    FORFILES /S /M *.txt /C "cmd /c type @file | more"
    FORFILES /P C:\ /S /M *.bat
    FORFILES /D -30 /M *.exe
             /C "cmd /c echo @path 0x09 was changed 30 days ago"
    FORFILES /D 01/01/2001
             /C "cmd /c echo @fname is new since Jan 1st 2001"
    FORFILES /D +12/12/2020 /C "cmd /c echo @fname is new today"
    FORFILES /M *.exe /D +1
    FORFILES /S /M *.doc /C "cmd /c echo @fsize" 
    FORFILES /M *.txt /C "cmd /c if @isdir==FALSE notepad.exe @file"

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '--help'.
Type "FORFILES /?" for usage.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\forfiles.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: forfiles.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/9b4886f187489a190bb2c412772c1998539f086c63a4cfd72ff3b107cbc21907/detection


## Possible Misuse

*The following table contains possible examples of `forfiles.exe` being misused. While `forfiles.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '\forfiles.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\forfiles.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_indirect_cmd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_indirect_cmd.yml) | `description: Detect indirect command execution via Program Compatibility Assistant (pcalua.exe or forfiles.exe).`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_indirect_cmd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_indirect_cmd.yml) | `- '\forfiles.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '\forfiles.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_servu_process_pattern.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_servu_process_pattern.yml) | `- '\forfiles.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Forfiles.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Forfiles.yml) | `Name: Forfiles.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Forfiles.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Forfiles.yml) | `- Command: forfiles /p c:\windows\system32 /m notepad.exe /c calc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Forfiles.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Forfiles.yml) | `Usecase: Use forfiles to start a new process to evade defensive counter measures`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Forfiles.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Forfiles.yml) | `- Command: forfiles /p c:\windows\system32 /m notepad.exe /c "c:\folder\normal.dll:evil.exe"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Forfiles.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Forfiles.yml) | `Usecase: Use forfiles to start a new process from a binary hidden in an alternate data stream`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Forfiles.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Forfiles.yml) | `- Path: C:\Windows\System32\forfiles.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Forfiles.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Forfiles.yml) | `- Path: C:\Windows\SysWOW64\forfiles.exe`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Various Windows utilities may be used to execute commands, possibly without invoking [cmd](https://attack.mitre.org/software/S0106). For example, [Forfiles](https://attack.mitre.org/software/S0193), the Program Compatibility Assistant (pcalua.exe), components of the Windows Subsystem for Linux (WSL), as well as other utilities may invoke the execution of programs and commands from a [Command-Line Interface](https://attack.mitre.org/techniques/T1059), Run window, or via scripts. (Citation: VectorSec ForFiles Aug 2017) (Citation: Evi1cg Forfiles Nov 2017)\n\nAdversaries may abuse these features for [Defense Evasion](https://attack.mitre.org/tactics/TA0005), specifically to perform arbitrary execution while subverting detections and/or mitigation controls (such as Group Policy) that limit/prevent the usage of [cmd](https://attack.mitre.org/software/S0106) or file extensions more commonly associated with malicious payloads.",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Indirect Command Execution - forfiles.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: Indirect Command Execution - forfiles.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | <blockquote>Adversaries may abuse utilities that allow for command execution to bypass security restrictions that limit the use of command-line interpreters. Various Windows utilities may be used to execute commands, possibly without invoking [cmd](https://attack.mitre.org/software/S0106). For example, [Forfiles](https://attack.mitre.org/software/S0193), the Program Compatibility Assistant (pcalua.exe), components of the Windows Subsystem for Linux (WSL), as well as other utilities may invoke the execution of programs and commands from a [Command and Scripting Interpreter](https://attack.mitre.org/techniques/T1059), Run window, or via scripts. (Citation: VectorSec ForFiles Aug 2017) (Citation: Evi1cg Forfiles Nov 2017) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | - [Atomic Test #2 - Indirect Command Execution - forfiles.exe](#atomic-test-2---indirect-command-execution---forfilesexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | ## Atomic Test #2 - Indirect Command Execution - forfiles.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | forfiles.exe may invoke the execution of programs and commands from a Command-Line Interface. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | [Reference](https://github.com/api0cradle/LOLBAS/blob/master/OSBinaries/Forfiles.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | forfiles /p c:\windows\system32 /m notepad.exe /c #{process} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | forfiles /p c:\windows\system32 /m notepad.exe /c "c:\folder\normal.dll:evil.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_xtunnel_bundestag.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_xtunnel_bundestag.yar) | $s3 = "forfiles" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## forfiles

Selects and runs a command on a file or set of files. This command is most commonly used in batch files.

### Syntax

```
forfiles [/P pathname] [/M searchmask] [/S] [/C command] [/D [+ | -] [{<date> | <days>}]]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /P `<pathname>` | Specifies the path from which to start the search. By default, searching starts in the current working directory. |
| /M `<searchmask>` | Searches files according to the specified search mask. The default searchmask is `*`. |
| /S | Instructs the **forfiles** command to search in subdirectories recursively. |
| /C `<command>` | Runs the specified command on each file. Command strings should be wrapped in double quotes. The default command is `"cmd /c echo @file"`. |
| /D `[{+\|-}][{<date> | <days>}]` | Selects files with a last modified date within the specified time frame:<ul><li>Selects files with a last modified date later than or equal to (**+**) or earlier than or equal to (**-**) the specified date, where *date* is in the format MM/DD/YYYY.</li><li>Selects files with a last modified date later than or equal to (**+**) the current date plus the number of days specified, or earlier than or equal to (**-**) the current date minus the number of days specified.</li><li>Valid values for *days* include any number in the range 0â€“32,768. If no sign is specified, **+** is used by default.</li></ul> |
| /? | Displays the help text in the cmd window. |

##### Remarks

- The `forfiles /S` command is similar to `dir /S`.

- You can use the following variables in the command string as specified by the **/C** command-line option:

    | Variable | Description |
    | -------- | ----------- |
    | @FILE | File name. |
    | @FNAME | File name without extension. |
    | @EXT | File name extension. |
    | @PATH | Full path of the file. |
    | @RELPATH | Relative path of the file. |
    | @ISDIR | Evaluates to TRUE if a file type is a directory. Otherwise, this variable evaluates to FALSE. |
    | @FSIZE | File size, in bytes. |
    | @FDATE | Last modified date stamp on the file. |
    | @FTIME | Last modified time stamp on the file. |

- The **forfiles** command lets you run a command on or pass arguments to multiple files. For example, you could run the **type** command on all files in a tree with the .txt file name extension. Or you could execute every batch file (*.bat) on drive C, with the file name Myinput.txt as the first argument.

- This command can:

    - Select files by an absolute date or a relative date by using the **/d** parameter.

    - Build an archive tree of files by using variables such as @FSIZE and @FDATE.

    - Differentiate files from directories by using the @ISDIR variable.

    - Include special characters in the command line by using the hexadecimal code for the character, in 0x*HH* format (for example, 0x09 for a tab).

- This command works by implementing the `recurse subdirectories` flag on tools that are designed to process only a single file.

#### Examples

To list all of the batch files on drive C, type:

```
forfiles /P c:\ /S /M *.bat /C "cmd /c echo @file is a batch file"
```

To list all of the directories on drive C, type:

```
forfiles /P c:\ /S /M * /C "cmd /c if @isdir==TRUE echo @file is a directory"
```

To list all of the files in the current directory that are at least one year old, type:

```
forfiles /S /M *.* /D -365 /C "cmd /c echo @file is at least one year old."
```

To display the text *file* is outdated for each of the files in the current directory that are older than January 1, 2007, type:

```
forfiles /S /M *.* /D -01/01/2007 /C "cmd /c echo @file is outdated."
```

To list the file name extensions of all the files in the current directory in column format, and add a tab before the extension, type:

```
forfiles /S /M *.* /C "cmd /c echo The extension of @file is 0x09@ext"
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


