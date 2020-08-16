---
title: jdeprscan.exe | OpenJDK Platform binary
---

# jdeprscan.exe 

* File Path: `C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jdeprscan.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `9C38E559ACCB2282CB5E5B92FA82C016`
SHA1 | `EF009253F9DE982AB021ABBB2B29498DA9163E8C`
SHA256 | `E27EC0EC9FCFB1B94F827DF7C780785A59C942B464A02E0C898DCD50D3E11878`
SHA384 | `3AF8AFDC6CBD7433402C1A1C479ABE49CE529B50F46365998EA12D7045B17AC8148CAC0FAC9A1E588537D972B8D23587`
SHA512 | `D7F4ED9A147B18D2832E6E58E845FBE3F2EF24412CBA6F36F4F04C0B52C5D6E99FDC8A6B0F2B52960F9BEC20847CFEDD5CD0BE64846F81866F3C471EA5547FA2`
SSDEEP | `384:IrAgbdNt3SyGUBbFVX45AUGK6jS1/SDgf2hEy:IxuYFN452Kgm6Uf2hX`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: jdeprscan [options] {dir|jar|class} ...

options:
        --class-path PATH
        --for-removal
        --full-version
  -? -h --help
  -l    --list
        --release 6|7|8|9|10|11
  -v    --verbose
        --version

Scans each argument for usages of deprecated APIs. An argument
may be a directory specifying the root of a package hierarchy,
a JAR file, a class file, or a class name. The class name must be
specified using a fully qualified class name using the $ separator
character for nested classes, for example,

    java.lang.Thread$State

The --class-path option provides a search path for resolution
of dependent classes.

The --for-removal option limits scanning or listing to APIs that are
deprecated for removal. Cannot be used with a release value of 6, 7, or 8.

The --full-version option prints out the full version string of the tool.

The --help (-? -h) option prints out a full help message.

The --list (-l) option prints out the set of deprecated APIs. No scanning is done,
so no directory, jar, or class arguments should be provided.

The --release option specifies the Java SE release that provides the set
of deprecated APIs for scanning.

The --verbose (-v) option enables additional message output during processing.

The --version option prints out the abbreviated version string of the tool.

```

### Usage (stderr):
```Batchfile
Usage: jdeprscan [options] {dir|jar|class} ...

options:
        --class-path PATH
        --for-removal
        --full-version
  -? -h --help
  -l    --list
        --release 6|7|8|9|10|11
  -v    --verbose
        --version

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

* Original Filename: jdeprscan.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jarsigner.exe](jarsigner.exe-3545DF7A746A46163EA98D79A3CFAA65.md) | 38
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdb.exe](jdb.exe-B66DF0DC0BDF18F4A14DFC6A58F23BAB.md) | 40
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdeprscan.exe](jdeprscan.exe-F63BEA1831254EB65EEA19012774C7B9.md) | 47
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jhsdb.exe](jhsdb.exe-61D7659F3C8D10C62224634404D1A91F.md) | 46
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jshell.exe](jshell.exe-7102DE0DBB816DFE04784CDDDF0EABC9.md) | 41
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\keytool.exe](keytool.exe-F859E5BDEA1498C82945E824021AB601.md) | 41
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\pack200.exe](pack200.exe-DC5AA7BCD19D6CE293F14AE57C3082EC.md) | 40
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmiregistry.exe](rmiregistry.exe-6240D6F87038D7B1F32E590D20B6EB45.md) | 40
[C:\Program Files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\serialver.exe](serialver.exe-8C875F970BA9AFB45B48DF121220D535.md) | 40
[C:\Program Files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\keytool.exe](keytool.exe-0EA9E813BC45594BC7B505FD193D233D.md) | 41
[C:\Program Files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\pack200.exe](pack200.exe-D8F4EAC78AB739846BD1D5BBD256DBC3.md) | 43
[C:\Program Files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\rmiregistry.exe](rmiregistry.exe-37B63F925D45FD055BA4A604F7E5F891.md) | 44
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jarsigner.exe](jarsigner.exe-24C345BA5B4270DD2E52E114356E9E76.md) | 61
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jdb.exe](jdb.exe-1AA2A866868B910E3B6E03B684B0D92A.md) | 63
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jhsdb.exe](jhsdb.exe-913B7D99340BB598826DB8B68C19D939.md) | 63
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\jshell.exe](jshell.exe-2DBEA6AB20129B0362A8485BD5218AB4.md) | 57
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\keytool.exe](keytool.exe-6045C32AB7C9FE9F5292B494A1B2E232.md) | 68
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\pack200.exe](pack200.exe-7707DC7CCEBDF3F3EA696534A43B93F2.md) | 63
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\rmiregistry.exe](rmiregistry.exe-671083EBFFF617DF6BF54C7B3B98E748.md) | 65
[C:\Program Files\Amazon Corretto\jdk11.0.8_10\bin\serialver.exe](serialver.exe-3CCFF738D117AD8BC9F6817D3D323F41.md) | 66




MIT License. Copyright (c) 2020 Strontic.


