
# logman.exe 

* File Path: `C:\Windows\system32\logman.exe`
* Description: Performance Log Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `16F3C9E88811A304E23C2A8B0B9618ED`
SHA1 | `3312004370A3A05F70EC2DF7F242FBA50BA75321`
SHA256 | `58BF717313D23FFF632B6E8D8BB58A96DF2489C80F6FC2D4C8BFE499275FB483`
SHA384 | `AB9F3BAC2217E95CA00C1CE10043B6D7BFE5E88DC6A8D03209E68CB4C3645C29BEB3318C3184A7609242D5A7127E0E77`
SHA415 | `5DBD02D00AD3B81E97D3310B133ECD05F97B70719740032DBD3A9A37924B4081D43BA355B194A19A5AE06FBDE2D792239DE2A5518FB408CC669EBB40AE8AC96D`
SSDEEP | `1536:O1gLO54vPgHQYpWSg2AoRv8S+GgTI8mHuYHwQsjXK25apHm:5LOevPgVUSxAoXBKlxeGjX75a4`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft r Logman.exe (10.0.14393.0)

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
                                http://go.microsoft.com/fwlink/?LinkID=136464
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
  Microsoft TechNet - http://go.microsoft.com/fwlink/?LinkID=136332

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

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Logman.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


