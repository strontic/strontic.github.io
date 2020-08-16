---
title: clhsdb.exe | OpenJDK Platform binary
---

# clhsdb.exe 

* File Path: `C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\clhsdb.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `0F18256DEF0978CC2212F4D67B003C2A`
SHA1 | `25683D23C120F463B96897AB5EDD2DD300BE4962`
SHA256 | `EDD0B37613FDCE61028E0073D1B704CBEFE0ECAF4EB66DEEA7EF62D8B1154F30`
SHA384 | `D420C062F0C362BFC4B3D87EC9BE007B3ED6C3F71491D3AF17AF904EF3870558F898B4AD2FE86834889B7A61353F321E`
SHA512 | `1B6E22D9431B8588FBD0FAB6793BA69BA4FA7A276D833A22CD84FBE3E31298BA705085A46AE95F753D2E9C3AC629177B914DD0961F0AC06548C4AD3CA0773298`
SSDEEP | `384:GpsMJRn1qEmSHhV84QeetcYK6jShjZlDgf2h3N:Gps+neS/84le/Kg0HUf2h9`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage:  clhsdb [[pid] | [path-to-java-executable [path-to-corefile]] | help | -help ]
           pid:                     attach to the process whose id is 'pid'
           path-to-java-executable: Debug a core file produced by this program
           path-to-corefile:        Debug this corefile.  The default is 'core'
        If no arguments are specified, you can select what to do from the GUI.

hsdb> 
```

### Usage (stderr):
```Batchfile
Opening core file, please wait...
Unable to open core file
core:

Windbg Error: OpenDumpFile failed!
sun.jvm.hotspot.debugger.DebuggerException: Windbg Error: OpenDumpFile failed!
	at sun.jvm.hotspot.debugger.windbg.WindbgDebuggerLocal.attach0(Native Method)
	at sun.jvm.hotspot.debugger.windbg.WindbgDebuggerLocal.attach(WindbgDebuggerLocal.java:160)
	at sun.jvm.hotspot.HotSpotAgent.attachDebugger(HotSpotAgent.java:673)
	at sun.jvm.hotspot.HotSpotAgent.setupDebuggerWin32(HotSpotAgent.java:569)
	at sun.jvm.hotspot.HotSpotAgent.setupDebugger(HotSpotAgent.java:335)
	at sun.jvm.hotspot.HotSpotAgent.go(HotSpotAgent.java:304)
	at sun.jvm.hotspot.HotSpotAgent.attach(HotSpotAgent.java:156)
	at sun.jvm.hotspot.CLHSDB.attachDebugger(CLHSDB.java:203)
	at sun.jvm.hotspot.CLHSDB.run(CLHSDB.java:63)
	at sun.jvm.hotspot.CLHSDB.main(CLHSDB.java:40)

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: clhsdb.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jimage.exe](jimage.exe-52585947B2B10A2C41E370B60D85A837.md) | 44




MIT License. Copyright (c) 2020 Strontic.


