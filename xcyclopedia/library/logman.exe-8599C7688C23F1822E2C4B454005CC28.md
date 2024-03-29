﻿---
title: logman.exe | Performance Log Utility
excerpt: What is logman.exe?
---

# logman.exe 

* File Path: `C:\Windows\system32\logman.exe`
* Description: Performance Log Utility

## Hashes

Type | Hash
-- | --
MD5 | `8599C7688C23F1822E2C4B454005CC28`
SHA1 | `04A320BBDB623BBCDC84D99DA3A5118AEFCD80B3`
SHA256 | `2E40AC8FECF1FF562DE9AAFAEA5192985AC3CC13BE32B508771C885FD43673DA`
SHA384 | `C7691C4E1506D489DCA966AE98BF2AD6064BCA081494CFCCAE08D7230A4681F2349477ED3AC7B2E3652D9D207DF3465C`
SHA512 | `A41086312DC2433B0071350F374ABC66345FE97F2F13C1ECDC232ED8C1B86B94FF11CB1A7A2E646ABD280349CD42D9DF8E4E3B5A9CFC5812C5022955740C5A6E`
SSDEEP | `1536:w/6DGGrJK5ZYkP7poyR4XlGX/lgxnHXKYT2OXmHuYHwMy3O2KY2naCigXly:w0X9kN94XligXDNxecFKRnaD7`
IMP | `6B33B29610D8D91ACB7A22E2E6972E9D`
PESHA1 | `A43AE8D4C7B9BAAB58097C80241BCC278F6248F7`
PE256 | `F71CBF478C814AE710EC8F6587048A8667A6990C6BC767CD4DE8A8758233E336`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft r Logman.exe (10.0.17763.1)

Usage:
  C:\Windows\system32\logman.exe [create|query|start|stop|delete|update|import|export] [options]

Verbs:
  create                        Create a new data collector.
  query                         Query data collector properties. If no name
                                is given all data collectors are listed.
  start                         Start an existing data collector and set the
                                begin time to manual.
  stop                          Stop an existing data collector and set the
                                end time to manual.
  delete                        Delete an existing data collector.
  update                        Update an existing data collector's properties.
  import                        Import a data collector set from an XML file.
  export                        Export a data collector set to an XML file.

Adverbs:
  counter                       Create a counter data collector.
  trace                         Create a trace data collector.
  alert                         Create an alert data collector.
  cfg                           Create a configuration data collector.
  providers                     Show registered providers.

Options (counter):
  -c <path [path [...]]>        Performance counters to collect.
  -cf <filename>                File listing performance counters to collect,
                                one per line.
  -f <bin|bincirc|csv|tsv|sql>  Specifies the log format for the data
                                collector. For SQL database format, you must
                                use the -o option in the command line with
                                the DNS!log option. The defaults is binary.
  -sc <value>                   Maximum number of samples to collect with a
                                performance counter data collector.
  -si <[[hh:]mm:]ss>            Sample interval for performance counter data
                                collectors.

Options (trace):
  -f <bin|bincirc|csv|tsv|sql>  Specifies the log format for the data
                                collector. For SQL database format, you must
                                use the -o option in the command line with
                                the DNS!log option. The defaults is binary.
  -mode <trace_mode>            Event Trace Session logger mode. For more
                                information visit -
                                https://go.microsoft.com/fwlink/?LinkID=136464
  -ct <perf|system|cycle>       Specifies the clock resolution to use when
                                logging the time stamp for each event. You
                                can use query performance counter, system
                                time, or CPU cycle.
  -ln <logger_name>             Logger name for Event Trace Sessions.
  -ft <[[hh:]mm:]ss>            Event Trace Session flush timer.
  -[-]p <provider [flags [level]]> A single Event Trace provider to enable.
                                The terms 'Flags' and 'Keywords' are
                                synonymous in this context.
  -pf <filename>                File listing multiple Event Trace providers
                                to enable.
  -[-]rt                        Run the Event Trace Session in real-time mode.
  -[-]ul                        Run the Event Trace Session in user mode.
  -bs <value>                   Event Trace Session buffer size in kb.
  -nb <min max>                 Number of Event Trace Session buffers.

Options (alert):
  -[-]el                        Enable/Disable event log reporting.
  -th <threshold [threshold [...]]> Specify counters and their threshold
                                values for and alert.
  -[-]rdcs <name>               Data collector set to start when alert fires.
  -[-]tn <task>                 Task to run when alert fires.
  -[-]targ <argument>           Task arguments.
  -si <[[hh:]mm:]ss>            Sample interval for performance counter data
                                collectors.

Options (cfg):
  -[-]ni                        Enable/Disable network interface query.
  -reg <path [path [...]]>      Registry values to collect.
  -mgt <query [query [...]]>    WMI objects to collect.
  -ftc <path [path [...]]>      Full path to the files to collect.

Options:
  -?                            Displays context sensitive help.
  -s <computer>                 Perform the command on specified remote system.
  -config <filename>            Settings file containing command options.
  [-n] <name>                   Name of the target object.
  -pid <pid>                    Process identifier.
  -xml <filename>               Name of the XML file to import or export.
  -as                           Perform the requested operation asynchronously.
  -[-]u <user [password]>       User to Run As. Entering a * for the password
                                produces a prompt for the password. The
                                password is not displayed when you type it at
                                the password prompt.
  -m <[start] [stop]>           Change to manual start or stop instead of a
                                scheduled begin or end time.
  -rf <[[hh:]mm:]ss>            Run the data collector for the specified
                                period of time.
  -b <M/d/yyyy h:mm:ss[AM|PM]>  Begin the data collector at specified time.
  -e <M/d/yyyy h:mm:ss[AM|PM]>  End the data collector at specified time.
  -o <path|dsn!log>             Path of the output log file or the DSN and
                                log set name in a SQL database. The default
                                path is '%systemdrive%\PerfLogs\Admin'.
  -[-]r                         Repeat the data collector daily at the
                                specified begin and end times.
  -[-]a                         Append to an existing log file.
  -[-]ow                        Overwrite an existing log file.
  -[-]v <nnnnnn|mmddhhmm>       Attach file versioning information to the end
                                of the log name.
  -[-]rc <task>                 Run the command specified each time the log
                                is closed.
  -[-]max <value>               Maximum log file size in MB or number of
                                records for SQL logs.
  -[-]cnf <[[hh:]mm:]ss>        Create a new file when the specified time has
                                elapsed or when the max size is exceeded.
  -y                            Answer yes to all questions without prompting.
  -fd                           Flushes all the active buffers of an existing
                                Event Trace Session to disk.
  -ets                          Send commands to Event Trace Sessions
                                directly without saving or scheduling.

Note:
  Where [-] is listed, an extra - negates the option.
  For example --u turns off the -u option.

More Information:
  Microsoft TechNet - https://go.microsoft.com/fwlink/?LinkID=136332

Examples:
  logman start perf_log
  logman update perf_log -si 10 -f csv -v mmddhhmm
  logman create counter perf_log -c "\Processor(_Total)\% Processor Time"
  logman create counter perf_log -c "\Processor(_Total)\% Processor Time" -max 10 -rf 01:00
  logman create trace trace_log -nb 16 256 -bs 64 -o c:\logfile
  logman create alert new_alert -th "\Processor(_Total)\% Processor Time>50"
  logman create cfg cfg_log -reg "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\\"
  logman create cfg cfg_log -mgt "root\cimv2:SELECT * FROM Win32_OperatingSystem"
  logman query providers
  logman query providers Microsoft-Windows-Diagnostics-Networking
  logman start process_trace -p Microsoft-Windows-Kernel-Process 0x10 win:Informational -ets
  logman start usermode_trace -p "Service Control Manager Trace" -ul -ets
  logman query usermode_trace -p "Service Control Manager Trace" -ul -ets
  logman stop usermode_trace -p "Service Control Manager Trace" -ul -ets
  logman start process_trace -p Microsoft-Windows-Kernel-Process -mode newfile -max 1 -o output%d.etl -ets
  logman start "NT Kernel Logger" -o log.etl -ets
  logman start "NT Kernel Logger" -p "Windows Kernel Trace" (process,thread) -ets

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\logman.exe |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\system32\SspiCli.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Logman.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/2e40ac8fecf1ff562de9aafaea5192985ac3cc13be32b508771c885fd43673da/detection/


## Possible Misuse

*The following table contains possible examples of `logman.exe` being misused. While `logman.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_trace_evasion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_etw_trace_evasion.yml) | `- "logman" `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_disable_eventlog.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_disable_eventlog.yml) | `description: Detects command that is used to disable or delete Windows eventlog via logman Windows utility`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_disable_eventlog.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_disable_eventlog.yml) | `- https://ss64.com/nt/logman.html`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_disable_eventlog.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_disable_eventlog.yml) | `- 'logman '`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## logman

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Creates and manages Event Trace Session and Performance logs and supports many functions of Performance Monitor from the command line.

### Syntax

```
logman [create | query | start | stop | delete| update | import | export | /?] [options]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| [logman create](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/logman-create.md) | Creates a counter, trace, configuration data collector, or API. |
| [logman query](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/logman-query.md) | Queries data collector properties. |
| [logman start &#124; stop](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/logman-start-stop.md) | Starts or stops data collection. |
| [logman delete](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/logman-delete.md) | Deletes an existing data collector. |
| [logman update](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/logman-update.md) | Updates the properties of an existing data collector. |
| [logman import &#124; export](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/logman-import-export.md) | Imports a data collector set from an XML file or export a data collector set to an XML file. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


