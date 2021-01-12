---
title: vsstrace.exe | vsstrace, Volume Shadow Copy Service (VSS) trace formatting tool
excerpt: What is vsstrace.exe?
---

# vsstrace.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\vsstrace.exe`
* Description: vsstrace, Volume Shadow Copy Service (VSS) trace formatting tool

## Hashes

Type | Hash
-- | --
MD5 | `8BDDEF365647B8C84651581AA066E2B6`
SHA1 | `E2438C6046AF6F38C8F5B646996FE4EC9D7EC5CB`
SHA256 | `72619984FCFE978792AC77A0A4DCA39109B55F2024B82CE672210958FABA5F3E`
SHA384 | `38BB000B06749FF5473EFD81A2885EF8A9FAC20BB0E6BC7F28EF1AC49461826C19C5DF1E4F0E0096921AF30D9B231285`
SHA512 | `9B60A2BB76E05D0703C5F305038C0C720721188F25DF7ACFC10A48F9205D0F68282AA0F83EA8F9B2966C57DC582F2A17AE9EBFCE303C9ADBD5801AA5002F6D73`
SSDEEP | `768:JhFAMDMnTP2DQjm9uBX3zs8OduA4/b/d:/FAFTnm9uBnzxeuAQb`
IMP | `C825F7F8F7A497A89F39CE337ADAF682`
PESHA1 | `609A6A428192C4C00A0E1EEE8D72FCBC8712B905`
PE256 | `B8CDFD007C23668C7EF6D4DE0D3EB8988FB058D0A8C268C20E0D7771FF39BB9F`

## Runtime Data

### Usage (stdout):
```cmhg

Usage: vsstrace [-help <modules | levels | all>] [-l <level>] [-f <flags>]
                [-+<module>] [-+ident] [-+pid <process id>] [-+tid <thread id>]
                [-etl <input ETL file>] [-o <output TXT File>]

  -f and -+<module>: both effect which modules will be traced;
    the order in which they are specified will effect which modules are masked;
    you can mask all (-f 0) and then add specific modules by name (+coord +xml)

  -tid/-pid: by default all process IDs (pid) and thread IDs (tid) are enabled;
    asterisk (*) can be used as a wildcard for "any" process or thread;
    the order in which they are provided will effect which traces are included;
    you can mask all (-pid *) and then enable specific ones (+pid 0xe8c)

  -o: provides alternate output stream. If you want to exclude console
    output and just write to a file, redirect output to a file using > sign


    Examples:
        vsstrace -f 0 +coord +swprv
        vsstrace -f 0x6
        vsstrace -GEN
        vsstrace -etl vss.etl -o vss.log
        vsstrace -f 0xffff -pid * +pid 0xe8c -tid * +tid 0x31a

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\MFC42u.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\vsstrace.exe |
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

* Original Filename: vsstrace.exe
* Product Name: vsstrace
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


