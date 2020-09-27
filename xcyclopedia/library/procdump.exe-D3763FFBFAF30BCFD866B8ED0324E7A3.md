---
title: procdump.exe | Sysinternals process dump utility
excerpt: What is procdump.exe?
---

# procdump.exe 

* File Path: `C:\SysinternalsSuite\procdump.exe`
* Description: Sysinternals process dump utility

## Hashes

Type | Hash
-- | --
MD5 | `D3763FFBFAF30BCFD866B8ED0324E7A3`
SHA1 | `E9967DDB2860174F4FAC3C82A7DCDDFE106AFB25`
SHA256 | `916CC8D6BF2282AE0D2DB587F4F96780AF59E685A1F1A511E0B2B276669DC802`
SHA384 | `6706A10B08E809AEA04D8D3ECFF467B9619ABE1071AAA34ED9DC36C9DF900DECB21A06CD191E50AEFBF42B98033BD026`
SHA512 | `4F14DEE268B0982D620B909C243F61870E56BAB161458BF50F7102207F563D244D100B9CFFA89B271A9CFDFFD2BD1856BDBFCD65DF2EA1EC41AD8638C08C1F55`
SSDEEP | `12288:RhkYuFNNIYgv1npe39hqdbaoys3Fm7eNMd1MY:RdNEiUoL3Fv81l`
IMP | `83B075100F8ECC5BF8446EDDD8E9CD6E`
PESHA1 | `7C8C117470D5D611FAF521136703FB1258B315CB`
PE256 | `9E537DE30214983492DB3FC38E5AE52FE32D93CF6DF5C7D6927083983AE08699`

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
                 { {[-w] Process_Name | Service_Name | PID} [Dump_File | Dump_Folder]}
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
C:\SysinternalsSuite\procdump.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/916cc8d6bf2282ae0d2db587f4f96780af59e685a1f1a511e0b2b276669dc802/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\SysinternalsSuite\procdump64.exe](procdump64.exe-F13DAB7D9CE88DDC0C80C2B9C5F422B5.md) | 57

## Possible Misuse

*The following table contains possible examples of `procdump.exe` being misused. While `procdump.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- ' -ma '  # ProcDump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- ' comsvcs.dll,MiniDump'  # Process dumping method apart from procdump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- ' comsvcs.dll,#24'  # Process dumping method apart from procdump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memory_dump_file_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_lsass_memory_dump_file_creation.yml) | `description: LSASS memory dump creation using operating systems utilities. Procdump will use process name in output file if no name is specified` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `description: Detects process LSASS memory dump using procdump or taskmgr based on the CallTrace pointing to dbghelp.dll or dbgcore.dll for win10` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_lsass_memdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_lsass_memdump.yml) | `- https://blog.menasec.net/2019/02/threat-hunting-21-procdump-or-taskmgr.html` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `description: Detect creation of dump files containing the memory space of lsass.exe, which contains sensitive credentials. Identifies usage of Sysinternals procdump.exe to export the memory space of lsass.exe which contains sensitive credentials.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|contains: '\procdump'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_procdump.yml) | `title: Renamed ProcDump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_procdump.yml) | `description: Detects the execution of a renamed ProcDump executable often used by attackers or malware` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_procdump.yml) | `- https://docs.microsoft.com/en-us/sysinternals/downloads/procdump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_procdump.yml) | `OriginalFileName: 'procdump'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_procdump.yml) | `- '*\procdump.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_procdump.yml) | `- Procdump illegaly bundled with legitimate software` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_procdump.yml) | `title: Suspicious Use of Procdump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_procdump.yml) | `description: Detects suspicious uses of the SysInternals Procdump utility by using a special command line parameter in combination with the lsass.exe process. This way we're also able to catch cases in which the attacker has renamed the procdump executable.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_procdump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_procdump.yml) | `- Another tool that uses the command line switches of Procdump` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Dump LSASS.exe Memory using ProcDump [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: Dump LSASS.exe Memory using ProcDump [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | For example, on the target host use procdump: | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | * <code>procdump -ma lsass.exe lsass_dump</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | - [Atomic Test #2 - Dump LSASS.exe Memory using ProcDump](#atomic-test-2---dump-lsassexe-memory-using-procdump) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | ## Atomic Test #2 - Dump LSASS.exe Memory using ProcDump | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | ProcDump. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | If you see a message saying "procdump.exe is not recognized as an internal or external command", try using the  get-prereq_commands to download and install the ProcDump tool first. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | \| procdump_exe \| Path of Procdump executable \| Path \| PathToAtomicsFolder&#92;T1003.001&#92;bin&#92;procdump.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | ##### Description: ProcDump tool from Sysinternals must exist on disk at specified location (#{procdump_exe}) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Invoke-WebRequest "https://download.sysinternals.com/files/Procdump.zip" -OutFile "$env:TEMP\Procdump.zip" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Expand-Archive $env:TEMP\Procdump.zip $env:TEMP\Procdump -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md) | Copy-Item $env:TEMP\Procdump\Procdump.exe #{procdump_exe} -Force | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


