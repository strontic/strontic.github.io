---
title: tracelog.exe | Trace control utility
excerpt: What is tracelog.exe?
---

# tracelog.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\tracelog.exe`
* Description: Trace control utility

## Hashes

Type | Hash
-- | --
MD5 | `B67AA5C2AF632B34596BE02FDD274B28`
SHA1 | `99751335A71AE276472232366D69F3893EA29785`
SHA256 | `5722900ED58968A5A536F04A4BFEC375D381810DC5C03E60F68FAD73726B3180`
SHA384 | `556B8E4A1AE37BA6B9EF83801AF73B5D9EC326E3292B0375A69F2CCE48955974E149AE9E3FA907E893827B943676D8EA`
SHA512 | `CC70694E58B112DB4450709AD57CCCDB684292A51A98390122B1EAAE1B05C393E7CCDB8E985877A49B15CBE0167D4611CC2186FAB1FEF72B2025D9AC9B70F39E`
SSDEEP | `3072:RoFO3/efPsEWTdVUwcqZanlSxPO5VYxMX/9LL:lefEEMUtSxsvFv`
IMP | `EA8A061571DAD052D4FE8984F532674C`
PESHA1 | `4F278EB4571DF0DC0D024A772BC6861B207CF26D`
PE256 | `AE17786F7AC321E0999C6DC50F31AB2E79138D1CACB3C9EAF966BAA54B51B562`

## Runtime Data

### Usage (stdout):
```cmhg
ERROR: no action specified

Microsoft (R) tracelog.exe (10.0.19041.1)
 Microsoft Corporation. All rights reserved.

Usage: tracelog [actions] [options] | [-h | -help | -?]

Actions can be specified as "-action LoggerName" or "-action=LoggerName".

Actions:

-start         <LoggerName> Starts the <LoggerName> trace session.
-stop          <LoggerName> Stops the <LoggerName> trace session.
-update        <LoggerName> Updates the <LoggerName> trace session.
-enable        <LoggerName> Enables providers to the <LoggerName> session.
-enableex      <LoggerName> Enables providers to the <LoggerName> session.
-timeout       <n>          Forces enable to be synchronous (timeout value
                            specified in milliseconds).
-capturestate  <LoggerName> Request provider to log state information to the
                            <LoggerName> session.
-incrementfile <LoggerName> Increment to the next file for the <LoggerName> trace
                            session (EVENT_TRACE_FILE_MODE_NEWFILE should be enabled)
-systemrundown <LoggerName> Request SystemTraceProvider to log rundown
                            information to the <LoggerName> session.
-disable       <LoggerName> Disables providers for the <LoggerName> session.
-flush         <LoggerName> Flushes the <LoggerName> active buffers.
-addautologger <LoggerName> Creates the registry keys for the <LoggerName>
                            autologger session. Provide the session GUID using
                            the -sessionguid parameter.
-remove        GlobalLogger Removes the registry keys that activate the
                            GlobalLogger.
-enumguid                   Enumerate registered trace guids.
-enumguidex    [#<guid>]    Enumerate registered trace guids.
-q             <LoggerName> [-lp]
                            Query status of <LoggerName> trace session.
                            Use -lp to list providers enabled to the session.
-l             [-lp]        List all trace sessions.
                            Use -lp to list providers enabled to each session.
-h, -?, -help               Display usage information.

Options:

-b   <n>                    Sets buffer size to <n> kilobytes.
-min <n>                    Sets minimum buffers.
-max <n>                    Sets maximum buffers.
-f <name>                   Log to file <name>.
-kb                         Use kilobytes for log file size.
-append                     Append to file.
-prealloc                   Pre-allocate.
-seq <n>                    Sequential logfile of up to n megabytes.
-cir <n>                    Circular logfile of n Mbytes.
-newfile <n>                Log to a new file after every n megabytes.
                            File name must contain %d.
-UseSystemTime              Use System Time clock.
-UsePerfCounter             Use Performance Counter clock.
-UseCPUCycle                Use CPU Cycle Count clock.
-ft <n>                     Set flush timer to n seconds.
-QpcDelta                   Turn on QPC Delta tracking between Container and Host.
                            Only supported on Start calls on some OS versions.
-bt <n>                     Specify that n buffers should be filled before the
                            system begins flushing them.
-paged                      Use pageable memory for buffers.
-addtotriagedump            Write out buffers for triage memory dumps.
-noprocess                  Disable Process Start/End tracing.
-nothread                   Disable Thread Start/End tracing.
-nodisk                     Disable Disk I/O tracing.
-nonet                      Disable Network TCP/IP tracing.
-fio                        Enable file I/O tracing.
-pf                         Enable page faults tracing.
-hf                         Enable hard faults tracing.
-img                        Enable image load tracing.
-cm                         Enable registry calls tracing.
-um                         Enable Process Private tracing.
-guid <file>                Enable tracing for providers specified in <file>.
                            The file must be formatted as:
                                ; comment line
                                guid1;matchanykeyword;level
                                guid2;matchanykeyword;level
      #<guid>               Enable tracing for a provider by guid.
      *<name>               Enable tracing for a provider by guid from hashed
                            name.
-rt                         Enable tracing in real time mode.
-kd                         Enable tracing in kernel debugger.
-level <n>                  Enable providers with specified level.
-matchanykw <n>             Enable providers with specified MatchAnyKeyword.
-matchallkw <n>             Enable providers with specified MatchAllKeyword.
-enableproperty <flags>     Enable providers with specified EnableProperty
                            flags.
-sourceguid #<guid>         Pass <guid> to the enabled providers' callbacks
                            as the SourceId.
-flag  <n>                  Enable Flags passed to the providers.
                            Note: Flags have been replaced by MatchAnyKeyword.
-eflag <Name+Name+...>      Enable kernel events by name.
       <n> <eflag...>       Enable kernel events using <n> extended flags.
       Help                 Print the list of named kernel events that can be
                            enabled.
-dpcisr                     Enable kernel events for DPC/ISR analysis.
-ls                         Generate Local Sequence Numbers.
-gs                         Generate Global Squence Numbers.
-heap                       Use this for Heap Guid.
-critsec                    Use this for CritSec Guid.
-pids <n> <pid1 pid2 ... >  Tracing for Heap and CritSec for <n> processes.
-buffering                  Enable tracing in buffering mode.
-secure                     Enable tracing in secure mode.
-sessionguid                Autologger session GUID Registry value.
-lowcapacity                Don't create buffers per processor.
-stackwalk <Events>         Enable stack walking for specified events.
-hybridshutdown [stop|persist]
                            Control hybrid shutdown logger behavior.
-systemlogger               Logger can receive SystemTraceProvider events.
-ProfileSource <src>|Help   Configure profiling source to use.
                            Use Help to see the list of available sources.
-SetProfInt <n> <src>       Configure profiling interval for specified
                            source.
-Pmc <Ctr1,Ctr2,...>:<Name+Name+...>
                            Configure PMC counter sampling on kernel events.
                            Use -ProfileSource Help for a list of counters.
                            Use -eflag Help for a list of kernel events.
-independent                Enable independent mode on the trace session.
-ExeFilter <Executable names>
                            Specify an Executable name filter with names
                            separated by semi-colon.
-PkgIdFilter <Package Full Name>
                            Specify Package id filter(s) separated by
                            semi-colon.
-PkgAppIdFilter <PRAID>     Specify Package Relative App Id filter(s)
                            separated by semi-colon.
-PidFilter <n> <pid1 pid2 ... >
                            Specify Pid filter with <n> Pids (maximum of 8
                            allowed).
-EventIdFilter -<in|out> <n> <id1 id2 ...>
                            Specify an event id filter with <n> event ids
                            (maximum 64 event ids allowed).
-StackWalkFilter -<in|out> <n> <id1 id2 ...>
                            Specify an event id filter with <n> event ids
                            (maximum 64 event ids allowed).
-Lbr <EventName+EventName+...>:<Filter1,Filter2>
                            Configure LBR tracing on kernel events.
-Ipt <EventName+EventName+...>:<BufferSize=size,CodeMode=mode>
                            Configure IPT tracing on kernel events.
                            size is a positive integer <= 32 (default) in the unit
                            of KB, and will be rounded up to the next power of 2 (minimal 4)
                            mode can be User (default), Kernel and UserKernel.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\tracelog.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tracelog.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\tracelog.exe](tracelog.exe-A40D4D4E355DECDCDC00D42A72481FF9.md) | 52




MIT License. Copyright (c) 2020-2021 Strontic.


