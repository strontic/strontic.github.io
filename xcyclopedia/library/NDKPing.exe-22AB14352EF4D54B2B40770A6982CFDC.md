---
title: NDKPing.exe | RDMA Ping Cmd
excerpt: What is NDKPing.exe?
---

# NDKPing.exe 

* File Path: `C:\WINDOWS\system32\NDKPing.exe`
* Description: RDMA Ping Cmd

## Hashes

Type | Hash
-- | --
MD5 | `22AB14352EF4D54B2B40770A6982CFDC`
SHA1 | `9F39D06501F0E8862D2ABC5F248433860EEA36B0`
SHA256 | `F92CBFBD8BABF5DA4F0406C2C7D92AF00A6C45806F1AB856611F8F7FB4359379`
SHA384 | `DF7EA81A6EC664DD9A7F5141584053A54806762D07AF3AB30FA4796C7E1CA137091F26D68F606AA665AA1FEDDAB1C73A`
SHA512 | `3184D9B0B28D203E60AE223C646A5CA3106D5E24A25A948D9FBE2FB8638DE8EAFB32867A97B3DF84C13B4CE0E5ACAF207C149AA783558529FA44911BAE4A3A9C`
SSDEEP | `384:i8jyC96x0ZcUuk021i9iAK8HZeiKoiLxIW82fzWXWWkDBRJ7filZ8:R6xMcpVPeieaW82fYM1P7L`
IMP | `17F5437822DB9AF8E58AE3971B905F6C`
PESHA1 | `CFEC4A85326C304645D01BA1DF31D43CC9E9C4F4`
PE256 | `C0730CA5A1022B1E1459C11F0999DC7DEE3654908ED182D00CF7FC978C9ED28E`

## Runtime Data

### Usage (stdout):
```cmhg
NDKPing can run on a system as Server or Client.
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
	 -LogFilename <LogFileName> -- Specify NDKPing test results log file name, relative path or full path.
	                               (Default: [systemdrive]\NDKPingResults.log). On client side only.
	 -A -- Specify that at client side NDKPing test results should be appended to the log file if it already exists.
	 -V -- Specify that at client side NDKPing test results should be printed out on screen except being stored in a log file.
	 -TestType <TestType> -- Specify the type of test to run.

TestType Options: (Server and Client must be with same TestType)
	 rping -- Tests RDMA connectivity with Send/Receive transfers and logs the status of each of them.

	 Read/Write tests will be in future version!!! 

Usage Sample:
	 As a Server:
	             NDKPing -S -ServerAddr 10.10.10.10:55555 -ServerIf 3 -TestType rping -W 60 
	 As a Client:
	             NDKPing -C -ServerAddr 10.10.10.10:55555 -ClientAddr 10.10.10.11 -ClientIf 4 -TestType rping -LogFilename .\NDKPingResults.log -V 

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\NDKPing.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RdmaPing.sys
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/f92cbfbd8babf5da4f0406c2c7d92af00a6c45806f1ab856611f8f7fb4359379/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\NDKPing.exe](NDKPing.exe-5FC26E00B9012CC0188F65BB999174E9.md) | 46
[C:\WINDOWS\system32\NDKPing.exe](NDKPing.exe-E9AD6C80432ABCAF0F562FA3452C92F4.md) | 44




MIT License. Copyright (c) 2020-2021 Strontic.


