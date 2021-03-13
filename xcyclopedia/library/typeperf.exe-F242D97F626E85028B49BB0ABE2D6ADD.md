---
title: typeperf.exe | Command line performance monitor
excerpt: What is typeperf.exe?
---

# typeperf.exe 

* File Path: `C:\windows\SysWOW64\typeperf.exe`
* Description: Command line performance monitor

## Hashes

Type | Hash
-- | --
MD5 | `F242D97F626E85028B49BB0ABE2D6ADD`
SHA1 | `5B34F1B7EC4AF63F0F3EB47A9992965DA518D115`
SHA256 | `EF1E50F0CC9FA1751838B6E0ECD533CBD446BF90733938509FE255CBCB4C4309`
SHA384 | `AE65A39180221BC84973C715E014081E5B5AD1A3536D751164007628A4C3A75718B6DBC8F657467B7F1F04E554AA9B61`
SHA512 | `A595C004E74F03904610E6584F3BE0C194EDEF28E81BBEE67A124A4D8BE1D524C9D49220F252F8F0F13393778C98E80D044D47FC603B119264260301B0E78836`
SSDEEP | `768:OrezRE0dPDcjADsLkgF8fnkOh+BmqqmfdNMO/2O+/ooaTnHuYOXcCb:OL05gEIL2Pv0QqqoUS2OcaTnOYscC`

## Signature

* Status: The file C:\windows\SysWOW64\typeperf.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: TypePerf.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




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


