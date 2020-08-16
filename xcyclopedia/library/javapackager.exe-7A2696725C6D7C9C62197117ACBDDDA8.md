---
title: javapackager.exe | OpenJFX Platform binary
---

# javapackager.exe 

* File Path: `C:\Program Files\Amazon Corretto\jdk1.8.0_265\bin\javapackager.exe`
* Description: OpenJFX Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `7A2696725C6D7C9C62197117ACBDDDA8`
SHA1 | `09CC96B6D5A79AE69A806CFD9EBCFEAC5D865075`
SHA256 | `28E86C42051D27589FF7B1E6C4D17D4329D4913A29D8A5132F56E5CC137C64EC`
SHA384 | `ACC89D078F91253F146A915334F6D3E492C666C3FFCBD202CE6F20481BB0E7AF97AF0C7EE6285959D0601CB142A1D8CA`
SHA512 | `60E7229E4618AE903D6506D57BB72EF940289772CAFB789BA24F273A0B2153EC292B8432DC687363FDB60C0BBDBDA1D848A14EEBB35609D58C870B13D0186570`
SSDEEP | `3072:w982i0/16CUicomL0yAktZpN/hLXVzYZAs0y0v:wviGR/c0yvZpuF2`

## Runtime Data

### Usage (stdout):
```Batchfile
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
```Batchfile
Error: Unknown command: --help

```

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
[C:\Program Files\Amazon Corretto\jdk1.8.0_265\bin\javafxpackager.exe](javafxpackager.exe-A28292598545FD5A54E62E9122293E38.md) | 94




MIT License. Copyright (c) 2020 Strontic.


