﻿---
title: relog.exe | Performance Relogging Utility
excerpt: What is relog.exe?
---

# relog.exe 

* File Path: `C:\Windows\SysWOW64\relog.exe`
* Description: Performance Relogging Utility

## Hashes

Type | Hash
-- | --
MD5 | `B5BD958DCD88565CC17E9330032F99CE`
SHA1 | `86F8CC31C4996C7D1DACB060870E48733429CE68`
SHA256 | `2030C6509CEE45E3629A9B47D09BD421B83F48F356ED597A03C89306610D720C`
SHA384 | `6B687DF91A56B8C2AA6AB9D0B834E2FB9F2F9B64CF78234D15C3C34E98D8F85776849FC558BF4C3EA42905DBED695672`
SHA512 | `55804FA3AABCDAF14628633D855A5113C6E26A027F45709E1AF8F8D91942125C923BD47C7C7082D4B6FDDF92981EC510890965518E382022753D209FA95DEB7E`
SSDEEP | `768:/zsVR22awTzqvJneZ/HI7vUjO9ZNvv/2rEaQLo6Ec22C2ieU0i:/zsVFdYJIQDv9raEqc2AieU0i`
IMP | `6224A72BD9E47088A3D467560173CDC1`
PESHA1 | `5C2CF5F72F680F735599ED3A768694841EE58C8D`
PE256 | `2A169A626C8275D6ADC5DF9176A4F50B7F67A1EB6C13D98DBDE3406539C4E02B`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft r Relog.exe (10.0.19041.546)

Relog creates new performance logs from data in existing performance logs by
changing the sampling rate and/or converting the file format. Supports all
performance log formats, including Windows NT 4.0 compressed logs.

Usage:
C:\Windows\SysWOW64\relog.exe <filename [filename ...]> 
                                [options]

Parameters:
  <filename [filename ...]>     Performance file to relog.

Options:
  -?                            Displays context sensitive help.
  -a                            Append output to the existing binary file.
  -c <path [path ...]>          Counters to filter from the input log.
  -cf <filename>                File listing performance counters to filter
                                from the input log. Default is all counters
                                in the original log file.
  -f <CSV|TSV|BIN|SQL>          Output file format.
  -t <value>                    Only write every nth record into the output
                                file. Default is to write every record.
  -o                            Output file path or SQL database.
  -b <M/d/yyyy h:mm:ss[AM|PM]>  Begin time for the first record to write into
                                the output file.
  -e <M/d/yyyy h:mm:ss[AM|PM]>  End time for the last record to write into
                                the output file.
  -config <filename>            Settings file containing command options.
  -q                            List performance counters in the input file.
  -y                            Answer yes to all questions without prompting.

Examples:
  relog logfile.csv -c "\Processor(_Total)\% Processor Time" -o logfile.blg
  relog logfile.blg -cf counters.txt -f bin
  relog logfile.blg -f csv -o logfile.csv -t 2
  relog logfile.blg -q -o counters.txt

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\relog.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Relog.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.546 (WinBuild.160101.0800)
* Product Version: 10.0.19041.546
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/2030c6509cee45e3629a9b47d09bd421b83f48f356ed597a03c89306610d720c/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\relog.exe](relog.exe-83A6C3AB58208C8B047E0C20261DBC77.md) | 96


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## relog

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Extracts performance counters from performance counter logs into other formats, such as text-TSV (for tab-delimited text), text-CSV (for comma-delimited text), binary-BIN, or SQL.

>[!NOTE]
>For more information about incorporating **relog** into your Windows Management Instrumentation (WMI) scripts, see the [Scripting blog](https://devblogs.microsoft.com/scripting/).

### Syntax

```
relog [<filename> [<filename> ...]] [/a] [/c <path> [<path> ...]] [/cf <filename>] [/f  {bin|csv|tsv|SQL}] [/t <value>] [/o {outputfile|DSN!CounterLog}] [/b <M/D/YYYY> [[<HH>:] <MM>:] <SS>] [/e <M/D/YYYY> [[<HH>:] <MM>:] <SS>] [/config {<filename>|i}] [/q]
```

#### Parameters

| Parameter | Description |
|--|--|
| `filename [filename ...]` | Specifies the pathname of an existing performance counter log. You can specify multiple input files. |
| -a | Appends output file instead of overwriting. This option does not apply to SQL format where the default is always to append. |
| -c `path [path ...]` | Specifies the performance counter path to log. To specify multiple counter paths, separate them with a space and enclose the counter paths in quotation marks (for example, `"path1 path2"`). |
| -cf filename | Specifies the pathname of the text file that lists the performance counters to be included in a relog file. Use this option to list counter paths in an input file, one per line. Default setting is all counters in the original log file are relogged. |
| -f `{bin | csv | tsv | SQL}` | Specifies the pathname of the output file format. The default format is **bin**. For a SQL database, the output file specifies the `DSN!CounterLog`. You can specify the database location by using the ODBC manager to configure the DSN (Database System Name). |
| -t value | Specifies sample intervals in *n* records. Includes every nth data point in the relog file. Default is every data point. |
| -o `{Outputfile | SQL:DSN!Counter_Log}` | Specifies the pathname of the output file or SQL database where the counters will be written. <P>**Note:** For the 64-bit and 32-bit versions of relog.exe, you must define a DSN in the ODBC Data Source (64-bit and 32-bit respectively) on the system. Use the "SQL Server" ODBC driver to define a DSN. |
| -b `<M/D/YYYY> [[<HH>:]<MM>:]<SS>]` | Specifies the beginning time to copy the first record from the input file. Date and time must be in this exact format M/D/YYYYHH:MM:SS. |
| -e `<M/D/YYYY> [[<HH>:]<MM>:]<SS>]` | Specifies the end time to copy the last record from the input file. Date and time must be in this exact format M/D/YYYYHH:MM:SS. |
| -config `{filename | i}` | Specifies the pathname of the settings file that contains command-line parameters. If you're using a configuration file, you can use **-i** as a placeholder for a list of input files that can be placed on the command line. If you're using the command line, don't use **-i**. You can also use wildcards, such as `*.blg` to specify several input file names at once. |
| -q | Displays the performance counters and time ranges of log files specified in the input file. |
| -y | Bypasses prompting by answering "yes" to all questions. |
| /? | Displays help at the command prompt. |

##### Remarks

- The general format for counter paths is as follows: `[\<computer>] \<object>[<parent>\<instance#index>] \<counter>]` where the parent, instance, index, and counter components of the format may contain either a valid name or a wildcard character. The computer, parent, instance, and index components aren't necessary for all counters.

- You determine the counter paths to use based on the counter itself. For example, the **LogicalDisk** object has an instance `<index>`, so you must provide the `<#index>` or a wildcard. Therefore, you could use the following format: `\LogicalDisk(*/*#*)\\*`.

- In comparison, the **Process** object doesn't require an instance `<index>`. Therefore, you can use the following format: `\Process(*)\ID Process`.

- If a wildcard character is specified in the **Parent** name, all instances of the specified object that match the specified instance and counter fields will be returned.

- If a wildcard character is specified in the **Instance** name, all instances of the specified object and parent object will be returned if all instance names corresponding to the specified index match the wildcard character.

- If a wildcard character is specified in the **Counter** name, all counters of the specified object are returned.

- Partial counter path string matches (for example, pro*) aren't supported.

- Counter files are text files that list one or more of the performance counters in the existing log. Copy the full counter name from the log or the **/q** output in `<computer>\<object>\<instance>\<counter>` format. List one counter path on each line.

- When run, the **relog** command copies specified counters from every record in the input file, converting the format if necessary. Wildcard paths are allowed in the counter file.

- Use the **/t** parameter to specify that input files are inserted into output files at intervals of every `nth` record. By default, data is relogged from every record.

- You can specify that your output logs include records from before the beginning time (that is, **/b**) to provide data for counters that require computation values of the formatted value. The output file will have the last records from input files with timestamps less than the **/e** (that is, end time) parameter.

- The contents of the setting file used with the **/config** option should have the following format: `<commandoption>\<value>`, where `<commandoption>` is a command line option and `<value>` specifies its value.

###Q# Examples

To resample existing trace logs at fixed intervals of 30, list counter paths, output files, and formats, type:

```
relog c:\perflogs\daily_trace_log.blg /cf counter_file.txt /o c:\perflogs\reduced_log.csv /t 30 /f csv
```

To resample existing trace logs at fixed intervals of 30, list counter paths, and output file, type:

```
relog c:\perflogs\daily_trace_log.blg /cf counter_file.txt /o c:\perflogs\reduced_log.blg /t 30
```

To resample existing trace logs into a database, type:

```
relog "c:\perflogs\daily_trace_log.blg" -f sql -o "SQL:sql2016x64odbc!counter_log"
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


