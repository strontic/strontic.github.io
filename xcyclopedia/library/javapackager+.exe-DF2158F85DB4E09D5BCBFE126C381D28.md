---
title: javapackager .exe | OpenJFX Platform binary
excerpt: What is javapackager .exe?
---

# javapackager .exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\javapackager .exe`
* Description: OpenJFX Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `DF2158F85DB4E09D5BCBFE126C381D28`
SHA1 | `DF5DB0B8F4B452E5F63760BA6587A7EDCFF687E3`
SHA256 | `3D5DA7731441C2B15FBD152FDFC41D11B2EF121AD0FA32FE8D9A9BD67C9597CD`
SHA384 | `1E9DE4CC48DA87262AF41C7C95C04E3388D8E61C0343CC520ADD15A61C37A18B5A68E5726178350C9080B1CFCCCB7061`
SHA512 | `6E405FC3F905AEABBA3D8DEE00AB4193A34AAA8FA68CA1D5BA9F4B9B9A21C7C6C63C39E9740D379F3BDA9C9BB76ACF5F9E988F25DE23C5977BFBDFDB473A71C2`
SSDEEP | `3072:k/ipj3RHEqs3NOZD/NXQGOiMQvJdKWgmijvBd4g7yiMtJc:LNlQ3NkHOkJtgeNtJc`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: javapackager -command [-options]

where command is one of: 
  -createjar
          The packager produces jar archive according to other parameters. 
  -deploy 
          The packager generates the jnlp and html files according to other
          parameters.
  -createbss
          Converts css file into binary form 
  -signJar
          Signs jar file(s) with a provided certificate.
  -makeall
          Performs compilation, createjar and deploy steps as one call with 
          most arguments predefined. The sources must be located in "src"
          folder, the resulting files (jar, jnlp, html) are put in "dist"
          folder. This command may be configured only in a minimal way and is
          as automated as possible.

Options for createjar command include: 
  -appclass <application class>
          qualified name of the application class to be executed.
  -preloader <preloader class>
          qualified name of the preloader class to be executed.
  -paramfile <file>
          properties file with default named application parameters.
  -argument arg
          An unnamed argument to be put in <fx:argument> element in the JNLP
          file.
  -classpath <files>
          list of dependent jar file names.
  -manifestAttrs <manifest attributes>
          List of additional manifest attributes. Syntax: "name1=value1,
          name2=value2,name3=value3.
  -noembedlauncher 
          If present, the packager will not add the JavaFX launcher classes
          to the jarfile.
  -nocss2bin
          The packager won't convert CSS files to binary form before copying
          to jar. 
  -runtimeversion <version> 
          version of the required JavaFX Runtime.
  -outdir <dir>
          name of the directory to generate output file to.
  -outfile <filename>
          The name (without the extension) of the resulting file.
  -srcdir <dir>
          Base dir of the files to pack.
  -srcfiles <files>
          List of files in srcdir. If omitted, all files in srcdir (which
          is a mandatory argument in this case) will be packed.

Options for deploy command include:
  -title <title>
          title of the application.
  -vendor <vendor>
          vendor of the application.
  -description <description>
          description of the application.
  -appclass <application class>
          qualified name of the application class to be executed.
  -preloader <preloader class>
          qualified name of the preloader class to be executed.
  -paramfile <file>
          properties file with default named application parameters.
  -htmlparamfile <file>
          properties file with parameters for the resulting applet.
  -width <width>
          width of the application.
  -height <height>
          height of the application.
  -native <type>
          generate self-contained application bundles (if possible).
          If type is specified then only bundle of this type is created.
          List of supported types includes: installer, image, exe, msi, dmg, rpm, deb.
  -name <name>
          name of the application.
  -embedjnlp
          If present, the jnlp file will be embedded in the html document.
  -embedCertificates
          If present, the certificates will be embedded in the jnlp file.
  -allpermissions
          If present, the application will require all security permissions 
          in the jnlp file.
  -updatemode <updatemode>
          sets the update mode for the jnlp file.
  -isExtension
          if present, the srcfiles are treated as extensions.
  -callbacks
          specifies user callback methods in generated HTML. The format is
          "name1:value1,name2:value2,..."
  -templateInFilename
          name of the html template file. Placeholders are in form of
          #XXXX.YYYY(APPID)#
  -templateOutFilename
          name of the html file to write the filled-in template to.
  -templateId
          Application ID of the application for template processing.
  -argument arg
          An unnamed argument to be put in <fx:argument> element in the JNLP
          file.
  -outdir <dir>
          name of the directory to generate output file to.
  -outfile <filename>
          The name (without the extension) of the resulting file.
  -srcdir <dir>
          Base dir of the files to pack.
  -srcfiles <files>
          List of files in srcdir. If omitted, all files in srcdir (which
          is a mandatory argument in this case) will be used.

Options for createbss command include:
  -outdir <dir>
          name of the directory to generate output file to.
  -srcdir <dir>
          Base dir of the files to pack.
  -srcfiles <files>
          List of files in srcdir. If omitted, all files in srcdir (which
          is a mandatory argument in this case) will be used.

Options for signJar command include:
  -keyStore <file>
          Keystore filename.
  -alias 
          Alias for the key.
  -storePass
          Password to check integrity of the keystore or unlock the keystore.
  -keyPass
          Password for recovering the key.
  -storeType
          Keystore type, the default value is "jks".
  -outdir <dir>
          name of the directory to generate output file(s) to.
  -srcdir <dir>
          Base dir of the files to signed.
  -srcfiles <files>
          List of files in srcdir. If omitted, all files in srcdir (which
          is a mandatory argument in this case) will be signed.

Options for makeAll command include:
  -appclass <application class>
          qualified name of the application class to be executed.
  -preloader <preloader class>
          qualified name of the preloader class to be executed.
  -classpath <files>
          list of dependent jar file names.
  -name <name>
          name of the application.
  -width <width>
          width of the application.
  -height <height>
          height of the application.
  -v      enable verbose output.

Sample usages:
--------------
javapackager -createjar -appclass package.ClassName  
  -srcdir classes -outdir out -outfile outjar -v
          Packages the content of the classes directory to outjar.jar,
          sets the application class to package.ClassName.
javapackager -deploy -outdir outdir -outfile outfile -width 34 -height 43 
  -name AppName -appclass package.ClassName -v -srcdir compiled
          Generates outfile.jnlp and corresponding outfile.html files in 
          outdir for aplication AppName that is started by package.ClassName
          class and has dimensions of 34x43.
javapackager -makeall -appclass brickbreaker.Main -name BrickBreaker
  -width 600 -height 600
          This command does all the packaging work including compilation: 
          compile, createjar, deploy.

```

### Usage (stderr):
```cmhg
Error: Unknown command: --help

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\javapackager.exe |
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

* Original Filename: javapackager.exe
* Product Name: OpenJFX Platform 8
* Company Name: N/A
* File Version: 8.0.2020.0
* Product Version: 8.0.2020.0
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\javafxpackager .exe](javafxpackager+.exe-74BE3EB4DF355EA3D82D03F5A3D05C26.md) | 94




MIT License. Copyright (c) 2020-2021 Strontic.


