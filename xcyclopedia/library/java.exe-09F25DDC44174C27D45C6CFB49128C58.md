---
title: java.exe | OpenJDK Platform binary
excerpt: What is java.exe?
---

# java.exe 

* File Path: `C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\java.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `09F25DDC44174C27D45C6CFB49128C58`
SHA1 | `2623525B0EA843A177180777BFB71E6168229C94`
SHA256 | `D5677C7117F8212B85A2E6FFC9BC05C4C5B15957F38429CB36D1E1AADFB9F82D`
SHA384 | `B34C4E469103B0C9617452CC035483ABAD34AE5DE6B63F6D304BC858F72479AFD8753B17D644281324CD2BDFB2D85E0C`
SHA512 | `2ACAC3AEEA7DC7D0BCDEBBBA0C667557599B19A1167BD47A7936F2C535015A3E6A75BD53B35300656C33B94AA17B36B6DBD9CEEFE4CCAAD5BCBA2AEE3BD8A2E9`
SSDEEP | `6144:X0TFpCddwYdXaTC8aEwuHAnmf9TBr7k/PMZ:XspCdCY9lEIS9TunMZ`
IMP | `0F5CC683FA39EDBE3CA8321B37BF56BC`
PESHA1 | `0CB88689612DDB68D1D12E959A23909DBCCD4AC9`
PE256 | `B1F80AFBD35161793F3A90428E97FD1022A7311D430C40C63384156411ECCAA9`

## Runtime Data

### Usage (stderr):
```cmhg
Usage: java [-options] class [args...]
           (to execute a class)
   or  java [-options] -jar jarfile [args...]
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

### Loaded Modules:

Path |
-- |
C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\java.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/d5677c7117f8212b85a2e6ffc9bc05c4c5b15957f38429cb36d1e1aadfb9f82d/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\jre\bin\java.exe](java.exe-7911C3FAF5EB6BEFDF66111F4CF96862.md) | 96
[C:\Program Files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\java.exe](java.exe-2518D9BEC36317CD59660BA5E43AB373.md) | 96

## Possible Misuse

*The following table contains possible examples of `java.exe` being misused. While `java.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_atlassian_confluence_cve_2021_26084_exploit.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_atlassian_confluence_cve_2021_26084_exploit.yml) | `ParentImage\|endswith: '\Atlassian\Confluence\jre\bin\java.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_greenbug_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_greenbug_may20.yml) | `- '\programdata\oracle\java.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_10189.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_10189.yml) | `ParentImage\|endswith: 'DesktopCentral_Server\jre\bin\java.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`java.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of java.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "java.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


