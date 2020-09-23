---
title: jdeps.exe | OpenJDK Platform binary
excerpt: What is jdeps.exe?
---

# jdeps.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jdeps.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `3391DEEABD10D7DF3EC9A1EA35F11ADA`
SHA1 | `B2E941E004FF3645FA9E978AAC87A579D8DF9ACA`
SHA256 | `2CCACA6E8C7F2689D2F48902ADB113DCFF1D150B62BA157243AAB8BD8F7074BE`
SHA384 | `9B8884CB9808B2CD62056DFAA79E92787827D22ECD8CE3F3A02E07A9FCBD5C9817B55F78DB9B25C1C1AD0F9A83D8FD7C`
SHA512 | `0724FA697D85E386F46A1348484895BD0E78D2CD090D6595B0094D1B62C87A3BFEBDE1FCEC2A7F48A2F809897E38D1F01408069E8158185F8B0FE0FB51D345D8`
SSDEEP | `384:GpsL5hnMaGmSHhV8yJydeeL4SzlTK6jSqlskDgf2hH:Gps7nhS/8yJyMeLvKgNekUf2hH`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: jdeps <options> <classes...>
where <classes> can be a pathname to a .class file, a directory, a JAR file,
or a fully-qualified class name.  Possible options include:
  -dotoutput <dir>                   Destination directory for DOT file output
  -s           -summary              Print dependency summary only
  -v           -verbose              Print all class level dependencies
                                     Equivalent to -verbose:class -filter:none.
  -verbose:package                   Print package-level dependencies excluding
                                     dependencies within the same package by default
  -verbose:class                     Print class-level dependencies excluding
                                     dependencies within the same package by default
  -cp <path>   -classpath <path>     Specify where to find class files
  -p <pkgname> -package <pkgname>    Finds dependences matching the given package name
                                     (may be given multiple times)
  -e <regex>   -regex <regex>        Finds dependences matching the given pattern
                                     (-p and -e are exclusive)
  -f <regex>   -filter <regex>       Filter dependences matching the given pattern
                                     If given multiple times, the last one will be used.
  -filter:package                    Filter dependences within the same package (default)
  -filter:archive                    Filter dependences within the same archive
  -filter:none                       No -filter:package and -filter:archive filtering
                                     Filtering specified via the -filter option still applies.
  -include <regex>                   Restrict analysis to classes matching pattern
                                     This option filters the list of classes to
                                     be analyzed.  It can be used together with
                                     -p and -e which apply pattern to the dependences
  -P           -profile              Show profile or the file containing a package
  -apionly                           Restrict analysis to APIs i.e. dependences
                                     from the signature of public and protected
                                     members of public classes including field
                                     type, method parameter types, returned type,
                                     checked exception types etc
  -R           -recursive            Recursively traverse all dependencies.
                                     The -R option implies -filter:none.  If -p, -e, -f
                                     option is specified, only the matching dependences
                                     are analyzed.
  -jdkinternals                      Finds class-level dependences on JDK internal APIs.
                                     By default, it analyzes all classes on -classpath
                                     and input files unless -include option is specified.
                                     This option cannot be used with -p, -e and -s options.
                                     WARNING: JDK internal APIs may not be accessible in
                                     the next release.
  -version                           Version information

```

### Usage (stderr):
```cmhg
Exception in thread "main" java.nio.file.InvalidPathException: Illegal char <?> at index 1: /?
	at sun.nio.fs.WindowsPathParser.normalize(WindowsPathParser.java:182)
	at sun.nio.fs.WindowsPathParser.parse(WindowsPathParser.java:153)
	at sun.nio.fs.WindowsPathParser.parse(WindowsPathParser.java:77)
	at sun.nio.fs.WindowsPath.parse(WindowsPath.java:94)
	at sun.nio.fs.WindowsFileSystem.getPath(WindowsFileSystem.java:255)
	at java.nio.file.Paths.get(Paths.java:84)
	at com.sun.tools.jdeps.JdepsTask.findDependencies(JdepsTask.java:494)
	at com.sun.tools.jdeps.JdepsTask.run(JdepsTask.java:324)
	at com.sun.tools.jdeps.JdepsTask.run(JdepsTask.java:306)
	at com.sun.tools.jdeps.Main.main(Main.java:48)

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jdeps.exe |
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

* Original Filename: jdeps.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\extcheck.exe](extcheck.exe-803AFFB2F03A9D302817D45E59C3BB4F.md) | 71
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\javac.exe](javac.exe-3A9578BFD3BB7869169BAC29E497AF55.md) | 74
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\javadoc.exe](javadoc.exe-60735A8E38579FDB6320851C1DE38408.md) | 69
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\javah.exe](javah.exe-41789B4535F6A0A491368C7CDBF08149.md) | 71
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\javap.exe](javap.exe-D4B6FF69D8B33AE1C748D03B170A5828.md) | 71
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jfr.exe](jfr.exe-B941B77B992BC329570061F0856916EA.md) | 68
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jjs.exe](jjs.exe-50283CF0315C0D9CB58A0C666D5CEFF7.md) | 69
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\native2ascii.exe](native2ascii.exe-3CD4E62074A39B93E3448C1F46CE55F2.md) | 63
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\pack200.exe](pack200.exe-2B30CC6FFE825CC181A4A3F9FDF071D7.md) | 68
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\rmid.exe](rmid.exe-C86BB878FAD845F245B23042C5135E97.md) | 66
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\jjs.exe](jjs.exe-EF545E6EFCC0E8BA4089FE7DC1DFDE90.md) | 68
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\rmid.exe](rmid.exe-148834ECF2DA0E30B7D80AC0019E6C67.md) | 66
[C:\program files (x86)\Amazon Corretto\jre8\bin\jjs.exe](jjs.exe-F1EAC51F83F1299AD8072546BD948015.md) | 71
[C:\program files (x86)\Amazon Corretto\jre8\bin\rmid.exe](rmid.exe-D8EC5ABE57565E6260EA2D62D74EF506.md) | 66




MIT License. Copyright (c) 2020 Strontic.


