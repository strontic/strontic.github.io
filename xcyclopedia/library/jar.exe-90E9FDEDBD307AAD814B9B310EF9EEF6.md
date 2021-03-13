---
title: jar.exe | OpenJDK Platform binary
excerpt: What is jar.exe?
---

# jar.exe 

* File Path: `C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jar.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `90E9FDEDBD307AAD814B9B310EF9EEF6`
SHA1 | `3DEBDC74489A29149D87814BB28DE9E9F848EECA`
SHA256 | `F4616727D6E0C03CFE9C834A851F3CF22B8CD8ACEE24435080F21C41E9AEC20E`
SHA384 | `69AEB17823D57170ACA44AC2F83E22FAA5FF5509E06B5EAF0C3B80CAF408DB56FA5E327AFADB3953DDBCAD8AB91663E6`
SHA512 | `6704168495174B1631DB48045920013413EA951BB4D0EF5752F47774785BFD76866925FB1A414879CB7D60F59D20F01F6F0CD3FEDF586B37520F369482113BD1`
SSDEEP | `384:5bdNt3yyvZPABbFK+5APxK6jSjACGDgf2hUu:LO+N+FK+54KgGtGUf2hUu`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: jar [OPTION...] [ [--release VERSION] [-C dir] files] ...
jar creates an archive for classes and resources, and can manipulate or
restore individual classes or resources from an archive.

 Examples:
 # Create an archive called classes.jar with two class files:
 jar --create --file classes.jar Foo.class Bar.class
 # Create an archive using an existing manifest, with all the files in foo/:
 jar --create --file classes.jar --manifest mymanifest -C foo/ .
 # Create a modular jar archive, where the module descriptor is located in
 # classes/module-info.class:
 jar --create --file foo.jar --main-class com.foo.Main --module-version 1.0
     -C foo/ classes resources
 # Update an existing non-modular jar to a modular jar:
 jar --update --file foo.jar --main-class com.foo.Main --module-version 1.0
     -C foo/ module-info.class
 # Create a multi-release jar, placing some files in the META-INF/versions/9 directory:
 jar --create --file mr.jar -C foo classes --release 9 -C foo9 classes

To shorten or simplify the jar command, you can specify arguments in a separate
text file and pass it to the jar command with the at sign (@) as a prefix.

 Examples:
 # Read additional options and list of class files from the file classes.list
 jar --create --file my.jar @classes.list


 Main operation mode:

  -c, --create               Create the archive
  -i, --generate-index=FILE  Generate index information for the specified jar
                             archives
  -t, --list                 List the table of contents for the archive
  -u, --update               Update an existing jar archive
  -x, --extract              Extract named (or all) files from the archive
  -d, --describe-module      Print the module descriptor, or automatic module name

 Operation modifiers valid in any mode:

  -C DIR                     Change to the specified directory and include the
                             following file
  -f, --file=FILE            The archive file name. When omitted, either stdin or
                             stdout is used based on the operation
      --release VERSION      Places all following files in a versioned directory
                             of the jar (i.e. META-INF/versions/VERSION/)
  -v, --verbose              Generate verbose output on standard output

 Operation modifiers valid only in create and update mode:

  -e, --main-class=CLASSNAME The application entry point for stand-alone
                             applications bundled into a modular, or executable,
                             jar archive
  -m, --manifest=FILE        Include the manifest information from the given
                             manifest file
  -M, --no-manifest          Do not create a manifest file for the entries
      --module-version=VERSION    The module version, when creating a modular
                             jar, or updating a non-modular jar
      --hash-modules=PATTERN Compute and record the hashes of modules 
                             matched by the given pattern and that depend upon
                             directly or indirectly on a modular jar being
                             created or a non-modular jar being updated
  -p, --module-path          Location of module dependence for generating
                             the hash

 Operation modifiers valid only in create, update, and generate-index mode:

  -0, --no-compress          Store only; use no ZIP compression

 Other options:

  -?, -h, --help[:compat]    Give this, or optionally the compatibility, help
      --help-extra           Give help on extra options
      --version              Print program version

 An archive is a modular jar if a module descriptor, 'module-info.class', is
 located in the root of the given directories, or the root of the jar archive
 itself. The following operations are only valid when creating a modular jar,
 or updating an existing non-modular jar: '--module-version',
 '--hash-modules', and '--module-path'.

 Mandatory or optional arguments to long options are also mandatory or optional
 for any corresponding short options.


```

### Usage (stderr):
```cmhg
Illegal option: /
Try `jar --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jar.exe |
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

* Original Filename: jar.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jar.exe](jar.exe-B39F84FB8C26E73075627CF8A3E30B00.md) | 50
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javap.exe](javap.exe-E53972D2FEB5711E552CE72695BF2572.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jcmd.exe](jcmd.exe-B264E0660D3BF070AAD25F2F033B9436.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdeps.exe](jdeps.exe-A2D8568F6868C17A7A8C88B625FDB100.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-08F03ABD9FF453E929D3232120C51BD7.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jimage.exe](jimage.exe-D25C31744405D6ACAA96E47DE6F8D837.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jmod.exe](jmod.exe-66A78959DA40CE102F7BB09A8C73395A.md) | 49
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jps.exe](jps.exe-8B98A486BF91B0F184B1C587BB2B680F.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstat.exe](jstat.exe-92DD217A9387CDFD9D0F65CACD5DE308.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstatd.exe](jstatd.exe-F51B29210060B0377FB4EA13AFD3FD9D.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-1D16A2748895E35498E4E22F15EB5AC0.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\klist.exe](klist.exe-9371A9AC3DC11410EA50EA8C21C83C89.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-C6FB113B79364970E2246CCFB40878D0.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmic.exe](rmic.exe-BBCF27C5346C3075D09DF7355AEBB582.md) | 49
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-D98CF348139BB44E4EFCA15FEA955F7C.md) | 52
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-065E5E752266CD2FA6F1CF2564249B21.md) | 46
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-17561E8FCB677496BC34D76B2F9BE380.md) | 43
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\klist.exe](klist.exe-7D151D16C96009205B92251019F782AF.md) | 46
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-F45CED87218ADC894C655258D1FC5C10.md) | 41
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-62D6E0918BC131ABDB5F5A98A66346EF.md) | 49
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\javap.exe](javap.exe-5FDBAB868D53F447324D0CEC119EADF4.md) | 63
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jcmd.exe](jcmd.exe-8B031007B293E1B238FE7040C1E78BA9.md) | 66
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jdeps.exe](jdeps.exe-93A0053100DB342311A5461DC158F9C5.md) | 65
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jfr.exe](jfr.exe-B33A8A8C02F57743444E9F96936783DE.md) | 68
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jimage.exe](jimage.exe-52585947B2B10A2C41E370B60D85A837.md) | 61
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jmod.exe](jmod.exe-FD6825DE6B411FB98408250B4242E4CF.md) | 63
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jps.exe](jps.exe-EAB3A072CA16676197FF86E06CBA9F13.md) | 69
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jstat.exe](jstat.exe-94511EDBA5FC73EF516B66FF0BBFF032.md) | 65
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jstatd.exe](jstatd.exe-5B818E750FE168F05BFF9A30354DEF83.md) | 61
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\kinit.exe](kinit.exe-2E9727621161826FE230D5C529D4D57A.md) | 65
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\klist.exe](klist.exe-0114F130B4E2B2C847324EF3EE2231B1.md) | 61
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\ktab.exe](ktab.exe-F3797AE1D338EAA8C55B716127B2FE64.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\rmic.exe](rmic.exe-B0BE3B0798C023F1A21C4E066BAE9527.md) | 68
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\rmid.exe](rmid.exe-1D81A7BE447A5B0CF10B76D15B1C69BC.md) | 63




MIT License. Copyright (c) 2020-2021 Strontic.


