---
title: java.exe | OpenJDK Platform binary
---

# java.exe 

* File Path: `C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\java.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `A7432D50174B9CE73820190D5C53A328`
SHA1 | `32251FE6E082698C0317F8B4C1793F13021BA095`
SHA256 | `E6585FFDA88FDFEBA0B941372799ED846D53F9D0C96B1DC783E4E7327ABD1BE9`
SHA384 | `ED643979CA6100D16B7ADDF4ECFE491BC48C67CEAE050691E361B9298FB7E7C746B0807AAD71428F49395FE52870412F`
SHA512 | `511E9237073EF5F0B33C141F7FE9CFA7B22D98352FE645D50F3A94DA437933A47B83F08438F7C74E9421734F0CA1D6BEC78C2D69A11FA8095DD6B2FD108100CA`
SSDEEP | `3072:e6Hm9nIIhfzMz+St5dOu7aq2WeCuXbvHXbz3DVIQuB6e+peARB9M5ZNTBfAO8Vc2:TtIK6RXB9M5ZNTBN7k/P7/q2`

## Runtime Data

### Usage (stderr):
```Batchfile
Usage: java [-options] class [args...]
           (to execute a class)
   or  java [-options] -jar jarfile [args...]
           (to execute a jar file)
where options include:
    -d32	  use a 32-bit data model if available
    -d64	  use a 64-bit data model if available
    -client	  to select the "client" VM
    -server	  to select the "server" VM
                  The default VM is client.

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

### Loaded Modules:

Path |
-- |
C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\java.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `0F8CE162B26B70AE59D17A0B2A93AB3A`
* Thumbprint: `0180ED75D6615415E4D6C6C217613B4134F5745E`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=London Jamocha Community CIC, O=London Jamocha Community CIC, L=London, C=GB

## File Metadata

* Original Filename: java.exe
* Product Name: OpenJDK Platform 8
* Company Name: AdoptOpenJDK
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\java.exe](java.exe-14C8D2CCB3E6701C84D6659562E5494E.md) | 97
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javaw.exe](javaw.exe-FC2AF8B73B73165E7D6F00A4327FF387.md) | 54
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\java.exe](java.exe-415FE375F2BC0114CE6F34AEC91D1D10.md) | 97
[C:\program files (x86)\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\javaw.exe](javaw.exe-6CE5BDFF0E2F280B0A270ECD1AC31E68.md) | 54
[C:\program files (x86)\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\javaw.exe](javaw.exe-E525F9C4FEAE503CFAE7D6706867A898.md) | 54

## Possible Misuse

*The following table contains possible examples of `java.exe` being misused. While `java.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_greenbug_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_greenbug_may20.yml) | `            - '\programdata\oracle\java.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_10189.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_10189.yml) | `        ParentImage\|endswith: 'DesktopCentral_Server\jre\bin\java.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`java.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) |         description = "Detects uncommon file size of java.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) |         and filename == "java.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


