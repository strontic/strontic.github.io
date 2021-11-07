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
MD5 | `41CAF6B240AA0711BAF7271593B29770`
SHA1 | `6802713D33F952A8E5B29646D4F565781E072F9D`
SHA256 | `2C76E0336D3E3F15FBE0FEFE4143510C2132A6808F6D88B29B229414648FC7CC`
SHA384 | `D2CB8955079AE512BC0304A2318C2E4028654385D9817ED9520DF839FDB48153337906E918AEAB5C2BFC65617BA24948`
SHA512 | `0120370BD619AA94B9B7596F15414F18BF91BE36BA8A73F0DA9A0512814CFAC4F9D7B68AEE4B3B658E74C1B626AAF0443CD2087B1279191A414CB3F2B0D58A8A`
SSDEEP | `6144:xNUvnSuA48IttoWaOwJt3QauZfAFDnbhbYpA61KDA4:jCnSueIttQt3Qafx48J`
IMP | `E61CD2AA90474CA9DFFAD3043C7DA49E`
PESHA1 | `CA4BDC4B17847E7F93FC9DBA780B43F11C000FC5`
PE256 | `B9518C18DB13E2CE14EA4C60FA904714471657D761559844A07C6D0596B38186`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft Windows Performance Recorder Version 10.0.19041 (CoreSystem)
Copyright (c) 2019 Microsoft Corporation. All rights reserved.

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wpr.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WPR.exe
* Product Name: Microsoft Windows Performance Recorder
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.746 (WinBuild.160101.0800)
* Product Version: 10.0.19041.746
* Language: English (United States)
* Legal Copyright:  2019 Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/2c76e0336d3e3f15fbe0fefe4143510c2132a6808f6d88b29b229414648fc7cc/detection


## Possible Misuse

*The following table contains possible examples of `wpr.exe` being misused. While `wpr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file wpr.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "WPR.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


