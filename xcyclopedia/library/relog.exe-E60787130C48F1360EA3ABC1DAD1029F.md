
# relog.exe 

* File Path: `C:\Windows\system32\relog.exe`
* Description: Performance Relogging Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E60787130C48F1360EA3ABC1DAD1029F`
SHA1 | `AFCFF85A1610F4569C3442FAA90363F1396F08A6`
SHA256 | `EF2FB9EAEBDFA842E076C8C2ED9A0C8F9616FB81F654B1DF21575951D3D728E4`
SHA384 | `7A01F59DF8E0A87B235A9194CD28DFD6C15595B24EA57BB1882CA5107F6E019D388C00439DEF7FBB66DCA5B07396E0CE`
SHA415 | `5810407415B25F09F5CB34BC9AACF100EE2D67C2F975A35F0EC30C475A0C244F33089D6F019A65374DB1E004F3DA710EF00B3E68A1245703B8F717A20FD45AC5`
SSDEEP | `768:FJo5y/Aje2Jua024aH94TTSl3MEU4y/AHtcNdmhuP+uiHIl+XTEk6z:FeHZH9IWlccgAHt4dm42uMIl+Ek6z`

## Runtime Data

### Usage (stdout):
```Batchfile

Microsoft r Relog.exe (10.0.14393.0)

Relog creates new performance logs from data in existing performance logs by
changing the sampling rate and/or converting the file format. Supports all
performance log formats, including Windows NT 4.0 compressed logs.

Usage:
C:\Windows\system32\relog.exe <filename [filename ...]> 
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


