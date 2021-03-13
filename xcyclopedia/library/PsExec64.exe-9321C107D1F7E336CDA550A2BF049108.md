---
title: PsExec64.exe | Execute processes remotely
excerpt: What is PsExec64.exe?
---

# PsExec64.exe 

* File Path: `C:\SysinternalsSuite\PsExec64.exe`
* Description: Execute processes remotely

## Hashes

Type | Hash
-- | --
MD5 | `9321C107D1F7E336CDA550A2BF049108`
SHA1 | `FB0A150601470195C47B4E8D87FCB3F50292BEB2`
SHA256 | `AD6B98C01EE849874E4B4502C3D7853196F6044240D3271E4AB3FC6E3C08E9A4`
SHA384 | `CD963CE07865FBF9B6B2CDA760EB0A55F82F2F07719CC97BC74F71848631A0881409B3663B7AB6C440AA8E5E9C74A2BB`
SHA512 | `5AC1DAC5061DD14C1D79D2910C4DF6ED059059C7D3F987EBE9790626C327D5FA9C7CDBB4150C004D14750223F33B4FC27FA16B3681371D406C2B715BA757BE0E`
SSDEEP | `6144:o9123sLoT4aK8/A+kVG1FHEpgJEvf6sSMWTk7bjgxdO5mVx:on2ZHk/C6vfdHKO5s`
IMP | `159D56D406180A332FBC99290F30700E`
PESHA1 | `30C6FD26332C216A6BE902F6399E9AFB2FBC8AF5`
PE256 | `B2692FA4EB9EF82F9F81B0CE59417D90D4E41E9A0F3B4446BB3847B716DCCCBC`

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
C:\SysinternalsSuite\PsExec64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 2/71
* VirusTotal Link: https://www.virustotal.com/gui/file/ad6b98c01ee849874e4b4502c3d7853196f6044240d3271e4ab3fc6e3c08e9a4/detection/


## Possible Misuse

*The following table contains possible examples of `PsExec64.exe` being misused. While `PsExec64.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\psexec64.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- '*\psexec64.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_psexec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_psexec.yml) | `- '*\PsExec64.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | and not filename matches /(psexec.exe\|PSEXESVC.EXE\|PsExec64.exe)$/is | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


