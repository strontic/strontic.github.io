---
title: MSBuild.exe | MSBuild.exe
excerpt: What is MSBuild.exe?
---

# MSBuild.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\MSBuild.exe`
* Description: MSBuild.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `3AEEA43956FF3F7ECF57ADF4C9524241`
SHA1 | `EE70D325FC52480B278D37A10C13156B325F8285`
SHA256 | `B25346AC48099606DE4BD7F72A4E76876587AADF5734EAA83B81B9E79437ACAB`
SHA384 | `9A4ED376D3BEBCF3578E17F40319DCED5538778111875F5E00D40CFE796B5CF27BD8BAB149897B1CCB178EC295819CCB`
SHA512 | `BA30E86D28DEA8AD5BE47455CA35582E8CED5F305DB56718B906202FEDDD9AA3F31775EC0E9F433265942AF6EE0D343ED6FBC5DFF87B0E0781767B56D9808C9F`
SSDEEP | `3072:ca0t0yH5wC7TwqPNi/X77NLpj/Wnqv7w2XpFU4rwOeVubZSpf02RFi3hrnL:L0ny8cKw/X7Rpqn+RXf2p02bi3xL`
PESHA1 | `028D75CB5B5761EA383B981F6F0108A3DEDFA550`
PE256 | `2C575F8C1EBEDE91EC391CCCE3108F92CA8922FC4C80C46894DB938CB62178F2`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Build Engine version 4.8.4161.0
[Microsoft .NET Framework, version 4.0.30319.42000]
Copyright (C) Microsoft Corporation. All rights reserved.

Syntax:              MSBuild.exe [options] [project file]

Description:         Builds the specified targets in the project file. If
                     a project file is not specified, MSBuild searches the
                     current working directory for a file that has a file
                     extension that ends in "proj" and uses that file.

Switches:

  /target:<targets>  Build these targets in this project. Use a semicolon or a
                     comma to separate multiple targets, or specify each
                     target separately. (Short form: /t)
                     Example:
                       /target:Resources;Compile

  /property:<n>=<v>  Set or override these project-level properties. <n> is
                     the property name, and <v> is the property value. Use a
                     semicolon or a comma to separate multiple properties, or
                     specify each property separately. (Short form: /p)
                     Example:
                       /property:WarningLevel=2;OutDir=bin\Debug\

  /maxcpucount[:n]   Specifies the maximum number of concurrent processes to 
                     build with. If the switch is not used, the default
                     value used is 1. If the switch is used without a value
                     MSBuild will use up to the number of processors on the 
                     computer. (Short form: /m[:n])
      
  /toolsversion:<version>
                     The version of the MSBuild Toolset (tasks, targets, etc.)
                     to use during build. This version will override the 
                     versions specified by individual projects. (Short form: 
                     /tv)
                     Example:
                       /toolsversion:3.5
   
  /verbosity:<level> Display this amount of information in the event log.
                     The available verbosity levels are: q[uiet], m[inimal],
                     n[ormal], d[etailed], and diag[nostic]. (Short form: /v)
                     Example:
                       /verbosity:quiet

  /consoleloggerparameters:<parameters>
                     Parameters to console logger. (Short form: /clp)
                     The available parameters are:
                        PerformanceSummary--Show time spent in tasks, targets
                            and projects.
                        Summary--Show error and warning summary at the end.
                        NoSummary--Don't show error and warning summary at the
                            end.
                        ErrorsOnly--Show only errors.
                        WarningsOnly--Show only warnings.
                        NoItemAndPropertyList--Don't show list of items and
                            properties at the start of each project build.    
                        ShowCommandLine--Show TaskCommandLineEvent messages  
                        ShowTimestamp--Display the Timestamp as a prefix to any
                            message.                                           
                        ShowEventId--Show eventId for started events, finished 
                            events, and messages
                        ForceNoAlign--Does not align the text to the size of
                            the console buffer
                        DisableConsoleColor--Use the default console colors
                            for all logging messages.
                        DisableMPLogging-- Disable the multiprocessor
                            logging style of output when running in 
                            non-multiprocessor mode.
                        EnableMPLogging--Enable the multiprocessor logging
                            style even when running in non-multiprocessor
                            mode. This logging style is on by default. 
                        Verbosity--overrides the /verbosity setting for this
                            logger.
                     Example:
                        /consoleloggerparameters:PerformanceSummary;NoSummary;
                                                 Verbosity=minimal

  /noconsolelogger   Disable the default console logger and do not log events
                     to the console. (Short form: /noconlog)

  /fileLogger[n]     Logs the build output to a file. By default
                     the file is in the current directory and named 
                     "msbuild[n].log". Events from all nodes are combined into
                     a single log. The location of the file and other
                     parameters for the fileLogger can be specified through 
                     the addition of the "/fileLoggerParameters[n]" switch.
                     "n" if present can be a digit from 1-9, allowing up to 
                     10 file loggers to be attached. (Short form: /fl[n])
    
  /fileloggerparameters[n]:<parameters>                                
                     Provides any extra parameters for file loggers.
                     The presence of this switch implies the 
                     corresponding /filelogger[n] switch.
                     "n" if present can be a digit from 1-9.
                     /fileloggerparameters is also used by any distributed
                     file logger, see description of /distributedFileLogger.
                     (Short form: /flp[n])
                     The same parameters listed for the console logger are
                     available. Some additional available parameters are:
                        LogFile--path to the log file into which the
                            build log will be written.
                        Append--determines if the build log will be appended
                            to or overwrite the log file. Setting the
                            switch appends the build log to the log file;
                            Not setting the switch overwrites the 
                            contents of an existing log file. 
                            The default is not to append to the log file.
                        Encoding--specifies the encoding for the file, 
                            for example, UTF-8, Unicode, or ASCII
                     Default verbosity is Detailed.
                     Examples:
                       /fileLoggerParameters:LogFile=MyLog.log;Append;
                                           Verbosity=diagnostic;Encoding=UTF-8

                       /flp:Summary;Verbosity=minimal;LogFile=msbuild.sum 
                       /flp1:warningsonly;logfile=msbuild.wrn 
                       /flp2:errorsonly;logfile=msbuild.err
    
  /distributedlogger:<central logger>*<forwarding logger>                     
                     Use this logger to log events from MSBuild, attaching a
                     different logger instance to each node. To specify
                     multiple loggers, specify each logger separately. 
                     (Short form /dl)
                     The <logger> syntax is:
                       [<logger class>,]<logger assembly>[;<logger parameters>]
                     The <logger class> syntax is:
                       [<partial or full namespace>.]<logger class name>
                     The <logger assembly> syntax is:
                       {<assembly name>[,<strong name>] | <assembly file>}
                     The <logger parameters> are optional, and are passed
                     to the logger exactly as you typed them. (Short form: /l)
                     Examples:
                       /dl:XMLLogger,MyLogger,Version=1.0.2,Culture=neutral
                       /dl:MyLogger,C:\My.dll*ForwardingLogger,C:\Logger.dll

  /distributedFileLogger                                                       
                     Logs the build output to multiple log files, one log file
                     per MSBuild node. The initial location for these files is
                     the current directory. By default the files are called 
                     "MSBuild<nodeid>.log". The location of the files and
                     other parameters for the fileLogger can be specified 
                     with the addition of the "/fileLoggerParameters" switch.

                     If a log file name is set through the fileLoggerParameters
                     switch the distributed logger will use the fileName as a 
                     template and append the node id to this fileName to 
                     create a log file for each node.
    
  /logger:<logger>   Use this logger to log events from MSBuild. To specify
                     multiple loggers, specify each logger separately.
                     The <logger> syntax is:
                       [<logger class>,]<logger assembly>[;<logger parameters>]
                     The <logger class> syntax is:
                       [<partial or full namespace>.]<logger class name>
                     The <logger assembly> syntax is:
                       {<assembly name>[,<strong name>] | <assembly file>}
                     The <logger parameters> are optional, and are passed
                     to the logger exactly as you typed them. (Short form: /l)
                     Examples:
                       /logger:XMLLogger,MyLogger,Version=1.0.2,Culture=neutral
                       /logger:XMLLogger,C:\Loggers\MyLogger.dll;OutputAsHTML

  /validate          Validate the project against the default schema. (Short
                     form: /val)

  /validate:<schema> Validate the project against the specified schema. (Short
                     form: /val)
                     Example:
                       /validate:MyExtendedBuildSchema.xsd

  /ignoreprojectextensions:<extensions>
                     List of extensions to ignore when determining which 
                     project file to build. Use a semicolon or a comma 
                     to separate multiple extensions.
                     (Short form: /ignore)
                     Example:
                       /ignoreprojectextensions:.sln
    
  /nodeReuse:<parameters>
                     Enables or Disables the reuse of MSBuild nodes.
                     The parameters are:
                     True --Nodes will remain after the build completes
                            and will be reused by subsequent builds (default)
                     False--Nodes will not remain after the build completes
                     (Short form: /nr)
                     Example:
                       /nr:true
    
  /preprocess[:file] 
                     Creates a single, aggregated project file by
                     inlining all the files that would be imported during a
                     build, with their boundaries marked. This can be
                     useful for figuring out what files are being imported
                     and from where, and what they will contribute to
                     the build. By default the output is written to
                     the console window. If the path to an output file 
                     is provided that will be used instead.
                     (Short form: /pp)
                     Example:
                       /pp:out.txt
    
  /detailedsummary 
                     Shows detailed information at the end of the build
                     about the configurations built and how they were
                     scheduled to nodes. 
                     (Short form: /ds)
    
  @<file>            Insert command-line settings from a text file. To specify
                     multiple response files, specify each response file
                     separately.
                     
                     Any response files named "msbuild.rsp" are automatically 
                     consumed from the following locations: 
                     (1) the directory of msbuild.exe
                     (2) the directory of the first project or solution built

  /noautoresponse    Do not auto-include any MSBuild.rsp files. (Short form:
                     /noautorsp)

  /nologo            Do not display the startup banner and copyright message.

  /version           Display version information only. (Short form: /ver)

  /help              Display this usage message. (Short form: /? or /h)

Examples:

        MSBuild MyApp.sln /t:Rebuild /p:Configuration=Release
        MSBuild MyApp.csproj /t:Clean 
                             /p:Configuration=Debug;TargetFrameworkVersion=v3.5
    

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\MSBuild.exe |
C:\WINDOWS\System32\KERNEL32.dll |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\MSCOREE.DLL |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSBuild.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0 built by: NET48REL1
* Product Version: 4.8.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/b25346ac48099606de4bd7f72a4e76876587aadf5734eaa83b81b9e79437acab/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\MSBuild.exe](MSBuild.exe-D10A3CFCC08AAE3A7234498F213CF89E.md) | 74

## Possible Misuse

*The following table contains possible examples of `MSBuild.exe` being misused. While `MSBuild.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\msbuild.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\msbuild.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [silenttrinity_stager_msbuild_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/silenttrinity_stager_msbuild_activity.yml) | `title: Silenttrinity Stager Msbuild Activity`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [silenttrinity_stager_msbuild_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/silenttrinity_stager_msbuild_activity.yml) | `ParentImage\|endswith: '\msbuild.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '\msbuild.exe'  # https://github.com/elastic/detection-rules/blob/main/rules/windows/defense_evasion_execution_msbuild_started_by_office_app.toml`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_possible_applocker_bypass.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_possible_applocker_bypass.yml) | `- '\msbuild.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_script_event_consumer_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_script_event_consumer_spawn.yml) | `- '\msbuild.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_emotet_rudll32_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_emotet_rudll32_execution.yml) | `- '\tracker.exe' #When Visual Studio compile NodeJS program, it might use MSBuild to create tracker.exe and then, the tracker.exe fork rundll32.exe `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `Name: Msbuild.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Command: msbuild.exe pshell.xml`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Command: msbuild.exe project.csproj`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Command: msbuild.exe @sample.rsp`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Command: msbuild.exe /logger:TargetLogger,C:\Loggers\TargetLogger.dll;MyParameters,Foo`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Command: msbuild.exe project.proj`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `Description: Execute jscript/vbscript code through XML/XSL Transformation. Requires Visual Studio MSBuild v14.0+.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v2.0.50727\Msbuild.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v2.0.50727\Msbuild.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v3.5\Msbuild.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v3.5\Msbuild.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v4.0.30319\Msbuild.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\Msbuild.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Path: C:\Program Files (x86)\MSBuild\14.0\bin\MSBuild.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- IOC: Msbuild.exe should not normally be executed on workstations`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Link: https://pentestlab.blog/2017/05/29/applocker-bypass-msbuild/`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Msbuild.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Msbuild.yml) | `- Link: https://www.daveaglick.com/posts/msbuild-loggers-and-logging-events`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Csi.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Csi.yml) | `- Path: c:\Program Files (x86)\Microsoft Visual Studio\2017\Community\MSBuild\15.0\Bin\Roslyn\csi.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `- Command: dotnet.exe msbuild [Path_TO_XML_CSPROJ]`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dotnet.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Dotnet.yml) | `Description: dotnet.exe with msbuild (SDK Version) will execute unsigned code`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1127.001 MSBuild](../../T1127.001/T1127.001.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: MSBuild Bypass Using Inline Tasks (C#) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: MSBuild Bypass Using Inline Tasks (VB) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1127.001 MSBuild](../../T1127.001/T1127.001.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: MSBuild Bypass Using Inline Tasks (C#) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: MSBuild Bypass Using Inline Tasks (VB) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| [Port Monitors](../../T1547.010/T1547.010.md) \| Scheduled Task/Job [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [MSBuild](../../T1127.001/T1127.001.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| [PowerShell Profile](../../T1546.013/T1546.013.md) \| Scheduled Task/Job [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [MSBuild](../../T1127.001/T1127.001.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | # T1127.001 - MSBuild | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | <blockquote>Adversaries may use MSBuild to proxy execution of code through a trusted Windows utility. MSBuild.exe (Microsoft Build Engine) is a software build platform used by Visual Studio. It handles XML formatted project files that define requirements for loading and building various platforms and configurations.(Citation: MSDN MSBuild) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | Adversaries can abuse MSBuild to proxy execution of malicious code. The inline task capability of MSBuild that was introduced in .NET version 4 allows for C# or Visual Basic code to be inserted into an XML project file.(Citation: MSDN MSBuild)(Citation: Microsoft MSBuild Inline Tasks 2017) MSBuild will compile and execute the inline task. MSBuild.exe is a signed Microsoft binary, so when it is used this way it can execute arbitrary code and bypass application control defenses that are configured to allow MSBuild.exe execution.(Citation: LOLBAS Msbuild)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | - [Atomic Test #1 - MSBuild Bypass Using Inline Tasks (C#)](#atomic-test-1---msbuild-bypass-using-inline-tasks-c) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | - [Atomic Test #2 - MSBuild Bypass Using Inline Tasks (VB)](#atomic-test-2---msbuild-bypass-using-inline-tasks-vb) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | ## Atomic Test #1 - MSBuild Bypass Using Inline Tasks (C#) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | Executes the code in a project file using msbuild.exe. The default C# project example file (T1127.001.csproj) will simply print "Hello From a Code Fragment" and "Hello From a Class." to the screen. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | \| msbuildpath \| Default location of MSBuild \| Path \| C:&#92;Windows&#92;Microsoft.NET&#92;Framework&#92;v4.0.30319\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | \| msbuildname \| Default name of MSBuild \| Path \| msbuild.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | ## Atomic Test #2 - MSBuild Bypass Using Inline Tasks (VB) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1127.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1127.001/T1127.001.md) | Executes the code in a project file using msbuild.exe. The default Visual Basic example file (vb.xml) will simply print "Hello from a Visual Basic inline task!" to the screen. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_url_persitence.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_url_persitence.yar) | $file1 = /[\x0a\x0d](IconFile\|(Base\|)URL)\s*=[^\x0d]*(powershell\|cmd\|certutil\|mshta\|wscript\|cscript\|rundll32\|wmic\|regsvr32\|msbuild)(\.exe\|)[^\x0d]{2,50}\x0d/ nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | Identifier: MSBuild Katz-XML | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Detects an XML that executes Mimikatz on an endpoint via MSBuild" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


