---
title: OffDumpTool.exe | OfflineDump Tool EXECUTABLE
excerpt: What is OffDumpTool.exe?
---

# OffDumpTool.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\OffDumpTool.exe`
* Description: OfflineDump Tool EXECUTABLE

## Hashes

Type | Hash
-- | --
MD5 | `E88793B02D14AD912D4421D90098E166`
SHA1 | `1DE208B9FD82545454E08A790373AE81A53EF423`
SHA256 | `5C2F19D77A8064E34D1711D13A377882A36B4C2F63FD2683F76F3172F2704801`
SHA384 | `B29EA453A8685EB8C2908629E5758BB299FAD0DAC2ADD270129C631B5D445F929033773E42CB79B39DBB091D3D6C15DC`
SHA512 | `99FFF64AB576CA514A0AD51E6DB242D4DAB178470284DDCA128F23335F946251DD2F1268E86B33363A9F985767972299EB30116E9E40FCDC63546BCBCCAF5834`
SSDEEP | `3072:VzhaACBMODsYnzyysiCWgqZBnWkCdtiRO10xhGJHsVysVTVhOMsMtE:VzhaznDsYnzy1/WgkxnlyV`
IMP | `619C42374CE64AE6BCF4F4F04F4AEFF9`
PESHA1 | `5F55630E3EFD5A9292FBBDD46E40D6D340E4F1DB`
PE256 | `8E36281E315FF24CDA38510A096498570999C003C625071C1C3D321018746920`

## Runtime Data

### Usage (stdout):
```cmhg
Device string in use: $localpub:qsize=0($LogFile:file=OfflineDumpTool.wtl,encoding=UNICODE,writemode=overwrite;$Console;$Debugger)
WTTLogger_CPP_GitEnlistment(winpbld); Version: 2.7.3483.0

====Offline Dump Tool Version = 10.0.19041.1 (WinBuild.160101.0800)====

Machine: Build=19041.00 
	Platform=AMD64 
	OS=Windows 10 Enterprise 
	ServicePack="" 
	Version=6.3 
	BuildLab="vb_release" 
	BuildDate=191206-1406 
	Language=English (US) (REDMOND) 
	Config=n/a 

offlinedump test tool.
Background and Assumptions:
    This utility:
          - Takes input that conforms to the Microsoft Offline Dump Specification
          - Must be run as an administrator
          - Denotes System under Test (SUT) as the System that crashed
          - Denotes Debug System (DS) as system running the Windows debugger
          
    The System Under Test (SUT):
          - Has a disk partition suitable for storing an offline crash
          - May be distinct from the Debug System (DS)
          - May be a different system architecture from the Debug System
          
    To expedite debugging, two distinct systems are recommended
    This is based on assumption, relative to SUT:
          - The Debug System has greater stability
          - The Debug System has higher performance
          
    The file extension has the following conventions:
          .RAW (Raw Partition saved as a File)
               [Output or Input to Tool]
          .DMP (Windows Dump File loadable by Windows Debugger)
               [Output from Tool]
               Windows Phone: [Input to Tool]
          .BIN (Silicon Vendor Specific BIN File)
               [Output from Tool]
          .DDR (DDR memory sections File)
               [Input to Tool]
          
          
BASIC Usage Commands:
     /help
          This help text
          
     /parsepart
          This will Parse the Raw_Dump Partition and create:
              .DMP = Windows Dump file 
              .BIN = Silicon vendor specific bins
          Example: offlinedumptool /parsepart
          Note: Must run command on System under Test (SUT)
          Output file: raw_dump.DMP, <possibly others>
          Exact output filenames encoded in headers of Offline Specification
          
     /zeropart
          Wipes the contents of dedicated raw dump partition by filling it with zeros.
          
     /wipedump
          Wipes the raw dump header in the dedicated partition.
          
     /dumprawpart <DUMPFILE.RAW>
          This will dump the raw dump partition to a file. 
          Example: offlinedumptool /dumprawpart dumpfile.raw
          Note: Must run command on System under Test (SUT)
          Output .RAW file is further processed using the /parsedump option
          
     /parsedump <DUMPFILE.RAW> 
          This will open the Raw_Dump Partition file as raw dump and parse the headers. 
          Example: offlinedumptool /parsedump DUMPFILE.RAW 
          Note: .BIN file can be processed using this utility on Debug System
          Exact output filenames encoded in headers of Offline Specification
          Output file: raw_dump.DMP
          option /noapreg will not attempt to process APREG section
          
     /parsewpdump <WP_DUMPFILE.DMP>
          It will extract WP silicon vendor sections from WP dump secondary data and save as .bins 
          Example: offlinedumptool /parsewpdump memory.dmp
          Note: Windows Phone Specific Option, all other options are supported exclusively for Windows
                Must run command on .DMP file from Windows Phone System under Test (SUT)
                The input .DMP file is generated from another Windows Phone tool
          Output file(s): <section>.BIN ...
          Exact output filenames encoded in headers of Offline Specification
          
     OPTIONAL ADD ON COMMANDS :-
     /noapreg 
          Does not attempt to find APREG in the DDR sections
          
     /apreg64 <address in Hex> 
          Assumes the APREG format to of 64 bit and attempts to find the MSM_DUMP_TABLE 
          at that location.
          
     /supplementalbugcheckdata <path_to_hloscrashdmp.bin>
          Bugcheck data from supplied hloscrashdmp.bin is used to replace default FATAL_ABNORMAL_RESET_ERROR (0x14c)
          information in generated .dmp file if no such information is found in SV specific section.
          
RECOMMENDED Usage Commands:
          For example on Windows Systems Under Test (SUT), option A or B:
          A)  Raw Partition -- > Raw File -- > .DMP, .BIN(s)
              -----------------------------------------------------------
              /dumprawpart (on SUT)            /parsedump, windbg (on DS)
          
              1) 'offlinedumptool /dumprawpart dump.raw' (on SUT)
                 output is user specified 'dump.raw' file
              2) 'offlinedumptool /parsedump dump.raw' (on DS)
                 output is .DMP file (windbg loadable)
                 output is .BIN file(s) (as specified in .RAW file)
              3) 'windbg -z crash.dmp' (on DS)
          
          B)  Raw Partition       ----- >      .DMP, .BIN(s)
              --------------------------------------------------
              /parsepart (on SUT)              windbg (on DS)
          
              1) 'offlinedumptool /parsepart' (on SUT)
                 output is .DMP file (windbg loadable)
                 output is .BIN file(s) (as specified in .RAW file)
              2) 'windbg -z crash.dmp' (on DS)
          
          For Windows Phone Systems Under Test (SUT):
          A)  .DMP File (generated on SUT)      -- > .BIN(s)
              -----------------------------------------------
              /parsewpdump wp_dumpfile.dmp, windbg (on DS)
          
              1) 'offlinedumptool /parsewpdump wp_dumpfile.DMP' (on DS)
                 output is .BIN file(s) (as specified in .DMP file)
              2) 'windbg -z wp_dumpfile.dmp' (on DS)
          
Summary: Total=0, Passed=0, Failed=0, Blocked=0, Warned=0, Skipped=0

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\OffDumpTool.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: A certificate chain processed, but terminated in a root certificate which is not trusted by the trust provider
* Serial: `33000003A2973D2E4F88A4ECA10000000003A2`
* Thumbprint: `59A344D03FA3079B29AF4EA80C6E37C7102848D9`
* Issuer: CN=Microsoft Testing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: offdumptool.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/5c2f19d77a8064e34d1711d13a377882a36b4c2f63fd2683f76f3172f2704801/detection





MIT License. Copyright (c) 2020 Strontic.


