---
title: relog.exe | Performance Relogging Utility
---

# relog.exe 

* File Path: `C:\windows\system32\relog.exe`
* Description: Performance Relogging Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B086A07457B6E0FA73EF7D16992123E8`
SHA1 | `D4CCAECABDC211EC79C3DB948503DFB7BA301FEF`
SHA256 | `E662B75446E5367566FEF260E523F346D5D6D690443395A05F0E587C8F36D366`
SHA384 | `EE0072C6DC2C35889995EF716072F3A0B16064498F8BAE4C69793CD9E4C0C25B20645C130D62F54DA2B6928B8E993114`
SHA512 | `E9AC98DA5FC70D0E768047ECE71BE49C5826E95ACF910F4CAD9A09D68EDFB46D9DBC2D5BF1313071665462384002D9C9854519356AECDF1E5C1E724D27569092`
SSDEEP | `768:VTYCeqPU08TikDi4fO6Z8Np+7ikmh5Aod1SZeY1uNRZN+82NsjFVlaOktpncnxpa:VTYPDiVQ8N82kEr1SZR1uDl2NqzKNUx4`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\relog.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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


