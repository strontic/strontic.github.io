---
title: conhost.exe | Console Window Host
excerpt: What is conhost.exe?
---

# conhost.exe 

* File Path: `C:\WINDOWS\system32\conhost.exe`
* Description: Console Window Host

## Hashes

Type | Hash
-- | --
MD5 | `6031C3A5682DC7D48DD6B8398D03E41D`
SHA1 | `B80E4A8C51EA5E516EE8F545FA3D6CD3A5674579`
SHA256 | `27DF0052DC30ABF0C834B61C684BA8E11B4A480B308908267282DD2ED71EA894`
SHA384 | `50AFCA961DE5EC1C4F78DCE5A79D3F3379B07A6C31F396F799085ED036CDE770C0187097BE14E640675E947345E02455`
SHA512 | `B0147B21F2B99BF037201439653A01587EAD9657517C9A4CD2EA7D74677347BE2622ECD088D7C4A5A292B5D53467C3F4396DC3EB4A14D27948B329921EDDE53C`
SSDEEP | `24576:jeD/ysECQR9xsEligLp0UiBosrRgT1iNfY0huVftfK5:jeDhQR9xsxgLWlBosrRgT1iNg0IU`
IMP | `60EEC14761E9673289633B722526CF2E`
PESHA1 | `44AB8C407CE937BB1D40B9CB56D5361C047D52EC`
PE256 | `4CEAA99E109EE4974C9CB752E3600CD0095FB073C8F0AEF71FD2C7F9FDF3FC86`

## Runtime Data

### Usage (stdout):
```cmhg
[2J[m[55;1H
























[H               creates macros.
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
MKLINK         Creates Symbolic Links and Hard Links
MODE           Configures a system device.
]0;C:\WINDOWS\system32\conhost.exe[?25h[?25l[99;1H











































[HRENAME         Renames a file or files.[K
REPLACE        Replaces files.[K
RMDIR          Removes a directory.[K
ROBOCOPY       Advanced utility to copy files and directory trees[K
SET            Displays, sets, or removes Windows environment variables.[K
SETLOCAL       Begins localization of environment changes in a batch file.[K
SC             Displays or configures services (background processes).[K
SCHTASKS       Schedules commands and programs to run on a computer.[K
SHIFT          Shifts the position of replaceable parameters in batch files.[K
SHUTDOWN       Allows proper local or remote shutdown of machine.[K
SORT           Sorts input.[K
START          Starts a separate window to run a specified program or command.[K
SUBST          Associates a path with a drive letter.[K
SYSTEMINFO     Displays machine specific properties and configuration.[K
TASKLIST       Displays all currently running tasks including services.[K
TASKKILL       Kill or stop a running process or application.[K
TIME           Displays or sets the system time.[K
TITLE          Sets the window title for a CMD.EXE session.[K
TREE           Graphically displays the directory structure of a drive or[K
               path.[K
TYPE           Displays the contents of a text file.[K
VER            Displays the Windows version.[K
VERIFY         Tells Windows whether to verify that your files are written[K
               correctly to a disk.[K
VOL            Displays a disk volume label and serial number.[K
XCOPY          Copies files and directory trees.[K
WMIC           Displays WMI information inside interactive command shell.[K
[K
For more information on tools see the command-line reference in the online help.[K
[K[?25h
```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\conhost.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CONHOST.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/27df0052dc30abf0c834b61c684ba8e11b4a480b308908267282dd2ed71ea894/detection


## Possible Misuse

*The following table contains possible examples of `conhost.exe` being misused. While `conhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `CommandLine\|contains: 'conhost.exe 0xffffffff -ForceV1'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `title: Conhost Parent Process Executions`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `description: Detects the conhost execution as parent process. Can be used to evaded defense mechanism.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `ParentImage\|endswith: '\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_conhost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_conhost.yml) | `- Unlikely, conhost is a child less process`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\conhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
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


