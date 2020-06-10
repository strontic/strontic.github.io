
# wpr.exe 
* File Path: `C:\WINDOWS\system32\wpr.exe`
* Description: Microsoft Windows Performance Recorder
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `AC101B88D4A649A7D2E7620C45EDE341`
SHA1 | `E53FD4A55C4D9D526357C73DA16844C955C324C0`
SHA256 | `EECBF924A2DFA96D2B585A9B5EDE60491841CA4D3AF9019A92946BA58B1F8D20`
SHA384 | `1F33455593462028A9D7223A363E8BE662975904CB8F16D85981DFF60806AB43B6E0BE3606CB269C5E25BFD3ECDF0BB4`
SHA415 | `68B015E1F837A2DD07C84F06726A683CCF942EEB8B581647FADA507E0FA765C33AF58B6261E4290B769F8806F50BB08EFF1D6D2AE4FD7495B91EB3D163F7BAD0`
SSDEEP | `6144:k8gUK8MM3AzJxeCQfBLzDQV8xlHeYYLQAdh5YC6piC/:BKtM3ACCkw++C`

## Runtime Data
### Usage (stdout):
```Batchfile

Microsoft Windows Performance Recorder Version 10.0.18362 (CoreSystem)
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
```Batchfile

	Invalid command syntax.

	Error code: 0xc5600602
	Invalid option: help

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WPR.exe
* Product Name: Microsoft Windows Performance Recorder
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.778 (WinBuild.160101.0800)
* Product Version: 10.0.18362.778
* Language: English (United States)
* Legal Copyright:  2019 Microsoft Corporation. All rights reserved.


