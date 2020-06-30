---
title: WinMgmt.exe | WMI Service Control Utility
---

# WinMgmt.exe 

* File Path: `C:\Windows\system32\wbem\WinMgmt.exe`
* Description: WMI Service Control Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B4B55EE866E956C91700EAB60B878D7F`
SHA1 | `82DD71E42D461688FDE081AE8863DB63389B5B92`
SHA256 | `A2FC74C6F75FC247659A6B26165116D9E76AE0EF9E540D231698FEA5F61C8273`
SHA384 | `1E995705D31364971EFB62F0800D62C30C8E9DE8BDEF0905B45F8CE6B9B17AB17550BADEED2CB1D9BC84290C8DEE87AF`
SHA512 | `461EA9A10A0381B93F747A967A925798A6188F10A3AB9EEED6F3DE4046BBDC6FBCBFFCDB1BEF4B4C6FEED02893D434CECDBBEEE78E84E377FBCF9775F9624B04`
SSDEEP | `1536:1yuaAl4zh/qsMw7XHdShIPoANJLlAXuSXv+qSFEAeOFd:1k9HshIPFJRAhP2EAeU`

## Runtime Data

### Usage (stdout):
```Batchfile
Invalid parameter

Windows Management Instrumentation

Usage:  winmgmt	[/backup <filename>] [/restore <filename> <flag>]
		[/resyncperf] [/standalonehost [<level>]] [/sharedhost]
		[/verifyrepository [<path>]] [/salvagerepository]
		[/resetrepository]

/backup <filename>
	Causes WMI to back up the repository to the specified file name. The
	filename argument should contain the full path to the file location.
	This process requires a write lock on the repository so that write
	operations to the repository are suspended until the backup process is
	completed.

/restore <filename> <flag>
	Manually restores the WMI repository from the specified backup file.
	The filename argument should contain the full path to the backup file
	location. To perform the restore operation, WMI saves the existing
	repository to write back if the operation fails. Then the repository is
	restored from the backup file that is specified in the filename
	argument. If exclusive access to the repository cannot be achieved,
	existing clients are disconnected from WMI. The flag argument must be a
	1 (force - disconnect users and restore) or 0 (default - restore if no
	users connected) and specifies the restore mode.

/resyncperf
	Registers the system performance libraries with WMI.

/standalonehost [<level>]
	Moves the Winmgmt service to a standalone Svchost process that has a
	fixed DCOM endpoint. The default endpoint is "ncacn_ip_tcp.0.24158".
	However, the endpoint may be changed by running Dcomcnfg.exe. The level
	argument is the authentication level for the Svchost process. If level
	is not specified, the default is 4 (RPC_C_AUTHN_LEVEL_PKT).

/sharedhost
	Moves the Winmgmt service into the shared Svchost process.

/verifyrepository [<path>]
	Performs a consistency check on the WMI repository. When you add the
	/verifyrepository switch without the <path> argument, then the live
	repository currently used by WMI is verified. When you specify the path
	argument, you can verify any saved copy of the repository. In this
	case, the path argument should contain the full path to the saved
	repository copy. The saved repository should be a copy of the entire
	repository folder.

/salvagerepository
	Performs a consistency check on the WMI repository, and if an
	inconsistency is detected, rebuilds the repository.  The content of the
	inconsistent repository is merged into the rebuilt repository, if it
	can be read. The salvage operation always works with the repository
	that the WMI service is currently using. MOF files that contain the
	#pragma autorecover preprocessor statement are restored to the
	repository.

/resetrepository
	The repository is reset to the initial state when the operating system
	is first installed. MOF files that contain the #pragma autorecover
	preprocessor statement are restored to the repository.


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winmgmt.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-0BE7ED026AA1220DE3C2F099983E35CA.md) | 40
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-1EBB06162C3C56B97B98D144B00FFD28.md) | 43
[C:\WINDOWS\system32\wbem\wbemtest.exe](wbemtest.exe-6C18ACC7CDEFAECAA87E3956BE3E5117.md) | 38
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-7191ED192D1E26E50B671C2AAD99D451.md) | 35
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-7EEBC2D73DB966BC35A8031FA60FC161.md) | 82
[C:\WINDOWS\system32\wbem\WinMgmt.exe](WinMgmt.exe-A6C0A35BFA37660599DF474940FFD646.md) | 77
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-D96E50EFADC0675C470151AC6261F47C.md) | 75
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-3CCDE22442B58A5642B694F8157D0040.md) | 79
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-AE6F6C96E29E44B34CA7986E20D7562B.md) | 79
[C:\WINDOWS\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-B8FAB36A19DB84D93BB1DD037CEF60B7.md) | 66
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-C68950E7D9C927A3E85BD95112DE45BC.md) | 69




MIT License. Copyright (c) 2020 Strontic.


