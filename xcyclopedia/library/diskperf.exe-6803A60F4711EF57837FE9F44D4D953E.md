---
title: diskperf.exe | Disk Performance Configuration Utility
excerpt: What is diskperf.exe?
---

# diskperf.exe 

* File Path: `C:\Windows\SysWOW64\diskperf.exe`
* Description: Disk Performance Configuration Utility

## Hashes

Type | Hash
-- | --
MD5 | `6803A60F4711EF57837FE9F44D4D953E`
SHA1 | `B8659BE11EDE50CFAE5467AB837EC4BF95AB6EE1`
SHA256 | `1839A4AAD437B18B30E9FE880EDBDA89EEA9B76DD0725DAD2C99029CEB4E64BC`
SHA384 | `A7B02C7CD35D8423639FF25116DEDC18B3206E6F685B18B15876B22642D4375226A6C54F03D9A611B013E2ACD728C6C6`
SHA512 | `3EAD8149FE47CC80F1A27BACEB1BB78040165F91811D8D1DCB8327023533668DF64925D05351110798C1EEF506E31CEF893A325F3B553DA5B0B4F533E531ADE5`
SSDEEP | `384:gCOMTMpVlHw8jwHmz3Db9SIb/n7RZXdWoJW2:gCOMW/Hw8RjDbljnlZXJB`
IMP | `241BF50230A3DBE17E5AC2F48DA766C1`
PESHA1 | `6BF3927BF6FD1243342FBB27ED47480F0F9797D1`
PE256 | `98F081B297CF768851AD6B0EE314F38A37FC2EC52755F07C84C30E2B301DBE71`

## Runtime Data

### Usage (stdout):
```cmhg


DISKPERF=====================

Starts and stops system disk performance counters.

Used without the command switches, DISKPERF reports what disk
performance counters are enabled on the specified Windows 2000 computer.

Disk performance counters can be specified to report the
performance of the individual physical drives, or the individual
logical drives or storage volumes. Note that these two sets of
performance counters are measured independently. The user
has the option of enabling and disabling them independently
using the command line switches.
NOTE: This command can only be used to control remote
Windows 2000 systems. In newer systems, these performance counters
are automatically enabled.

DISKPERF [-Y[D|V] | -N[D|V]] [\\computername]

  -Y  Sets the system to start all disk performance counters
      when the system is restarted.

  -YD Enables the disk performance counters for physical drives.
      when the system is restarted.
  -YV Enables the disk performance counters for logical drives
      or storage volumes when the system is restarted.
  -N  Sets the system to disable all disk performance counters
      when the system is restarted.

  -ND Disables the disk performance counters for physical drives.
  -NV Disables the disk performance counters for logical drives.
  \\computername        Is the name of the computer you want to
                        see or set disk performance counter use.
                        The computer must be a Windows 2000 system.
  NOTE: Disk performance counters are permanently enabled on
        systems beyond Windows 2000.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\diskperf.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DISKPERF.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/1839a4aad437b18b30e9fe880edbda89eea9b76dd0725dad2c99029ceb4e64bc/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## diskperf

The **diskperf** command remotely enables or disables physical or logical disk performance counters on computers running Windows.

### Syntax

```
diskperf [-y[d|v] | -n[d|v]] [\\computername]
```

### Options

| Option | Description |
| ------ | ----------- |
| -y | Starts all disk performance counters when the computer restarts. |
| -yd | Enables disk performance counters for physical drives when the computer restarts. |
| -yv | Enables disk performance counters for logical drives or storage volumes when the computer restarts. |
| -n | Disables all disk performance counters when the computer restarts. |
| -nd | Disable disk performance counters for physical drives when the computer restarts. |
| -nv | Disable disk performance counters for logical drives or storage volumes when the computer restarts. |
| `\\<computername>` | Specifies the name of the computer where you want to enable or disable disk performance counters. |
| -? | Displays context sensitive help. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


