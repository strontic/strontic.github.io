---
title: kinit.exe | OpenJDK Platform binary
---

# kinit.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\kinit.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `9DB3F4A11DF7C72A619559550437B160`
SHA1 | `776A1DD4ADF723CE4AB26C842D70F31702F61CAD`
SHA256 | `34954A1F61B885B4FD52F38B266F6BF552BDCF3BF34E92355350A645B2573771`
SHA384 | `B7CDE4D9A89791C107F921DCEA393D522879FE5569EC114D9972231453D517799FDE3F9A983AB6CD02CF021E28DFEA6A`
SHA512 | `2F7A5862268E9D43D4F290A9F99E43C990F5BB27FC01B3EED3FDC91771AB0105613A8C59EF918ED9261840152757D14B137590B26D23C9888461DD9D8DB1169F`
SSDEEP | `384:GpsS5hnoqSmSHhV8j1Wee74Sz6K6jSNQuMUDgf2hr:GpsUnBS/8Bbe7EKgAUf2hr`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage:

1. Initial ticket request:
    kinit [-A] [-f] [-p] [-c cachename] [-l lifetime] [-r renewable_time]
          [[-k [-t keytab_file_name]] [principal] [password]
2. Renew a ticket:
    kinit -R [-c cachename] [principal]

Available options to Kerberos 5 ticket request:
	-A   do not include addresses
	-f   forwardable
	-p   proxiable
	-c   cache name (i.e., FILE:\d:\myProfiles\mykrb5cache)
	-l   lifetime
	-r   renewable time (total lifetime a ticket can be renewed)
	-k   use keytab
	-t   keytab file name
	principal   the principal name (i.e., qweadf@ATHENA.MIT.EDU qweadf)
	password    the principal's Kerberos password

```

### Usage (stderr):
```Batchfile
Exception: invalid Principal name: --helpKrbException: Cannot locate default realm
java.lang.IllegalArgumentException: invalid Principal name: --helpKrbException: Cannot locate default realm
	at sun.security.krb5.internal.tools.KinitOptions.<init>(KinitOptions.java:150)
	at sun.security.krb5.internal.tools.Kinit.<init>(Kinit.java:130)
	at sun.security.krb5.internal.tools.Kinit.main(Kinit.java:96)

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\kinit.exe |
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

* Original Filename: kinit.exe
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
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jrunscript.exe](jrunscript.exe-D7605E1C70C8E4A616CA9BDB46FBEAC9.md) | 72
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\kinit.exe](kinit.exe-06E306A8844F160ED5171B649CD1AF17.md) | 80
[C:\program files (x86)\Amazon Corretto\jre8\bin\kinit.exe](kinit.exe-4090B7E81AF9AD4ADA7BE45A6DFB0DB8.md) | 82




MIT License. Copyright (c) 2020 Strontic.


