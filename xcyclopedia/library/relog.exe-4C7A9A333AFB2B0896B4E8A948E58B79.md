﻿---
title: relog.exe | Performance Relogging Utility
excerpt: What is relog.exe?
---

# relog.exe 

* File Path: `C:\Windows\system32\relog.exe`
* Description: Performance Relogging Utility

## Hashes

Type | Hash
-- | --
MD5 | `4C7A9A333AFB2B0896B4E8A948E58B79`
SHA1 | `948FEBD5456420916256FCC94E3ED19AAFE5390B`
SHA256 | `100AF46C952E58105DBC51EB92510F6990377A3FFC57E82074A8BFB64C56C529`
SHA384 | `01D078341EF753B90A6737429F665524C16F1CED299F33048EB7B285BFEB66E3F2384B307218DF78BA0FEF3CC7B6B6CC`
SHA512 | `2FBB960AAA2322F0BD5BC14096F9640F0AEAD480BEAB9DF687837516B7EE898E1A2B3C14FFD34BA663B0F11AC1B4B0EA81850AC92176903F324D38D1BADD872D`
SSDEEP | `768:mC+N6nlPSz0JPC/3c6f7Jl1/zdBNZj99mNUkiyDvkejoLWoe3F22Ms/qc/:7+HMUl5zbNB99mNUkiy4KWWTF2U/qc/`
IMP | `6043170F48FA2A2802231975BB43BBDA`
PESHA1 | `F7D903EBBB41E638AB9406B1AAC947604E2C4049`
PE256 | `8475E6AFC739930ADDAEB208656E9F648A42A43761913D6E00169945B73BD074`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft r Relog.exe (10.0.17763.1)

Relog creates new performance logs from data in existing performance logs by
changing the sampling rate and/or converting the file format. Supports all
performance log formats, including Windows NT 4.0 compressed logs.

Usage:
C:\Windows\system32\relog.exe <filename [filename ...]> 
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
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\pdh.dll |
C:\Windows\system32\relog.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Relog.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/100af46c952e58105dbc51eb92510f6990377a3ffc57e82074a8bfb64c56c529/detection/



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


