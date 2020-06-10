
# WinMgmt.exe 
* File Path: `C:\Windows\SysWOW64\wbem\WinMgmt.exe`
* Description: WMI Service Control Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `AE6F6C96E29E44B34CA7986E20D7562B`
SHA1 | `0F56469166D098E8184281C6E7681B9D5D67D101`
SHA256 | `99F019D890F61A347AFA059FD82CF1A875363D8DFA50D14D040BA289F72ABA92`
SHA384 | `C85455ACCF50A15D62BB9102F7064D50B74C1F2F6606E6B0AD492A2C2EE6A3E03DA145117F1358FF52B99F7414AB0CA2`
SHA415 | `C207EE8D05FF5A13C27F3A4F1978FB1E68613B905E1168D1C513C7A0310C4B6D2C0419980621782A041C65809A7E327C65E737512DC8324C052B3C477883371D`
SSDEEP | `1536:aO1GBuMQuZ+dShIPoANJLlAXuSXv+qSFEAeOFdj:rsuM+shIPFJRAhP2EAeU`

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
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
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


