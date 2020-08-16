---
title: jinfo.exe | OpenJDK Platform binary
---

# jinfo.exe 

* File Path: `C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jinfo.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `536380B9EDDA1DC69DB259C3D1715DF0`
SHA1 | `66D02E4B39ABE5C2E2CC4C9BC1C50FA28C0B94F4`
SHA256 | `8517557722A9C266DEA8981A9B4B2B1A57972A5F02C9673977BE589B78014DEA`
SHA384 | `0FB6FF0C607EDA81275484A7764042B538D93A03EBDA9D24FD34ECFD1CC6E9E4C0CED893FB4E94F157D7AE567538503B`
SHA512 | `1AE6B9C53C7879AE7C51E4CA2660AA1DEBAE03E6CADC0DCEFCD7B0D2CB56A7694582BE63F954A9DDAD5A01498B0686723E0B50ACF42AA39AE1F05C3BF9B3F61F`
SSDEEP | `384:Gps3gvnvB1fqolmSHhV83Ieeqc5K6jSnnhkDgf2hii:GpsAnp15AS/839eNKgAnhkUf2h9`

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
	at sun.jvm.hotspot.tools.JInfo.main(JInfo.java:138)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at sun.tools.jinfo.JInfo.runTool(JInfo.java:108)
	at sun.tools.jinfo.JInfo.main(JInfo.java:76)
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

* Original Filename: jinfo.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\hsdb.exe](hsdb.exe-7F335E40D9BD7CE769BCD22ED86643F2.md) | 63
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jstatd.exe](jstatd.exe-A53DBF1919BB8F028056008F6F017DF0.md) | 57




MIT License. Copyright (c) 2020 Strontic.


