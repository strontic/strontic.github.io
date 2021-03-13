---
title: vsstrace.exe | vsstrace, Volume Shadow Copy Service (VSS) trace formatting tool
excerpt: What is vsstrace.exe?
---

# vsstrace.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\vsstrace.exe`
* Description: vsstrace, Volume Shadow Copy Service (VSS) trace formatting tool

## Hashes

Type | Hash
-- | --
MD5 | `0692B32463768C1E240027A828AB3851`
SHA1 | `0ECB82690472BBDF9A27DBFBABD1FA7D8ED47168`
SHA256 | `39DE95ABC33F911FFE40B0804EE68ABBCD9D3B6C4C2A25005AD7ADE59B5C5BA9`
SHA384 | `97E4834CF33A58B4808F6E4CD8A2B4B8C8DF70BBF25C519849C35BDC189711D45F4E959883C53CED16BBE2439C058FF5`
SHA512 | `3C6F233A686E37D4912DACD9802FAC5B77D368E3C27B531F30021F5E1EF5D4C39EAB24FFFCF246E49A219E951499915A72F3FFB8B93401F047A0FAA8FC2E5128`
SSDEEP | `768:+TGyLZpAdkSttfK+KbRxwyaOi3GoURasUD9km3n/onhFAq5ncB4WcYWNx:MLvAdk0KbRxwy2+asVGnCFACcGgq`
IMP | `B353E2B19ADEFC9DA0B20DF10DA63461`
PESHA1 | `B94665D4ED8D7335657E7FE66C7A3825C9101CD1`
PE256 | `FD641DAF665DE0C1BCEA3AE68D84FF8C89162BF7ABC150443744C8CC81DCE286`

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
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\vsstrace.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


