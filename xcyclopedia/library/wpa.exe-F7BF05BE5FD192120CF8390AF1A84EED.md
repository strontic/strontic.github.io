---
title: wpa.exe | Windows Performance Analyzer
excerpt: What is wpa.exe?
---

# wpa.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\wpa.exe`
* Description: Windows Performance Analyzer

## Hashes

Type | Hash
-- | --
MD5 | `F7BF05BE5FD192120CF8390AF1A84EED`
SHA1 | `C4E3C253312B66B4C83DD7C6EACFC16054E7651A`
SHA256 | `BFB94B0A159E36D4B1D2D93785FEAA15532E70B0A0C7B3CA43A709D6478C53B8`
SHA384 | `102F3AA413BE0861A74842B71609EBF6272DAD9F9B788FBB458031E260F0E94DC4AE1A16D37D09DADE752F78D5C2CEEE`
SHA512 | `F74C9E5BDC4F8914875F5C6687E68D099BCC80753FDBA710A887C1FD6140431988D7092B094FA69A25C1ECEFF334E499EC1A1A08AF3DB8FA22C22AFCBA1EA434`
SSDEEP | `1536:l6FmtMYB9LrMofxvKojFBPNMC4FKN/vwz7NZ3IaZBOn42Syu:mm7DfMof9ZPqlKN/vwvIabOn5Syu`
IMP | `n/a`
PESHA1 | `CCCAD25D45FEE73EDB3B91D04798DB25ABB9D460`
PE256 | `967292239A758731AE76937C8B88F7A681083B84BFF7305399558A65B2FDDD84`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft (R) Windows Performance Analyzer Version 10.0.19041.1 (WinBuild.160101.0800)
Copyright (C) 2021 Microsoft Corporation.  All rights reserved.

Usage:

    wpa.exe <<[-i] <file path>> [trace specific options]> ...  [general options]

                             -INPUT FILE OPTIONS-

    [-i] <input file path>    Specifies a file to open for input. This option
                              may appear multiple times. Input file path can
                              take one of the following forms:

            [-i] <ETL file> [trace specific options]

            [-i] wpa://<ETL file>[?profile=<profile path>]
                 profile path    The path to a *.wpaprofile file specifying the
                                 UI profile to apply.

            [-i] <assessment xml file>

            [-i] wpa://<assessment xml file>[?issue=<issue id>][?profile=<profile path>]
                 issue id        The issue ID
                 profile path    The path to a *.wpaprofile file specifying the
                                 UI profile to apply.

                           -TRACE SPECIFIC OPTIONS-

    -slot <m>         Assigns the trace to profile slot m, where m is an
                      integer.
    -range <T1 T2>    Zoom to time range [T1,T2]. If units are not specified,
                      then the units are assumed to be nanoseconds.
                          Example: -range 10s 20s
                          Example: -range 5 15

    -region <name>    Zoom to the time range defined by a region.
    -marks <name1> <name2>    Zoom to the time range which starts at the first
                              mark and ends at the second mark.

                       -UNIFIED TRACE SPECIFIC OPTIONS-

    -range <T1 T2>    Zoom to time range [T1,T2]. If units are not specified,
                      then the units are assumed to be nanoseconds.
                          Example: -range 10s 20s
                          Example: -range 5 15

    -region <name>    Zoom to the time range defined by a region.

                              -GENERAL OPTIONS-

    -profile <profile path>    Applies the specified *.wpaprofile profile in
                               the UI.
    -symbols          Enable symbol decoding as the trace is loaded.
    -symcacheonly     Symbol loading uses only existing symcache files.
    -cliprundown      Do not display the rundown region of the trace.
    -tti              Process the trace even in the presence of time inversions.

    -help, -h, /?     Displays this help screen.


```

### Usage (stderr):
```cmhg
Windows Performance Analyzer 10.0.19041.1 (WinBuild.160101.0800)
Command line: help
Creating WPA Files directory: C:\Users\user\Documents\WPA Files

```

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\ecosystem.core.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\ecosystem.windows.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\microsoft.assessments.administration.presentation.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\Microsoft.Diagnostics.Tracing.EventSource.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\microsoft.performance.base.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\microsoft.performance.core4.interop.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\microsoft.performance.data.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\microsoft.performance.dataengine.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\microsoft.performance.shell.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\microsoft.performance.ui.dataengine.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\microsoft.performance.ui.dll | File
(R-D)   C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\microsoft.performance.windows.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_64\mscorlib\v4.0_4.0.0.0__b77a5c561934e089\mscorlib.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_64\PresentationCore\v4.0_4.0.0.0__31bf3856ad364e35\PresentationCore.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\PresentationFramework.Aero2\v4.0_4.0.0.0__31bf3856ad364e35\PresentationFramework.Aero2.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\PresentationFramework\v4.0_4.0.0.0__31bf3856ad364e35\PresentationFramework.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Configuration\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Configuration.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Core\v4.0_4.0.0.0__b77a5c561934e089\System.Core.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Drawing\v4.0_4.0.0.0__b03f5f7f11d50a3a\System.Drawing.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Windows.Forms\v4.0_4.0.0.0__b77a5c561934e089\System.Windows.Forms.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Xaml\v4.0_4.0.0.0__b77a5c561934e089\System.Xaml.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System.Xml\v4.0_4.0.0.0__b77a5c561934e089\System.XML.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\System\v4.0_4.0.0.0__b77a5c561934e089\System.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\UIAutomationTypes\v4.0_4.0.0.0__31bf3856ad364e35\UIAutomationTypes.dll | File
(R-D)   C:\Windows\Microsoft.NET\assembly\GAC_MSIL\WindowsBase\v4.0_4.0.0.0__31bf3856ad364e35\WindowsBase.dll | File
(R-D)   C:\Windows\System32\en-US\winnlsres.dll.mui | File
(RW-)   C:\Users\user | File
\...\Cor_SxSPublic_IPCBlock | Section
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\Cor_Private_IPCBlock_v4_8180 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\UrlZonesSM_user | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme1383959086 | Section
\Windows\Theme2042523233 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\wpa.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wpa.exe
* Product Name: Microsoft Windows Performance Analyzer
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  2019 Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/bfb94b0a159e36d4b1d2d93785feaa15532e70b0a0c7b3ca43a709d6478c53b8/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\wpaexporter.exe](wpaexporter.exe-53DE1C9E113BEFB76CFBB87C39482701.md) | 44




MIT License. Copyright (c) 2020 Strontic.


