
# relog.exe 

* File Path: `C:\Windows\SysWOW64\relog.exe`
* Description: Performance Relogging Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `75065FC41CB8E041C58AA653F240ECB3`
SHA1 | `E91181ADAE598D4B4D7440CB246750ADBD19B387`
SHA256 | `CD0F9B1132FD4B0350C2D87626695C3A02391611376BF0077614250261239F68`
SHA384 | `6BBFC8B136B88A229BEEF5EF4AA033C9DDD2EF0EC78C3356174BAEB17E4160B041EF9ED70883B82ABA54E60428175787`
SHA415 | `8AFF7D610FDD44D3FDA750D753598A789F0A5C7EC79EDA2C1C0406C4C21C3B8A8CB5895327CAA3C7D42CBA98C99B8023DB5DB5BAF297EBF52A16A077BA96711E`
SSDEEP | `768:IQI7ps/0v8V2DKHywKHq/lbksOwNJTgD7o1Il+XTSuabw6f:IVg0k0DKH1/lbkHoIl+SuabBf`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft r Relog.exe (10.0.14393.0)

Relog creates new
performance logs from
data in existing
performance logs by
changing the sampling
rate and/or converting
the file format.
Supports all performance
log formats, including
Windows NT 4.0
compressed logs.

Usage:
C:\Windows\SysWOW64\relog.exe <filename [filename ...]> 
                                [options]

Parameters:
  <filename [filename ...]>     Performance file to relog.

Options:
  -?                            Displays context sensitive help.
  -a                            Append output to the existing binary file.
  -c <path [path ...]>          Counters to filter from the input log.
  -cf <filename>                File listing performance counters to filter
                                from the input log. Default is all counters
                                in the original log file.
  -f <CSV|TSV|BIN|SQL>          Output file format.
  -t <value>                    Only write every nth record into the output
                                file. Default is to write every record.
  -o                            Output file path or SQL database.
  -b <M/d/yyyy h:mm:ss[AM|PM]>  Begin time for the first record to write into
                                the output file.
  -e <M/d/yyyy h:mm:ss[AM|PM]>  End time for the last record to write into
                                the output file.
  -config <filename>            Settings file containing command options.
  -q                            List performance counters in the input file.
  -y                            Answer yes to all questions without prompting.

Examples:
  relog logfile.csv -c "\Processor(_Total)\% Processor Time" -o logfile.blg
  relog logfile.blg -cf counters.txt -f bin
  relog logfile.blg -f csv -o logfile.csv -t 2
  relog logfile.blg -q -o counters.txt

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Relog.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


