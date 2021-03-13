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
MD5 | `F91BF214C9CD4A7E73B68882755905F8`
SHA1 | `8C36A1DD40D1F5EEDDC1D55B6FD6A7D1CCDEB980`
SHA256 | `9175DCDC9D866E0FD09FF4DABF8783A203201809489B1E73486E2183960C6A4D`
SHA384 | `D6050EE8AD3A331CC4B4502F3C6787303BF5B372EEC21795EF6314ECFBA3CC724A8E29C0CE3C93D2FDE38FB91E5EE873`
SHA512 | `A46D10A2B4B732CC935842EF0F8718471837B31CDEFA9C02E78EA5A9978F800604C3C5A37F49988401028840AFCC33E1E2652E562E6520DBCEE442664CE935A8`
SSDEEP | `384:6COMELFFyNdHwHfybLVnzp6+PQJfjsGeNZ+FWDJWujUS:6COMEryHHwHfEF6+4aGSZ+GC`
IMP | `C28394BB096619BE03BC663DF4326B95`
PESHA1 | `D1A97908BFDF07E503E9F768B26C176E325FD778`
PE256 | `A4F5EA762AED9BE1978616CD3FD7BB55FCB74B204B26FC062E0AB52968CDCB02`

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
* File Version: 10.0.19041.546 (WinBuild.160101.0800)
* Product Version: 10.0.19041.546
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/9175dcdc9d866e0fd09ff4dabf8783a203201809489b1e73486e2183960c6a4d/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\diskperf.exe](diskperf.exe-0952B0B59C748DF8B27F1C1B451CB407.md) | 86


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


