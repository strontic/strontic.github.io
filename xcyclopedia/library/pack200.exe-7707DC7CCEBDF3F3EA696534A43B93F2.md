---
title: pack200.exe | OpenJDK Platform binary
excerpt: What is pack200.exe?
---

# pack200.exe 

* File Path: `C:\program files\Amazon Corretto\jdk11.0.8_10\bin\pack200.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `7707DC7CCEBDF3F3EA696534A43B93F2`
SHA1 | `9633BE3012F84247DD6A78516350114FD5E90625`
SHA256 | `52B418C7462008B459C85B0E4AF5DD991FBFE64EBA9A4471A7F8F0A2618C2E00`
SHA384 | `CFFB4542D81D7B87EDF3830CAC7F95A25A8CFF1E6600E04C5581947EF0672E5B6F358BAC75E7F9498C857E6CD7253301`
SHA512 | `6401893AC6AEE3F9EBCC6BCE834502BEA9A765BAE6A8272AE57A945AA0B7EA1735A026AD553B579E3851FC79B63B82F8A3A06536589DB2C65E37395F9ACACA10`
SSDEEP | `384:qTgbdNt3Sy2OBbFI85AWPK6jSqXXDgf2hKt:xuWFI85NKghnUf2hKt`

## Runtime Data

### Usage (stdout):
```cmhg

Warning: The pack200 tool is deprecated, and is planned for removal in a future JDK release.

Usage:  pack200 [-opt... | --option=value]... x.pack[.gz] y.jar

Packing Options
  -r, --repack                    repack or normalize a jar, suitable for 
                                  signing with jarsigner
  -g, --no-gzip                   output a plain pack file, suitable to be
                                  compressed with a file compression utility
  --gzip                          (default) post compress the pack output
                                  with gzip
  -G, --strip-debug               remove debugging attributes (SourceFile,
                                  LineNumberTable, LocalVariableTable
                                  and LocalVariableTypeTable) while packing
  -O, --no-keep-file-order        do not transmit file ordering information
  --keep-file-order               (default) preserve input file ordering
  -S{N}, --segment-limit={N}      limit segment sizes (default unlimited)
  -E{N}, --effort={N}             packing effort (default N=5)
  -H{h}, --deflate-hint={h}       transmit deflate hint: true, false,
                                  or keep (default)
  -m{V}, --modification-time={V}  transmit modtimes: latest or keep (default)
  -P{F}, --pass-file={F}          transmit the given input element(s) unchanged
  -U{a}, --unknown-attribute={a}  unknown attribute action: error, strip,
                                  or pass (default)
  -C{N}={L}, --class-attribute={N}={L}  (user-defined attribute)
  -F{N}={L}, --field-attribute={N}={L}  (user-defined attribute)
  -M{N}={L}, --method-attribute={N}={L} (user-defined attribute)
  -D{N}={L}, --code-attribute={N}={L}   (user-defined attribute)
  -f{F}, --config-file={F}        read file F for Pack200.Packer properties
  -v, --verbose                   increase program verbosity
  -q, --quiet                     set verbosity to lowest level
  -l{F}, --log-file={F}           output to the given log file, 
                                  or '-' for System.out
  -?, -h, --help                  print this help message
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


Exit Status:
  0 if successful, >0 if an error occurred

Warning: The pack200 tool is deprecated, and is planned for removal in a future JDK release.


```

### Usage (stderr):
```cmhg
Usage:  pack200 [-opt... | --option=value]... x.pack[.gz] y.jar
(For more information, run pack200 --help .)

```

### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk11.0.8_10\bin\pack200.exe |
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

* Original Filename: pack200.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jarsigner.exe](jarsigner.exe-3545DF7A746A46163EA98D79A3CFAA65.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdb.exe](jdb.exe-B66DF0DC0BDF18F4A14DFC6A58F23BAB.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdeprscan.exe](jdeprscan.exe-F63BEA1831254EB65EEA19012774C7B9.md) | 46
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jhsdb.exe](jhsdb.exe-61D7659F3C8D10C62224634404D1A91F.md) | 47
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jshell.exe](jshell.exe-7102DE0DBB816DFE04784CDDDF0EABC9.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\keytool.exe](keytool.exe-F859E5BDEA1498C82945E824021AB601.md) | 49
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\pack200.exe](pack200.exe-DC5AA7BCD19D6CE293F14AE57C3082EC.md) | 49
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmiregistry.exe](rmiregistry.exe-6240D6F87038D7B1F32E590D20B6EB45.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\serialver.exe](serialver.exe-8C875F970BA9AFB45B48DF121220D535.md) | 43
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\keytool.exe](keytool.exe-0EA9E813BC45594BC7B505FD193D233D.md) | 47
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\pack200.exe](pack200.exe-D8F4EAC78AB739846BD1D5BBD256DBC3.md) | 50
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\rmiregistry.exe](rmiregistry.exe-37B63F925D45FD055BA4A604F7E5F891.md) | 46
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jarsigner.exe](jarsigner.exe-24C345BA5B4270DD2E52E114356E9E76.md) | 60
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jdb.exe](jdb.exe-1AA2A866868B910E3B6E03B684B0D92A.md) | 68
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jdeprscan.exe](jdeprscan.exe-9C38E559ACCB2282CB5E5B92FA82C016.md) | 63
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jhsdb.exe](jhsdb.exe-913B7D99340BB598826DB8B68C19D939.md) | 68
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jshell.exe](jshell.exe-2DBEA6AB20129B0362A8485BD5218AB4.md) | 58
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\keytool.exe](keytool.exe-6045C32AB7C9FE9F5292B494A1B2E232.md) | 72
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\rmiregistry.exe](rmiregistry.exe-671083EBFFF617DF6BF54C7B3B98E748.md) | 69
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\serialver.exe](serialver.exe-3CCFF738D117AD8BC9F6817D3D323F41.md) | 65




MIT License. Copyright (c) 2020 Strontic.


