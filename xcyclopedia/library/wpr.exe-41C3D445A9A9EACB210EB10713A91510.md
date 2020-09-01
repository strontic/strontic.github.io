---
title: wpr.exe | Microsoft Windows Performance Recorder
---

# wpr.exe 

* File Path: `C:\Windows\system32\wpr.exe`
* Description: Microsoft Windows Performance Recorder

## Hashes

Type | Hash
-- | --
MD5 | `41C3D445A9A9EACB210EB10713A91510`
SHA1 | `43FA01FCBEAFF0FD91D3B013EB3731FD0BB9B72E`
SHA256 | `FA94893095A4879B1C0B8994440B786D3AED8FEAA4B785388784B4FC14DFBED4`
SHA384 | `B71457D42F066E776D0496D8C938DB0D2B826D2C9A5E080846BE46201D45AF0C23331E9B0B44222661013DF45A93BE30`
SHA512 | `D0D15A3ED7D6E08985572BC29BFF427657C601A840B173A477C2E5CEF1F6CC0E5567E5CEC0DD2F69992698AB292055A66B19AA49BA5F1AD6B5CEEAC2438F8C36`
SSDEEP | `3072:AOP1GQlPB5MwJtDNCjiimHxEVfNAzMYOzycVbaVlc2C+FtGeZs2TLxl7KJ39vxOX:AOf5rtcjiiDNMXOWcmlJIeGAS3`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft Windows Performance Recorder Version 10.0.14393 (CoreSystem)
Copyright (c) 2015 Microsoft Corporation. All rights reserved.

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
	-log			 - Configure debug logging to the event log
	-disablepagingexecutive	 - Change the Disable Paging Executive settings
	-heaptracingconfig	 - Change heap tracing settings for a process
	-capturestateondemand	 - Capture states for the configured providers in the current recording
	-pmcsources		 - Query the list of hardware counters available on the system
	-setprofint		 - Set sampled profile interval
	-profint		 - Query the current profile interval
	-resetprofint		 - Restores the default profile interval values

```

### Usage (stderr):
```Batchfile

	Invalid command syntax.

	Error code: 0xc5600602
	Invalid option: help

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


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
* File Version: 10.0.14393.2969 (rs1_release.190503-1820)
* Product Version: 10.0.14393.2969
* Language: English (United States)
* Legal Copyright:  2015 Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `wpr.exe` being misused. While `wpr.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) |       description = "Windows Password Recovery - file wpr.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) |       $s1 = "WPR.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


