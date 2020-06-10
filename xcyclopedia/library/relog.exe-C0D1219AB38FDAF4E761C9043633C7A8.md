
# relog.exe 
* File Path: `C:\WINDOWS\system32\relog.exe`
* Description: Performance Relogging Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `C0D1219AB38FDAF4E761C9043633C7A8`
SHA1 | `B5D0CEB42EF511C4CE0732A83937689AEEF56F93`
SHA256 | `1429C59F52FB140C21FD536FB47E85262F29F789A160659F7467EA32F66225ED`
SHA384 | `B4CB434A54B35035C1A4A5F46DC1571E2FA4C20F112C9A2D25AB0EBF481FFCBA78225251369899E27F4C4E414BCC5402`
SHA415 | `3384DBE3D35EB7306CF7EB0BEC13628E2C5DB277F86CD7FD9C5FE2F90D77E6D4719AC58371D85C4C58D80228107A4E1C78F8982DB93978ECD43A54908B9CE4EA`
SSDEEP | `768:jS+J9nlfS+UpKYp86NByg+BOU3S+QLur+h4sLRjs+JT95Uk8dQMV4sc8222Mp/qz:G+axNi3Dsc1sdjswjdGTV4scL2R/qR1`

## Runtime Data
### Usage (stdout):
```Batchfile

Microsoft r Relog.exe (10.0.18362.1)

Relog creates new performance logs from data in existing performance logs by
changing the sampling rate and/or converting the file format. Supports all
performance log formats, including Windows NT 4.0 compressed logs.

Usage:
C:\WINDOWS\system32\relog.exe <filename [filename ...]> 
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

* Original Filename: Relog.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


