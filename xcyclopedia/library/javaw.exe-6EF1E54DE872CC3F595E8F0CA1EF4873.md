---
title: javaw.exe | OpenJDK Platform binary
---

# javaw.exe 

* File Path: `C:\program files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\javaw.exe`
* Description: OpenJDK Platform binary

## Screenshot

![javaw.exe](screenshots/javaw.exe-6CE5BDFF0E2F280B0A270ECD1AC31E68-6.png)

## Hashes

Type | Hash
-- | --
MD5 | `6EF1E54DE872CC3F595E8F0CA1EF4873`
SHA1 | `51716D89A67C22F6B0597251CEEFCFC07B2C69B5`
SHA256 | `AA43021BBF19FCF42F28D30FFB9191F9C3CCF7236A20F994750FC9F4991A48E5`
SHA384 | `FE16131F65D573FA9BDA9B456CB1082DD6927A86F566F949938DE3E3F060DD930D4ABC538075407AA09B31748AA343B4`
SHA512 | `69D0328E35CEDD1EA828D4BAC79533FBEE8C062E5CECA9F9095613847D3F0E3E839F695380137523DF7B8A9FED72C77184F14879E572A1E044324DCFCE557CE3`
SSDEEP | `6144:joYCzfmQKiU/HTj2JDOHfFsozseI9TB9naZ67k/iAy:jovzfm1ikSD4tZI9Tfc1KAy`

## Runtime Data

### Usage (stderr):
```cmhg
Usage: javaw [-options] class [args...]
           (to execute a class)
   or  javaw [-options] -jar jarfile [args...]
           (to execute a jar file)
where options include:
    -d32	  use a 32-bit data model if available
    -d64	  use a 64-bit data model if available
    -server	  to select the "server" VM
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
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_b555e41d4684ddec | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme4048709601 | Section
\Windows\Theme603176458 | Section


### Loaded Modules:

Path |
-- |
C:\program files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\javaw.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `0F8CE162B26B70AE59D17A0B2A93AB3A`
* Thumbprint: `0180ED75D6615415E4D6C6C217613B4134F5745E`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=London Jamocha Community CIC, O=London Jamocha Community CIC, L=London, C=GB

## File Metadata

* Original Filename: javaw.exe
* Product Name: OpenJDK Platform 8
* Company Name: AdoptOpenJDK
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javaw.exe](javaw.exe-725B4D061520D66C1A34A12C66659D00.md) | 96
[C:\program files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\javaw.exe](javaw.exe-6EEAF0FBE28B66421603A4D4CB6C8FDE.md) | 96

## Possible Misuse

*The following table contains possible examples of `javaw.exe` being misused. While `javaw.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_adwind.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mal_adwind.yml) | `description: Detects javaw.exe in AppData folder as used by Adwind / JRAT` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


