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
MD5 | `1B0E9B5FCB62DE0787235ECCA560B610`
SHA1 | `E19DA2C35BA1C38ADF12D1A472C1FCF1F1A811A7`
SHA256 | `697334C236CCE7D4C9E223146EE683A1219ADCED9729D4AE771FD6A1502A6B63`
SHA384 | `A8572EB5D98A4F1F641D91B517A14FD714CFE337C060BE33A7B6EE4078602FAAF5CC8E0C938574DA3CF65CED5185EC05`
SHA512 | `B71C46E301F5F415368AD7D7FF9A0E4CA6997DECF11053756F85C2CD83BB8B456EDB41CF5708169E2CC6E94940DB13339A970BECEE0F7CDFB786DABDDF94AC08`
SSDEEP | `12288:qFkZjRZXh71jot4IXPXa1nV5AvkT+SpueXUVY9uDHT1aMTzo8RP:qGZjbh7BZIv85+kixeXUaYDHZaMT88p`
IMP | `9833F5715D91CDA5A84888790AE9BB45`
PESHA1 | `CD8839B768DEB85023A95689EFA90A72DB2A7408`
PE256 | `53B647BFBAD80E8E5E5E0001B2B300A434B48262EC09193F7C3D2AF74E3CF710`

## Runtime Data

### Usage (stdout):
```cmhg
[2J[?25l[m[30;1H




































































[HRENAME         Renames a file or files.
REPLACE        Replaces files.
RMDIR          Removes a directory.
ROBOCOPY       Advanced utility to copy files and directory trees
SET            Displays, sets, or removes Windows environment variables.
SETLOCAL       Begins localization of environment changes in a batch file.
SC             Displays or configures services (background processes).
SCHTASKS       Schedules commands and programs to run on a computer.
SHIFT          Shifts the position of replaceable parameters in batch files.
SHUTDOWN       Allows proper local or remote shutdown of machine.
SORT           Sorts input.
START          Starts a separate window to run a specified program or command.
SUBST          Associates a path with a drive letter.
SYSTEMINFO     Displays machine specific properties and configuration.
TASKLIST       Displays all currently running tasks including services.
TASKKILL       Kill or stop a running process or application.
TIME           Displays or sets the system time.
TITLE          Sets the window title for a CMD.EXE session.
TREE           Graphically displays the directory structure of a drive or
               path.
TYPE           Displays the contents of a text file.
VER            Displays the Windows version.
VERIFY         Tells Windows whether to verify that your files are written
               correctly to a disk.
VOL            Displays a disk volume label and serial number.
XCOPY          Copies files and directory trees.
WMIC           Displays WMI information inside interactive command shell.

For more information on tools see the command-line reference in the online help.
]0;C:\Windows\system32\help.exe[?25h[HR[30;1H
```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/697334c236cce7d4c9e223146ee683a1219adced9729d4ae771fd6a1502a6b63/detection/


## Possible Misuse

*The following table contains possible examples of `conhost.exe` being misused. While `conhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_wsreset.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_wsreset.yml) | `Image\|endswith: '\conhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
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



MIT License. Copyright (c) 2020 Strontic.


