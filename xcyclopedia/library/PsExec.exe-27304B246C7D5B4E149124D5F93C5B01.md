---
title: PsExec.exe | Execute processes remotely
excerpt: What is PsExec.exe?
---

# PsExec.exe 

* File Path: `C:\SysinternalsSuite\PsExec.exe`
* Description: Execute processes remotely

## Hashes

Type | Hash
-- | --
MD5 | `27304B246C7D5B4E149124D5F93C5B01`
SHA1 | `E50D9E3BD91908E13A26B3E23EDEAF577FB3A095`
SHA256 | `3337E3875B05E0BFBA69AB926532E3F179E8CFBF162EBB60CE58A0281437A7EF`
SHA384 | `ED52290FC2695D9781FC2F56D0EEA2F11995468F67C1CD07ED275AB56F074F69A3D647FF74FBA887CFBB2033E179839E`
SHA512 | `BEC172A2F92A95796199CFC83F544A78685B52A94061CE0FFB46B265070EE0BCC018C4F548F56018BF3FF1E74952811B2AFB6DF79AB8D09F1EC73C9477AF636B`
SSDEEP | `3072:Yao79VuJ6titIi/H7ZUFgllxiBD+P5xWr3geNtdS+DlGttzhA9HY4ZUFxPkwlmlP:YaSq4TBWISSTgu7DlGtEC1xn/O5r4S`
IMP | `C1E59519B5E5D84AF07AFA6F5A8625F1`
PESHA1 | `B477BCA07BC32E8863119973BC91F6A55F10405F`
PE256 | `0C4FC597FA407059C94B3534F49BC090A11CCB4E4E6D969AF267E14D69359F71`

## Runtime Data

### Usage (stdout):
```cmhg

PsExec v2.2 - Execute processes remotely
Copyright (C) 2001-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

PsExec executes a program on a remote system, where remotely executed console
applications execute interactively.

Usage: psexec [\\computer[,computer2[,...] | @file]][-u user [-p psswd][-n s][-r servicename][-h][-l][-s|-e][-x][-i [session]][-c [-f|-v]][-w directory][-d][-<priority>][-a n,n,...] cmd [arguments]
     -a         Separate processors on which the application can run with
                commas where 1 is the lowest numbered CPU. For example,
                to run the application on CPU 2 and CPU 4, enter:
                "-a 2,4"
     -c         Copy the specified program to the remote system for
                execution. If you omit this option the application
                must be in the system path on the remote system.
     -d         Don't wait for process to terminate (non-interactive).
     -e         Does not load the specified account's profile.
     -f         Copy the specified program even if the file already
                exists on the remote system.
     -i         Run the program so that it interacts with the desktop of the
                specified session on the remote system. If no session is
                specified the process runs in the console session.
     -h         If the target system is Vista or higher, has the process
                run with the account's elevated token, if available.
     -l         Run process as limited user (strips the Administrators group
                and allows only privileges assigned to the Users group).
                On Windows Vista the process runs with Low Integrity.
     -n         Specifies timeout in seconds connecting to remote computers.
     -p         Specifies optional password for user name. If you omit this
                you will be prompted to enter a hidden password.
     -r         Specifies the name of the remote service to create or interact.
                with.
     -s         Run the remote process in the System account.
     -u         Specifies optional user name for login to remote
                computer.
     -v         Copy the specified file only if it has a higher version number
                or is newer on than the one on the remote system.
     -w         Set the working directory of the process (relative to
                remote computer).
     -x         Display the UI on the Winlogon secure desktop (local system
                only).
     -arm       Specifies the remote computer is of ARM architecture.
     -priority	Specifies -low, -belownormal, -abovenormal, -high or
                -realtime to run the process at a different priority. Use
                -background to run at low memory and I/O priority on Vista.
     computer   Direct PsExec to run the application on the remote
                computer or computers specified. If you omit the computer
                name PsExec runs the application on the local system, 
                and if you specify a wildcard (\\*), PsExec runs the
                command on all computers in the current domain.
     @file      PsExec will execute the command on each of the computers listed
                in the file.
     cmd	    Name of application to execute.
     arguments  Arguments to pass (note that file paths must be
                absolute paths on the target system).
     -accepteula This flag suppresses the display of the license dialog.
     -nobanner   Do not display the startup banner and copyright message.

You can enclose applications that have spaces in their name with
quotation marks e.g. psexec \\marklap "c:\long name app.exe".
Input is only passed to the remote system when you press the enter
key, and typing Ctrl-C terminates the remote process.

If you omit a user name the process will run in the context of your
account on the remote system, but will not have access to network
resources (because it is impersonating). Specify a valid user name
in the Domain\User syntax if the remote process requires access
to network resources or to run in a different account. Note that
the password and command is encrypted in transit to the remote system.

Error codes returned by PsExec are specific to the applications you
execute, not PsExec.


```

### Usage (stderr):
```cmhg
Access is denied.
PsExec could not start C:\temp\strontic-xcyclopedia\notepad.exe:

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\PsExec.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000010A2C79AED7797BA6AC00010000010A`
* Thumbprint: `3BDA323E552DB1FDE5F4FBEE75D6D5B2B187EEDC`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: psexec.c
* Product Name: Sysinternals PsExec
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 2.2
* Product Version: 2.2
* Language: English (United States)
* Legal Copyright: Copyright (C) 2001-2016 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3337e3875b05e0bfba69ab926532e3f179e8cfbf162ebb60ce58a0281437a7ef/detection/


## Possible Misuse

*The following table contains possible examples of `PsExec.exe` being misused. While `PsExec.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [zeek_smb_converted_win_susp_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/zeek/zeek_smb_converted_win_susp_psexec.yml) | `title: Suspicious PsExec Execution - Zeek` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [zeek_smb_converted_win_susp_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/zeek/zeek_smb_converted_win_susp_psexec.yml) | `description: detects execution of psexec or paexec with renamed service name, this rule helps to filter out the noise if psexec is used for legit purposes or if attacker uses a different psexec client other than sysinternal one` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_hack_smbexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_hack_smbexec.yml) | `- https://blog.ropnop.com/using-credentials-to-own-windows-boxes-part-2-psexec-and-services/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_psexec.yml) | `title: Suspicious PsExec Execution` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_psexec.yml) | `description: detects execution of psexec or paexec with renamed service name, this rule helps to filter out the noise if psexec is used for legit purposes or if attacker uses a different psexec client other than sysinternal one` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_psexec.yml) | `- https://blog.menasec.net/2019/02/threat-hunting-3-detecting-psexec.html` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_powershell_exploit_scripts.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_powershell_exploit_scripts.yml) | `- '*\Invoke-PsExec.ps1'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_defender_psexec_wmi_asr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_defender_psexec_wmi_asr.yml) | `title: PSExec and WMI Process Creations Block` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_defender_psexec_wmi_asr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_defender_psexec_wmi_asr.yml) | `description: Detects blocking of process creations originating from PSExec and WMI commands` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_defender_psexec_wmi_asr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_defender_psexec_wmi_asr.yml) | `- https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-atp/attack-surface-reduction?WT.mc_id=twitter#block-process-creations-originating-from-psexec-and-wmi-commands` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_defender_psexec_wmi_asr.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_defender_psexec_wmi_asr.yml) | `definition: 'Requirements:Enabled Block process creations originating from PSExec and WMI commands from Attack Surface Reduction (GUID: d1e49aac-8f56-4280-b9ba-993a6d77406c)'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_tool_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_tool_psexec.yml) | `title: PsExec Tool Execution` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_tool_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/other/win_tool_psexec.yml) | `description: Detects PsExec service installation and execution events (service and Sysmon)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_malicious_commandlets.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_malicious_commandlets.yml) | `- "*Invoke-PsExec*"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- psexec.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_psexesvc_start.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_psexesvc_start.yml) | `title: PsExec Service Start` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_psexesvc_start.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_psexesvc_start.yml) | `description: Detects a PsExec service start` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'psexec.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'psexec.c'  # old versions of psexec (2016 seen)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\psexec.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- "psexec.exe"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- "psexec.c"  # old versions of psexec (2016 seen)` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- '*\psexec.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_psexec.yml) | `title: Renamed PsExec` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_psexec.yml) | `description: Detects the execution of a renamed PsExec often used by attackers or malware` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_psexec.yml) | `Product: 'Sysinternals PsExec'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_psexec.yml) | `- '*\PsExec.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_psexec.yml) | `- Software that illegaly integrates PsExec in a renamed form` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_psexec.yml) | `- Administrators that have renamed PsExec and no one knows why` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"http://pen-testing.sans.org/blog/pen-testing/2013/08/08/psexec-uac-bypass",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "Adversaries may execute a binary, command, or script via a method that interacts with Windows services, such as the Service Control Manager. This can be done by either creating a new service or modifying an existing service. This technique is the execution used in conjunction with New Service and Modify Existing Service during service persistence or privilege escalation.\n\nDetection: Changes to service Registry entries and command-line invocation of tools capable of modifying services that do not correlate with known software, patch cycles, etc., may be suspicious. If a service is used only to execute a binary or script and not to persist, then it will likely be changed back to its original form shortly after the service is restarted so the service is not left broken, as is the case with the common administrator tool PsExec.\n\nPlatforms: Windows\n\nData Sources: Windows Registry, Process command-line parameters, Process monitoring\n\nPermissions Required: Administrator, SYSTEM\n\nRemote Support: Yes",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Use PsExec to execute a command on a remote host [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Copy and Execute File with PsExec [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: Use PsExec to execute a command on a remote host [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Copy and Execute File with PsExec [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.004/T1003.004.md) | \| psexec_exe \| Path to PsExec executable \| Path \| PathToAtomicsFolder&#92;T1003.004&#92;bin&#92;PsExec.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.004/T1003.004.md) | ##### Description: PsExec from Sysinternals must exist on disk at specified location (#{psexec_exe}) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.004/T1003.004.md) | Copy-Item $env:TEMP\PSTools\PsExec.exe #{psexec_exe} -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.002/T1021.002.md) | - [Atomic Test #3 - Copy and Execute File with PsExec](#atomic-test-3---copy-and-execute-file-with-psexec) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.002/T1021.002.md) | ## Atomic Test #3 - Copy and Execute File with PsExec | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.002/T1021.002.md) | Copies a file to a remote host and executes it using PsExec. Requires the download of PsExec from [https://docs.microsoft.com/en-us/sysinternals/downloads/psexec](https://docs.microsoft.com/en-us/sysinternals/downloads/psexec). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.002/T1021.002.md) | psexec.exe #{remote_host} -accepteula -c #{command_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | [PsExec](https://attack.mitre.org/software/S0029) can also be used to execute commands or payloads via a temporary Windows service created through the service control manager API.(Citation: Russinovich Sysinternals) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | - [Atomic Test #2 - Use PsExec to execute a command on a remote host](#atomic-test-2---use-psexec-to-execute-a-command-on-a-remote-host) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | ## Atomic Test #2 - Use PsExec to execute a command on a remote host | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | Upon successful execution, cmd will utilize psexec.exe to spawn calc.exe on a remote endpoint (default:localhost). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | \| psexec_exe \| Path to PsExec \| string \| C:&#92;PSTools&#92;PsExec.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | ##### Description: PsExec tool from Sysinternals must exist on disk at specified location (#{psexec_exe}) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | Copy-Item $env:TEMP\PsTools\PsExec.exe "#{psexec_exe}" -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) | description = "Detects Empire component - file Invoke-PsExec.ps1" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mimikatz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mimikatz.yar) | $x14 = "Clear screen (doesn't work with redirections, like PsExec)" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Looks like a cloaked PsExec. May be APT group activity." | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | $s1 = "Sysinternals PsExec" wide fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | and not filename matches /(psexec.exe\|PSEXESVC.EXE\|PsExec64.exe)$/is | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


