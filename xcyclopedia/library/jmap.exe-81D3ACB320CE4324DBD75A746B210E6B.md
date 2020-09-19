---
title: jmap.exe | OpenJDK Platform binary
---

# jmap.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jmap.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `81D3ACB320CE4324DBD75A746B210E6B`
SHA1 | `195AC7D95787DFB100B721FE311E357D4463816D`
SHA256 | `416C67284B447F49BA9AB66A5CA3D64762CF7F586DDF96E4E0189068EDE8FAB4`
SHA384 | `69EFEF87EE4C3683EC8A69BEE9ED4A5B9DE25BB068F395DAC54CD85C43A4AF956F91E5E416FCA059E18CECBA788F77AD`
SHA512 | `5308B3A6A0989D4881D5B0FE13A6CF89F31D8B8BFD7A0EAF678FC07C3520C068B6721CDC47F36F97E4D7FF6778A5D42892862A9EB24260C9DD7D33ADB57D3F62`
SSDEEP | `384:GpsJgvnvi1fqImSHhV828eeDcFK6jSPDgf2hTg:Gpsana18S/825eIKgKUf2hTg`

## Runtime Data

### Usage (stdout):
```cmhg
Attaching to remote server help, please wait...

```

### Usage (stderr):
```cmhg
Error attaching to remote server: java.rmi.ConnectException: Connection refused to host: 172.20.207.139; nested exception is: 
	java.net.ConnectException: Connection refused: connect
sun.jvm.hotspot.debugger.DebuggerException: java.rmi.ConnectException: Connection refused to host: 172.20.207.139; nested exception is: 
	java.net.ConnectException: Connection refused: connect
	at sun.jvm.hotspot.RMIHelper.lookup(RMIHelper.java:115)
	at sun.jvm.hotspot.HotSpotAgent.connectRemoteDebugger(HotSpotAgent.java:518)
	at sun.jvm.hotspot.HotSpotAgent.setupDebugger(HotSpotAgent.java:374)
	at sun.jvm.hotspot.HotSpotAgent.go(HotSpotAgent.java:304)
	at sun.jvm.hotspot.HotSpotAgent.attach(HotSpotAgent.java:183)
	at sun.jvm.hotspot.tools.Tool.start(Tool.java:196)
	at sun.jvm.hotspot.tools.Tool.execute(Tool.java:118)
	at sun.jvm.hotspot.tools.PMap.main(PMap.java:72)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at sun.tools.jmap.JMap.runTool(JMap.java:201)
	at sun.tools.jmap.JMap.main(JMap.java:130)
Caused by: java.rmi.ConnectException: Connection refused to host: 172.20.207.139; nested exception is: 
	java.net.ConnectException: Connection refused: connect
	at sun.rmi.transport.tcp.TCPEndpoint.newSocket(TCPEndpoint.java:623)
	at sun.rmi.transport.tcp.TCPChannel.createConnection(TCPChannel.java:216)
	at sun.rmi.transport.tcp.TCPChannel.newConnection(TCPChannel.java:202)
	at sun.rmi.server.UnicastRef.newCall(UnicastRef.java:343)
	at sun.rmi.registry.RegistryImpl_Stub.lookup(RegistryImpl_Stub.java:116)
	at java.rmi.Naming.lookup(Naming.java:101)
	at sun.jvm.hotspot.RMIHelper.lookup(RMIHelper.java:113)
	... 13 more
Caused by: java.net.ConnectException: Connection refused: connect
	at java.net.DualStackPlainSocketImpl.connect0(Native Method)
	at java.net.DualStackPlainSocketImpl.socketConnect(DualStackPlainSocketImpl.java:79)
	at java.net.AbstractPlainSocketImpl.doConnect(AbstractPlainSocketImpl.java:350)
	at java.net.AbstractPlainSocketImpl.connectToAddress(AbstractPlainSocketImpl.java:206)
	at java.net.AbstractPlainSocketImpl.connect(AbstractPlainSocketImpl.java:188)
	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:172)
	at java.net.SocksSocketImpl.connect(SocksSocketImpl.java:392)
	at java.net.Socket.connect(Socket.java:607)
	at java.net.Socket.connect(Socket.java:556)
	at java.net.Socket.<init>(Socket.java:452)
	at java.net.Socket.<init>(Socket.java:229)
	at sun.rmi.transport.proxy.RMIDirectSocketFactory.createSocket(RMIDirectSocketFactory.java:40)
	at sun.rmi.transport.proxy.RMIMasterSocketFactory.createSocket(RMIMasterSocketFactory.java:148)
	at sun.rmi.transport.tcp.TCPEndpoint.newSocket(TCPEndpoint.java:617)
	... 19 more


```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Users\user\AppData\Local\Temp\hsperfdata_user\2580 | File
(R-D)   C:\Windows\System32\en-US\kernel32.dll.mui | File
(RW-)   C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\lib\ext\jfxrt.jar | File
(RW-)   C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\lib\jfr.jar | File
(RW-)   C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\lib\jsse.jar | File
(RW-)   C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\lib\rt.jar | File
(RW-)   C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\lib\sa-jdi.jar | File
(RW-)   C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\lib\tools.jar | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_fd031af45b0106f2 | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\hsperfdata_user_2580 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section


### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jmap.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: jmap.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\wsgen.exe](wsgen.exe-F8437CEA06A787E6478E09BCC7881A53.md) | 61
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\wsimport.exe](wsimport.exe-0305766ED05D85C5B6BF0877F1A2AB70.md) | 58




MIT License. Copyright (c) 2020 Strontic.


