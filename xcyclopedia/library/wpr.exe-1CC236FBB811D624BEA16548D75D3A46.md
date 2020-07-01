---
title: wpr.exe | Microsoft Windows Performance Recorder
---

# wpr.exe 

* File Path: `C:\windows\system32\wpr.exe`
* Description: Microsoft Windows Performance Recorder
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1CC236FBB811D624BEA16548D75D3A46`
SHA1 | `52E2454464DEDD872218A4B3AFA74B573CFA71D2`
SHA256 | `37869599B8F17A1D5F7BF91A20A1CE4555919A4758078FFE8DDDAD422BE5CCAA`
SHA384 | `E1CD5530816B663204511ECEBA8AEACEBB3C859AE77CD921AB6692F29A86DBF884095DAE6D2FF356031A8DDBB4CC2B71`
SHA512 | `E3AF862AE5D47E0DEE7356A45E740A8FA5F5305FD834C4BE3517E00DA457B0514C7F0E173D1509C653BAF78444EA71AB1C76D2FF41A433110FA33658DC4F4733`
SSDEEP | `6144:kUgeiahIngARB1uU5cwmwoL59jaTg85YtcpwCXE:FIbuU5cwtoHja01lCX`

## Runtime Data

### Usage (stdout):
```Batchfile

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
```Batchfile

	Invalid command syntax.

	Error code: 0xc5600602
	Invalid option: help

```

### Child Processes:


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





MIT License. Copyright (c) 2020 Strontic.


