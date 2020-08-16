---
title: NDKPing.exe | RDMA Ping Cmd
---

# NDKPing.exe 

* File Path: `C:\Windows\system32\NDKPing.exe`
* Description: RDMA Ping Cmd

## Hashes

Type | Hash
-- | --
MD5 | `5FC26E00B9012CC0188F65BB999174E9`
SHA1 | `84B873DA341D53FBA671C10869F02AC8B8507E13`
SHA256 | `E2E6EA04DB42F5ABD29C767681798B070A25B0768106689E36613B2E3A810170`
SHA384 | `08298EF487B0BC404F1146D427947BD08D2FD5668A17A9FDA0284E4F3BFDD024CF466145849289AFFEDAAD09FD780295`
SHA512 | `BE5EBF8E75808048357303DCDB6B908E8C8E64B15E3225256957B49E45E42E3216E693A43AAC9B6432E711F657366D6C091F86790D719A276E8D2AB445AE087F`
SSDEEP | `384:AuO3duY0GpGl3/gqnjpXi9iAK8HZeiKoWtl4t82foWYWWDD1IDBRJJuhKtklxt:TO3W02njIPei0tlg82fK9I1PG`

## Runtime Data

### Usage (stdout):
```Batchfile
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

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RdmaPing.sys
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Common Files\Microsoft Shared\ink\TabTip32.exe](TabTip32.exe-DCB3378628CC715C93B9D53DF1857029.md) | 35
[C:\Windows\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-9B19B73580F7813DAD7C7C4671D004E5.md) | 29
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-8159944C79034D2BCABF73D461A7E643.md) | 27
[C:\WINDOWS\system32\DeviceCensus.exe](DeviceCensus.exe-AC7BD0E738FDE12FB29DA98D88C903EA.md) | 27
[C:\Windows\system32\dllhost.exe](dllhost.exe-C6723950D1A8CD49D93C8D082B175D41.md) | 43
[C:\WINDOWS\system32\NDKPing.exe](NDKPing.exe-E9AD6C80432ABCAF0F562FA3452C92F4.md) | 41
[C:\Windows\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-EA059E3BA7E07347BDE08EF016E09D50.md) | 29
[C:\Windows\system32\prproc.exe](prproc.exe-912400A90CA88E80ABC6CB8F30C1BB41.md) | 32
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-100E032F234550530487627EC8FACAA8.md) | 35
[C:\WINDOWS\system32\ResetEngine.exe](ResetEngine.exe-5A802B773089A709FC7E731368C4E328.md) | 27
[C:\WINDOWS\system32\ScriptRunner.exe](ScriptRunner.exe-C024FF9A88E26EEB26A1A942260489BC.md) | 33
[C:\Windows\system32\SlideToShutDown.exe](SlideToShutDown.exe-FD18CDC89BFD664E85644B460C37D85B.md) | 35
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-7582BF723A39B56BCCEF2C170E330BD7.md) | 33
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-8B50BFD5811304543479B20D0A281C56.md) | 33
[C:\Windows\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-AB2C7BC86F9E1BB245E43C81A01A7380.md) | 25
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-BE467A8F33CDEB0538E98CF10101E9E0.md) | 32




MIT License. Copyright (c) 2020 Strontic.


