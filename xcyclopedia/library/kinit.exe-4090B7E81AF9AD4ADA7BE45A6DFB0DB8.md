---
title: kinit.exe | OpenJDK Platform binary
---

# kinit.exe 

* File Path: `C:\Program Files (x86)\Amazon Corretto\jre8\bin\kinit.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `4090B7E81AF9AD4ADA7BE45A6DFB0DB8`
SHA1 | `4D649A852080DFB78AEE5231BCD0A9E18FD87DDA`
SHA256 | `4BC37663B73934566367A86FAFFDE8457E6DD7813D5CAE668ABBB19C3CF7C357`
SHA384 | `AE326A5B196F7018C8507D825C6465E18C972A73D50A0AB2F3BEA13C05636F755A850C18D0854EF51196AD013C377520`
SHA512 | `91BB75329000920C5A9A52E21BECB0C8538D82066A7C43072AF82C7FCF77279623CE5C1A55E5FB06B272FDBA41E795B5900FE2C2D818070DC8D8F556DB08499B`
SSDEEP | `384:GpsU5hnoqSmSHhV8j1Wee74SzVK6jSt1Ry9Dgf2hvrP:Gps+nBS/8Bbe77KgFUf2hTP`

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
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jar.exe](jar.exe-FC0D5E4B2EE50EEA7AEFC756F034B42C.md) | 66
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jrunscript.exe](jrunscript.exe-D7605E1C70C8E4A616CA9BDB46FBEAC9.md) | 71
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\kinit.exe](kinit.exe-06E306A8844F160ED5171B649CD1AF17.md) | 82
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\kinit.exe](kinit.exe-9DB3F4A11DF7C72A619559550437B160.md) | 82
[C:\Program Files\Amazon Corretto\jdk1.8.0_265\jre\bin\rmiregistry.exe](rmiregistry.exe-AC45D66B78E93F793F684492A0A3BCF8.md) | 40




MIT License. Copyright (c) 2020 Strontic.


