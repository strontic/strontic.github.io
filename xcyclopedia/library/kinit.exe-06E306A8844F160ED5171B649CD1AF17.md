---
title: kinit.exe | OpenJDK Platform binary
---

# kinit.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\kinit.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `06E306A8844F160ED5171B649CD1AF17`
SHA1 | `0A5CDB31F22429F7275385443EFEDFDDFCA685B5`
SHA256 | `D587EDBCB4ED8B933873A65737A8BEFF27D29560983BF59E634AEFE4B1674746`
SHA384 | `2FFE9AACF61E0F9CBE1855F2E0D730DE2266F6B51938BA7B37D489C2821211571E786CF9AE4143E82FB62F5B3A58F29D`
SHA512 | `AAA380959C268D1CBB8ACD01FA3DE21FCEE3136EC96E6E04736DB0E3A0A2D063339BDA98F4AC3237972B7208040DC1932E281D4E159EA66467DA9F0A5FB68B4F`
SSDEEP | `384:Gpsus5hnoqSmSHhV8j1Wee74SzVK6jSHDwxnCDgf2hs:GpsBnBS/8Bbe77KgqM0Uf2hs`

## Runtime Data

### Usage (stdout):
```cmhg
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
```cmhg
Exception: invalid Principal name: --helpKrbException: Cannot locate default realm
java.lang.IllegalArgumentException: invalid Principal name: --helpKrbException: Cannot locate default realm
	at sun.security.krb5.internal.tools.KinitOptions.<init>(KinitOptions.java:150)
	at sun.security.krb5.internal.tools.Kinit.<init>(Kinit.java:130)
	at sun.security.krb5.internal.tools.Kinit.main(Kinit.java:96)

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\kinit.exe |
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
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jar.exe](jar.exe-FC0D5E4B2EE50EEA7AEFC756F034B42C.md) | 69
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jrunscript.exe](jrunscript.exe-D7605E1C70C8E4A616CA9BDB46FBEAC9.md) | 71
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\kinit.exe](kinit.exe-9DB3F4A11DF7C72A619559550437B160.md) | 80
[C:\program files (x86)\Amazon Corretto\jre8\bin\kinit.exe](kinit.exe-4090B7E81AF9AD4ADA7BE45A6DFB0DB8.md) | 82




MIT License. Copyright (c) 2020 Strontic.


