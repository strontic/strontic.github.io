
# tracerpt.exe 

* File Path: `C:\Windows\system32\tracerpt.exe`
* Description: Event Trace Report Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1226243D657FBDA3A5C7E12F5761CB9E`
SHA1 | `638AA3D8ED9744D24BB23721F6593B57B768B7D7`
SHA256 | `BD8A93FE516F15B90D96A0B0F550D9A8422A9D72B44544D179F51BD077F935DD`
SHA384 | `E79B1D03A3821902CD32337C98F11AA5062E6B5F8C22EDB29AFCC163353CD4CA6EAA102CF55190804D5F4CC83ADD7BF5`
SHA512 | `DF70AC8B45D3FDAB6E33FE18426E55042367E26D6B6CB0763EB7D197EDEC42EB2C7CDB52CE65081FF3073BE3728CD72A6CC7CB97D1FEFF2176ADB590EEFB0D0D`
SSDEEP | `6144:nawo9w5b/XThU6gbXkWOvUjzI2O3PmEqwaP3nT5soA:qqp/XojrVhP3ntso`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft r TraceRpt.Exe (10.0.14393.0)

Usage:
  C:\Windows\system32\tracerpt.exe <[-l] <value [value [...]]>|-rt <session_name [session_name [...]]>> [options]

Options:
  -?                            Displays context sensitive help.
  -config <filename>            Settings file containing command options.
  -y                            Answer yes to all questions without prompting.
  -f <XML|HTML>                 Report format.
  -of <CSV|EVTX|XML>            Dump format, the default is XML.
  -en <ANSI|Unicode>            Output file encoding. Only allowed with CSV
                                output format.
  -df <filename>                Microsoft specific counting/reporting schema
                                file.
  -import <filename [filename [...]]> Event Schema import file.
  -int <filename>               Dump interpreted event structure into
                                specified file.
  -rts                          Report raw timestamp in event trace header. 
                                Can only be used with -o, not -report or
                                -summary.
  -tmf <filename>               Trace Message Format definition file
  -tp <value>                   TMF file search path.  Multiple paths can be
                                used, separated with ';'.
  -i <value>                    Specifies the provider image path.  The
                                matching PDB will be located in the Symbol
                                Server. Multiple paths can be used, separated
                                with ';'.
  -pdb <value>                  Specifies the symbol server path.  Multiple
                                paths can be used, separated with ';'.
  -gmt                          Convert WPP payload timestamps to GMT time
  -rl <value>                   System Report Level from 1 to 5, the default
                                value is 1.
  -summary [filename]           Summary report text file. Default is
                                summary.txt.
  -o [filename]                 Text output file. Default is dumpfile.xml.
  -report [filename]            Text output report file. Default is
                                workload.xml.
  -lr                           Less restrictive; use best effort for events
                                not matching event schema.
  -export [filename]            Event Schema export file. Default is
                                schema.man.
  [-l] <value [value [...]]>    Event Trace log file to process.
  -rt <session_name [session_name [...]]> Real-time Event Trace Session data
                                source.

Examples:
  tracerpt logfile1.etl logfile2.etl -o logdump.xml -of XML
  tracerpt logfile.etl -o logdmp.xml -of XML -lr -summary logdmp.txt -report logrpt.xml
  tracerpt logfile1.etl logfile2.etl -o -report
  tracerpt logfile.etl counterfile.blg -report logrpt.xml -df schema.xml
  tracerpt -rt "NT Kernel Logger" -o logfile.csv -of CSV


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TraceRpt.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



MIT License. Copyright (c) 2020 Strontic.


