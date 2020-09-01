---
title: javaw.exe | OpenJDK Platform binary
---

# javaw.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\javaw.exe`
* Description: OpenJDK Platform binary

## Screenshot

![javaw.exe](screenshots/javaw.exe-6CE5BDFF0E2F280B0A270ECD1AC31E68-6.png)

## Hashes

Type | Hash
-- | --
MD5 | `D661049262036AB21331115E7DA9B9F6`
SHA1 | `0ADAD80378E84006FBDA6915DC5043EBF81B0E40`
SHA256 | `20A2406CE5602476A9519CFD717AA4BF2880DDDEE82CAF1DAA6EBBEB270BD7F5`
SHA384 | `B72C1354858F481CC3E4E82C6F044732491A0CCEBB7CCA8259F69EBDC7E5B2E46B7B24912956BA24DE07B7FABAA7A4CD`
SHA512 | `4D0427115F43887DEE416380E41418C5A5902784780FD7D5E716E564834F6C0677A76EFE12F1308D7FFE22E11DE9D9791AE955D323775BEC1167B0E8BC04B3E9`
SSDEEP | `3072:kI1xqku6rM2slnAhcJzEPZAHQMbQa24TBfXS47k/IXatGa:kIM6HslzJAPZAHQWV24TBv7k/dF`

## Runtime Data

### Usage (stderr):
```Batchfile
Usage: javaw [-options] class [args...]
           (to execute a class)
   or  javaw [-options] -jar jarfile [args...]
           (to execute a jar file)
where options include:
    -d32	  use a 32-bit data model if available
    -d64	  use a 64-bit data model if available
    -server	  to select the "server" VM
    -client	  is a synonym for the "server" VM  [deprecated]
                  The default VM is server.

    -cp <class search path of directories and zip/jar files>
    -classpath <class search path of directories and zip/jar files>
                  A ; separated list of directories, JAR archives,
                  and ZIP archives to search for class files.
    -D<name>=<value>
                  set a system property
    -verbose:[class|gc|jni]
                  enable verbose output
    -version      print product version and exit
    -version:<value>
                  Warning: this feature is deprecated and will be removed
                  in a future release.
                  require the specified version to run
    -showversion  print product version and continue
    -jre-restrict-search | -no-jre-restrict-search
                  Warning: this feature is deprecated and will be removed
                  in a future release.
                  include/exclude user private JREs in the version search
    -? -help      print this help message
    -X            print help on non-standard options
    -ea[:<packagename>...|:<classname>]
    -enableassertions[:<packagename>...|:<classname>]
                  enable assertions with specified granularity
    -da[:<packagename>...|:<classname>]
    -disableassertions[:<packagename>...|:<classname>]
                  disable assertions with specified granularity
    -esa | -enablesystemassertions
                  enable system assertions
    -dsa | -disablesystemassertions
                  disable system assertions
    -agentlib:<libname>[=<options>]
                  load native agent library <libname>, e.g. -agentlib:hprof
                  see also, -agentlib:jdwp=help and -agentlib:hprof=help
    -agentpath:<pathname>[=<options>]
                  load native agent library by full pathname
    -javaagent:<jarpath>[=<options>]
                  load Java programming language agent, see java.lang.instrument
    -splash:<imagepath>
                  show splash screen with specified image
See http://www.oracle.com/technetwork/java/javase/documentation/index.html for more details.

```

### Window Title:
Java Virtual Machine Launcher

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_fd031af45b0106f2 | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme4048709601 | Section
\Windows\Theme603176458 | Section


### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\javaw.exe |
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

* Original Filename: javaw.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\javaw.exe](javaw.exe-7092B30DB438E77CC22951366F17DCA3.md) | 96
[C:\program files (x86)\Amazon Corretto\jre8\bin\javaw.exe](javaw.exe-C60D3E91C016742D2686A8810CA930D9.md) | 97

## Possible Misuse

*The following table contains possible examples of `javaw.exe` being misused. While `javaw.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_adwind.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mal_adwind.yml) | `description: Detects javaw.exe in AppData folder as used by Adwind / JRAT` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


