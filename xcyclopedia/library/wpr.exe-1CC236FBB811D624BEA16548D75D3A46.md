---
title: wpr.exe | Microsoft Windows Performance Recorder
excerpt: What is wpr.exe?
---

# wpr.exe 

* File Path: `C:\Windows\system32\wpr.exe`
* Description: Microsoft Windows Performance Recorder

## Hashes

Type | Hash
-- | --
MD5 | `1CC236FBB811D624BEA16548D75D3A46`
SHA1 | `52E2454464DEDD872218A4B3AFA74B573CFA71D2`
SHA256 | `37869599B8F17A1D5F7BF91A20A1CE4555919A4758078FFE8DDDAD422BE5CCAA`
SHA384 | `E1CD5530816B663204511ECEBA8AEACEBB3C859AE77CD921AB6692F29A86DBF884095DAE6D2FF356031A8DDBB4CC2B71`
SHA512 | `E3AF862AE5D47E0DEE7356A45E740A8FA5F5305FD834C4BE3517E00DA457B0514C7F0E173D1509C653BAF78444EA71AB1C76D2FF41A433110FA33658DC4F4733`
SSDEEP | `6144:kUgeiahIngARB1uU5cwmwoL59jaTg85YtcpwCXE:FIbuU5cwtoHja01lCX`
IMP | `0F7365EDF941165E0FACBC5296015670`
PESHA1 | `26A9828A7837E7F12D2EE098593DD43D74FEEB35`
PE256 | `61171C07ADCF9258D0C77BDF32D7367C1D29B4A68C91F69FE7BE9443B43E4297`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft Windows Performance Recorder Version 10.0.17763 (CoreSystem)
Copyright (c) 2018 Microsoft Corporation. All rights reserved.

	Usage: wpr options ...

	-help			 - Provide command line help information
	-profiles		 - Enumerates the profile names and descriptions from a profile file
	-purgecache		 - Purges the dynamic symbols cache
	-start			 - Starts one or more profiles
	-marker			 - Fires an event marker
	-markerflush		 - Fires an event marker and flushes the working set
	-status			 - Displays status on active recording (if any)
	-profiledetails		 - Displays the detailed information about a set of profiles
	-providers		 - Displays detailed information about providers
	-cancel			 - Cancels recording initiated via WPR (if any)
	-stop			 - Stops recording initiated via WPR (if any) and saves
	-flush			 - Flushes logging sessions initiated through WPR (if any)
	-log			 - Configure debug logging to the event log
	-disablepagingexecutive	 - Change the Disable Paging Executive settings
	-heaptracingconfig	 - Change heap tracing settings for a process
	-snapshotconfig		 - Change snapshot settings for a process
	-capturestateondemand	 - Capture states for the configured providers in the current recording
	-pmcsources		 - Query the list of hardware counters available on the system
	-setprofint		 - Set sampled profile interval
	-profint		 - Query the current profile interval
	-resetprofint		 - Restores the default profile interval values
	-boottrace		 - Configures the registry entries for autologger/globallogger sessions
	-enableperiodicsnapshot	 - Enable Periodic Snapshot for the specified interval and given process id
	-disableperiodicsnapshot - Disable Periodic Snapshot for all process
	-singlesnapshot		 - On demand Snapshot for the specified process
	-instancename		 - Specifies a name to uniquely identify the tracing instance. 
				   Useful when managing multiple concurrent wpr sessions. Must be last parameter.

```

### Usage (stderr):
```cmhg

	Invalid command syntax.

	Error code: 0xc5600602
	Invalid option: --help

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\WindowsPerformanceRecorderControl.dll |
C:\Windows\system32\wpr.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WPR.exe
* Product Name: Microsoft Windows Performance Recorder
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1075 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1075
* Language: English (United States)
* Legal Copyright:  2018 Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/37869599b8f17a1d5f7bf91a20a1ce4555919a4758078ffe8dddad422be5ccaa/detection/


## Possible Misuse

*The following table contains possible examples of `wpr.exe` being misused. While `wpr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file wpr.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "WPR.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


