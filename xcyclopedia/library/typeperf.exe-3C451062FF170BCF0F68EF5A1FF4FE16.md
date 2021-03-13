---
title: typeperf.exe | Command line performance monitor
excerpt: What is typeperf.exe?
---

# typeperf.exe 

* File Path: `C:\Windows\SysWOW64\typeperf.exe`
* Description: Command line performance monitor

## Hashes

Type | Hash
-- | --
MD5 | `3C451062FF170BCF0F68EF5A1FF4FE16`
SHA1 | `B9232D5C793597D0362C7CCE04598FA3F74E925E`
SHA256 | `7BC9B82F3DCE94D42B13E93EA134864715C7CE2F6E1E62C0FE7F0DD4E18664AA`
SHA384 | `60DEF226C9AF3DF34C39A7BD12D3DBAF73DA9B0ECADF179EF4AE93AFB2CCDAC037843AF43A02FC87A2DE8359D6336703`
SHA512 | `EC102C6B2A260312B3295A9C7B024CA116609F03EE9E4521E86CB46DD3146DFDA38796BBB3FF7F895F205E7DE2E2272F3FA2946F332F7B8F0ACA9A771318A301`
SSDEEP | `768:Vrez2ecGi6KS8ak9ivuIwz8doMwQNd6YGvI3/YroadNomPQV+UEhAz:VJGiWre1mdsaGw3AMadNomOEhQ`
IMP | `5DCDDB44A0DA4CD1D962C12AD1A2DA22`
PESHA1 | `FBC7B9A149023315A0B4B66A3F499BC59912A27A`
PE256 | `1BF241DEF9C1AB1887111B3C448D057516155EE0D98CF3A68853EEF00EDFDEAD`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft r TypePerf.exe (10.0.19041.546)

Typeperf writes performance data to the command window
or to a log file. To stop Typeperf, press CTRL+C.

Usage:
C:\Windows\SysWOW64\typeperf.exe { <counter [counter ...]> 
                                | -cf <filename> 
                                | -q [object] 
                                | -qx [object] 
                                } [options]

Parameters:
  <counter [counter ...]>       Performance counters
                                to monitor.

Options:
  -?                            Displays context
                                sensitive help.
  -f <CSV|TSV|BIN|SQL>          Output file format.
                                Default is CSV.
  -cf <filename>                File containing
                                performance counters
                                to monitor, one per
                                line.
  -si <[[hh:]mm:]ss>            Time between samples.
                                Default is 1 second.
  -o <filename>                 Path of output file or
                                SQL database. Default
                                is STDOUT.
  -q [object]                   List installed
                                counters (no
                                instances). To list
                                counters for one
                                object, include the
                                object name, such as
                                Processor.
  -qx [object]                  List installed
                                counters with
                                instances. To list
                                counters for one
                                object, include the
                                object name, such as
                                Processor.
  -sc <samples>                 Number of samples to
                                collect. Default is to
                                sample until CTRL+C.
  -config <filename>            Settings file
                                containing command
                                options.
  -s <computer_name>            Server to monitor if
                                no server is specified
                                in the counter path.
  -y                            Answer yes to all
                                questions without
                                prompting.

Note:
  Counter is the full name of a performance counter in
  "\\<Computer>\<Object>(<Instance>)\<Counter>" format,
  such as "\\Server1\Processor(0)\% User Time".

Examples:
  typeperf "\Processor(_Total)\% Processor Time"
  typeperf -cf counters.txt -si 5 -sc 50 -f TSV -o domain2.tsv
  typeperf -qx PhysicalDisk -o counters.txt

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\typeperf.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TypePerf.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.546 (WinBuild.160101.0800)
* Product Version: 10.0.19041.546
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/7bc9b82f3dce94d42b13e93ea134864715c7ce2f6e1e62c0fe7f0dd4e18664aa/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\typeperf.exe](typeperf.exe-F79CB8B640C8DEDA1896588BCBA690CE.md) | 96


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## typeperf

The **typeperf** command writes performance data to the command window or to a log file. To stop **typeperf**, press CTRL+C.

### Syntax

```
typeperf <counter [counter ...]> [options]
typeperf -cf <filename> [options]
typeperf -q [object] [options]
typeperf -qx [object] [options]
```

#### Parameters

| Parameter | Description |
|--|--|
| `<counter [counter [â€¦]]>` | Specifies performance counters to monitor. The `<counter>` parameter is the full name of a performance counter in \\Computer\Object(Instance)\Counter format, such as `\\Server1\Processor(0)\% User Time`.  |

##### Options

| Option | Description |
|--|--|
| -f `<CSV | TSV | BIN | SQL>` | Specifies the output file format. The default is CSV. |
| -cf `<filename>` | Specifies a file containing a list of performance counters to monitor, with one counter per line. |
| -si `<[[hh:]mm:]ss>` | Specifies the sample interval. The default is one second. |
| -o `<filename>` | Specifies the path for the output file, or the SQL database. The default is STDOUT (written to the command window). |
| -q `[object]` | Display a list of installed counters (no instances). To list counters for one object, include the object name. ***EXAMPLE |
| -qx `[object]` | Display a list of installed counters with instances. To list counters for one object, include the object name. |
| -sc `<samples>` | Specifies the number of samples to collect. The default is to collect data until CTRL+C is pressed. |
| -config `<filename>` | Specifies a settings file containing command options. |
| -s `<computer_name>` | Specifies a remote computer to monitor if no computer is specified in the counter path. |
| -y | Answer *yes* to all questions without prompting. |
| /? | Displays help at the command prompt. |

### Examples

To write the values for the local computer's performance counter `\Processor(_Total)\% Processor Time` to the command window at a default sample interval of 1 second until CTRL+C is pressed, type:

```
typeperf \Processor(_Total)\% Processor Time
```

To write the values for the list of counters in the file *counters.txt* to the tab-delimited file *domain2.tsv* at a sample interval of 5 seconds until 50 samples have been collected, type:

```
typeperf -cf counters.txt -si 5 -sc 50 -f TSV -o domain2.tsv
```

To query installed counters with instances for the counter object *PhysicalDisk* and writes the resulting list to the file *counters.txt*, type:

```
typeperf -qx PhysicalDisk -o counters.txt
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


