---
title: jdeps.exe | OpenJDK Platform binary
---

# jdeps.exe 

* File Path: `C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jdeps.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `93A0053100DB342311A5461DC158F9C5`
SHA1 | `E85F4D5937527C63F9001AA1BFCFD64947071BDA`
SHA256 | `6B08E4AD578CADBA15C50968774B1745509D4D416C2BC591D718EAB7EE54D1A6`
SHA384 | `02C3C1216781725EB11E953708F29CD8125C94607A76FD18A095C45C5B43D1233B2A138400C1B1AA62C761F34E75ED20`
SHA512 | `9461BBEFB2FA8DE95687B72B44BE1EBE6503C8EEC2940C522AD93EAF326FEF9713E943B4760DAF00B6AB0B16813B4D6D496F1A9C1FA6247901B57749682B5EF0`
SSDEEP | `384:bbdNt3yyZi8kaiuBbF2KM5A7zNK6jShECMDgf2hx:9OlpLIFHM5sKgnUf2hx`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: jdeps <options> <path ...>]
<path> can be a pathname to a .class file, a directory, a JAR file.

Possible options include:
  -h -? --help                  Print this help message
  -dotoutput <dir>
  --dot-output <dir>            Destination directory for DOT file output
  -s       -summary             Print dependency summary only.
  -v       -verbose             Print all class level dependences
                                Equivalent to -verbose:class -filter:none.
  -verbose:package              Print package-level dependences excluding
                                dependences within the same package by default
  -verbose:class                Print class-level dependences excluding
                                dependences within the same package by default
  -apionly
  --api-only                    Restrict analysis to APIs i.e. dependences
                                from the signature of public and protected
                                members of public classes including field
                                type, method parameter types, returned type,
                                checked exception types etc.
  -jdkinternals
  --jdk-internals               Finds class-level dependences on JDK internal
                                APIs. By default, it analyzes all classes
                                on --class-path and input files unless -include
                                option is specified. This option cannot be
                                used with -p, -e and -s options.
                                WARNING: JDK internal APIs are inaccessible.
  -cp <path>
  -classpath <path>
  --class-path <path>           Specify where to find class files
  --module-path <module path>   Specify module path
  --upgrade-module-path <module path>  Specify upgrade module path
  --system <java-home>          Specify an alternate system module path
  --add-modules <module-name>[,<module-name>...]
                                Adds modules to the root set for analysis
  --multi-release <version>     Specifies the version when processing
                                multi-release jar files.  <version> should
                                be integer >= 9 or base.
  -q       -quiet               Suppress warning messages
  -version --version            Version information

Module dependence analysis options:
  -m <module-name>
  --module <module-name>        Specify the root module for analysis
  --generate-module-info <dir>  Generate module-info.java under the specified
                                directory. The specified JAR files will be
                                analyzed. This option cannot be used with
                                --dot-output or --class-path. Use 
                                --generate-open-module option for open modules.
  --generate-open-module <dir>  Generate module-info.java for the specified
                                JAR files under the specified directory as
                                open modules. This option cannot be used with
                                --dot-output or --class-path.
  --check <module-name>[,<module-name>...
                                Analyze the dependence of the specified modules
                                It prints the module descriptor, the resulting
                                module dependences after analysis and the
                                graph after transition reduction.  It also
                                identifies any unused qualified exports.
  --list-deps                   Lists the module dependences.  It also prints
                                any JDK internal API packages if referenced.
                                This option does not show dependences on the
                                class path or not found.
  --list-reduced-deps           Same as --list-deps with not listing
                                the implied reads edges from the module graph.
                                If module M1 reads M2, and M2 requires
                                transitive on M3, then M1 reading M3 is implied
                                and is not shown in the graph.
  --print-module-deps           Same as --list-reduced-deps with printing
                                a comma-separated list of module dependences.
                                This output can be used by jlink --add-modules
                                in order to create a custom image containing
                                those modules and their transitive dependences.

Options to filter dependences:
  -p <pkg>
  -package <pkg>
  --package <pkg>               Finds dependences matching the given package
                                name (may be given multiple times).
  -e <regex>
  -regex <regex>
  --regex <regex>               Finds dependences matching the given pattern.
  --require <module-name>       Finds dependences matching the given module
                                name (may be given multiple times). --package,
                                --regex, --require are mutual exclusive.
  -f <regex> -filter <regex>    Filter dependences matching the given
                                pattern. If given multiple times, the last
                                one will be used.
  -filter:package               Filter dependences within the same package.
                                This is the default.
  -filter:archive               Filter dependences within the same archive.
  -filter:module                Filter dependences within the same module.
  -filter:none                  No -filter:package and -filter:archive
                                filtering.  Filtering specified via the
                                -filter option still applies.


Options to filter classes to be analyzed:
  -include <regex>              Restrict analysis to classes matching pattern
                                This option filters the list of classes to
                                be analyzed.  It can be used together with
                                -p and -e which apply pattern to the dependences
  -P       -profile             Show profile containing a package
  -R       -recursive           Recursively traverse all run-time dependences.
                                The -R option implies -filter:none.  If -p,
                                -e, -f option is specified, only the matching
                                dependences are analyzed.
  -I       --inverse            Analyzes the dependences per other given options
                                and then find all artifacts that directly
                                and indirectly depend on the matching nodes.
                                This is equivalent to the inverse of
                                compile-time view analysis and print
                                dependency summary.  This option must use
                                with --require, --package or --regex option.
  --compile-time                Compile-time view of transitive dependences
                                i.e. compile-time view of -R option.
                                Analyzes the dependences per other given options
                                If a dependence is found from a directory,
                                a JAR file or a module, all classes in that 
                                containing archive are analyzed.

```

### Usage (stderr):
```cmhg
Exception in thread "main" java.nio.file.InvalidPathException: Illegal char <?> at index 1: /?
	at java.base/sun.nio.fs.WindowsPathParser.normalize(WindowsPathParser.java:182)
	at java.base/sun.nio.fs.WindowsPathParser.parse(WindowsPathParser.java:153)
	at java.base/sun.nio.fs.WindowsPathParser.parse(WindowsPathParser.java:77)
	at java.base/sun.nio.fs.WindowsPath.parse(WindowsPath.java:92)
	at java.base/sun.nio.fs.WindowsFileSystem.getPath(WindowsFileSystem.java:229)
	at java.base/java.nio.file.Path.of(Path.java:147)
	at java.base/java.nio.file.Paths.get(Paths.java:69)
	at jdk.jdeps/com.sun.tools.jdeps.JdepsTask.buildConfig(JdepsTask.java:581)
	at jdk.jdeps/com.sun.tools.jdeps.JdepsTask.run(JdepsTask.java:543)
	at jdk.jdeps/com.sun.tools.jdeps.JdepsTask.run(JdepsTask.java:519)
	at jdk.jdeps/com.sun.tools.jdeps.Main.main(Main.java:49)

```

### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jdeps.exe |
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

* Original Filename: jdeps.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jar.exe](jar.exe-B39F84FB8C26E73075627CF8A3E30B00.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\javap.exe](javap.exe-E53972D2FEB5711E552CE72695BF2572.md) | 52
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jcmd.exe](jcmd.exe-B264E0660D3BF070AAD25F2F033B9436.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jdeps.exe](jdeps.exe-A2D8568F6868C17A7A8C88B625FDB100.md) | 58
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-08F03ABD9FF453E929D3232120C51BD7.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jimage.exe](jimage.exe-D25C31744405D6ACAA96E47DE6F8D837.md) | 52
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jmod.exe](jmod.exe-66A78959DA40CE102F7BB09A8C73395A.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jps.exe](jps.exe-8B98A486BF91B0F184B1C587BB2B680F.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstat.exe](jstat.exe-92DD217A9387CDFD9D0F65CACD5DE308.md) | 55
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jstatd.exe](jstatd.exe-F51B29210060B0377FB4EA13AFD3FD9D.md) | 52
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-1D16A2748895E35498E4E22F15EB5AC0.md) | 40
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\klist.exe](klist.exe-9371A9AC3DC11410EA50EA8C21C83C89.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-C6FB113B79364970E2246CCFB40878D0.md) | 41
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmic.exe](rmic.exe-BBCF27C5346C3075D09DF7355AEBB582.md) | 43
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-D98CF348139BB44E4EFCA15FEA955F7C.md) | 44
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jfr.exe](jfr.exe-065E5E752266CD2FA6F1CF2564249B21.md) | 41
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\kinit.exe](kinit.exe-17561E8FCB677496BC34D76B2F9BE380.md) | 41
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\klist.exe](klist.exe-7D151D16C96009205B92251019F782AF.md) | 44
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\ktab.exe](ktab.exe-F45CED87218ADC894C655258D1FC5C10.md) | 41
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\rmid.exe](rmid.exe-62D6E0918BC131ABDB5F5A98A66346EF.md) | 44
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jar.exe](jar.exe-90E9FDEDBD307AAD814B9B310EF9EEF6.md) | 65
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\javap.exe](javap.exe-5FDBAB868D53F447324D0CEC119EADF4.md) | 72
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jcmd.exe](jcmd.exe-8B031007B293E1B238FE7040C1E78BA9.md) | 55
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jfr.exe](jfr.exe-B33A8A8C02F57743444E9F96936783DE.md) | 58
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jimage.exe](jimage.exe-52585947B2B10A2C41E370B60D85A837.md) | 69
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jmod.exe](jmod.exe-FD6825DE6B411FB98408250B4242E4CF.md) | 58
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jps.exe](jps.exe-EAB3A072CA16676197FF86E06CBA9F13.md) | 61
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jstat.exe](jstat.exe-94511EDBA5FC73EF516B66FF0BBFF032.md) | 71
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jstatd.exe](jstatd.exe-5B818E750FE168F05BFF9A30354DEF83.md) | 71
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\kinit.exe](kinit.exe-2E9727621161826FE230D5C529D4D57A.md) | 63
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\klist.exe](klist.exe-0114F130B4E2B2C847324EF3EE2231B1.md) | 66
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\ktab.exe](ktab.exe-F3797AE1D338EAA8C55B716127B2FE64.md) | 57
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\rmic.exe](rmic.exe-B0BE3B0798C023F1A21C4E066BAE9527.md) | 58
[C:\program files\Amazon Corretto\jdk11.0.8_10\bin\rmid.exe](rmid.exe-1D81A7BE447A5B0CF10B76D15B1C69BC.md) | 58




MIT License. Copyright (c) 2020 Strontic.


