---
title: wsutil.exe | Windows Web Services Tool
excerpt: What is wsutil.exe?
---

# wsutil.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\wsutil.exe`
* Description: Windows Web Services Tool

## Hashes

Type | Hash
-- | --
MD5 | `D6D86B6E0BB097235CDD7E64B7C7A72F`
SHA1 | `BA8A9EBF0C9610D044F2766064171017B634E7C4`
SHA256 | `9084EB5B12A6657C37E0A0C13F346293E35F36BC1639406F8BFDF28032A06280`
SHA384 | `C426B88A67BA15358E1FA72E9A00FE77C87F2DAD8215EE86AF6E8E03E9BB06AA56595F59A0636BCB64A3B8361886B3A9`
SHA512 | `072D962642FDE5097F2440F8D50D727CB6A15B0D7E9D9031FCE3DBBC65C0EB0547F47E59E5A90C4FB0A1CBDC1F0F3A19E6534A31B0D08755E5C9298598B9E04B`
SSDEEP | `3072:SLX7dISJAlmQwlR0nf2IgiDnK9Cpcztjb2K15Pt7Zy7/LO/YQrGNgtif5KAvT/p7:CCVcLVmhjn+3862QQnGOzvvMHFN`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `554AC0C84EB602BABFD41AD282683231D16257EC`
PE256 | `D310F804F5F83595B251FF73BDDEB48C7CB5049D67D0BB6FD7C3989F1737707B`

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
error WSUTIL0034  error WSUTIL0014  Failed to open specified input file 'help'. Error Message:
Value cannot be null.
Parameter name: format
   If you have passed in an url, Wsutil does not support downloading metadata from running services. Please check the documentation for detailed instructions on how to retrieve metadata from running webservices.
warning WSUTIL0075  Error during compilation. No file was generated.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\wsutil.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\wsutil.exe](wsutil.exe-174A4C5A388A2344A2A6A8DC7F57B99F.md) | 97




MIT License. Copyright (c) 2020 Strontic.


