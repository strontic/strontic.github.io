---
title: relog.exe | Performance Relogging Utility
excerpt: What is relog.exe?
---

# relog.exe 

* File Path: `C:\windows\SysWOW64\relog.exe`
* Description: Performance Relogging Utility

## Hashes

Type | Hash
-- | --
MD5 | `360B18A3C1D4829270E1C362B136B139`
SHA1 | `D6CDC62CC645EB81515F2AADEC8F888150C7FE33`
SHA256 | `9C3B9DEF86E340419C324EBD3DE0C6F3C9A97694CEBBFC3224F94BEC30B7E098`
SHA384 | `6DDB2E4C85BDCBB51F969E4871F474ED1FCE2F55B60863C55F3A356E4A007679161F9AC8554520D499287948361FA907`
SHA512 | `737130AA6CE4152BC87D37E10B18D52818117D8CE498DB9B71DA1BD34918EBB9C5F014D6A7901C256A1D59B6C06136FA0632CE0B053CE7E21395769E7CAEB421`
SSDEEP | `768:55Ye2jWct8gE/jtiUOlgc2GNdrXOcq57rWjupScIXMC8VW:55YXjWwEpiUL96SgbXMC8A`

## Signature

* Status: The file C:\windows\SysWOW64\relog.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Relog.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




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


