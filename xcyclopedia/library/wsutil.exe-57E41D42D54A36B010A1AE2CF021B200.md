---
title: wsutil.exe | Windows Web Services Tool
excerpt: What is wsutil.exe?
---

# wsutil.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\wsutil.exe`
* Description: Windows Web Services Tool

## Hashes

Type | Hash
-- | --
MD5 | `57E41D42D54A36B010A1AE2CF021B200`
SHA1 | `47EACC7C662466396E01B91B11CAA226CB9CEC40`
SHA256 | `80D68454B2997358EA5924404B7D41E9A7EAD0242311DB9069163FBCF242A8E8`
SHA384 | `EC9474C9983DE064A4F08F3423C16AA133249F8A776969B53A10742857FB03A891875511857B02A86DEC566D69A2DD28`
SHA512 | `30DE259819DE99ADD6C6A72D811398C0978BE3CCAF674E8A1BDC9A39F27777EC77BBC64322802CA8CE3A52BCBD9E4D93CB799C75CE999F2B0C9557D27AC72375`
SSDEEP | `3072:NCSc98vbXX6mwkYQM78cVf/czVgr0g8AStl+lJ2FRQgSboDzETZJlnoO8VQ9vCUe:3vukYQ5cVfU+ezDAqOzPvMnFfLPL`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `A61237BEF3B56BA856EC9C887827A51FA5831716`
PE256 | `7EEF628F207BE67A7158A8A8217EDA53A49130DA7200FF7E0C5E30B210DA4664`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Windows Web Services Tool, version 1.0098 
Copyright (c) Microsoft Corporation.  All rights reserved.

Wsutil Compiler Options

Syntax: wsutil.exe [@resfile] [metadataDocument]* [option]*

---   RESPONSE FILE  ---
@resfile                Specify the response file that contains all 
                        the arguments.

---   metadataDocument  ---
fileName                Specify input fileName. Metadata document type is 
                        determined according to the file content. 
                        Standard command-line wildcards can be used.
/wsdl:fileName[:url]    Specify input file as WSDL file; optional url specify
                        the location that the metadata was retrieved from.
/xsd:fileName           Specify input file as XSD Schema file
/wsp:fileName[:url]     Specify input file as policy file; optional url specify
                        the location that the metadata was retrieved from.


---  output options   ---
/out:directory          Specify output directory for generated file
/noclient               Do not generate client stub
/noservice              Do not generate service stub
/nopolicy               Do not generate policy related metadata

--- misc options  ---
/?, /help               Display this message.
/W:{0|1|2|3|4}          Specify warning level 0-4 (default = 1)
/fullName               Prepend fileName to generated identifiers.
/prefix:name            Prepend specified name to generated identifiers.
/nologo                 Do not generate compiler specific information on 
                        console output
/nostamp                Do not generate compiler specific information on 
                        generated file
/nosummary              Do not produce summary after processing. When combined
                        with /nologo, the tool is silent on success.
/string:WS_STRING|WCHAR*    Specify the string type. By default WCHAR* 
                            string is used.
/ignoreTrailingContent  Specify the trailing content for generated 
                        structures to be ignored during deserialization.
/ignoreUnhandledAttributes      Specify the unhandled attributes for generated
                        structures to be ignored during deserialization.



```

### Usage (stderr):
```cmhg
error WSUTIL0013  Failed to open specified input file 'help'. Error Message:
Could not find file 'C:\Users\user\help'.
warning WSUTIL0075  Error during compilation. No file was generated.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\wsutil.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Wsutil.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


