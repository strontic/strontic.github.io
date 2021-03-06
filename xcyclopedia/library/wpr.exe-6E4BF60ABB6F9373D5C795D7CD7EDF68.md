﻿---
title: wpr.exe | Microsoft Windows Performance Recorder
excerpt: What is wpr.exe?
---

# wpr.exe 

* File Path: `C:\Windows\system32\wpr.exe`
* Description: Microsoft Windows Performance Recorder

## Hashes

Type | Hash
-- | --
MD5 | `6E4BF60ABB6F9373D5C795D7CD7EDF68`
SHA1 | `A78B4AEF2DE0EC9675C92FFAABAFA438B79FE576`
SHA256 | `30940147D6C68C79C9CB8E56CEDB4DAA4F025EDDF1134274DE90DD39D0D8EAD0`
SHA384 | `A7E008CC9393C194FD46AA6B762920950A51FC613E0A784A93F93B3AC48128D0F049DC6B37BFA7873830D389F7F4B6B1`
SHA512 | `0F993938797ADFE1E13457A4777946B65679EBD9AEBC84F64D12170E0948596022CE25A3C57C0ED216AF1A957BE5672AEE57B920B26A2416CA74B9B2AC338247`
SSDEEP | `6144:egtvJfDldaBXZd0PaHw/kDeuiEKvK5cnbhbYg06X0R:JZJfreXZd0pseuiIS//E`
IMP | `E61CD2AA90474CA9DFFAD3043C7DA49E`
PESHA1 | `E6E806F059535CDAA2655ADEF8979FCD518309C3`
PE256 | `D661C1CB218965082FDF827B3ACB8BF7E966E06B098218E1DB70DFC0284BB6AC`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WPR.exe
* Product Name: Microsoft Windows Performance Recorder
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.329 (WinBuild.160101.0800)
* Product Version: 10.0.19041.329
* Language: English (United States)
* Legal Copyright:  2019 Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/30940147d6c68c79c9cb8e56cedb4daa4f025eddf1134274de90dd39d0d8ead0/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\wpr.exe](wpr.exe-3836F328B1E6F7C642B35115D9A2E774.md) | 93

## Possible Misuse

*The following table contains possible examples of `wpr.exe` being misused. While `wpr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file wpr.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "WPR.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


