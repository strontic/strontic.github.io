---
title: WinMgmt.exe | WMI Service Control Utility
excerpt: What is WinMgmt.exe?
---

# WinMgmt.exe 

* File Path: `C:\Windows\system32\wbem\WinMgmt.exe`
* Description: WMI Service Control Utility

## Hashes

Type | Hash
-- | --
MD5 | `16960C591549024DE6400C41917BA082`
SHA1 | `A22F02418BD1D8569D4E7E0D95385A5640FE6D21`
SHA256 | `ACF5CB14318C8CCD2645F9F72A8885EF3631CED88EBF2B832DFA541373B062E3`
SHA384 | `B7BFCD03F85790705DBF8D5F3BBD667DED194EADDF87548C98811CE62EC3014C89CD6B212B85717AAD80C1549D315F58`
SHA512 | `F2AE52D1DF101166BF0E61FDCBB9464823AACAA79D4F526D43805DE73F8BCA3E0DAE314B18E9DF4755EA42EEFF146B5D8AAEB1472AF371E5D3FC724EE9CE2B63`
SSDEEP | `1536:O6/vNRQsuQivv2vdShIPoANJLlAXuSXv+qSFEAeOFi:tc2vshIPFJRAhP2EAeP`
IMP | `798ACA9C42114FEEB9FA9A5FD82CBA43`
PESHA1 | `A23BF496D4F683B72B1C865B430FB60A7A079D0D`
PE256 | `BC6F5E042A8DE63FCACEF093E1FADE8F9CD2236A2F68156BAA7C9B6D38250D3F`

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

### Child Processes:
powershell.exe

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wbem\WinMgmt.exe |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/acf5cb14318c8ccd2645f9f72a8885ef3631ced88ebf2b832dfa541373b062e3/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-0BE7ED026AA1220DE3C2F099983E35CA.md) | 43
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-1EBB06162C3C56B97B98D144B00FFD28.md) | 43
[C:\windows\system32\wbem\wbemtest.exe](wbemtest.exe-5296801CCC59CE9ACCCD6B71C336FF6D.md) | 47
[C:\WINDOWS\system32\wbem\wbemtest.exe](wbemtest.exe-6C18ACC7CDEFAECAA87E3956BE3E5117.md) | 38
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-7191ED192D1E26E50B671C2AAD99D451.md) | 33
[C:\windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-092579DC0605F9E0AFC60F24E7B7FAAE.md) | 75
[C:\WINDOWS\system32\wbem\WinMgmt.exe](WinMgmt.exe-2DF88907278A31C8110899B49F314176.md) | 82
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-2F273D2B73B94F799A2D822F25373013.md) | 80
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-7EEBC2D73DB966BC35A8031FA60FC161.md) | 77
[C:\WINDOWS\system32\wbem\WinMgmt.exe](WinMgmt.exe-A6C0A35BFA37660599DF474940FFD646.md) | 82
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-B4B55EE866E956C91700EAB60B878D7F.md) | 75
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-C484B6FDECA3277FE586925BBBA5EF7E.md) | 91
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-D96E50EFADC0675C470151AC6261F47C.md) | 80
[C:\Windows\SysWOW64\wbem\wbemcntl.dll](wbemcntl.dll-71797B2BDC1615C0546726E2D9120A75.md) | 35
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-3CCDE22442B58A5642B694F8157D0040.md) | 79
[C:\WINDOWS\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-92F019DB0F8F8E1411B721700386834E.md) | 75
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-AE6F6C96E29E44B34CA7986E20D7562B.md) | 72
[C:\WINDOWS\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-B8FAB36A19DB84D93BB1DD037CEF60B7.md) | 66
[C:\windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-C6252D21A543F04AF3E7DAF358BE68A4.md) | 68
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-C68950E7D9C927A3E85BD95112DE45BC.md) | 71




MIT License. Copyright (c) 2020-2021 Strontic.


