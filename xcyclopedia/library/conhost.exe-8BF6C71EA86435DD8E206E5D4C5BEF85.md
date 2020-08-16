---
title: conhost.exe | Console Window Host
---

# conhost.exe 

* File Path: `C:\Windows\system32\conhost.exe`
* Description: Console Window Host

## Hashes

Type | Hash
-- | --
MD5 | `8BF6C71EA86435DD8E206E5D4C5BEF85`
SHA1 | `578C53A7A785A7238272E28C53684FB51995E663`
SHA256 | `7A9595B552E23FB058A698ED8201369EEECAEE69BD3650EE1E9FE924E64C2BE1`
SHA384 | `90D1452B54F80B02E7CC69B8F7DFB8F9A8DA0F7EE03B3C9CB58AAE8170A04F84566A55C63B3A4DCC75F9FE43B42838AF`
SHA512 | `024E7AA5197A6A0DEF57882B93FE5A18945685CF469218AC30F2A52A3CD531BC2A63A3773C822DACEACF66AB92B07C171896552570FAB291533A4189B33C4ED5`
SSDEEP | `12288:zTeDhxNBAwKbsaXzR73MWJZF1CrLdeeIob5FGW//BAoX:/eDRBAwKbs+3VtGLzIob5FtBR`

## Runtime Data

### Usage (stdout):
```Batchfile
[2J[m[30;1H






















[HDISKPART       Displays or configures Disk Partition properties.
DOSKEY         Edits command lines, recalls Windows commands, and
               creates macros.
DRIVERQUERY    Displays current device driver status and properties.
ECHO           Displays messages, or turns command echoing on or off.
ENDLOCAL       Ends localization of environment changes in a batch file.
ERASE          Deletes one or more files.
EXIT           Quits the CMD.EXE program (command interpreter).
FC             Compares two files or sets of files, and displays the
               differences between them.
FIND           Searches for a text string in a file or files.
FINDSTR        Searches for strings in files.
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
]0;C:\Windows\system32\conhost.exe[?25h[25l




































[HPOPD           Restores the previous value of the current directory saved by[K
               PUSHD.[K
PRINT          Prints a text file.[K
PROMPT         Changes the Windows command prompt.[K
PUSHD          Saves the current directory then changes it.[K
RD             Removes a directory.[K
RECOVER        Recovers readable information from a bad or defective disk.[K
REM            Records comments (remarks) in batch files or CONFIG.SYS.[K
REN            Renames a file or files.[K
RENAME         Renames a file or files.[K
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
[K[?25h[25l








[21;1HTYPE           Displays the contents of a text file.[K
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


## Possible Misuse

*The following table contains possible examples of `conhost.exe` being misused. While `conhost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `            - '\System32\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `        Image\|endswith: '\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_between-hk-and-burma.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_between-hk-and-burma.yar) | 		$file1 = "\\Microsoft\\Internet Explorer\\conhost.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) |       $two4 = "/Delete /F /TN Conhost & del" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) |       $a10 = "\\conhost.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | 		description = "Anomaly rule looking for certain strings in a system file (maybe false positive on certain systems) - file conhost.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | 		filename == "conhost.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


