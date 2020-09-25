---
title: inkscape.exe | Inkscape vector graphics editor
excerpt: What is inkscape.exe?
---

# inkscape.exe 

* File Path: `C:\Program Files\Inkscape\bin\inkscape.exe`
* Description: Inkscape vector graphics editor
* Comments: Published under the GNU GPL


## Hashes

Type | Hash
-- | --
MD5 | `F30F53F65E0E2C4835820A406761EF42`
SHA1 | `826FAE688FA97768A12D5E081FB96C0635BC90BC`
SHA256 | `30017F1397213C148E2BAEE02FD91426A34A4D3D85269CB3FA413924BD91582B`
SHA384 | `3FDB666256B23582102150EB203D34843DC8770480839809BBA2BA422636DF3DC07BD19B7CC4B4D987A110C6FE98BC64`
SHA512 | `0A49D26A1B1841F03EBF42331EA796247726EE1F203C2A947CC8ED467169D4483F11FB0FCF07AFC386CFC435F64C0853666C3C69F49562C0F09981BC2C808EB4`
SSDEEP | `1536:L6B9JShoUFiWUspbjg1b1bnsn4fH/4xGA6uaGSXS1DNBhzgVDkuHAuKu9uSgztF3:Lko93bg1RhoAuaM1DfwkDuOZFZ9`
IMP | `71D1CFEDDB86B72ED9979EA52C80F861`
PESHA1 | `861863A7F0CEB14946BB8F3D89B99A001CA69A23`
PE256 | `A08D509B07FF927566E947E74001E9D924147CA4362C614E3BF5022F9E94E71D`

## Runtime Data

### Usage (stdout):
```cmhg
Usage:
  org.inkscape.Inkscape [OPTION] file1 [file2 [fileN]]

Process (or open) one or more files.

Help Options:
  -?, --help                                 Show help options
  --help-all                                 Show all help options
  --help-gapplication                        Show GApplication options
  --help-gtk                                 Show GTK+ Options

Application Options:
  -V, --version                              Print Inkscape version
  --system-data-directory                    Print system data directory
  --user-data-directory                      Print user data directory
  --  
File import:                        
  -p, --pipe                                 Read input file from standard input (stdin)
  --pdf-page=PAGE                            PDF page number to import
  --pdf-poppler                              Use poppler when importing via commandline
  --convert-dpi-method=[...]                 Method used to convert pre-0.92 document dpi, if needed: [none|scale-viewbox|scale-document]
  --no-convert-text-baseline-spacing         Do not fix pre-0.92 document's text baseline spacing on opening
  --  
File export:                        
  -o, --export-filename=EXPORT-FILENAME      Output file name (file type is guessed from extension)
  --export-overwrite                         Overwrite input file
  --export-type=[...]                        File type(s) to export: [svg,png,ps,eps,pdf,emf,wmf,xaml]
  --  
Export geometry:                    
  -C, --export-area-page                     Area to export is page
  -D, --export-area-drawing                  Area to export is whole drawing (ignoring page size)
  -a, --export-area=x0:y0:x1:y1              Area to export in SVG user units
  --export-area-snap                         Snap the bitmap export area outwards to the nearest integer values
  -d, --export-dpi=DPI                       Resolution for bitmaps and rasterized filters; default is 96
  -w, --export-width=WIDTH                   Bitmap width in pixels (overrides --export-dpi)
  -h, --export-height=HEIGHT                 Bitmap height in pixels (overrides --export-dpi)
  --export-margin=MARGIN                     Margin around export area: units of page size for SVG, mm for PS/EPS/PDF
  --  
Export options:                     
  -i, --export-id=OBJECT-ID[;OBJECT-ID]*     ID(s) of object(s) to export
  -j, --export-id-only                       Hide all objects except object with ID selected by export-id
  -l, --export-plain-svg                     Remove Inkscape-specific SVG attributes/properties
  --export-ps-level=PS-Level                 Postscript level (2 or 3); default is 3
  --export-pdf-version=PDF-VERSION           PDF version (1.4 or 1.5)
  -T, --export-text-to-path                  Convert text to paths (PS/EPS/PDF/SVG)
  --export-latex                             Export text separately to LaTeX file (PS/EPS/PDF)
  --export-ignore-filters                    Render objects without filters instead of rasterizing (PS/EPS/PDF)
  -t, --export-use-hints                     Use stored filename and DPI hints when exporting object selected by --export-id
  -b, --export-background=COLOR              Background color for exported bitmaps (any SVG color string)
  -y, --export-background-opacity=VALUE      Background opacity for exported bitmaps (0.0 to 1.0, or 1 to 255)
  --  
Query object/document geometry:     
  -I, --query-id=OBJECT-ID[,OBJECT-ID]*      ID(s) of object(s) to be queried
  -S, --query-all                            Print bounding boxes of all objects
  -X, --query-x                              X coordinate of drawing or object (if specified by --query-id)
  -Y, --query-y                              Y coordinate of drawing or object (if specified by --query-id)
  -W, --query-width                          Width of drawing or object (if specified by --query-id)
  -H, --query-height                         Height of drawing or object (if specified by --query-id)
  --  
Advanced file processing:           
  --vacuum-defs                              Remove unused definitions from the <defs> section(s) of document
  --select=OBJECT-ID[,OBJECT-ID]*            Select objects: comma-separated list of IDs
  --                                       
  --actions=ACTION(:ARG)[;ACTION(:ARG)]*     List of actions (with optional arguments) to execute
  --action-list                              List all available actions
  --                                       
  --verb=VERB[;VERB]*                        List of verbs to execute
  --verb-list                                List all available verbs
  --  
Interface:                          
  -g, --with-gui                             With graphical user interface (required by some actions/verbs)
  --batch-process                            Close GUI after executing all actions/verbs
  --                                       
  --shell                                    Start Inkscape in interactive shell mode


Examples:
  Export input SVG (in.svg) to PDF (out.pdf) format:
	inkscape --export-filename=out.pdf in.svg
  Export input files (in1.svg, in2.svg) to PNG format keeping original name (in1.png, in2.png):
	inkscape --export-type=png in1.svg in2.svg
  See 'man inkscape' and http://wiki.inkscape.org/wiki/index.php/Using_the_Command_Line for more details.

```

### Usage (stderr):
```cmhg
Missing argument for -h

```

### Child Processes:
gdbus.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.508_none_faefa4f37613d18e | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme2547664911 | Section
\Windows\Theme3854699184 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\Inkscape\bin\inkscape.exe |
C:\Program Files\Inkscape\bin\libaspell-15.dll |
C:\Program Files\Inkscape\bin\libatkmm-1.6-1.dll |
C:\Program Files\Inkscape\bin\libcairo-2.dll |
C:\Program Files\Inkscape\bin\libcairomm-1.0-1.dll |
C:\Program Files\Inkscape\bin\libcdr-0.1.dll |
C:\Program Files\Inkscape\bin\libdouble-conversion.dll |
C:\Program Files\Inkscape\bin\libffi-7.dll |
C:\Program Files\Inkscape\bin\libfontconfig-1.dll |
C:\Program Files\Inkscape\bin\libfreetype-6.dll |
C:\Program Files\Inkscape\bin\libgc-1.dll |
C:\Program Files\Inkscape\bin\libgcc_s_seh-1.dll |
C:\Program Files\Inkscape\bin\libgdk_pixbuf-2.0-0.dll |
C:\Program Files\Inkscape\bin\libgdk-3-0.dll |
C:\Program Files\Inkscape\bin\libgdkmm-3.0-1.dll |
C:\Program Files\Inkscape\bin\libgdl-3-5.dll |
C:\Program Files\Inkscape\bin\libgiomm-2.4-1.dll |
C:\Program Files\Inkscape\bin\libglib-2.0-0.dll |
C:\Program Files\Inkscape\bin\libglibmm-2.4-1.dll |
C:\Program Files\Inkscape\bin\libgmodule-2.0-0.dll |
C:\Program Files\Inkscape\bin\libgobject-2.0-0.dll |
C:\Program Files\Inkscape\bin\libgomp-1.dll |
C:\Program Files\Inkscape\bin\libgraphite2.dll |
C:\Program Files\Inkscape\bin\libgtk-3-0.dll |
C:\Program Files\Inkscape\bin\libgtkmm-3.0-1.dll |
C:\Program Files\Inkscape\bin\libgtkspell3-3-0.dll |
C:\Program Files\Inkscape\bin\libharfbuzz-0.dll |
C:\Program Files\Inkscape\bin\libiconv-2.dll |
C:\Program Files\Inkscape\bin\libinkscape_base.dll |
C:\Program Files\Inkscape\bin\libintl-8.dll |
C:\Program Files\Inkscape\bin\libpangomm-1.4-1.dll |
C:\Program Files\Inkscape\bin\libpcre-1.dll |
C:\Program Files\Inkscape\bin\libsigc-2.0-0.dll |
C:\Program Files\Inkscape\bin\libssp-0.dll |
C:\Program Files\Inkscape\bin\libstdc++-6.dll |
C:\Program Files\Inkscape\bin\libwinpthread-1.dll |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\comdlg32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\mscms.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\SETUPAPI.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\SYSTEM32\USP10.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\WS2_32.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21\COMCTL32.dll |


## Signature

* Status: The file C:\Program Files\Inkscape\bin\inkscape.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: inkscape.exe
* Product Name: Inkscape
* Company Name: Inkscape project
* File Version: 1.0.1
* Product Version: 1.0.1
* Language: English (United States)
* Legal Copyright:  2020 Inkscape project
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/30017f1397213c148e2baee02fd91426a34a4d3d85269cb3fa413924bd91582b/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\Inkscape\bin\inkscape.exe](inkscape.exe-507868AD76E292FD82203D0BE512965C.md) | 86
[C:\program files\Inkscape\bin\inkview.exe](inkview.exe-17A62568710BE883F2B419098E3E2B20.md) | 86
[C:\Program Files\Inkscape\bin\inkview.exe](inkview.exe-ED010CDD22BE2438CAE317B1DD012314.md) | 85




MIT License. Copyright (c) 2020 Strontic.


