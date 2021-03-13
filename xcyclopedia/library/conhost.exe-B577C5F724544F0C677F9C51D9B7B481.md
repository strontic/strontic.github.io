---
title: conhost.exe | Console Window Host
excerpt: What is conhost.exe?
---

# conhost.exe 

* File Path: `C:\Windows\system32\conhost.exe`
* Description: Console Window Host

## Hashes

Type | Hash
-- | --
MD5 | `B577C5F724544F0C677F9C51D9B7B481`
SHA1 | `2976D388F210AFC42B5F7AEAFA58805BA7589B8F`
SHA256 | `A9B3185119953859889B462FAF68D75DF365FF569EE1B9A5C5CE1C26CB443CB9`
SHA384 | `A4281EB08A0B1D9F9867AD1BD4587D8A77ADAE147DE49D83E99815BADBC60BC0DF3F3C7ECAC0F9A537398F588A1B1BCB`
SHA512 | `2BB6D97B3CDB0B9EF940F09CB23477A67FED2F7D6B0753CCDD6B7CA7DC55F23B9E25F89E9A674B946E47789BD0264DEB3780AB58F499D08D912D7BE7B73B7EB7`
SSDEEP | `12288:fS3UrwBJ7TR1WASnE6dQuiAfE9khVlnc3TsPLT4fscR:a3UcJ7TR1hx6W/94lc3TsPAfs0`
IMP | `AFFE8C3BE3BBE4F0AC2EF124256F372D`
PESHA1 | `C39E665513ABD46298A54F16E4A22EDD1A74EB0D`
PE256 | `829DA05F36F82B32960DFFCA200DCB99D61305D643D08D724255783B0C85AF14`

## Runtime Data

### Usage (stdout):
```cmhg
[2J[m[30;1H

































[HFINDSTR        Searches for strings in files.
FOR            Runs a specified command for each file in a set of files.
FORMAT         Formats a disk for use with Windows.
FSUTIL         Displays or configures the file system properties.
FTYPE          Displays or modifies file types used in file extension
               associations.
GOTO           Directs the Windows command interpreter to a labeled line in
               a batch program.
GPRESULT       Displays Group Policy information for machine or user.
GRAFTABL       Enables Windows to display an extended character set in
               graphics mode.
HELP           Provides Help information for Windows commands.
ICACLS         Display, modify, backup, or restore ACLs for files and
               directories.
IF             Performs conditional processing in batch programs.
LABEL          Creates, changes, or deletes the volume label of a disk.
MD             Creates a directory.
MKDIR          Creates a directory.
MKLINK         Creates Symbolic Links and Hard Links
MODE           Configures a system device.
MORE           Displays output one screen at a time.
MOVE           Moves one or more files from one directory to another
               directory.
OPENFILES      Displays files opened by remote users for a file share.
PATH           Displays or sets a search path for executable files.
PAUSE          Suspends processing of a batch file and displays a message.
POPD           Restores the previous value of the current directory saved by
               PUSHD.
PRINT          Prints a text file.
]0;C:\Windows\system32\conhost.exe[?25h[25l


































[HRENAME         Renames a file or files.[K
REPLACE        Replaces files.[K
RMDIR          Removes a directory.[K
ROBOCOPY       Advanced utility to copy files and directory trees[K
SET            Displays, sets, or removes Windows environment variables.[K
SETLOCAL       Begins localization of environment changes in a batch file.[K
SC             Displays or configures services (background processes).[K
SCHTASKS       Schedules commands and programs to run on a computer.[K
SHIFT          Shifts the position of replaceable parameters in batch files.[K
SHUTDOWN       Allows proper local or remote shutdown of machine.[K
SORT           Sorts input.[K
START          Starts a separate window to run a specified program or command.[K
SUBST          Associates a path with a drive letter.[K
SYSTEMINFO     Displays machine specific properties and configuration.[K
TASKLIST       Displays all currently running tasks including services.[K
TASKKILL       Kill or stop a running process or application.[K
TIME           Displays or sets the system time.[K
TITLE          Sets the window title for a CMD.EXE session.[K
TREE           Graphically displays the directory structure of a drive or[K
               path.[K
TYPE           Displays the contents of a text file.[K
VER            Displays the Windows version.[K
VERIFY         Tells Windows whether to verify that your files are written[K
               correctly to a disk.[K
VOL            Displays a disk volume label and serial number.[K
XCOPY          Copies files and directory trees.[K
WMIC           Displays WMI information inside interactive command shell.[K
[K
For more information on tools see the command-line reference in the online help.[K
[K[?25h
```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\conhost.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CONHOST.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/a9b3185119953859889b462faf68d75df365ff569ee1b9a5c5ce1c26cb443cb9/detection


## Possible Misuse

*The following table contains possible examples of `conhost.exe` being misused. While `conhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `title: Conhost Parent Proces Executions`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `description: Detects the conhost execution as parent process. Can be used to evaded defense mechanism.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `ParentImage: '*\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `- Unlikely, conhost is a child less process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `Image\|endswith: '\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Indirect Command Execution - conhost.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Indirect Command Execution - conhost.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | - [Atomic Test #3 - Indirect Command Execution - conhost.exe](#atomic-test-3---indirect-command-execution---conhostexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | ## Atomic Test #3 - Indirect Command Execution - conhost.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | conhost.exe refers to a host process for the console window. It provide an interface between command prompt and Windows explorer. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1202.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1202/T1202.md) | conhost.exe "#{process}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_between-hk-and-burma.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_between-hk-and-burma.yar) | $file1 = "\\Microsoft\\Internet Explorer\\conhost.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $two4 = "/Delete /F /TN Conhost & del" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $a10 = "\\conhost.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file conhost.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "conhost.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


