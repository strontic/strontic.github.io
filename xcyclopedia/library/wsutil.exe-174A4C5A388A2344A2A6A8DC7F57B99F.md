---
title: wsutil.exe | Windows Web Services Tool
excerpt: What is wsutil.exe?
---

# wsutil.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\wsutil.exe`
* Description: Windows Web Services Tool

## Hashes

Type | Hash
-- | --
MD5 | `174A4C5A388A2344A2A6A8DC7F57B99F`
SHA1 | `BC88E50EC7B45A146ED73D4474C63D7D425CCA6E`
SHA256 | `F905D7FEE591625A24D6391C84A734BE0B119D43C01F05988A20C3E310668037`
SHA384 | `227F85FC70C782A632EFDACCD3E9A6FA9BC7E3D53DBBE3FEB9A8685FF65A9ED086A47CA5A0FEF67408ADE15B7A192FF0`
SHA512 | `376ABC1A6197F880DA31112C8F3C929DFD09EAF497484CEB6A14A54CFD064BCDD3159B3765A0EF0A1E2CE29AF669E82CCCBF0B17EFB0F27A4EE2DC370C70DD6A`
SSDEEP | `3072:7LX7dISJAlmQwlR0nf2IgiDnK9Cpcztjb2K15Pt7Zy7/LO/YQrGNgtif5KAvT/pn:lCVcLVmhjn+382ElnLOzvvMHFz`
IMP | `n/a`
PESHA1 | `35E106CCD8F4D3B8E0B2C8A1AE5347CF5B04270C`
PE256 | `E508144F9CCB6E1C5D46BF87C73113B61435DFC8769962D2E6D3BE153B45C682`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\wsutil.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\wsutil.exe](wsutil.exe-D6D86B6E0BB097235CDD7E64B7C7A72F.md) | 97




MIT License. Copyright (c) 2020 Strontic.


