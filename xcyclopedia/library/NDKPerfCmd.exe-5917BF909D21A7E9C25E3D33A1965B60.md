---
title: NDKPerfCmd.exe | RDMA Perf Cmd
excerpt: What is NDKPerfCmd.exe?
---

# NDKPerfCmd.exe 

* File Path: `C:\WINDOWS\system32\NDKPerfCmd.exe`
* Description: RDMA Perf Cmd

## Hashes

Type | Hash
-- | --
MD5 | `5917BF909D21A7E9C25E3D33A1965B60`
SHA1 | `7ACC760A5B8668DC4763FE897BD75EDA4A072BD0`
SHA256 | `1D0EAFE7F26749E712D313597F90C502584E0246CDF07B0E654898C9D82E6899`
SHA384 | `D14FB7BE9C9A03F5FFD5703CB9559AB7BFDC8B4E83CF078548800FD3212898DA1C468F143266B10208998CEE063F7682`
SHA512 | `E03A9FC41D90E8C5E583443A1B1DEF7C4B83AED7164B041D53F37297AB84D8C77C1CCE49602C8D1E38BF929CD7E970F9FBF2A1FB8C4CFF454F2544C01F52864D`
SSDEEP | `384:b8HRuaZmZ1Ve5+sCi9iAjX3LZjigCCRfEIVBWPfWbDBRJlbzl9V:QX21MwsDxjiMhEIVGi1PlbF`
IMP | `7DA48A208498A9FA7B90D053471C59D9`
PESHA1 | `71E469CF1D78750E6A733051F59C05F4B0B144E0`
PE256 | `B825379336064548A02A91B37F92F9C0464856D4229BE90C78AAC94CA4B0D01E`

## Runtime Data

### Usage (stdout):
```cmhg
NDKPerfCmd.exe can run on a system as Server or Client.
Run as a Server:
	 -S -- Specify that the system will be a Server.
	 -ServerAddr <ServerIPAddress>:<ServerPort> -- Specify ip address of the server and the port on which to listen in format of ipServer:portServer.
	 -ServerIf <ServerInterfaceIndex> -- Specify the interface index for the server.
	 -TestType <TestType> -- Specify the type of test to run.
	 -W <Timeout> -- Specify the timeout of Server Listen socket, in seconds. If this parameter is not specified, will wait infinitely.

Run as a Client:
	 -C -- Specify that the system will be a Client.
	 -ServerAddr <ServerIPAddress>:<ServerPort> -- Specify ip address of the server and the port on which to listen in format of ipServer:portServer.
	 -ClientAddr <ClientIPAddress> -- Specify the ip address of the Client.
	 -ClientIf <ClientInterfaceIndex> -- Specify the interface index for the Client.
	 -LogFilename <LogFileName> -- Specify NDKPerfCmd test results log file name, relative path or full path.
	                               (Default: [systemdrive]\NDKPerfResults.log). On client side only.
	 -A -- Specify that at client side NDKPerfCmd test results should be appended to the log file if it already exists.
	 -V -- Specify that at client side NDKPerfCmd test results should be printed out on screen except being stored in a log file.
	 -TestType <TestType> -- Specify the type of test to run, rping or rperf.

	 -ts <TransferSize> -- Specify the size of data to transfer (in bytes).

TestType Options: (Server and Client must be with same TestType)
	 rping -- Tests RDMA connectivity with Send/Receive transfers and logs the status of each of them.

	 rperf -- Tests RDMA congestion with Send/Receive transfers and logs the status of each of them.

	 Read/Write tests will be in future version!!! 

Usage Sample:
	 As a Server:
	             NDKPerfCmd.exe -S -ServerAddr 10.10.10.10:55555 -ServerIf 3 -TestType rping -W 60 
	 As a Client:
	             NDKPerfCmd.exe -C -ServerAddr 10.10.10.10:55555 -ClientAddr 10.10.10.11 -ClientIf 4 -TestType rping -LogFilename .\NDKPerfResults.log -V 

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\NDKPerfCmd.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RdmaPerf.sys
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/1d0eafe7f26749e712d313597f90c502584e0246cdf07b0e654898c9d82e6899/detection





MIT License. Copyright (c) 2020-2021 Strontic.


