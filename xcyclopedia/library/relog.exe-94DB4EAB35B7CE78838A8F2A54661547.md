---
title: relog.exe | Performance Relogging Utility
---

# relog.exe 

* File Path: `C:\Windows\system32\relog.exe`
* Description: Performance Relogging Utility

## Hashes

Type | Hash
-- | --
MD5 | `94DB4EAB35B7CE78838A8F2A54661547`
SHA1 | `A7E3FEF221BFF555A5DF618365E091BEC06D2102`
SHA256 | `245C64930182B28134A2E2A79BB8A9601F00E41BEF9DFE345887C7FA5C346BCD`
SHA384 | `7DAD250182E65129A4F9AFE7974B485234AAFCBD7C2BB6C0BCDA644DED9C28CBA7933A8CCE859E5D0B86D87CBB338429`
SHA512 | `20DFFA31E45A2D46BF7AA210FBCAC7E176F900EBDC8862D43F6419DD157EA8538F2A365DD30E0B29CD2D0F63A169F0B18F69B4DAA1C207F7E6792BFD62FCC630`
SSDEEP | `1536:XJHh2xPFzVVJjZdr6wRLhDl4x6ILgw99Rid+OCY2s/5se8:qrBV9a4GUILVI+O52k5sj`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft r Relog.exe (10.0.19041.1)

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

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Relog.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## relog

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Extracts performance counters from performance counter logs into other formats, such as text-TSV (for tab-delimited text), text-CSV (for comma-delimited text), binary-BIN, or SQL.

### Syntax
```
relog [<FileName> [<FileName> ...]] [/a] [/c <path> [<path> ...]] [/cf <FileName>] [/f  {bin|csv|tsv|SQL}] [/t <Value>] [/o {OutputFile|DSN!CounterLog}] [/b <M/D/YYYY> [[<HH>:] <MM>:] <SS>] [/e <M/D/YYYY> [[<HH>:] <MM>:] <SS>] [/config {<FileName>|i}] [/q]
```

##### Parameters

|                                         Parameter                                          |                                                                                                                                                                  Description                                                                                                                                                                   |
|--------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                *FileName* [*FileName ...*]                                 |                                                                                                                      Specifies the pathname of an existing performance counter log. You can specify multiple input files.                                                                                                                      |
|                                             -a                                             |                                                                                                          Appends output file instead of overwriting. This option does not apply to SQL format where the default is always to append.                                                                                                           |
|                                   -c *path* [*path ...*]                                   |                                                       Specifies the performance counter path to log. To specify multiple counter paths, separate them with a space and enclose the counter paths in quotation marks (for example, **"**<em>Counterpath1</em> <em>Counterpath2</em>**"**)                                                       |
|                                       -cf *FileName*                                       |                                            Specifies the pathname of the text file that lists the performance counters to be included in a relog file. Use this option to list counter paths in an input file, one per line. Default setting is all counters in the original log file are relogged.                                            |
|                                  -f {bin\| csv\|tsv\|SQL}                                  |                                       Specifies the pathname of the output file format. The default format is **bin**. For a SQL database, the output file specifies the *DSN!CounterLog*. You can specify the database location by using the ODBC manager to configure the DSN (Database System Name).                                        |
|                                         -t *Value*                                         |                                                                                                           Specifies sample intervals in "*N*" records. Includes every nth data point in the relog file. Default is every data point.                                                                                                           |
| -o {*OutputFile* \| *"SQL:DSN!Counter_Log*} where DSN is a ODBC DSN defined on the system. |                                                   Specifies the pathname of the output file or SQL database where the counters will be written. <br>Note: For the 64-bit and 32-bit versions of Relog.exe, you need to define a DSN in the ODBC Data Source (64-bit and 32-bit respectively). Use the "SQL Server" ODBC driver to define a DSN                                                   |
|                          -b \<*M*/*D*/*YYYY*> [[*HH*:]*MM*:]*SS*                           |                                                                          Specifies begin time for copying first record from the input file. date and time must be in this exact format <em>M</em>**/**<em>D</em>**/**<em>YYYYHH</em>**:**<em>MM</em>**:**<em>SS</em>.                                                                          |
|                          -e \<*M*/*D*/*YYYY*> [[*HH*:]*MM*:]*SS*                           |                                                                           Specifies end time for copying last record from the input file. date and time must be in this exact format <em>M</em>**/**<em>D</em>**/**<em>YYYYHH</em>**:**<em>MM</em>**:**<em>SS</em>.                                                                            |
|                                -config {*FileName* \| *i*}                                 | Specifies the pathname of the settings file that contains command-line parameters. Use *-i* in the configuration file as a placeholder for a list of input files that can be placed on the command line. On the command line, however, you do not need to use *i*. You can also use wildcards such as \*.blg to specify many input file names. |
|                                             -q                                             |                                                                                                                          Displays the performance counters and time ranges of log files specified in the input file.                                                                                                                           |
|                                             -y                                             |                                                                                                                                            Bypasses prompting by answering "yes" to all questions.                                                                                                                                             |
|                                             /?                                             |                                                                                                                                                      Displays help at the command prompt.                                                                                                                                                      |

### Remarks
Counter path format:
- The general format for counter paths is as follows: [\\\<computer>] \\\<Object>[\<Parent>\\<Instance#Index>] \\\<Counter>] where the parent, instance, index, and counter components of the format may contain either a valid name or a wildcard character. The computer, parent, instance, and index components are not necessary for all counters.
- You determine the counter paths to use based on the counter itself. For example, the LogicalDisk object has an instance <Index>, so you must provide the <#index> or a wildcard. Therefore, you could use the following format: **\LogicalDisk(\*/\*#\*)\\\\***
- In comparison, the Process object does not require an instance \<Index>. Therefore, you could use the following format: **\Process(\*)\ID Process**
- If a wildcard character is specified in the parent name, all instances of the specified object that match the specified instance and counter fields will be returned.
- If a wildcard character is specified in the instance name, all instances of the specified object and parent object will be returned if all instance names corresponding to the specified index match the wildcard character.
- If a wildcard character is specified in the counter name, all counters of the specified object are returned.
- Partial counter path string matches (for example, pro*) are not supported.

Counter files:
-   Counter files are text files that list one or more of the performance counters in the existing log. Copy the full counter name from the log or the **/q** output in \<computer>\\\<Object>\\\<Instance>\\\<Counter> format. list one counter path on each line.

Copying counters:
-   When executed, **relog** copies specified counters from every record in the input file, converting the format if necessary. Wildcard paths are allowed in the counter file.
Saving input file subsets:
-   Use the **/t** parameter to specify that input files are inserted into output files at intervals of every <n>th record. By default, data is relogged from every record.
Using **/b** and **/e** parameters with log files
-   You can specify that your output logs include records from before begin-time (that is, **/b**) to provide data for counters that require computation values of the formatted value. The output file will have the last records from input files with timestamps less than the **/e** (that is, end time) parameter.
Using the **/config** option:
-   The contents of the setting file used with the **/config** option should have the following format:
    -   \<CommandOption>\\\<Value>, where \<CommandOption> is a command line option and \<Value> specifies its value.

For more information about incorporating **relog** into your Windows Management Instrumentation (WMI) scripts, see "Scripting WMI" at the [Microsoft Windows Resource Kits Web site](https://go.microsoft.com/fwlink/?LinkId=4665).

### Examples
To resample existing trace logs at fixed intervals of 30, list counter paths, output files and formats:
```
relog c:\perflogs\daily_trace_log.blg /cf counter_file.txt /o c:\perflogs\reduced_log.csv /t 30 /f csv
```
To resample existing trace logs at fixed intervals of 30, list counter paths and output file:
```
relog c:\perflogs\daily_trace_log.blg /cf counter_file.txt /o c:\perflogs\reduced_log.blg /t 30
```
To resample existing trace logs into a database use:
```
relog "c:\perflogs\daily_trace_log.blg" -f sql -o "SQL:sql2016x64odbc!counter_log"
```

### Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


