---
title: wpr.exe | Microsoft Windows Performance Recorder
excerpt: What is wpr.exe?
---

# wpr.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\wpr.exe`
* Description: Microsoft Windows Performance Recorder

## Hashes

Type | Hash
-- | --
MD5 | `3836F328B1E6F7C642B35115D9A2E774`
SHA1 | `E584719FE68C2482E2B0F4042148442F53BB5757`
SHA256 | `A368454E020E720987DED3D604D654F6314803397153D64D0D2744401B3FF11F`
SHA384 | `BA2F75DA6D628627B25BD29A8B8F77B9608116FDAE52DF630D3276E47612520EE86F3DBDAF8348C54B3C1F9755E23030`
SHA512 | `E165855D0B56FE250C3D2FEC53C997D94B9A86B5F1A8D41E7218438EEF06A26B76866B0F447AB14AA995E8B7EC989605E37B8518CA25C6494CCBE98FFE935910`
SSDEEP | `6144:FgtvJfDldaBXZd0PaHw/kDeuiEKvK5cnbhbYk06S0Rj:2ZJfreXZd0pseuiISX/X1`
IMP | `E61CD2AA90474CA9DFFAD3043C7DA49E`
PESHA1 | `C6A075712C6F0CF95E9919965A77B476EF335455`
PE256 | `CC1558826C64A2A8C0C10BD9C9031A827DA7D9D781A1CDDA3302F3859A223B59`

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
C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\wpr.exe |
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

* Original Filename: WPR.exe
* Product Name: Microsoft Windows Performance Recorder
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  2019 Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/a368454e020e720987ded3d604d654f6314803397153d64d0d2744401b3ff11f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wpr.exe](wpr.exe-6E4BF60ABB6F9373D5C795D7CD7EDF68.md) | 93

## Possible Misuse

*The following table contains possible examples of `wpr.exe` being misused. While `wpr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "Windows Password Recovery - file wpr.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "WPR.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


