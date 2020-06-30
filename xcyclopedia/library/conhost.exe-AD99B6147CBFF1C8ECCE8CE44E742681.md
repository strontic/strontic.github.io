---
title: conhost.exe | Console Window Host
---

# conhost.exe 

* File Path: `C:\Windows\system32\conhost.exe`
* Description: Console Window Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `AD99B6147CBFF1C8ECCE8CE44E742681`
SHA1 | `74F28DD9B0DA310D85F1931DB2749A26A9A8AB02`
SHA256 | `912D217D9F34121BC6150A2D7F22B49D2C876942653348C671F358FF58AF0EBA`
SHA384 | `CE807092D13966F89A0CC9F073DD4CBCF344407FCEEBF0582E9F5350A51B79C375E048353F351D7898B133C0C28738FD`
SHA512 | `4171EDE855E2C1343728CCDF0D4CDB822E078D13CDBAAD4AE5D256CCBBF72F6255134C37670349C76D2F6E1334C141177B9C07950CF309D9738977B95650F63C`
SSDEEP | `12288:Z5VnZ6Fc5FgVOv9N/eP6GXTaCNqc+6qOBJoTblzu3snT+tCblZ9/:ZrnZVfjvTO6wTaCNqcp183li6T6Ih`

## Runtime Data

### Usage (stdout):
```Batchfile
[2J[?25l[m[30;1H


































[HFOR            Runs a specified command for each file in a set of files.
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
PROMPT         Changes the Windows command prompt.
]0;C:\Windows\system32\help.exe[?25h[?25l

































[HRENAME         Renames a file or files.[81X[81C
REPLACE        Replaces files.[90X[90C
RMDIR          Removes a directory.[85X[85C
ROBOCOPY       Advanced utility to copy files and directory trees[55X[55C
SET            Displays, sets, or removes Windows environment variables.[48X[48C
SETLOCAL       Begins localization of environment changes in a batch file.[46X[46C
SC             Displays or configures services (background processes).[50X[50C
SCHTASKS       Schedules commands and programs to run on a computer.[52X[52C
SHIFT          Shifts the position of replaceable parameters in batch files.[44X[44C
SHUTDOWN       Allows proper local or remote shutdown of machine.[55X[55C
SORT           Sorts input.[93X[93C
START          Starts a separate window to run a specified program or command.[42X[42C
SUBST          Associates a path with a drive letter.[67X[67C
SYSTEMINFO     Displays machine specific properties and configuration.[50X[50C
TASKLIST       Displays all currently running tasks including services.[49X[49C
TASKKILL       Kill or stop a running process or application.[59X[59C
TIME           Displays or sets the system time.[72X[72C
TITLE          Sets the window title for a CMD.EXE session.[61X[61C
TREE           Graphically displays the directory structure of a drive or[47X[47C
               path.[100X[100C
TYPE           Displays the contents of a text file.[68X[68C
VER            Displays the Windows version.[76X[76C
VERIFY         Tells Windows whether to verify that your files are written[46X[46C
               correctly to a disk.[85X[85C
VOL            Displays a disk volume label and serial number.[58X[58C
XCOPY          Copies files and directory trees.[72X[72C
WMIC           Displays WMI information inside interactive command shell.[47X[47C
[120X[120C
For more information on tools see the command-line reference in the online help.[40X[40C
[120X[120C[?25h
```

### Usage (stderr):
```Batchfile

```

### Child Processes:


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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `conhost.exe` being misused. While `conhost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `        Image\|endswith: '\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_creation_system_file.yml) | `            - '*\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


