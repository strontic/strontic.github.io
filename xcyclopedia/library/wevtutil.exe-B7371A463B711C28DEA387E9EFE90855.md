﻿---
title: wevtutil.exe | Eventing Command Line Utility
excerpt: What is wevtutil.exe?
---

# wevtutil.exe 

* File Path: `C:\Windows\system32\wevtutil.exe`
* Description: Eventing Command Line Utility

## Hashes

Type | Hash
-- | --
MD5 | `B7371A463B711C28DEA387E9EFE90855`
SHA1 | `552EB2AECB4B52FF6650F94BC949FCE05576C161`
SHA256 | `4A727688B939E08C26064EA08DCFF29B3D4608D28820874030524F79B4B1CCA8`
SHA384 | `51D747513F44472D2FC7ABFA119AFEE19E2B62629B8F44A7B71D043B56A28F40D4382488801D62159F3895DC17C4C86B`
SHA512 | `BA989B608CD7867137B73E9082D5C8E8FD8B85CF83201D2CF87C891460D517CC0BB9CE893237710B6F5C3F4D62B0470832967D1CA47F1B5FDCF6D1B7097ED688`
SSDEEP | `6144:3cg4TR2QnhitEh08GdHyo+s38AMd3LitqM:3f4TR2QnUc08od8nut`
IMP | `D3310B6271278C48FE7AE9F4AD5259B6`
PESHA1 | `1083BACDFC1EE2E2C60810150F6DA7D8828F88EB`
PE256 | `987890A48276DEFF86256F8BFCCFCFAF63D854CA510C066D0545874EBE40E41D`

## Runtime Data

### Usage (stdout):
```cmhg
Windows Events Command Line Utility.

Enables you to retrieve information about event logs and publishers, install
and uninstall event manifests, run queries, and export, archive, and clear logs.

Usage:

You can use either the short (for example, ep /uni) or long (for example, 
enum-publishers /unicode) version of the command and option names. Commands, 
options and option values are not case-sensitive.

Variables are noted in all upper-case.

wevtutil COMMAND [ARGUMENT [ARGUMENT] ...] [/OPTION:VALUE [/OPTION:VALUE] ...]

Commands:

el | enum-logs          List log names.
gl | get-log            Get log configuration information.
sl | set-log            Modify configuration of a log.
ep | enum-publishers    List event publishers.
gp | get-publisher      Get publisher configuration information.
im | install-manifest   Install event publishers and logs from manifest.
um | uninstall-manifest Uninstall event publishers and logs from manifest.
qe | query-events       Query events from a log or log file.
gli | get-log-info      Get log status information.
epl | export-log        Export a log.
al | archive-log        Archive an exported log.
cl | clear-log          Clear a log.

Common options:

/{r | remote}:VALUE
If specified, run the command on a remote computer. VALUE is the remote computer 
name. Options /im and /um do not support remote operations.

/{u | username}:VALUE
Specify a different user to log on to the remote computer. VALUE is a user name
in the form domain\user or user. Only applicable when option /r is specified.

/{p | password}:VALUE
Password for the specified user. If not specified, or if VALUE is "*", the user 
will be prompted to enter a password. Only applicable when the /u option is
specified.

/{a | authentication}:[Default|Negotiate|Kerberos|NTLM]
Authentication type for connecting to remote computer. The default is Negotiate.

/{uni | unicode}:[true|false]
Display output in Unicode. If true, then output is in Unicode. 

To learn more about a specific command, type the following:

wevtutil COMMAND /?

```

### Usage (stderr):
```cmhg
Command help is not supported.
The parameter is incorrect.

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wevtutil.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wevtutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/4a727688b939e08c26064ea08dcff29b3d4608d28820874030524f79b4b1cca8/detection


## Possible Misuse

*The following table contains possible examples of `wevtutil.exe` being misused. While `wevtutil.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_eventlog_cleared.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_eventlog_cleared.yml) | `description: One of the Windows Eventlogs has been cleared. e.g. caused by "wevtutil cl" command execution`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_susp_eventlog_cleared.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_system_susp_eventlog_cleared.yml) | `description: One of the Windows Eventlogs has been cleared. e.g. caused by "wevtutil cl" command execution`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_etw_trace_evasion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_etw_trace_evasion.yml) | `- https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/wevtutil`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_notpetya.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_notpetya.yml) | `description: Detects NotPetya ransomware activity in which the extracted passwords are passed back to the main module via named pipe, the file system journal of drive C is deleted and windows eventlogs are cleared using wevtutil`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- wevtutil.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'wevtutil.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\wevtutil.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_eventlog_clear.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_eventlog_clear.yml) | `title: Suspicious Eventlog Clear or Configuration Using Wevtutil`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_eventlog_clear.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_eventlog_clear.yml) | `description: Detects clearing or configuration of eventlogs using wevtutil, powershell and wmic. Might be used by ransomwares during the attack (seen by NotPetya and others).`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_eventlog_clear.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_eventlog_clear.yml) | `Image\|endswith: '\wevtutil.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \wevtutil.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_detection.yml) | `- '\wevtutil.exe' `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #5: Disable Event Logging with wevtutil [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #5: Disable Event Logging with wevtutil [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.001/T1070.001.md) | * <code>wevtutil cl system</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.001/T1070.001.md) | * <code>wevtutil cl application</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.001/T1070.001.md) | * <code>wevtutil cl security</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.001/T1070.001.md) | wevtutil cl #{log_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | - [Atomic Test #5 - Disable Event Logging with wevtutil](#atomic-test-5---disable-event-logging-with-wevtutil) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | ## Atomic Test #5 - Disable Event Logging with wevtutil | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | Wevtutil can be used to disable logs.  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | wevtutil sl "#{log_name}" /e:false | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | wevtutil sl "#{log_name}" /e:true | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $a = "wevtutil clear-log" ascii wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wilted_tulip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wilted_tulip.yar) | $s1 = "('wevtutil.exe el') DO (call :do_clear" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wilted_tulip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wilted_tulip.yar) | $s2 = "wevtutil.exe cl %1" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nopetya_jun17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nopetya_jun17.yar) | $x6 = "wevtutil cl Setup & wevtutil cl System" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_recon_indicators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_recon_indicators.yar) | $s18 = "wevtutil cl " ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## wevtutil



Enables you to retrieve information about event logs and publishers. You can also use this command to install and uninstall event manifests, to run queries, and to export, archive, and clear logs.

### Syntax

```
wevtutil [{el | enum-logs}] [{gl | get-log} <Logname> [/f:<Format>]]
[{sl | set-log} <Logname> [/e:<Enabled>] [/i:<Isolation>] [/lfn:<Logpath>] [/rt:<Retention>] [/ab:<Auto>] [/ms:<MaxSize>] [/l:<Level>] [/k:<Keywords>] [/ca:<Channel>] [/c:<Config>]]
[{ep | enum-publishers}]
[{gp | get-publisher} <Publishername> [/ge:<Metadata>] [/gm:<Message>] [/f:<Format>]] [{im | install-manifest} <Manifest>]
[{um | uninstall-manifest} <Manifest>] [{qe | query-events} <Path> [/lf:<Logfile>] [/sq:<Structquery>] [/q:<Query>] [/bm:<Bookmark>] [/sbm:<Savebm>] [/rd:<Direction>] [/f:<Format>] [/l:<Locale>] [/c:<Count>] [/e:<Element>]]
[{gli | get-loginfo} <Logname> [/lf:<Logfile>]]
[{epl | export-log} <Path> <Exportfile> [/lf:<Logfile>] [/sq:<Structquery>] [/q:<Query>] [/ow:<Overwrite>]]
[{al | archive-log} <Logpath> [/l:<Locale>]]
[{cl | clear-log} <Logname> [/bu:<Backup>]] [/r:<Remote>] [/u:<Username>] [/p:<Password>] [/a:<Auth>] [/uni:<Unicode>]
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|{el \| enum-logs}|Displays the names of all logs.|
|{gl \| get-log} \<Logname> [/f:\<Format>]|Displays configuration information for the specified log, which includes whether the log is enabled or not, the current maximum size limit of the log, and the path to the file where the log is stored.|
|{sl \| set-log} \<Logname> [/e:\<Enabled>] [/i:\<Isolation>] [/lfn:\<Logpath>] [/rt:\<Retention>] [/ab:\<Auto>] [/ms:\<MaxSize>] [/l:\<Level>] [/k:\<Keywords>] [/ca:\<Channel>] [/c:\<Config>]|Modifies the configuration of the specified log.|
|{ep \| enum-publishers}|Displays the event publishers on the local computer.|
|{gp \| get-publisher} \<Publishername> [/ge:\<Metadata>] [/gm:\<Message>] [/f:\<Format>]]|Displays the configuration information for the specified event publisher.|
|{im \| install-manifest} \<Manifest>|Installs event publishers and logs from a manifest. For more information about event manifests and using this parameter, see the Windows Event Log SDK at the Microsoft Developers Network (MSDN) Web site ([https://msdn.microsoft.com](../../index.yml)).|
|{um \| uninstall-manifest} \<Manifest>|Uninstalls all publishers and logs from a manifest. For more information about event manifests and using this parameter, see the Windows Event Log SDK at the Microsoft Developers Network (MSDN) Web site ([https://msdn.microsoft.com](../../index.yml)).|
|{qe \| query-events} \<Path> [/lf:\<Logfile>] [/sq:\<Structquery>] [/q:\<Query>] [/bm:\<Bookmark>] [/sbm:\<Savebm>] [/rd:\<Direction>] [/f:\<Format>] [/l:\<Locale>] [/c:\<Count>] [/e:\<Element>]|Reads events from an event log, from a log file, or using a structured query. By default, you provide a log name for \<Path>. However, if you use the **/lf** option, then \<Path> must be a path to a log file. If you use the **/sq** parameter, \<Path> must be a path to a file that contains a structured query.|
|{gli \| get-loginfo} \<Logname> [/lf:\<Logfile>]|Displays status information about an event log or log file. If the **/lf** option is used, \<Logname> is a path to a log file. You can run **wevtutil el** to obtain a list of log names.|
|{epl \| export-log} \<Path> \<Exportfile> [/lf:\<Logfile>] [/sq:\<Structquery>] [/q:\<Query>] [/ow:\<Overwrite>]|Exports events from an event log, from a log file, or using a structured query to the specified file. By default, you provide a log name for \<Path>. However, if you use the **/lf** option, then \<Path> must be a path to a log file. If you use the **/sq** option, \<Path> must be a path to a file that contains a structured query. \<Exportfile> is a path to the file where the exported events will be stored.|
|{al \| archive-log} \<Logpath> [/l:\<Locale>]|Archives the specified log file in a self-contained format. A subdirectory with the name of the locale is created and all locale-specific information is saved in that subdirectory. After the directory and log file are created by running **wevtutil al**, events in the file can be read whether the publisher is installed or not.|
|{cl \| clear-log} \<Logname> [/bu:\<Backup>]|Clears events from the specified event log. The **/bu** option can be used to back up the cleared events.|

### Options

|       Option       |                                                                                                                                                                                                                                                                 Description                                                                                                                                                                                                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    /f:\<Format>    |                                                                                                                                                               Specifies that the output should be either XML or text format. If \<Format> is XML, the output is displayed in XML format. If \<Format> is Text, the output is displayed without XML tags. The default is Text.                                                                                                                                                                |
|   /e:\<Enabled>    |                                                                                                                                                                                                                                         Enables or disables a log. \<Enabled> can be true or false.                                                                                                                                                                                                                                          |
|  /i:\<Isolation>   | Sets the log isolation mode. \<Isolation> can be system, application or custom. The isolation mode of a log determines whether a log shares a session with other logs in the same isolation class. If you specify system isolation, the target log will share at least write permissions with the System log. If you specify application isolation, the target log will share at least write permissions with the Application log. If you specify custom isolation, you must also provide a security descriptor by using the **/ca** option. |
|  /lfn:\<Logpath>   |                                                                                                                                                                                                           Defines the log file name. \<Logpath> is a full path to the file where the Event Log service stores events for this log.                                                                                                                                                                                                           |
|  /rt:\<Retention>  |                                                            Sets the log retention mode. \<Retention> can be true or false. The log retention mode determines the behavior of the Event Log service when a log reaches its maximum size. If an event log reaches its maximum size and the log retention mode is true, existing events are retained and incoming events are discarded. If the log retention mode is false, incoming events overwrite the oldest events in the log.                                                             |
|    /ab:\<Auto>     |                                                                                                                                   Specifies the log auto-backup policy. \<Auto> can be true or false. If this value is true, the log will be backed up automatically when it reaches the maximum size. If this value is true, the retention (specified with the **/rt** option) must also be set to true.                                                                                                                                    |
|   /ms:\<MaxSize>   |                                                                                                                                                                        Sets the maximum size of the log in bytes. The minimum log size is 1048576 bytes (1024KB) and log files are always multiples of 64KB, so the value you enter will be rounded off accordingly.                                                                                                                                                                         |
|    /l:\<Level>     |                                                                                                                                                                     Defines the level filter of the log. \<Level> can be any valid level value. This option is only applicable to logs with a dedicated session. You can remove a level filter by setting \<Level\> to 0.                                                                                                                                                                      |
|   /k:\<Keywords>   |                                                                                                                                                                                         Specifies the keywords filter of the log. \<Keywords> can be any valid 64 bit keyword mask. This option is only applicable to logs with a dedicated session.                                                                                                                                                                                         |
|   /ca:\<Channel>   |                                                                                                                   Sets the access permission for an event log. \<Channel> is a security descriptor that uses the Security Descriptor Definition Language (SDDL). For more information about SDDL format, see the Microsoft Developers Network (MSDN) Web site ([https://msdn.microsoft.com](../../index.yml)).                                                                                                                    |
|    /c:\<Config>    |                                                                                                                                  Specifies the path to a configuration file. This option will cause log properties to be read from the configuration file defined in \<Config>. If you use this option, you must not specify a \<Logname\> parameter. The log name will be read from the configuration file.                                                                                                                                   |
|  /ge:\<Metadata>   |                                                                                                                                                                                                                 Gets metadata information for events that can be raised by this publisher. \<Metadata> can be true or false.                                                                                                                                                                                                                 |
|   /gm:\<Message>   |                                                                                                                                                                                                                       Displays the actual message instead of the numeric message ID. \<Message> can be true or false.                                                                                                                                                                                                                        |
|   /lf:\<Logfile>   |                                                                                                                                                                                  Specifies that the events should be read from a log or from a log file. \<Logfile> can be true or false. If true, the parameter to the command is the path to a log file.                                                                                                                                                                                   |
| /sq:\<Structquery> |                                                                                                                                                                                Specifies that events should be obtained with a structured query. \<Structquery> can be true or false. If true, \<Path\> is the path to a file that contains a structured query.                                                                                                                                                                                |
|    /q:\<Query>     |                                                                                                                                                                     Defines the XPath query to filter the events that are read or exported. If this option is not specified, all events will be returned or exported. This option is not available when **/sq** is true.                                                                                                                                                                     |
|  /bm:\<Bookmark>   |                                                                                                                                                                                                                                 Specifies the path to a file that contains a bookmark from a previous query.                                                                                                                                                                                                                                 |
|   /sbm:\<Savebm>   |                                                                                                                                                                                                             Specifies the path to a file that is used to save a bookmark of this query. The file name extension should be .xml.                                                                                                                                                                                                              |
|  /rd:\<Direction>  |                                                                                                                                                                                                   Specifies the direction in which events are read. \<Direction> can be true or false. If true, the most recent events are returned first.                                                                                                                                                                                                   |
|    /l:\<Locale>    |                                                                                                                                                                                          Defines a locale string that is used to print event text in a specific locale. Only available when printing events in text format using the **/f** option.                                                                                                                                                                                          |
|    /c:\<Count>     |                                                                                                                                                                                                                                                  Sets the maximum number of events to read.                                                                                                                                                                                                                                                  |
|   /e:\<Element>    |                                                                                                                                                           Includes a root element when displaying events in XML. \<Element> is the string that you want within the root element. For example, **/e:root** would result in XML that contains the root element pair \<root></root>.                                                                                                                                                            |
|  /ow:\<Overwrite>  |                                                                                                                                                                 Specifies that the export file should be overwritten. \<Overwrite> can be true or false. If true, and the export file specified in \<Exportfile\> already exists, it will be overwritten without confirmation.                                                                                                                                                                 |
|   /bu:\<Backup>    |                                                                                                                                                                                                      Specifies the path to a file where the cleared events will be stored. Include the .evtx extension in the name of the backup file.                                                                                                                                                                                                       |
|    /r:\<Remote>    |                                                                                                                                                                                            Runs the command on a remote computer. \<Remote> is the name of the remote computer. The **im** and **um** parameters do not support remote operation.                                                                                                                                                                                            |
|   /u:\<Username>   |                                                                                                                                                                          Specifies a different user to log on to a remote computer. \<Username> is a user name in the form domain\user or user. This option is only applicable when the **/r** option is specified.                                                                                                                                                                          |
|   /p:\<Password>   |                                                                                                                                               Specifies the password for the user. If the **/u** option is used and this option is not specified or \<Password> is \*, the user will be prompted to enter a password. This option is only applicable when the **/u** option is specified.                                                                                                                                                |
|     /a:\<Auth>     |                                                                                                                                                                                             Defines the authentication type for connecting to a remote computer. \<Auth> can be Default, Negotiate, Kerberos or NTLM. The default is Negotiate.                                                                                                                                                                                              |
|  /uni:\<Unicode>   |                                                                                                                                                                                                             Displays the output in Unicode. \<Unicode> can be true or false. If \<Unicode\> is true then the output is in Unicode.                                                                                                                                                                                                             |

### Remarks

-   Using a configuration file with the sl parameter

    The configuration file is an XML file with the same format as the output of wevtutil gl \<Logname> /f:xml. To shows the format of a configuration file that enables retention, enables autobackup, and sets the maximum log size on the Application log:
    ```
    <?xml version=1.0 encoding=UTF-8?>
    <channel name=Application isolation=Application
    xmlns=https://schemas.microsoft.com/win/2004/08/events>
    <logging>
    <retention>true</retention>
    <autoBackup>true</autoBackup>
    <maxSize>9000000</maxSize>
    </logging>
    <publishing>
    </publishing>
    </channel>
    ```

### Examples

List the names of all logs:
```
wevtutil el
```
Display configuration information about the System log on the local computer in XML format:
```
wevtutil gl System /f:xml
```
Use a configuration file to set event log attributes (see Remarks for an example of a configuration file):
```
wevtutil sl /c:config.xml
```
Display information about the Microsoft-Windows-Eventlog event publisher, including metadata about the events that the publisher can raise:
```
wevtutil gp Microsoft-Windows-Eventlog /ge:true
```
Install publishers and logs from the myManifest.xml manifest file:
```
wevtutil im myManifest.xml
```
Uninstall publishers and logs from the myManifest.xml manifest file:
```
wevtutil um myManifest.xml
```
Display the three most recent events from the Application log in textual format:
```
wevtutil qe Application /c:3 /rd:true /f:text
```
Display the status of the Application log:
```
wevtutil gli Application
```
Export events from System log to C:\backup\system0506.evtx:
```
wevtutil epl System C:\backup\system0506.evtx
```
Clear all of the events from the Application log after saving them to C:\admin\backups\a10306.evtx:
```
wevtutil cl Application /bu:C:\admin\backups\a10306.evtx
```

##### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


