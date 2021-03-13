---
title: tracerpt.exe | Event Trace Report Tool
excerpt: What is tracerpt.exe?
---

# tracerpt.exe 

* File Path: `C:\Windows\SysWOW64\tracerpt.exe`
* Description: Event Trace Report Tool

## Hashes

Type | Hash
-- | --
MD5 | `1A5BC85BE140A2D7E6DE64EF2ECF3441`
SHA1 | `708B4AD7640BEC86C1F1951BD07DB18088A7B4AE`
SHA256 | `A632C902E1E1161B19EC43D3A9F8B325A47E8F1F063B6396C8BE43AEFB88E8BC`
SHA384 | `1B0FD065B7E8A11F0F52DC2184FE526C44198120299B8DA9CF725D35113C52BF78B5111CB44E5550854116421B06E963`
SHA512 | `EA455876E382D3A925032EE516A59F8AA2D6B79DC588623A527D0EB30D343D8AEB3B5C93BC1D74E7BAA3DF455E879FE1B9F3BBFAA05EF9DC4CC3005756052471`
SSDEEP | `6144:l0H/soILQHvuuV1Ynuslq57WVsEanDbGBe:ufsoIgHYusE5SHaDbGBe`
IMP | `7835E3A9354323D36EDE92465DE72126`
PESHA1 | `9257217FE1FF6B4EED8B02851B64F739ACBD855A`
PE256 | `DE9F40AF1F62D70AB73F6E6A262405616B888F34F094C87EEBD4B9F4C76B849E`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft r TraceRpt.Exe (10.0.19041.546)

Usage:
  C:\Windows\SysWOW64\tracerpt.exe <[-l] <value [value [...]]>|-rt <session_name [session_name [...]]>> [options]

Options:
  -?                            Displays context sensitive help.
  -config <filename>            Settings file containing command options.
  -y                            Answer yes to all questions without prompting.
  -f <XML|HTML>                 Report format.
  -of <CSV|EVTX|XML>            Dump format, the default is XML.
  -en <ANSI|Unicode>            Output file encoding. Only allowed with CSV
                                output format.
  -df <filename>                Microsoft specific counting/reporting schema
                                file.
  -import <filename [filename [...]]> Event Schema import file.
  -int <filename>               Dump interpreted event structure into
                                specified file.
  -rts                          Report raw timestamp in event trace header. 
                                Can only be used with -o, not -report or
                                -summary.
  -tmf <filename>               Trace Message Format definition file
  -tp <value>                   TMF file search path.  Multiple paths can be
                                used, separated with ';'.
  -i <value>                    Specifies the provider image path.  The
                                matching PDB will be located in the Symbol
                                Server. Multiple paths can be used, separated
                                with ';'.
  -pdb <value>                  Specifies the symbol server path.  Multiple
                                paths can be used, separated with ';'.
  -gmt                          Convert WPP payload timestamps to GMT time
  -rl <value>                   System Report Level from 1 to 5, the default
                                value is 1.
  -summary [filename]           Summary report text file. Default is
                                summary.txt.
  -o [filename]                 Text output file. Default is dumpfile.xml.
  -report [filename]            Text output report file. Default is
                                workload.xml.
  -lr                           Less restrictive; use best effort for events
                                not matching event schema.
  -export [filename]            Event Schema export file. Default is
                                schema.man.
  [-l] <value [value [...]]>    Event Trace log file to process.
  -rt <session_name [session_name [...]]> Real-time Event Trace Session data
                                source.

Examples:
  tracerpt logfile1.etl logfile2.etl -o logdump.xml -of XML
  tracerpt logfile.etl -o logdmp.xml -of XML -lr -summary logdmp.txt -report logrpt.xml
  tracerpt logfile1.etl logfile2.etl -o -report
  tracerpt logfile.etl counterfile.blg -report logrpt.xml -df schema.xml
  tracerpt -rt "NT Kernel Logger" -o logfile.csv -of CSV


```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\tracerpt.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TraceRpt.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.546 (WinBuild.160101.0800)
* Product Version: 10.0.19041.546
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/a632c902e1e1161b19ec43d3a9f8b325a47e8f1f063b6396c8be43aefb88e8bc/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tracerpt

The **tracerpt** command parses Event Trace Logs, log files generated by Performance Monitor, and real-time Event Trace providers. It also generates dump files, report files, and report schemas.

### Syntax

```
tracerpt <[-l] <value [value [...]]>|-rt <session_name [session_name [...]]>> [options]
```

#### Parameters

| Parameters | Description |
|--|--|
| -config `<filename>` | Specifies which settings file to load, which includes your command options. |
| -y | Specifies to answer **yes** to all questions, without prompting. |
| -f `<XML | HTML>` | Specifies the report file format. |
| -of `<CSV | EVTX | XML>` | Specifies the dump file format. The default is **XML*. |
| -df `<filename>` | Specifies to create a Microsoft-specific counting/reporting schema file. |
| -int `<filename>` | Specifies to dump the interpreted event structure to the specified file. |
| -rts | Specifies to add the report raw timestamp in the event trace header. Can only be used with **-o**. It's not supported with **-report** or **-summary**. |
| -tmf `<filename>` | Specifies which Trace Message Format definition file to use. |
| -tp `<value>` | Specifies the TMF file search path. Multiple paths may be used, separated by a semicolon (;). |
| -i `<value>` | Specifies the provider image path. The matching PDB will be located in the Symbol Server. Multiple paths can be used, separated by a semicolon (;). |
| -pdb `<value>` | Specifies the symbol server path. Multiple paths can be used, separated by a semicolon (;). |
| -gmt | Specifies to convert WPP payload timestamps to Greenwich Mean Time. |
| -rl `<value>` | Specifies the System Report Level from 1 to 5. Default is *1*. |
| -summary [filename] | Specifies to create a summary report text file. The filename, if not specified, is *summary.txt*. |
| -o [filename] | Specifies to create a text output file. The filename, if not specified, is *dumpfile.xml*. |
| -report [filename] | Specifies to create a text output report file. The filename, if not specified, is *workload.xml*. |
| -lr | Specifies to be less restrictive. This uses best efforts for events that don't match the events schema. |
| -export [filename] | Specifies to create an Event Schema export file. The filename, if not specified, is *schema.man*. |
| [-l] `<value [value [â€¦]]>` | Specifies the Event Trace log file to process. |
| -rt `<session_name [session_name [â€¦]]>` | Specifies the Real-time Event Trace Session data sources. |
| -? | Displays help at the command prompt. |

### Examples

To create a report based on the two event logs *logfile1.etl* and *logfile2.etl*, and to create the dump file *logdump.xml* in *XML* format, type:

```
tracerpt logfile1.etl logfile2.etl -o logdump.xml -of XML
```

To create a report based on the event log *logfile.etl*, to create the dump file *logdmp.xml* in XML format, to use best efforts to identify events not in the schema, and to produce a summary report file *logdump.txt* and a report file, *logrpt.xml*, type:

```
tracerpt logfile.etl -o logdmp.xml -of XML -lr -summary logdmp.txt -report logrpt.xml
```

To use the two event logs *logfile1.etl* and *logfile2.etl* to produce a dump file, and to report file with the default filenames, type:

```
tracerpt logfile1.etl logfile2.etl -o -report
```

To use the event log *logfile.etl* and the performance log *counterfile.blg* to produce the report file *logrpt.xml* and the Microsoft-specific XML schema file *schema.xml*, type:

```
tracerpt logfile.etl counterfile.blg -report logrpt.xml -df schema.xml
```

To read the real-time Event Trace Session NT Kernel Logger and to produce the dump file *logfile.csv* in *CSV* format, type:

```
tracerpt -rt NT Kernel Logger -o logfile.csv -of CSV
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


