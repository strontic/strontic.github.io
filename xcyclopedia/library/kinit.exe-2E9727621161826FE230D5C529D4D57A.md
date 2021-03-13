---
title: kinit.exe | OpenJDK Platform binary
excerpt: What is kinit.exe?
---

# kinit.exe 

* File Path: `C:\program files\Amazon Corretto\jdk11.0.8_10\bin\kinit.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `2E9727621161826FE230D5C529D4D57A`
SHA1 | `52D4B1E33615C7AA99A0F391858E0C596DF67CB1`
SHA256 | `8C1D2509EFF6474A2F8B35599EFAEA0B108D768FCAC74077475279370469D7FC`
SHA384 | `46B8FA165B3D04E7B0795CBFFC1E00C3BED815C298C02D7F3266DADD1A4D90B0990ABCECA334D446B1B972E23E952AC6`
SHA512 | `D1B159C334960A06BC0F6171A603D799A387B4642455F4FC27721F6DBB426ECD13900B24DF6C479A0A8853C046E9D5EE0F161BDF738D93E51B39E8C8633A2BAA`
SSDEEP | `384:RbdNt3yyfU9kBbFK1A5A7dK6jSWYniDgf2hu1:jOAFcA58KgTUf2hu1`

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
Exception: invalid Principal name: helpKrbException: Cannot locate default realm
java.lang.IllegalArgumentException: invalid Principal name: helpKrbException: Cannot locate default realm
	at java.security.jgss/sun.security.krb5.internal.tools.KinitOptions.<init>(KinitOptions.java:154)
	at java.security.jgss/sun.security.krb5.internal.tools.Kinit.<init>(Kinit.java:130)
	at java.security.jgss/sun.security.krb5.internal.tools.Kinit.main(Kinit.java:96)

```

### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk11.0.8_10\bin\kinit.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: kinit.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jar.exe](jar.exe-B39F84FB8C26E73075627CF8A3E30B00.md) | 46
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javap.exe](javap.exe-E53972D2FEB5711E552CE72695BF2572.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jcmd.exe](jcmd.exe-B264E0660D3BF070AAD25F2F033B9436.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdeps.exe](jdeps.exe-A2D8568F6868C17A7A8C88B625FDB100.md) | 38
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-08F03ABD9FF453E929D3232120C51BD7.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jimage.exe](jimage.exe-D25C31744405D6ACAA96E47DE6F8D837.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jmod.exe](jmod.exe-66A78959DA40CE102F7BB09A8C73395A.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jps.exe](jps.exe-8B98A486BF91B0F184B1C587BB2B680F.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstat.exe](jstat.exe-92DD217A9387CDFD9D0F65CACD5DE308.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstatd.exe](jstatd.exe-F51B29210060B0377FB4EA13AFD3FD9D.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-1D16A2748895E35498E4E22F15EB5AC0.md) | 52
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\klist.exe](klist.exe-9371A9AC3DC11410EA50EA8C21C83C89.md) | 46
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-C6FB113B79364970E2246CCFB40878D0.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmic.exe](rmic.exe-BBCF27C5346C3075D09DF7355AEBB582.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-D98CF348139BB44E4EFCA15FEA955F7C.md) | 41
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-065E5E752266CD2FA6F1CF2564249B21.md) | 40
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-17561E8FCB677496BC34D76B2F9BE380.md) | 54
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\klist.exe](klist.exe-7D151D16C96009205B92251019F782AF.md) | 49
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-F45CED87218ADC894C655258D1FC5C10.md) | 44
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-62D6E0918BC131ABDB5F5A98A66346EF.md) | 40
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jar.exe](jar.exe-90E9FDEDBD307AAD814B9B310EF9EEF6.md) | 65
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\javap.exe](javap.exe-5FDBAB868D53F447324D0CEC119EADF4.md) | 65
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jcmd.exe](jcmd.exe-8B031007B293E1B238FE7040C1E78BA9.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jdeps.exe](jdeps.exe-93A0053100DB342311A5461DC158F9C5.md) | 63
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jfr.exe](jfr.exe-B33A8A8C02F57743444E9F96936783DE.md) | 58
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jimage.exe](jimage.exe-52585947B2B10A2C41E370B60D85A837.md) | 61
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jmod.exe](jmod.exe-FD6825DE6B411FB98408250B4242E4CF.md) | 58
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jps.exe](jps.exe-EAB3A072CA16676197FF86E06CBA9F13.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jstat.exe](jstat.exe-94511EDBA5FC73EF516B66FF0BBFF032.md) | 63
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jstatd.exe](jstatd.exe-5B818E750FE168F05BFF9A30354DEF83.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\klist.exe](klist.exe-0114F130B4E2B2C847324EF3EE2231B1.md) | 69
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\ktab.exe](ktab.exe-F3797AE1D338EAA8C55B716127B2FE64.md) | 65
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\rmic.exe](rmic.exe-B0BE3B0798C023F1A21C4E066BAE9527.md) | 61
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\rmid.exe](rmid.exe-1D81A7BE447A5B0CF10B76D15B1C69BC.md) | 63




MIT License. Copyright (c) 2020-2021 Strontic.


