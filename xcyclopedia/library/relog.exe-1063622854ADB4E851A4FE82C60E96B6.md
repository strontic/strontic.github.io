
# relog.exe 
* File Path: `C:\WINDOWS\SysWOW64\relog.exe`
* Description: Performance Relogging Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `1063622854ADB4E851A4FE82C60E96B6`
SHA1 | `CDC5C83FACBFA3C35BBF42D559F0BC2252F3892F`
SHA256 | `0D716C8C79C9C304FD15E2DDAA4BE994DBA8DA7C758B02B590694646C257FDB5`
SHA384 | `367CA434C69575ED8BEFB0830FAFB9DE6439AFB63891BBC68B91C64AD5E10D806770F6B164A8EED1D17F2876BFEDE0F1`
SHA415 | `615D8005E617F57062CC469C554E16E5A766934E0424B268F847301BA0521ED6CC349276EEDBB782DD023B38EEF4CFE14186097EA5527F2A77BC90E95AA0AC3F`
SSDEEP | `768:07qzvS3oAfuVH/O8QowwPYMWajxAN2QNTbXuvnrtfvbk22MNiQ9c:07qzvSY1B5YMWSifuvnZk2liQ9c`

## Runtime Data
### Usage (stdout):
```Batchfile

Microsoft r Relog.exe (10.0.18362.1)

Relog creates new performance logs from data in existing performance logs by
changing the sampling rate and/or converting the file format. Supports all
performance log formats, including Windows NT 4.0 compressed logs.

Usage:
C:\WINDOWS\SysWOW64\relog.exe <filename [filename ...]> 
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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Relog.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


