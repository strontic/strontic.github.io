---
title: jstack.exe | OpenJDK Platform binary
---

# jstack.exe 

* File Path: `C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jstack.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `40BD00F58280DE28F726136775D3B6DA`
SHA1 | `10312AAA900BE6C6E82DA676E72CDCD941DD8AF4`
SHA256 | `15A358083A8F616A9D22A29AB92575FFB207F4BE7382BBDC3E52F39BD8BCFD2D`
SHA384 | `F094A7C82E90B17647E6016B4F15E31B01DE1CF73C4B78AE413F3C3A6C42E4DFF2EC7002591B4A40F93727C92B4156B8`
SHA512 | `66FB3EF0020BBBCF89D2A9841D38AD80E4B5FA2FD9CF2347FA108FC9103BAFFCC0EC07AED5329DF361451A2A168886B5C227518212B544637426A92ACC084853`
SSDEEP | `384:GpsSgvnvf1fqLmSHhV8aceetcdK6jSOWDgf2hx:GpsznH1zS/8aZeOKg1WUf2hx`

## Runtime Data

### Usage (stdout):
```Batchfile
Attaching to remote server help, please wait...

```

### Usage (stderr):
```Batchfile
Error attaching to remote server: java.net.MalformedURLException: invalid character, '?', in URL name: ///?/SARemoteDebugger
sun.jvm.hotspot.debugger.DebuggerException: java.net.MalformedURLException: invalid character, '?', in URL name: ///?/SARemoteDebugger
	at sun.jvm.hotspot.RMIHelper.lookup(RMIHelper.java:115)
	at sun.jvm.hotspot.HotSpotAgent.connectRemoteDebugger(HotSpotAgent.java:518)
	at sun.jvm.hotspot.HotSpotAgent.setupDebugger(HotSpotAgent.java:374)
	at sun.jvm.hotspot.HotSpotAgent.go(HotSpotAgent.java:304)
	at sun.jvm.hotspot.HotSpotAgent.attach(HotSpotAgent.java:183)
	at sun.jvm.hotspot.tools.Tool.start(Tool.java:196)
	at sun.jvm.hotspot.tools.Tool.execute(Tool.java:118)
	at sun.jvm.hotspot.tools.JStack.main(JStack.java:92)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at sun.tools.jstack.JStack.runJStackTool(JStack.java:140)
	at sun.tools.jstack.JStack.main(JStack.java:106)
Caused by: java.net.MalformedURLException: invalid character, '?', in URL name: ///?/SARemoteDebugger
	at java.rmi.Naming.intParseURL(Naming.java:282)
	at java.rmi.Naming.parseURL(Naming.java:237)
	at java.rmi.Naming.lookup(Naming.java:96)
	at sun.jvm.hotspot.RMIHelper.lookup(RMIHelper.java:113)
	... 13 more


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

* Original Filename: jstack.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\javac.exe](javac.exe-3A9578BFD3BB7869169BAC29E497AF55.md) | 60




MIT License. Copyright (c) 2020 Strontic.


