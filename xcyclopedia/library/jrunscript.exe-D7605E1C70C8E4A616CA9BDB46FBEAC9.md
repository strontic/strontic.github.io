---
title: jrunscript.exe | OpenJDK Platform binary
excerpt: What is jrunscript.exe?
---

# jrunscript.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jrunscript.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `D7605E1C70C8E4A616CA9BDB46FBEAC9`
SHA1 | `5F0BD7C65A6D189C6A904240307CD2E473B8C395`
SHA256 | `042574F95B7FBAD639F239E95DA1D1C5F1A85D20F42D8D692D870592323B06B7`
SHA384 | `463C3C1DF4D12E6A8B784FC84333FA578E6E63877B1706698A938645DCF5F03FB90B493C10381605B50DEEADB34E1192`
SHA512 | `ADC45F6834A2E037462A82C1B9E9116631A946D4C55FBC97A8F1939791D3790E9693F14CBF6626E9F8C494B191D71F53B8586BAB67E9734F319D28FD45409608`
SSDEEP | `384:Gpsu5hnmqnmSHhV8j6ee44Sz4K6jS39Q0SDgf2hHM:GpsgneS/8jne4WKgCSUf2hs`

## Runtime Data

### Usage (stderr):
```cmhg
Usage: jrunscript [options] [arguments...]

where [options] include:
  -classpath <path>    Specify where to find user class files 
  -cp <path>           Specify where to find user class files 
  -D<name>=<value>     Set a system property 
  -J<flag>             Pass <flag> directly to the runtime system 
  -l <language>        Use specified scripting language 
  -e <script>          Evaluate given script 
  -encoding <encoding> Specify character encoding used by script files 
  -f <script file>     Evaluate given script file 
  -f -                 Interactive mode, read script from standard input 
                       If this is used, this should be the last -f option 
  -help                Print this usage message and exit 
  -?                   Print this usage message and exit 
  -q                   List all scripting engines available and exit 
  
If [arguments..] are present and if no -e or -f option is used, then first
argument is script file and the rest of the arguments, if any, are passed
as script arguments. If [arguments..] and -e or -f option is used, then all
[arguments..] are passed as script arguments. If [arguments..], -e, -f are
missing, then interactive mode is used.

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jrunscript.exe |
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

* Original Filename: jrunscript.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jar.exe](jar.exe-FC0D5E4B2EE50EEA7AEFC756F034B42C.md) | 68
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\kinit.exe](kinit.exe-06E306A8844F160ED5171B649CD1AF17.md) | 71
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\rmid.exe](rmid.exe-C86BB878FAD845F245B23042C5135E97.md) | 69
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\kinit.exe](kinit.exe-9DB3F4A11DF7C72A619559550437B160.md) | 72
[C:\program files (x86)\Amazon Corretto\jre8\bin\kinit.exe](kinit.exe-4090B7E81AF9AD4ADA7BE45A6DFB0DB8.md) | 71




MIT License. Copyright (c) 2020-2021 Strontic.


