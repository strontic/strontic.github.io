---
title: javaws.exe | 
---

# javaws.exe 

* File Path: `C:\program files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javaws.exe`

## Hashes

Type | Hash
-- | --
MD5 | `3B80846BD1959514903C7334CE229F21`
SHA1 | `6AC709E26BFD5351B5D677C49204DCF371522A32`
SHA256 | `CD0142AD4EE5E46E84447A1A80D3841F3A009F59CECC58F10AD771BC42283F24`
SHA384 | `2D171499B2DD7B95805497A4A5E5816B79EEF717186A901589F3F4CA9AA4729444E594EAF952CF42F8B15AB78B0CECC5`
SHA512 | `1B2B3D7FBF50CBB6E2E0663E65F353E5727880C1812F116A37DE583F9F901A7499F54BF053B5998E9292A0BDCBC86CF97BA5588A46466012307EB94E72E0F3D1`
SSDEEP | `6144:Tr4C59jUJC03oDxVloRS0CRLJIceKYcFWbLUpsnJ1:Trz59jUJC03oDb+CVmLqFgLUOJ1`

## Runtime Data

### Usage (stdout):
```Batchfile
selected jre: C:\Program Files\Amazon Corretto\jdk11.0.8_10\

SYNOPSIS
    javaws [-run-options] jnlp file
    javaws [-control-options]

OPTIONS
    When specifying options, the name of the jnlp file can be after the command, the -jnlp option, an option with no arguments, or after an argument with an option that takes one argument. A html file that launches a jnlp can be specified after the -html option.
    The jnlp-file can either be a url or a local path.
    The JNLP file should only be specified once, whether as a main argument, after -jnlp or through an html file.
    Control options:
    -about               - Shows a sample application.(No argument expected)
    -help                - Prints out information about supported command and basic usage.(No argument expected)
    -license             - Display the GPL license and exit.(No argument expected)
    -viewer              - Shows the trusted certificate viewer.(No argument expected)
    -Xcacheids           - List available IDs in cache, which you can use to delete individual applications.(Expected none or one argument)
    -Xclearcache         - Clean the JNLP application cache. If you pass argument, only specified application is deleted.(Expected none or one argument)
    Run options:
    -allowredirect       - Follows HTTP redirects.(No argument expected)
    -arg arg             - Adds an application argument before launching.(Expected one or more arguments)
    -browser             - Launch embeded browser. Use in great need only!(Expected one or more arguments)
    -headless            - Disables download window, other UIs.(No argument expected)
    -html                - Location of HTML file to launch (url or file). You can use parameter ALL  or numbers (like 1 2 5) to select applets on page. However experimental, this switch should keep you still in safety.(Expected one or more arguments)
    -jnlp                - Location of JNLP file to launch (url or file).(Exactly one argument expected)
    -nosecurity          - Disables the secure runtime environment. You need also  deployment.security.itw.ignorecertissues to workaround corrupted signatures(No argument expected)
    -noupdate            - Disables checking for updates.(No argument expected)
    -param name=value    - Adds an applet parameter before launching.(Expected one or more arguments)
    -property name=value - Sets a system property before launching.(Expected one or more arguments)
    -strict              - Enables strict checking of JNLP file format.(No argument expected)
    -update seconds      - Check for updates.(Exactly one argument expected)
    -verbose             - Enable verbose output.(No argument expected)
    -version             - Print the IcedTea-Web version and exit.(No argument expected)
    -Xignoreheaders      - Skip jar header verification.(No argument expected)
    -xml                 - Uses a strict XML parser to parse the JNLP file.(No argument expected)
    -Xnofork             - Do not create another JVM.(No argument expected)
    -Xoffline            - Prevent ITW network connection. Only cache will be used. Application can still connect.(No argument expected)
    -Xtrustnone          - Instead of asking user, will foretold all answers as no.(No argument expected)


```

### Usage (stderr):
```Batchfile
WARNING: package javax.jnlp not in java.desktop
WARNING: package sun.awt.X11 not in java.desktop
Unable to use Firefox's proxy settings. Using "DIRECT" as proxy type.
netx: Invalid jnlp file /?

```

### Child Processes:
java.exe

### Loaded Modules:

Path |
-- |
C:\program files\AdoptOpenJDK\jdk-8.0.265.01-hotspot\bin\javaws.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `0F8CE162B26B70AE59D17A0B2A93AB3A`
* Thumbprint: `0180ED75D6615415E4D6C6C217613B4134F5745E`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=London Jamocha Community CIC, O=London Jamocha Community CIC, L=London, C=GB

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jre-8.0.265.01-hotspot\bin\javaws.exe](javaws.exe-3B80846BD1959514903C7334CE229F21.md) | 100




MIT License. Copyright (c) 2020 Strontic.


