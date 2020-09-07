---
title: diskperf.exe | Disk Performance Configuration Utility
---

# diskperf.exe 

* File Path: `C:\windows\SysWOW64\diskperf.exe`
* Description: Disk Performance Configuration Utility

## Hashes

Type | Hash
-- | --
MD5 | `4A1B27C7F905390DC6C428D6170D54DD`
SHA1 | `C0736DE29E9A0500FCA1115D19410754EF0CC4E9`
SHA256 | `6D1DFE10BF4482151DB3A8F34601DFDB527CC7EA107C0A74D8498DFA54E4E976`
SHA384 | `253CBC35A449CC973858409918BB5BCDD721482289008BBC356CA1AEEBA86577212E823115BB53CED9AC8C23037B19FD`
SHA512 | `A24AA80D5EB542A4B3428A8B75CCDE39CD6467456BE2719D14DE0D400E934CDAAB126EB93E17DB32FE66A1BB4E8FF364F90EA8AA4F390D5413AA5ACC80ED19EC`
SSDEEP | `384:4piOMtQz0EkQV+evvoX/Ml2fPgL8r/JulWRJWmP19:kiOMtQgEkQV+ekMyPmo/Juo31`

## Signature

* Status: The file C:\windows\SysWOW64\diskperf.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: DISKPERF.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


