---
title: tracefmt.exe | Format Message traces to text
excerpt: What is tracefmt.exe?
---

# tracefmt.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\tracefmt.exe`
* Description: Format Message traces to text

## Hashes

Type | Hash
-- | --
MD5 | `1C6138DA32D8934605648BAEAB531E7F`
SHA1 | `F0590E286F96B5B0896DC046D4B2E3AB28118A3A`
SHA256 | `879575B33789469A92D9A12301B9014CA3FA3152B9715CBBCFEA1AE2BF6D379D`
SHA384 | `25911758EE0E813453051C0CF06851B5651681D6E457A53C30723688DA398C0336D77DF0A195B06EB7FA066B941D9ADE`
SHA512 | `AE668FF2FE6A886E8F45F35D4703342D36A40217C378197D8AA697981B6D5390E17F55CF703B10016CEDCB9292576A48B2C42CC82A261AB288344B95E7A386EB`
SSDEEP | `12288:hSU/XE7VRTJEz/ZTWTkn0rBkr9RDrbL7rnD7SCyiSCyiSC+oQ:AU/XE7VRTi/ZTpn0rWRDrbL7rnD7SCyH`
IMP | `6EE784C71AEDA59373E4E5FA13E1CAEB`
PESHA1 | `137D2F1920CB6023BB4D04D6845D85D56388E87B`
PE256 | `FB864350E6B517BF7E3D117C2B8828CB3209D92F4A74E8A665BC3C5DFB701000`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\tracefmt.exe |
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

* Original Filename: TraceFmt.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


