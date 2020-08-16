---
title: jmap.exe | OpenJDK Platform binary
---

# jmap.exe 

* File Path: `C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jmap.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `81D3ACB320CE4324DBD75A746B210E6B`
SHA1 | `195AC7D95787DFB100B721FE311E357D4463816D`
SHA256 | `416C67284B447F49BA9AB66A5CA3D64762CF7F586DDF96E4E0189068EDE8FAB4`
SHA384 | `69EFEF87EE4C3683EC8A69BEE9ED4A5B9DE25BB068F395DAC54CD85C43A4AF956F91E5E416FCA059E18CECBA788F77AD`
SHA512 | `5308B3A6A0989D4881D5B0FE13A6CF89F31D8B8BFD7A0EAF678FC07C3520C068B6721CDC47F36F97E4D7FF6778A5D42892862A9EB24260C9DD7D33ADB57D3F62`
SSDEEP | `384:GpsJgvnvi1fqImSHhV828eeDcFK6jSPDgf2hTg:Gpsana18S/825eIKgKUf2hTg`

## Runtime Data

### Usage (stdout):
```Batchfile
Attaching to remote server help, please wait...

```

### Usage (stderr):
```Batchfile
Usage:
    jmap [option] <pid>
        (to connect to running process)
    jmap [option] <executable <core>
        (to connect to a core file)
    jmap [option] [server_id@]<remote server IP or hostname>
        (to connect to remote debug server)

where <option> is one of:
    <none>               to print same info as Solaris pmap
    -heap                to print java heap summary
    -histo[:live]        to print histogram of java object heap; if the "live"
                         suboption is specified, only count live objects
    -clstats             to print class loader statistics
    -finalizerinfo       to print information on objects awaiting finalization
    -dump:<dump-options> to dump java heap in hprof binary format
                         dump-options:
                           live         dump only live objects; if not specified,
                                        all objects in the heap are dumped.
                           format=b     binary format
                           file=<file>  dump heap to <file>
                         Example: jmap -dump:live,format=b,file=heap.bin <pid>
    -F                   force. Use with -dump:<dump-options> <pid> or -histo
                         to force a heap dump or histogram when <pid> does not
                         respond. The "live" suboption is not supported
                         in this mode.
    -h | -help           to print this help message
    -J<flag>             to pass <flag> directly to the runtime system

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

* Original Filename: jmap.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\wsgen.exe](wsgen.exe-F8437CEA06A787E6478E09BCC7881A53.md) | 61
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\wsimport.exe](wsimport.exe-0305766ED05D85C5B6BF0877F1A2AB70.md) | 58




MIT License. Copyright (c) 2020 Strontic.


