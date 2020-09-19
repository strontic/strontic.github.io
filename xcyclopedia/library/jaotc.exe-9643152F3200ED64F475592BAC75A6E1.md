---
title: jaotc.exe | OpenJDK Platform binary
---

# jaotc.exe 

* File Path: `C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jaotc.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `9643152F3200ED64F475592BAC75A6E1`
SHA1 | `0CFDA11BE8E65C0B49097E80EDADD74EAAFF1967`
SHA256 | `9BAF45BA540A182154C9D1284206E436FC9E29C4F49C75571999FF1A588EA3ED`
SHA384 | `1B2FA4E9D0D05D7B006497610B1351083978C134272F966E238568F5A77CE7D494E7C762AC7B9C6A6B4F14D167829A05`
SHA512 | `4FB2A1AE2AB1379E818FF6D707A318DA2BA99C755F9263EA35CD24F7D7285A63E053E4566F94B6E4D5633F1DAF6A9AA3E6BD127410C342C637E9CD83E8F893CA`
SSDEEP | `384:G1qA+RvU7+ehCrBbFBW5AlK6jS5XDgf2hJ:GJ+9Q+BJFBW5kKgeXUf2hJ`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: jaotc <options> list

  list       A : separated list of class names, modules, jar files
             or directories which contain class files.

where options include:
  --output <file>            Output file name
  --class-name <class names> List of classes to compile
  --jar <jarfiles>           List of jar files to compile
  --module <modules>         List of modules to compile
  --directory <dirs>         List of directories where to search for files to compile
  --search-path <dirs>       List of directories where to search for specified files
  --compile-commands <file>  Name of file with compile commands
  --compile-for-tiered       Generate profiling code for tiered compilation
  --compile-with-assertions  Compile with java assertions
  --compile-threads <number> Number of compilation threads to be used
  --ignore-errors            Ignores all exceptions thrown during class loading
  --exit-on-error            Exit on compilation errors
  --info                     Print information during compilation
  --verbose                  Print verbose information
  --debug                    Print debug information
  -? -h --help               Print this help message
  --version                  Version information
  --linker-path              Full path to linker executable
  -J<flag>                   Pass <flag> directly to the runtime system

```

### Usage (stderr):
```cmhg
Exception in thread "main" java.lang.InternalError: Can't locate Microsoft Visual Studio amd64 link.exe
	at jdk.aot@11.0.8/jdk.tools.jaotc.Linker.<init>(Linker.java:112)
	at jdk.aot@11.0.8/jdk.tools.jaotc.Main.run(Main.java:160)
	at jdk.aot@11.0.8/jdk.tools.jaotc.Main.run(Main.java:133)
	at jdk.aot@11.0.8/jdk.tools.jaotc.Main.main(Main.java:89)

```

### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jaotc.exe |
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

* Original Filename: jaotc.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jaotc.exe](jaotc.exe-96EA8F503210EF7E3A39EEF68AE137D0.md) | 55
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jaotc.exe](jaotc.exe-FA423CD06BE535088F629C821F437452.md) | 55




MIT License. Copyright (c) 2020 Strontic.


