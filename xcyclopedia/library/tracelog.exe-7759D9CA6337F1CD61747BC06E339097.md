---
title: tracelog.exe | Trace control utility
excerpt: What is tracelog.exe?
---

# tracelog.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\tracelog.exe`
* Description: Trace control utility

## Hashes

Type | Hash
-- | --
MD5 | `7759D9CA6337F1CD61747BC06E339097`
SHA1 | `23242F5A39ED211FD31D7F63135FF7E6A2FB98BE`
SHA256 | `E74D328C9F8472BB64678E045B1FCDAF8EB42D088FB5BC5D84755DE82910C3CF`
SHA384 | `88C668B0343129A20FD889039DC9A759660A196993F55BF31720E2A4C04A742654795202F35838CCC44D8245224DD440`
SHA512 | `2928B3B739706C90C27AF85B8A6270704A87CD2C2A8B4B85F4D7799680DC607CFD069494D0B1AF6D9AD3156005F2DD5E1A23859D6315A9FC2F79947A9F1882BD`
SSDEEP | `3072:6kHpo4DmTmpFxxoFOXfefPMkGzkVSxhibS:6M24DmTmfefkkLVO`
IMP | `5B8DB86FFD8BA51B7D897FD5A9118F0E`
PESHA1 | `243BBCD8386BDAE2D455CC3BF13CE4C10169BC3C`
PE256 | `9B4DC7CB9E96E24DB7F19F723A36787585ACBD89EAED20D0363973D097FB4CD0`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\tracelog.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\tracelog.exe](tracelog.exe-BE0CA960F8A13A473505821D2493A3DC.md) | 46




MIT License. Copyright (c) 2020 Strontic.


