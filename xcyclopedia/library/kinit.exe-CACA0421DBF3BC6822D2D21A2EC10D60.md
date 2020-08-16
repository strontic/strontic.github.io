---
title: kinit.exe | OpenJDK Platform binary
---

# kinit.exe 

* File Path: `C:\Program Files\Amazon Corretto\jdk1.8.0_265\bin\kinit.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `CACA0421DBF3BC6822D2D21A2EC10D60`
SHA1 | `2DA970AA3C25BEEF9C59FC47BE54712C4C6F9EFC`
SHA256 | `A0C820091A75104A7A580DC1EBC1CE80D7D1D50DF901D61A514FB030672022F2`
SHA384 | `5A445D064410D1A394EC4D33DB578E86035E81BBCCFBF79AD4E9FFC29B107AA0BD17C1C55774D6DB4A8CAA29CE2013DF`
SHA512 | `E803A814E7072AD0FC72267E86B83F6F69DAAADEBF718C40C07913D170B0BAA109D614F016BC4576DFD50D23D60B445DE62E6917F95BED9C8A9BFAD851E48138`
SSDEEP | `384:uPakKAKNdlS18eElK6jSw3h1jUDgf2hpPK+:AaH/m5ElKg4Uf2hhV`

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
[C:\Program Files\Amazon Corretto\jdk1.8.0_265\jre\bin\kinit.exe](kinit.exe-8279A6B305002709B2FA0E42D508F5B7.md) | 72
[C:\Program Files\Amazon Corretto\jre8\bin\kinit.exe](kinit.exe-279AB5BC8B1580FBD051A17B03A105FC.md) | 72




MIT License. Copyright (c) 2020 Strontic.


