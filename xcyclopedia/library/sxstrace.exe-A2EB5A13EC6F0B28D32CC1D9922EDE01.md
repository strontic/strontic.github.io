
# sxstrace.exe 
* File Path: `C:\WINDOWS\SysWOW64\sxstrace.exe`
* Description: Sxs Tracing Tool
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `A2EB5A13EC6F0B28D32CC1D9922EDE01`
SHA1 | `EC8498416AA1E31490BE83C767A2D4A0144B8B58`
SHA256 | `1B43A4D409BC32F8F409279DE6EB4D86710AFD4A4D44536D92E0ED1A19C2CAEB`
SHA384 | `C1AF91B59FAAC5FA0208CEA582600888781E50C0C2629F6605E0691C8A9644C9C40B8BB2DEA59E2E18AF4F3CBD8BA2DA`
SHA415 | `50D4A93EE48FFA2D13FB0D0C62D0EF01FD468DCF5A1869AC4D96FF3624E7C8648A280450BDDA8C5F718DEC28CC81E2DD7D440D02AF41B5C103EB319D4ED2066B`
SSDEEP | `384:Co6d1wF4cr63iKO5gpyDah3xyfkYSWFD5XgZG00lmKGO27XKQw+MNdui7EwE2mS+:dISEiJ72hA0M00lJGPgK2mS/fCHz6CR`

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


