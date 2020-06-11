
# sxstrace.exe 

* File Path: `C:\Windows\SysWOW64\sxstrace.exe`
* Description: Sxs Tracing Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A204ED0CCEABC754FA7F7F5DFBB1F44D`
SHA1 | `FEE50588E8A59A270B31153B9D35A6249E344CCC`
SHA256 | `E79F546FE88776B5C16B5E8BAA9F578AAF1CADB393B2197FF2D6B23CDEC0CD45`
SHA384 | `B7DCA7D3C182735B21DAC3C198783E3F1C04B54A4EB9621B89E704A1C2451058D693A083ACF9341A27ECA90A25BF93DB`
SHA415 | `A688B6B695A6B4397ECED343E1131655F00B51B0BD6FAF8906DB5436E7367ABC1D5D3A5BCAD9B2C1E47E4BC3E8301BBB096E36835CE7600271072A5EF628E4D2`
SSDEEP | `384:16d1wFtDt/BYismm3yMr7gqzYD10n/K5re0a5fG64kSXH4YXip7rDZVQhfN0W2MF:1ISd/BYis3CMfxcW0a5+uNwfNIVw`

## Runtime Data

### Usage (stdout):
```Batchfile
WinSxs Tracing Utility.
Usage: SxsTrace [Options]
Options:
   Trace -logfile:FileName [-nostop]
       Enabling tracing for sxs.
       Tracing log is saved to FileName.
       If -nostop is specified, will not prompt to stop tracing.
   Parse -logfile:FileName -outfile:ParsedFile  [-filter:AppName]
       Translate the raw trace file into a human readable format and save the result to ParsedFile.
       Use -filter option to filter the output.
   Stoptrace
       Stop the trace if it is not stopped before.
Example:  SxsTrace Trace -logfile:SxsTrace.etl
          SxsTrace Parse -logfile:SxsTrace.etl -outfile:SxsTrace.txt

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

* Original Filename: sxstrace.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


