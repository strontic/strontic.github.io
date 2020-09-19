---
title: jlink.exe | OpenJDK Platform binary
---

# jlink.exe 

* File Path: `C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jlink.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `07394595DDB48711F8120E27E11F1C75`
SHA1 | `481A2BBEAEA4F8E558D583F16D452F8320D8718E`
SHA256 | `2D46596D1738270E51BF71E64DF2275ACC186DE35F16C23065159332422F1554`
SHA384 | `B95F3D54D1F64232207C631DB3EC3F1303E71347849031E3293792005B8724118786BA7CF088E7B9BD0E876EBB5287CC`
SHA512 | `1FFC8089466CCC989881A876D0B29DDB7170177822A3920DAF0160F61E0DDF24195FD3F4F53AB581A25882A2043458D56FF364B25ADD694781B486C32DC920DB`
SSDEEP | `384:jb9biPqfSpkBbF5I5A7xK6jShYUlIeDgf2heEE0:lOP6F5I5oKg4TIeUf2hc0`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: jlink <options> --module-path <modulepath> --add-modules <module>[,<module>...]
Possible options include:
      --add-modules <mod>[,<mod>...]    Root modules to resolve
      --bind-services                   Link in service provider modules and
                                        their dependences
  -c, --compress=<0|1|2>                Enable compression of resources:
                                          Level 0: No compression
                                          Level 1: Constant string sharing
                                          Level 2: ZIP
      --disable-plugin <pluginname>     Disable the plugin mentioned
      --endian <little|big>             Byte order of generated jimage
                                        (default:native)
  -h, --help, -?                        Print this help message
      --ignore-signing-information      Suppress a fatal error when signed
                                        modular JARs are linked in the image.
                                        The signature related files of the
                                        signed modular JARs are not copied to
                                        the runtime image.
      --launcher <name>=<module>[/<mainclass>]
                                        Add a launcher command of the given
                                        name for the module and the main class
                                        if specified  
      --limit-modules <mod>[,<mod>...]  Limit the universe of observable
                                        modules
      --list-plugins                    List available plugins
  -p, --module-path <path>              Module path
      --no-header-files                 Exclude include header files
      --no-man-pages                    Exclude man pages
      --output <path>                   Location of output path
      --post-process-path <imagefile>   Post process an existing image
      --resources-last-sorter <name>    The last plugin allowed to sort
                                        resources
      --save-opts <filename>            Save jlink options in the given file
  -G, --strip-debug                     Strip debug information
      --suggest-providers [<name>,...]  Suggest providers that implement the
                                        given service types from the module path
  -v, --verbose                         Enable verbose tracing
      --version                         Version information
      @<filename>                       Read options from file

```

### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jlink.exe |
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

* Original Filename: jlink.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javac.exe](javac.exe-3AF21D2F89F7E5A7409CF655538E4908.md) | 44
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jlink.exe](jlink.exe-15C86A7D8376EC476DD2AE27EAEE31D1.md) | 50
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\javac.exe](javac.exe-C600CD49BD0682A3DBD8C8356D0799EA.md) | 69




MIT License. Copyright (c) 2020 Strontic.


