---
title: inkscape.exe | Inkscape vector graphics editor
---

# inkscape.exe 

* File Path: `C:\Program Files\Inkscape\bin\inkscape.exe`
* Description: Inkscape vector graphics editor
* Comments: Published under the GNU GPL


## Hashes

Type | Hash
-- | --
MD5 | `507868AD76E292FD82203D0BE512965C`
SHA1 | `CD20598A6BF95226447CA9DF40AED8CF0DBDD8F3`
SHA256 | `F4ED37B72FDB433C13D092CCD28E3010EED5B87CD1BE5CEE764EFA1FAAEF1E9E`
SHA384 | `39B005E31948EF3B27035248A4983E8DCB615781E6DC72C4159C1A63663D11B08507488E23739121E333F69B9AE9E30A`
SHA512 | `B0832796F7E059FCA01C8A3AEDA4C48D8E598AEA0EBA6C51FEDD28170D7D060E267E7E4942155129E905D5F28CDB2A758662983437CF294B83E6A3888E385B44`
SSDEEP | `1536:rJj/GWUspbjg1b1bnsn4fH/4xGA6uaGSXS1DNBhzgVDkuHAuKu9uSgztFZze:NjTbg1RhoAuaM1DfwkDuOZFZy`

## Runtime Data

### Usage (stdout):
```Batchfile
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
```Batchfile
Missing argument for -h

```

### Child Processes:
gdbus.exe

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
* File Version: 1.0
* Product Version: 1.0
* Language: English (United States)
* Legal Copyright:  2020 Inkscape project

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Inkscape\bin\inkview.exe](inkview.exe-17A62568710BE883F2B419098E3E2B20.md) | 93




MIT License. Copyright (c) 2020 Strontic.


