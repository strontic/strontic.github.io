---
title: javaw.exe | OpenJDK Platform binary
excerpt: What is javaw.exe?
---

# javaw.exe 

* File Path: `C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javaw.exe`
* Description: OpenJDK Platform binary

## Screenshot

![javaw.exe](screenshots/javaw.exe-6CE5BDFF0E2F280B0A270ECD1AC31E68-6.png)

## Hashes

Type | Hash
-- | --
MD5 | `2CD1B7F9036089B628BFC45F90B989FE`
SHA1 | `EB8A7F848AD47B6C8DD07D88C3D7ABF0B28DE06B`
SHA256 | `EBCA776647DC97B75FCE58B334018D52A6D7C8E8F37911E7F0CDA84540F3633B`
SHA384 | `E75A01995630CC31B49FEEC5C72D360F27EC2E1946136709BE726D7A679B3DFD032CD11B93A6EA93F9DA86ED4B9EE73A`
SHA512 | `4C81B41241F34F23BF0E95C1ACFA725376DA3CE6795EDD6EC7143CADA9173FC3E72087F332569D03CCF2CC2B8F8EB2A3F1571772BF711D379457E120745D4862`
SSDEEP | `768:iagQPdb2FM5R2TyJ5R3s8D/bkt5Ruz3Vb3hM51Q8DGD:lgoSM5RdJ5R3sozkt5RA3hM5uL`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: javaw [options] <mainclass> [args...]
           (to execute a class)
   or  javaw [options] -jar <jarfile> [args...]
           (to execute a jar file)
   or  javaw [options] -m <module>[/<mainclass>] [args...]
       javaw [options] --module <module>[/<mainclass>] [args...]
           (to execute the main class in a module)
   or  javaw [options] <sourcefile> [args]
           (to execute a single source-file program)

 Arguments following the main class, source file, -jar <jarfile>,
 -m or --module <module>/<mainclass> are passed as the arguments to
 main class.

 where options include:

    -client	  to select the "client" VM
    -cp <class search path of directories and zip/jar files>
    -classpath <class search path of directories and zip/jar files>
    --class-path <class search path of directories and zip/jar files>
                  A ; separated list of directories, JAR archives,
                  and ZIP archives to search for class files.
    -p <module path>
    --module-path <module path>...
                  A ; separated list of directories, each directory
                  is a directory of modules.
    --upgrade-module-path <module path>...
                  A ; separated list of directories, each directory
                  is a directory of modules that replace upgradeable
                  modules in the runtime image
    --add-modules <module name>[,<module name>...]
                  root modules to resolve in addition to the initial module.
                  <module name> can also be ALL-DEFAULT, ALL-SYSTEM,
                  ALL-MODULE-PATH.
    --list-modules
                  list observable modules and exit
    -d <module name>
    --describe-module <module name>
                  describe a module and exit
    --dry-run     create VM and load main class but do not execute main method.
                  The --dry-run option may be useful for validating the
                  command-line options such as the module system configuration.
    --validate-modules
                  validate all modules and exit
                  The --validate-modules option may be useful for finding
                  conflicts and other errors with modules on the module path.
    -D<name>=<value>
                  set a system property
    -verbose:[class|module|gc|jni]
                  enable verbose output
    -version      print product version to the error stream and exit
    --version     print product version to the output stream and exit
    -showversion  print product version to the error stream and continue
    --show-version
                  print product version to the output stream and continue
    --show-module-resolution
                  show module resolution output during startup
    -? -h -help
                  print this help message to the error stream
    --help        print this help message to the output stream
    -X            print help on extra options to the error stream
    --help-extra  print help on extra options to the output stream
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
                  load native agent library <libname>, e.g. -agentlib:jdwp
                  see also -agentlib:jdwp=help
    -agentpath:<pathname>[=<options>]
                  load native agent library by full pathname
    -javaagent:<jarpath>[=<options>]
                  load Java programming language agent, see java.lang.instrument
    -splash:<imagepath>
                  show splash screen with specified image
                  HiDPI scaled images are automatically supported and used
                  if available. The unscaled image filename, e.g. image.ext,
                  should always be passed as the argument to the -splash option.
                  The most appropriate scaled image provided will be picked up
                  automatically.
                  See the SplashScreen API documentation for more information
    @argument files
                  one or more argument files containing options
    -disable-@files
                  prevent further argument file expansion
    --enable-preview
                  allow classes to depend on preview features of this release
To specify an argument for a long option, you can use --<name>=<value> or
--<name> <value>.


```

### Usage (stderr):
```cmhg
Usage: javaw [options] <mainclass> [args...]
           (to execute a class)
   or  javaw [options] -jar <jarfile> [args...]
           (to execute a jar file)
   or  javaw [options] -m <module>[/<mainclass>] [args...]
       javaw [options] --module <module>[/<mainclass>] [args...]
           (to execute the main class in a module)
   or  javaw [options] <sourcefile> [args]
           (to execute a single source-file program)

 Arguments following the main class, source file, -jar <jarfile>,
 -m or --module <module>/<mainclass> are passed as the arguments to
 main class.

 where options include:

    -client	  to select the "client" VM
    -cp <class search path of directories and zip/jar files>
    -classpath <class search path of directories and zip/jar files>
    --class-path <class search path of directories and zip/jar files>
                  A ; separated list of directories, JAR archives,
                  and ZIP archives to search for class files.
    -p <module path>
    --module-path <module path>...
                  A ; separated list of directories, each directory
                  is a directory of modules.
    --upgrade-module-path <module path>...
                  A ; separated list of directories, each directory
                  is a directory of modules that replace upgradeable
                  modules in the runtime image
    --add-modules <module name>[,<module name>...]
                  root modules to resolve in addition to the initial module.
                  <module name> can also be ALL-DEFAULT, ALL-SYSTEM,
                  ALL-MODULE-PATH.
    --list-modules
                  list observable modules and exit
    -d <module name>
    --describe-module <module name>
                  describe a module and exit
    --dry-run     create VM and load main class but do not execute main method.
                  The --dry-run option may be useful for validating the
                  command-line options such as the module system configuration.
    --validate-modules
                  validate all modules and exit
                  The --validate-modules option may be useful for finding
                  conflicts and other errors with modules on the module path.
    -D<name>=<value>
                  set a system property
    -verbose:[class|module|gc|jni]
                  enable verbose output
    -version      print product version to the error stream and exit
    --version     print product version to the output stream and exit
    -showversion  print product version to the error stream and continue
    --show-version
                  print product version to the output stream and continue
    --show-module-resolution
                  show module resolution output during startup
    -? -h -help
                  print this help message to the error stream
    --help        print this help message to the output stream
    -X            print help on extra options to the error stream
    --help-extra  print help on extra options to the output stream
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
                  load native agent library <libname>, e.g. -agentlib:jdwp
                  see also -agentlib:jdwp=help
    -agentpath:<pathname>[=<options>]
                  load native agent library by full pathname
    -javaagent:<jarpath>[=<options>]
                  load Java programming language agent, see java.lang.instrument
    -splash:<imagepath>
                  show splash screen with specified image
                  HiDPI scaled images are automatically supported and used
                  if available. The unscaled image filename, e.g. image.ext,
                  should always be passed as the argument to the -splash option.
                  The most appropriate scaled image provided will be picked up
                  automatically.
                  See the SplashScreen API documentation for more information
    @argument files
                  one or more argument files containing options
    -disable-@files
                  prevent further argument file expansion
    --enable-preview
                  allow classes to depend on preview features of this release
To specify an argument for a long option, you can use --<name>=<value> or
--<name> <value>.


```

### Loaded Modules:

Path |
-- |
C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javaw.exe |
C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jli.dll |
C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\VCRUNTIME140.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_b555e41d4684ddec\COMCTL32.dll |


## Signature

* Status: Signature verified.
* Serial: `0F8CE162B26B70AE59D17A0B2A93AB3A`
* Thumbprint: `0180ED75D6615415E4D6C6C217613B4134F5745E`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=London Jamocha Community CIC, O=London Jamocha Community CIC, L=London, C=GB

## File Metadata

* Original Filename: javaw.exe
* Product Name: OpenJDK Platform 11
* Company Name: AdoptOpenJDK
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\java.exe](java.exe-B6E59B7366EB5856C992AC5CAD257C17.md) | 75
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\java.exe](java.exe-D36757DCE912D160CA59090F1B3A5409.md) | 77
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\javaw.exe](javaw.exe-FFAE755FD5D5CC1D967D4DEB3E9501FE.md) | 97
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\java.exe](java.exe-C3D6393B399F55B9432AA68D5C2C778C.md) | 66
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\javaw.exe](javaw.exe-4DA92AE589E68FE36F2C8FA022DD5AA5.md) | 74

## Possible Misuse

*The following table contains possible examples of `javaw.exe` being misused. While `javaw.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mal_adwind.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mal_adwind.yml) | `description: Detects javaw.exe in AppData folder as used by Adwind / JRAT`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


