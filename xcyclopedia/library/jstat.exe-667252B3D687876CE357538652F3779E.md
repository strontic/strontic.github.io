---
title: jstat.exe | OpenJDK Platform binary
excerpt: What is jstat.exe?
---

# jstat.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jstat.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `667252B3D687876CE357538652F3779E`
SHA1 | `98825447C8CC80795C2D01596FD5D3FB98767C08`
SHA256 | `4B562499F56B3016F84E5E32869AB1635D0091EC8DCBF10A91A00231E1170417`
SHA384 | `9CA85E12288F571675E43A6642315587284C23644FF385F97B7770FD37D8429179ED2C8AE1201475B74D21712FD28202`
SHA512 | `3D06401603B2EAF2886BA310D02AD0BCF91F819C8461B9526E306F507AF316252F256DF4BD1978556B7050400E32A9B307591A83EB6A652954C1B554CC4F0524`
SSDEEP | `384:Gpsr5Bn0qHmSHhV8euee74Sz+K6jS2oVDgf2hpW:Gps7nAS/8eze78Kg6Uf2hM`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: jstat -help|-options
       jstat -<option> [-t] [-h<lines>] <vmid> [<interval> [<count>]]

Definitions:
  <option>      An option reported by the -options option
  <vmid>        Virtual Machine Identifier. A vmid takes the following form:
                     <lvmid>[@<hostname>[:<port>]]
                Where <lvmid> is the local vm identifier for the target
                Java virtual machine, typically a process id; <hostname> is
                the name of the host running the target Java virtual machine;
                and <port> is the port number for the rmiregistry on the
                target host. See the jvmstat documentation for a more complete
                description of the Virtual Machine Identifier.
  <lines>       Number of samples between header lines.
  <interval>    Sampling interval. The following forms are allowed:
                    <n>["ms"|"s"]
                Where <n> is an integer and the suffix specifies the units as 
                milliseconds("ms") or seconds("s"). The default units are "ms".
  <count>       Number of samples to take before terminating.
  -J<flag>      Pass <flag> directly to the runtime system.

```

### Usage (stderr):
```cmhg
-h requires an integer argument
Usage: jstat -help|-options
       jstat -<option> [-t] [-h<lines>] <vmid> [<interval> [<count>]]

Definitions:
  <option>      An option reported by the -options option
  <vmid>        Virtual Machine Identifier. A vmid takes the following form:
                     <lvmid>[@<hostname>[:<port>]]
                Where <lvmid> is the local vm identifier for the target
                Java virtual machine, typically a process id; <hostname> is
                the name of the host running the target Java virtual machine;
                and <port> is the port number for the rmiregistry on the
                target host. See the jvmstat documentation for a more complete
                description of the Virtual Machine Identifier.
  <lines>       Number of samples between header lines.
  <interval>    Sampling interval. The following forms are allowed:
                    <n>["ms"|"s"]
                Where <n> is an integer and the suffix specifies the units as 
                milliseconds("ms") or seconds("s"). The default units are "ms".
  <count>       Number of samples to take before terminating.
  -J<flag>      Pass <flag> directly to the runtime system.

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jstat.exe |
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

* Original Filename: jstat.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jps.exe](jps.exe-5AFACE3595288F9EF62F39721DEEC88C.md) | 72
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\rmic.exe](rmic.exe-A763ACD55C2C10F6EBA024CDDD134E9F.md) | 69
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\jjs.exe](jjs.exe-EF545E6EFCC0E8BA4089FE7DC1DFDE90.md) | 72
[C:\program files\Amazon Corretto\jdk1.8.0_265\bin\jabswitch.exe](jabswitch.exe-7CA1D8DC77673F04F638D21BA5477C05.md) | 30




MIT License. Copyright (c) 2020 Strontic.


