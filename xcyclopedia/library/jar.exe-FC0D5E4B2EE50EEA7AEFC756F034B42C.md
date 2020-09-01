---
title: jar.exe | OpenJDK Platform binary
---

# jar.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jar.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `FC0D5E4B2EE50EEA7AEFC756F034B42C`
SHA1 | `12233D580D4270D36497C95BE9C73897C0474D20`
SHA256 | `01EC14B949B1B310512C042DB639FDAE452A30AD8BA77925F37E50CE355316E9`
SHA384 | `8CF8AA4E2691443EC54C32F6034F0BDC693508091E6FD018308505A0DB6BC9E6CF4B28FCF7BD7FDCD2CC0EC89A658286`
SHA512 | `384D969AC90F5D165A1C5789A053B2E9D8583B52DE868AC7AC65AC139E60DA98A3128BBD99E0E865CD279AF693BD4A5982BD19D2027524ED4165A84F11052CB4`
SSDEEP | `384:Gps95BnGqNmSHhV8jkeeF4SzbK6jSzvhEDgf2h+s:GpstnwS/8jBeFdKgqpEUf2hX`

## Runtime Data

### Usage (stderr):
```Batchfile
Illegal option: /
Usage: jar {ctxui}[vfmn0PMe] [jar-file] [manifest-file] [entry-point] [-C dir] files ...
Options:
    -c  create new archive
    -t  list table of contents for archive
    -x  extract named (or all) files from archive
    -u  update existing archive
    -v  generate verbose output on standard output
    -f  specify archive file name
    -m  include manifest information from specified manifest file
    -n  perform Pack200 normalization after creating a new archive
    -e  specify application entry point for stand-alone application 
        bundled into an executable jar file
    -0  store only; use no ZIP compression
    -P  preserve leading '/' (absolute path) and ".." (parent directory) components from file names
    -M  do not create a manifest file for the entries
    -i  generate index information for the specified jar files
    -C  change to the specified directory and include the following file
If any file is a directory then it is processed recursively.
The manifest file name, the archive file name and the entry point name are
specified in the same order as the 'm', 'f' and 'e' flags.

Example 1: to archive two class files into an archive called classes.jar: 
       jar cvf classes.jar Foo.class Bar.class 
Example 2: use an existing manifest file 'mymanifest' and archive all the
           files in the foo/ directory into 'classes.jar': 
       jar cvfm classes.jar mymanifest -C foo/ .


```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jar.exe |
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

* Original Filename: jar.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jrunscript.exe](jrunscript.exe-D7605E1C70C8E4A616CA9BDB46FBEAC9.md) | 68
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\kinit.exe](kinit.exe-06E306A8844F160ED5171B649CD1AF17.md) | 69
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\rmid.exe](rmid.exe-C86BB878FAD845F245B23042C5135E97.md) | 65
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\kinit.exe](kinit.exe-9DB3F4A11DF7C72A619559550437B160.md) | 68
[C:\program files (x86)\Amazon Corretto\jre8\bin\kinit.exe](kinit.exe-4090B7E81AF9AD4ADA7BE45A6DFB0DB8.md) | 66




MIT License. Copyright (c) 2020 Strontic.


