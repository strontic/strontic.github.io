---
title: tracefmt.exe | Format Message traces to text
excerpt: What is tracefmt.exe?
---

# tracefmt.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\tracefmt.exe`
* Description: Format Message traces to text

## Hashes

Type | Hash
-- | --
MD5 | `A02AC40EA76F0B6AFE2C9FF49BB15692`
SHA1 | `8492C2DBB8DE5E2C9F41C80DBAB597FF4BABF5BA`
SHA256 | `6C84033B6A0DF638BB5B37A66B6B4597A140CB0778DD4781EEDD3752DE8E92AB`
SHA384 | `92AD6697AB354337A12369CE2093F93BCA6FCC13A8E4FE4E3DD1AA1CFFA4074796328A0F384B8ABBCA9A45DB6BDE1DD3`
SHA512 | `DAD103D76C9E7544D8F679634C2E636BB6B3C5CEC2C12D2632CDF7F95D8B6A06E90F1BE4D8C44A8A1DD4DC0F93513D8221E92CB91BAE53A94F9D4142F9676ABF`
SSDEEP | `6144:3acUUG1ZxzFFsPaA7VnbqJ0/HELlxjpOMUoikXVcA9gIQ/yDsGX03EcROpyVKQ3x:qr5JvsyA7VnOJ0/HELlxjpEz/2DOP`
IMP | `5983ECEE2610945955CBB48DB42E1DDD`
PESHA1 | `9F0DBAEB105B7C56C207BBD66B4EA8186BA774E3`
PE256 | `873AAD758144EC92EFDB35221DF79C8EC1A12395D9288C969E18368C8B044ED5`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft (R) TraceFmt.Exe (10.0.19041.1)
 Microsoft Corporation. All rights reserved.

Tracefmt formats the messages in trace logs (.etl files) and creates a text
file of the formatted trace messages. You can specify a TMF file with the
formatting instructions for WPP events, or you can specify an image file and
Tracefmt finds the private PDB file for that image and reads the formatting
instructions from the PDB file.

Usage:

tracefmt [<EtlFiles...>] | -rt [<SessionName>]

Parameters:

<EtlFiles...>     - Format a ETW trace file (.etl). Can specify multiple files
                    separated by spaces.
-rt <SessionName> - Format messages from the named real-time trace session.
                    Default session name="NT Kernel Logger".
-tmf <TMFFiles>   - Trace message format file. Default="Default.tmf".
-i <ImageFiles>   - Finds PDBs for the images and creates TMFs.
                    Separate images with ';'.
-r <SymbolPath>   - Path to private PDB symbol files. Default is
                    "%_NT_SYMBOL_PATH%" (if defined) or
                    srv*\\symbols\symbols otherwise.
-p <TmfPath>      - TMF file directory. Without -i, it's an existing directory.
                    With -i, it's the path for the TMF that tracefmt creates.
-pdb <PdbPath>    - Path to one more more PDB files. Multiple files should be
                    seperated by ';'.
-manpath <Path>   - Path to one or more manifest repository folders. Manifests
                    will be automatically loaded from these folders as needed.
                    Multiple folders should be separated by ';'. The files in
                    the folder must be named GUID.man, using the provider's
                    decode GUID with no '{', '}', or '-' characters. (Use the
                    traceman tool to import manifests into the repository.)
-man ManFile      - Path to an XML manifest from which to load decoding data
                    for manifest-based ETW events (TdhLoadManifest).
-bin DllFile      - Path to a DLL file from which to load decoding data for
                    manifest-based ETW events (TdhLoadManifestFromBinary).
-h | /?           - Displays help.

Options:

-o                - Output file name, e.g. "FormattedData.txt".
-csv              - Output in CSV format.
-csvheader        - Adds columns headings to CSV file.
-hires            - High resolution timestamp.
-utc | -gmt       - Do not convert UTC timestamps to local time.
                    (Affects timestamps in event header and event content.)
-timeZoneSuffix   - Include a suffix on timestamps with a known time zone.
-sortableTime     - Use "yyyy-mm-ddThh:mm:ss" format for time stamps.
-noFileTimeUtc    - Treat event content FILETIME values as having an unknown
                    time zone. (Default assumes FILETIME is always UTC.)
-display          - Print formatted traces messages to console and output file.
-displayonly      - Print formatted traces messages only to console (no output
                    file).
-nosummary        - Suppress summary file.
-summaryonly      - Suppress output file.
-noprefix         - Omit the trace message prefix.
-ods              - Send trace messages to the OutputDebugString.
-trace            - Print tracefmt actions to the console as they occur.
-v                - Verbose console output.
-cp <codepage>    - Generated text files should use the specified encoding.
                    Valid codepage names include "utf8", "utf16", "ansi".
                    Default is the current ANSI code page.
-skipNoFormat     - Filter out events without format strings.
-skipTmfWpp       - Filter out TMF-based WPP events.
-preferJson       - When possible, decode events as JSON.
                    TMF-based WPP will still decode as text.
-jsonMeta <flags> - Control which values to include in the JSON "meta" suffix.
                    Default is 0xff3f. Set to 0 to disable the "meta" suffix.
                    Values will often be omitted from suffix if zero or null.
                    Flags (in hex): provider=1, event=2, time=4, cpu=8,
                    pid=10, tid=20, id=40, version=80, channel=100, level=200,
                    opcode=400, task=800, keywords=1000, tags=2000,
                    activity=4000, relatedActivity=8000, ktime=10000,
                    utime=20000, ptime=40000, attribs=80000.

Default values:

        <EtlFile>      C:\Logfile.Etl
        <SessionName>  "NT Kernel Logger"
        <OutputFile>   FmtFile.txt (local directory)
        <Summary file> FmtFile.sum (local directory)
        <TMFFile>      default.tmf (local directory)
        <Prefix>       "[%9!d!]%8!04X!.%3!04X!::%4!s! [%1!s!]"
        <SymbolPath>   %_NT_SYMBOL_PATH% or srv*\\symbols\symbols

Change Prefix by setting the TRACE_FORMAT_PREFIX environment variable.

If neither -tmf nor -p are specified, tracefmt uses the value of the
%TRACE_FORMAT_SEARCH_PATH% environment variable.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\tracefmt.exe |
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

* Original Filename: TraceFmt.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\tracefmt.exe](tracefmt.exe-1A132D3C750C4F6E6A49DD0B15037A01.md) | 52
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\winext\wdfkd.dll](wdfkd.dll-22783C7922A5F8678B086785C60E99A1.md) | 36
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\winxp\wmitrace.dll](wmitrace.dll-6C8CAEA4F842FCA3FFE733AB4D9C82F5.md) | 33
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\winext\rcdrkd.dll](rcdrkd.dll-17D72886BD70CE923FAB6A6427360028.md) | 52
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\winext\wdfkd.dll](wdfkd.dll-5602BDB2CC9426DBE930E593E65BFA78.md) | 30
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\winxp\wmitrace.dll](wmitrace.dll-2B386CB3C2E87D0AE428CDA7EB809640.md) | 47
[C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\perf_wpp.dll](perf_wpp.dll-5570A1894C91C49766FFF4CFDB1BE221.md) | 49
[C:\Windows\system32\nltest.exe](nltest.exe-0C96FBA0F1ABEEF164B077D34F5B6F6A.md) | 36
[C:\Windows\system32\nltest.exe](nltest.exe-1CC927B2EC04AAD119D2C6BD2194DA1F.md) | 35
[C:\Windows\system32\nltest.exe](nltest.exe-396EC29E0B1F77824E6479D8D810D315.md) | 35
[C:\Windows\system32\nshwfp.dll](nshwfp.dll-366C76832A6A12850407BF16F2D22441.md) | 33




MIT License. Copyright (c) 2020-2021 Strontic.


