
# sxstrace.exe 
* File Path: `C:\WINDOWS\system32\sxstrace.exe`
* Description: Sxs Tracing Tool
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `4EBE754606916994F8190FE32FF9B86F`
SHA1 | `BD0A9E0390D121B4ABDB1A6720A23BFAEA3F700F`
SHA256 | `3DF15EF34799831E1C9B1989A1CAB7B055532009E32B804E75020E23ABE90B15`
SHA384 | `2B2F80DD343E472C0E08FCE40838ED75E27ACB9E4E48A1BFED23B40790E76CA1BC42FDDCD760831FFB01AE67F7628630`
SHA415 | `C89B45F2CD5DFC2BE893AE6F15C024C385377D6B9BCC9B32F0A5A25DEB12591E02A792F4A39BCC262BFE45307F31A804077C3A1F322308A28148B3980C9AAC8F`
SSDEEP | `768:Ps6faWH+VHbh669Ti6F/UCASE2Br8685pMSwikE7IC+rgEyoK08zy:W669Ti6FniG4nwZY9YgE7P4y`

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
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sxstrace.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


