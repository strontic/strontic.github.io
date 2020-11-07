---
title: diskperf.exe | Disk Performance Configuration Utility
excerpt: What is diskperf.exe?
---

# diskperf.exe 

* File Path: `C:\Windows\system32\diskperf.exe`
* Description: Disk Performance Configuration Utility

## Hashes

Type | Hash
-- | --
MD5 | `7FACE5A6C4FA7913A7051BB8C8F9E7ED`
SHA1 | `9E184F02EE2FC57E03A00F3A62A1126EA7657451`
SHA256 | `293044B6001452F9855CE34BBF26F8A5C9D44A5CD2FBE9D8AC0651398C0F5FCB`
SHA384 | `2514CD4B80CA0BCAAF6B6546CD608752802A028D1EB16A1D4B7B3A2A994C4280863249833DFF1A96E33519A930C3AE4D`
SHA512 | `3730FD41AFF94C140CAD7F97C7935962527FEDF4C0784A99986D739E60ACE884EDEADEA4CEDC53EA6BA758DF12E87D2549531610BAF1564C05B158CDCFC57B18`
SSDEEP | `384:W1Y8+hriGBKOuP5X5ol44lDHtiPSmLkyT8QYRiOMRAt1z3VweQZ6KS9WDJW:WAhrtQol44lDASG8VRiOMReVwzZRSu`
IMP | `8C30315F0059261E5778F328A7850B04`
PESHA1 | `23DD3AC030134282020C0E480BA3EA60D260FE85`
PE256 | `8F10E0D2887584C039628249D83E1F79F7114C6727C089711A4430FB91C6223A`

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
C:\Windows\system32\diskperf.exe |
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

* Original Filename: DISKPERF.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/293044b6001452f9855ce34bbf26f8a5c9d44a5cd2fbe9d8ac0651398c0f5fcb/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\diskperf.exe](diskperf.exe-5038A44C5A7351D77A285877EB7CC95A.md) | 82


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



MIT License. Copyright (c) 2020 Strontic.


