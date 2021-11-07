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
MD5 | `2F273D2B73B94F799A2D822F25373013`
SHA1 | `1B4F5094B0CEEF8ECE93B1CEE3AA0DBA8C92E31A`
SHA256 | `9587494C2CCB011BD1DD77500B4D6840268AFD6C567DFD0BEAC51ED3C92147D0`
SHA384 | `FD44F85EEC164639A70D570E32AF8BF6D3BA473EB67A13A9A151A9AD1E8F10F65BBE9FE2B0ACCECC0F905743ACDF5973`
SHA512 | `E090FB7A306361A4B92AD9F87F0F8A100B81996D9B0512A36FF8231062ECE347500952DAC775C5AE98616825882931A1039BFB7E05D1FEE73B2AADD62AC387FE`
SSDEEP | `1536:ob/PdxA8uRzZbvvAvdShIPoANJLlAXuSXv+qSFEAeOFg:eEAvshIPFJRAhP2EAeB`
IMP | `798ACA9C42114FEEB9FA9A5FD82CBA43`
PESHA1 | `A6A67C90FDB8ED2652DE51D60388F935154A71FF`
PE256 | `9AA28E8144BE49E8E8D23DC665F8639EAEF90C16DF6C676B9A5752897DDB885C`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wbem\WinMgmt.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/9587494c2ccb011bd1dd77500b4d6840268afd6c567dfd0beac51ed3c92147d0/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-0BE7ED026AA1220DE3C2F099983E35CA.md) | 40
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-1EBB06162C3C56B97B98D144B00FFD28.md) | 43
[C:\windows\system32\wbem\wbemtest.exe](wbemtest.exe-5296801CCC59CE9ACCCD6B71C336FF6D.md) | 50
[C:\WINDOWS\system32\wbem\wbemtest.exe](wbemtest.exe-6C18ACC7CDEFAECAA87E3956BE3E5117.md) | 38
[C:\Windows\system32\wbem\wbemtest.exe](wbemtest.exe-7191ED192D1E26E50B671C2AAD99D451.md) | 35
[C:\windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-092579DC0605F9E0AFC60F24E7B7FAAE.md) | 75
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-16960C591549024DE6400C41917BA082.md) | 80
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-7EEBC2D73DB966BC35A8031FA60FC161.md) | 77
[C:\WINDOWS\system32\wbem\WinMgmt.exe](WinMgmt.exe-A6C0A35BFA37660599DF474940FFD646.md) | 82
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-B4B55EE866E956C91700EAB60B878D7F.md) | 75
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-C484B6FDECA3277FE586925BBBA5EF7E.md) | 80
[C:\Windows\system32\wbem\WinMgmt.exe](WinMgmt.exe-D96E50EFADC0675C470151AC6261F47C.md) | 97
[C:\Windows\SysWOW64\wbem\wbemcntl.dll](wbemcntl.dll-71797B2BDC1615C0546726E2D9120A75.md) | 40
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-3CCDE22442B58A5642B694F8157D0040.md) | 72
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-AE6F6C96E29E44B34CA7986E20D7562B.md) | 72
[C:\WINDOWS\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-B8FAB36A19DB84D93BB1DD037CEF60B7.md) | 69
[C:\windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-C6252D21A543F04AF3E7DAF358BE68A4.md) | 68
[C:\Windows\SysWOW64\wbem\WinMgmt.exe](WinMgmt.exe-C68950E7D9C927A3E85BD95112DE45BC.md) | 68




MIT License. Copyright (c) 2020-2021 Strontic.


