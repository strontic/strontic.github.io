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
MD5 | `D837FA4DEE7D84C19FF6F71FC48A6625`
SHA1 | `BA93B6F897778B91DB9D179E14C352AF82210061`
SHA256 | `22117361C2C34CB18BEEE2CA9770B3AA6C8D032A0941991454DD222BEC6D9295`
SHA384 | `CE1AA13C6155B7A6ED19B7C292B7EB49D177478B8F64B60358DB56E77C2D91FCE93E7E485FBC5C4F53D567DCD04A8E80`
SHA512 | `EFC3D924F33A396C2DF7062B1629BC1787D67F187CF00E8B5C05644C05AFFDC0CE2E33E62E76FD4416D30AE1037DDED952E40C1F96F0C5DC7F284D6D8578711C`
SSDEEP | `12288:+hvMHP+iLytDVpky5gWugl//TAd5N9N+4QfyqU/Qvp7XGV:+haWw8V+yOI65J+4QqOvpzg`
IMP | `5E04B84014354D11014564789EE9BDA7`
PESHA1 | `0A663D3F81D7B82CACF66C48BBD2ECED9BA956AE`
PE256 | `1FDC0256E6DD0C034CC5F648075C78709402B4BF7E772852A7E944019D198420`

## Runtime Data

### Usage (stdout):
```cmhg
[2J[m[30;1H











































[H               graphics mode.
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
PUSHD          Saves the current directory then changes it.
RD             Removes a directory.
RECOVER        Recovers readable information from a bad or defective disk.
REM            Records comments (remarks) in batch files or CONFIG.SYS.
REN            Renames a file or files.
RENAME         Renames a file or files.
REPLACE        Replaces files.
RMDIR          Removes a directory.
ROBOCOPY       Advanced utility to copy files and directory trees
]0;C:\Windows\system32\conhost.exe[?25h[25l
























[5;1HSET            Displays, sets, or removes Windows environment variables.[K
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
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
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

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/22117361c2c34cb18beee2ca9770b3aa6c8d032a0941991454dd222bec6d9295/detection


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


