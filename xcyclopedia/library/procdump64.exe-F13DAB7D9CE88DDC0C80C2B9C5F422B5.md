---
title: procdump64.exe | Sysinternals process dump utility
excerpt: What is procdump64.exe?
---

# procdump64.exe 

* File Path: `C:\SysinternalsSuite\procdump64.exe`
* Description: Sysinternals process dump utility

## Hashes

Type | Hash
-- | --
MD5 | `F13DAB7D9CE88DDC0C80C2B9C5F422B5`
SHA1 | `F02DF19B44E880B9810D226B743B1A4B93E49A16`
SHA256 | `E2A7A9A803C6A4D2D503BB78A73CD9951E901BEB5FB450A2821EAF740FC48496`
SHA384 | `B076B210F1C748D399AA364DD6A286FC8FEBC3C91920BD2845ECF8299F64B6B6E846278CB72F45D0A0A4585B6B17D7B6`
SHA512 | `73015D73EF35A020C846A09AF56AC01F0BAAC6626A0BB590D38F7FD7461194D935A7BC8CD92BA0D2B6B9842BF8075D21F2B333279A73CF37FBE9A486CE9487EB`
SSDEEP | `6144:BbaoysBY+FE3jneNMYZJzK1ZIQ68NeLHW2vX5NVUQYLToL6N:Bbaoys3Fm7eNMd1MI`
IMP | `E6F7F291413118F49398761021BAFCF2`
PESHA1 | `538F4E6A02ABF77D24044E8741D1FEBFCE3B2A2A`
PE256 | `E5529B0F5ABA7981F2470EF7DF11C9A956BAFFFABF20D894AB0430C9855FFE99`

## Runtime Data

### Usage (stdout):
```cmhg

ProcDump v10.0 - Sysinternals process dump utility
Copyright (C) 2009-2020 Mark Russinovich and Andrew Richards
Sysinternals - www.sysinternals.com

Monitors a process and writes a dump file when the process exceeds the
specified criteria or has an exception.

Capture Usage: 
   procdump.exe [-mm] [-ma] [-mp] [-mc Mask] [-md Callback_DLL] [-mk]
                [-n Count]
                [-s Seconds]
                [-c|-cl CPU_Usage [-u]]
                [-m|-ml Commit_Usage]
                [-p|-pl Counter_Threshold]
                [-h]
                [-e [1 [-g] [-b]]]
                [-l]
                [-t]
                [-f  Include_Filter, ...]
                [-fx Exclude_Filter, ...]
                [-o]
                [-r [1..5] [-a]]
                [-at Timeout]
                [-wer]
                [-64]
                {
                 {{[-w] Process_Name | Service_Name | PID} [Dump_File | Dump_Folder]}
                |
                 {-x Dump_Folder Image_File [Argument, ...]}
                }
Install Usage: 
   procdump.exe -i [Dump_Folder]
                [-mm] [-ma] [-mp] [-mc Mask] [-md Callback_DLL] [-mk]
                [-r]
                [-at Timeout]
                [-k]
                [-wer]
Uninstall Usage: 
   procdump.exe -u

Options:
   -mm     Write a 'Mini' dump file. (default)
           Includes the Process, Thread, Module, Handle and Address Space info.
   -ma     Write a 'Full' dump file.
           Includes All the Image, Mapped and Private memory.
   -mp     Write a 'MiniPlus' dump file.
           Includes all Private memory and all Read/Write Image or Mapped memory.
           To minimize size, the largest Private memory area over 512MB is excluded.
           A memory area is defined as the sum of same-sized memory allocations.
           The dump is as detailed as a Full dump but 10%-75% the size.
           Note: CLR processes are dumped as Full (-ma) due to debugging limitations.
   -mc     Write a 'Custom' dump file.
           Include memory defined by the specified MINIDUMP_TYPE mask (Hex).
   -md     Write a 'Callback' dump file.
           Include memory defined by the MiniDumpWriteDump callback routine
           named MiniDumpCallbackRoutine of the specified DLL.
   -mk     Also write a 'Kernel' dump file.
           Includes the kernel stacks of the threads in the process.
           OS doesn't support a kernel dump (-mk) when using a clone (-r).
           When using multiple dump sizes, a kernel dump is taken for each dump size.

   -a      Avoid outage. Requires -r. If the trigger will cause the target
           to suspend for a prolonged time due to an exceeded concurrent
           dump limit, the trigger will be skipped.
   -at     Avoid outage at Timeout. Cancel the trigger's collection at N seconds.
   -b      Treat debug breakpoints as exceptions (otherwise ignore them).
   -c      CPU threshold above which to create a dump of the process.
   -cl     CPU threshold below which to create a dump of the process.
   -e      Write a dump when the process encounters an unhandled exception.
           Include the 1 to create dump on first chance exceptions.
   -f      Filter (include) on the content of exceptions and debug logging.
           Wildcards (*) are supported.
   -fx     Filter (exclude) on the content of exceptions and debug logging.
           Wildcards (*) are supported.
   -g      Run as a native debugger in a managed process (no interop).
   -h      Write dump if process has a hung window (does not respond to
           window messages for at least 5 seconds).
   -i      Install ProcDump as the AeDebug postmortem debugger.
           Only -mm, -ma, -mp, -mc, -md and -r are supported as additional options.
           Uninstall (-u only) restores the previous configuration.
   -k      Kill the process after cloning (-r), or at end of dump collection.
   -l      Display the debug logging of the process.
   -m      Memory commit threshold in MB at which to create a dump.
   -ml     Trigger when memory commit drops below specified MB value.
   -n      Number of dumps to write before exiting.
   -o      Overwrite an existing dump file.
   -p      Trigger on the specified performance counter when the threshold
           is exceeded. Note: to specify a process counter when there are
           multiple instances of the process running, use the process ID
           with the following syntax: "\Process(<name>_<pid>)\counter"
   -pl     Trigger when performance counter falls below the specified value.
   -r      Dump using a clone. Concurrent limit is optional (default 1, max 5).
           OS doesn't support a kernel dump (-mk) when using a clone (-r).
           CAUTION: a high concurrency value may impact system performance.
           - Windows 7   : Uses Reflection. OS doesn't support -e.
           - Windows 8.0 : Uses Reflection. OS doesn't support -e.
           - Windows 8.1+: Uses PSS. All trigger types are supported.
   -s      Consecutive seconds before dump is written (default is 10).
   -t      Write a dump when the process terminates.
   -u      Treat CPU usage relative to a single core (used with -c).
           As the only option, Uninstalls ProcDump as the postmortem debugger.
   -w      Wait for the specified process to launch if it's not running.
   -wer    Queue the (largest) dump to Windows Error Reporting.
   -x      Launch the specified image with optional arguments. 
           If it is a Store Application or Package, ProcDump will start
           on the next activation (only).
   -64     By default ProcDump will capture a 32-bit dump of a 32-bit process
           when running on 64-bit Windows. This option overrides to create a
           64-bit dump. Only use for WOW64 subsystem debugging.

License Agreement:
   Use the -accepteula command line option to automatically accept the
   Sysinternals license agreement.

Automated Termination:
   -cancel <Target Process PID>
           Using this option or setting an event with the name "ProcDump-<PID>"
           is the same as typing Ctrl+C to gracefully terminate ProcDump.
           Graceful termination ensures the process is resumed if a capture is active.
           The cancellation applies to ALL ProcDump instances monitoring the process.

Filename:
   Default dump filename: PROCESSNAME_YYMMDD_HHMMSS.dmp
   The following substitutions are supported:
           PROCESSNAME   Process Name
           PID           Process ID
           EXCEPTIONCODE Exception Code
           YYMMDD        Year/Month/Day
           HHMMSS        Hour/Minute/Second

Examples:
   Use -? -e to see example command lines.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\procdump64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: procdump
* Product Name: ProcDump
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 10.0
* Product Version: 10.0
* Language: English (United States)
* Legal Copyright: Copyright (C) 2009-2020 Mark Russinovich and Andrew Richards
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/e2a7a9a803c6a4d2d503bb78a73cd9951e901beb5fb450a2821eaf740fc48496/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\procdump.exe](procdump.exe-D3763FFBFAF30BCFD866B8ED0324E7A3.md) | 57

## Possible Misuse

*The following table contains possible examples of `procdump64.exe` being misused. While `procdump64.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cred_dump_tools_dropped_files.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_cred_dump_tools_dropped_files.yml) | `- '\procdump64.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_judgement_panda_gtr19.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_judgement_panda_gtr19.yml) | `- '*\aaaa\procdump64.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_procdump.yml) | `- '*\procdump64.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


