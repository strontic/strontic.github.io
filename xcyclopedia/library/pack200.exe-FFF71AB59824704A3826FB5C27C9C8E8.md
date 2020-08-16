---
title: pack200.exe | OpenJDK Platform binary
---

# pack200.exe 

* File Path: `C:\Program Files (x86)\Amazon Corretto\jre8\bin\pack200.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `FFF71AB59824704A3826FB5C27C9C8E8`
SHA1 | `E530B9B6B3ED149AEF564AB91F71EA809804B5A8`
SHA256 | `ED673121AE62FD043DE7621F82EFD64C0D0CE52CFD029570EBA738848C9768F6`
SHA384 | `3D756C6B8B70FE35B34694F20FED6CB51D24E28C330AC49CA501110EF9F6D5700ADCD1A0770DA1013462A17E8BF0B7E1`
SHA512 | `3722CB820070C9FF4854899933CD4F3EF6356F53D32D709A919D82C42D6816C57022EA85A1257D7EBB43FE0D04977A9F18BA217E122E01F62B42C6EC8CAE6717`
SSDEEP | `384:GpsP5hncqDmSHhV8VWee34SzvRK6jS/VSWDgf2hzq8:Gps/noS/8Vbe3JRKgMSWUf2hzf`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage:  pack200 [-opt... | --option=value]... x.pack[.gz] y.jar

Packing Options
  -g, --no-gzip                   output a plain *.pack file with no zipping
  --gzip                          (default) post-process the pack output with gzip
  -G, --strip-debug               remove debugging attributes while packing
  -O, --no-keep-file-order        do not transmit file ordering information
  --keep-file-order               (default) preserve input file ordering
  -S{N}, --segment-limit={N}      output segment limit (default N=1Mb)
  -E{N}, --effort={N}             packing effort (default N=5)
  -H{h}, --deflate-hint={h}       transmit deflate hint: true, false, or keep (default)
  -m{V}, --modification-time={V}  transmit modtimes: latest or keep (default)
  -P{F}, --pass-file={F}          transmit the given input element(s) uncompressed
  -U{a}, --unknown-attribute={a}  unknown attribute action: error, strip, or pass (default)
  -C{N}={L}, --class-attribute={N}={L}  (user-defined attribute)
  -F{N}={L}, --field-attribute={N}={L}  (user-defined attribute)
  -M{N}={L}, --method-attribute={N}={L} (user-defined attribute)
  -D{N}={L}, --code-attribute={N}={L}   (user-defined attribute)
  -f{F}, --config-file={F}        read file F for Pack200.Packer properties
  -v, --verbose                   increase program verbosity
  -q, --quiet                     set verbosity to lowest level
  -l{F}, --log-file={F}           output to the given log file, or '-' for System.out
  -?, -h, --help                  print this message
  -V, --version                   print program version
  -J{X}                           pass option X to underlying Java VM

Notes:
  The -P, -C, -F, -M, and -D options accumulate.
  Example attribute definition:  -C SourceFile=RUH .
  Config. file properties are defined by the Pack200 API.
  For meaning of -S, -E, -H-, -m, -U values, see Pack200 API.
  Layout definitions (like RUH) are defined by JSR 200.

Repacking mode updates the JAR file with a pack/unpack cycle:
    pack200 [-r|--repack] [-opt | --option=value]... [repackedy.jar] y.jar


```

### Usage (stderr):
```Batchfile
Usage:  pack200 [-opt... | --option=value]... x.pack[.gz] y.jar
(For more information, run pack200 --help .)

```

## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: pack200.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\javadoc.exe](javadoc.exe-60735A8E38579FDB6320851C1DE38408.md) | 71
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jdb.exe](jdb.exe-A84E4AB77C8F90E25B6D0C916B0D25E1.md) | 61
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\orbd.exe](orbd.exe-DB61ACE931C41EF0EF48577287B3DAB8.md) | 60
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\pack200.exe](pack200.exe-2B30CC6FFE825CC181A4A3F9FDF071D7.md) | 83
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\bin\rmiregistry.exe](rmiregistry.exe-457267F19E98514E55991A66650E25F3.md) | 71
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\orbd.exe](orbd.exe-96A845462BBC79AA171FE9C03CE33766.md) | 57
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\pack200.exe](pack200.exe-0FF0267A0F8C0055F1B1AAF5198A1472.md) | 85
[C:\Program Files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\rmiregistry.exe](rmiregistry.exe-737C1DCE9C428110E1DBA54B571A5B03.md) | 72
[C:\Program Files (x86)\Amazon Corretto\jre8\bin\orbd.exe](orbd.exe-B8A6EDEBFC7BD2FB7A7C1C12A3DBEF24.md) | 57
[C:\Program Files (x86)\Amazon Corretto\jre8\bin\rmiregistry.exe](rmiregistry.exe-EE9B42A4CF7692CC7F4C7C48685E9708.md) | 72




MIT License. Copyright (c) 2020 Strontic.


