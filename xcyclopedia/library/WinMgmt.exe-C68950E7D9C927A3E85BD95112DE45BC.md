---
title: WinMgmt.exe | WMI Service Control Utility
excerpt: What is WinMgmt.exe?
---

# WinMgmt.exe 

* File Path: `C:\Windows\SysWOW64\wbem\WinMgmt.exe`
* Description: WMI Service Control Utility

## Hashes

Type | Hash
-- | --
MD5 | `C68950E7D9C927A3E85BD95112DE45BC`
SHA1 | `34A4012C9EB518446D76A26158FF980AF3CCF5FB`
SHA256 | `3815FC3FA1DCCCFA9B698A93501C9AB1FB466CBFB2B218630BCAA7B26F0D3FD1`
SHA384 | `4A47F536509BF94994085BCE6591C50A05F16AD2A41539DA1F08C39E1317BC403114FD95E6CFCE717BC773C159BC38D1`
SHA512 | `7467BA1E74C81B4237E32F5CCAD196091FE1228272CDD41D62BF3FA49D8D59EEE8D37A3BCADC4BE1DE3A7B013449F7379D3C08A2CF1501D4E60744D1B9B25ECE`
SSDEEP | `1536:77DN3bEqMHiqudShIPoANJLlAXuSXv+qSFEAeOFiD:bN3wqmushIPFJRAhP2EAeXD`
IMP | `8807B6357F8C4C979DE1B85769E34B08`
PESHA1 | `F2A02BDC118BF062FE86CE9194FA1CC4749D2B7E`
PE256 | `1AD695937328230C66E5AB636CF676B49EEE9A23D29159E90685DFC07E0B240E`

## Runtime Data

### Usage (stdout):
```cmhg
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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\wbem\WinMgmt.exe |


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/3815fc3fa1dcccfa9b698a93501c9ab1fb466cbfb2b218630bcaa7b26f0d3fd1/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-0BE7ED026AA1220DE3C2F099983E35CA.md) | 43
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-1EBB06162C3C56B97B98D144B00FFD28.md) | 43
[C:\windows\system32\wbem\wbemtest.exe](wbemtest.exe-5296801CCC59CE9ACCCD6B71C336FF6D.md) | 47
[C:\WINDOWS\system32\wbem\wbemtest.exe](wbemtest.exe-6C18ACC7CDEFAECAA87E3956BE3E5117.md) | 36
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-7191ED192D1E26E50B671C2AAD99D451.md) | 33
[C:\windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-092579DC0605F9E0AFC60F24E7B7FAAE.md) | 68
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-16960C591549024DE6400C41917BA082.md) | 71
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-2F273D2B73B94F799A2D822F25373013.md) | 68
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-7EEBC2D73DB966BC35A8031FA60FC161.md) | 74
[C:\WINDOWS\system32\wbem\WinMgmt.exe](WinMgmt.exe-A6C0A35BFA37660599DF474940FFD646.md) | 69
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-B4B55EE866E956C91700EAB60B878D7F.md) | 69
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-C484B6FDECA3277FE586925BBBA5EF7E.md) | 69
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-D96E50EFADC0675C470151AC6261F47C.md) | 72
[C:\Windows\SysWOW64\wbem\wbemcntl.dll](wbemcntl.dll-71797B2BDC1615C0546726E2D9120A75.md) | 36
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-3CCDE22442B58A5642B694F8157D0040.md) | 72
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-AE6F6C96E29E44B34CA7986E20D7562B.md) | 71
[C:\WINDOWS\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-B8FAB36A19DB84D93BB1DD037CEF60B7.md) | 71
[C:\windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-C6252D21A543F04AF3E7DAF358BE68A4.md) | 71




MIT License. Copyright (c) 2020-2021 Strontic.


