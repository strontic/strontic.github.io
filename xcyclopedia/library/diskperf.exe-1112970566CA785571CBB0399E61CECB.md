---
title: diskperf.exe | Disk Performance Configuration Utility
---

# diskperf.exe 

* File Path: `C:\windows\system32\diskperf.exe`
* Description: Disk Performance Configuration Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1112970566CA785571CBB0399E61CECB`
SHA1 | `CE763D5FF745878FB4842E763DD2E4E67A4BE967`
SHA256 | `B6F71BCF28A4861D4DD1ED4E43F51E21452396805549E617729A20BF7112BA01`
SHA384 | `4F9245F6AB9002D98DFE12DDDDD3380808DFD8BB599DDFFAA9A3F7A17D4F672417432C7958252D060746C211D5A8250F`
SHA512 | `81C8782254404C83AE868E2D938BCC4A470842C7E464BB6382AE15CB474A94882F837AA9A672ADA00B39C8C221F7C8B7EAD517E43F2D1DC4221838AD16C9FDD7`
SSDEEP | `384:kiOMTvUrjsJAn49ayXnnOwAxjuEc0MqbYEKxniZqvydPkyKgj9WRJW:kiOMjcjsJAn49DOTxK4bYE8is6dPQgjQ`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\diskperf.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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


