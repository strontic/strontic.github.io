---
title: NDKPing.exe | RDMA Ping Cmd
---

# NDKPing.exe 

* File Path: `C:\WINDOWS\system32\NDKPing.exe`
* Description: RDMA Ping Cmd
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E9AD6C80432ABCAF0F562FA3452C92F4`
SHA1 | `0DAA1DB3F9692B350BE7DE3FC2E410C7354C0B1A`
SHA256 | `6B5E04C6CC05B0F9B48B6512FFE8990BE535B30CABF618A3CCBBEAFAE7715E8F`
SHA384 | `17ABE2B5B6CB6343B0AB2B0CF33DBF2ED9BC597E94D1DD3CDDAEC8BEDAB1D22C1A8F7583C74BCFA826BE4A1195FCE56A`
SHA512 | `E2F1B8C8A70441578C4CB455020A94B8E54F74B3959D914A82A9D1887CBDE5CCDEF774956AA812565BCF5ADC0B9FD994723CAF2F04F31C2036B30304772C8D8F`
SSDEEP | `384:20fVRIE2MvvcSji9iAK8HZeiKoKO77282fgWJWW:2k8ESSSPeiMOG82fH`

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

### Usage (stderr):
```Batchfile

Error: Unable to stop NDKPing driver.
5: Access is denied.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RdmaPing.sys
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


