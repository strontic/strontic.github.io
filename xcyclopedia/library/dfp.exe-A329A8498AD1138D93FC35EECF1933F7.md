
# dfp.exe 

* File Path: `C:\WINDOWS\system32\dfp.exe`
* Description: Disk Footprint Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A329A8498AD1138D93FC35EECF1933F7`
SHA1 | `84E36303B684B0AFB366CAD99C0A46A58EFDD5AF`
SHA256 | `DBB8F982FC65125C1AD654CCD19948017918656916A8037952CEEECD261D6C92`
SHA384 | `17727672A8A525D2E4131D841E8D615F3BB9A5CDDC6BA91B24EB27FBAEE486182AF92FA0BA0E8872826301ADD53DB7C9`
SHA512 | `5B4B72FE04E68392F44145E0C8353FFA3266A137E92B58E6C8DD9495C3E9FD6718680B81B8430136A07CB7492818E40DDDB35F784101F2AD1801F143CE68247C`
SSDEEP | `768:bknZVecIF+2tSF0Klx/0aBSJLdosFAd+mZWj:QnKcIyz10JLPqUyW`

## Runtime Data

### Usage (stdout):
```Batchfile
Disk Footprint Tool

Reports on disk and drive usage.

dfp.exe [/log <log_path>] [/elapsed] [/drives] [/all] [/b]
        [/depth <n>] [/summary] [/xml <xml_path>] [/anonymize]
        [/snap <snap path>] [/prevsnap <previous snap path]
        [/study {changes}|{largest}|{growth}|{wellknown}|{apps}|{temp}]
        [/top <n>] 
        [<folder to scan>]

Options
 /log           Specifies the path to the log file.
 /elapsed       Display the time taken to execute.
 /drives        Report drive usage.
 /all /a        Report usage on files (defaults to folders).
 /b             Report friendly sizes.
 /depth /d      Report on folders to the specified depth (defaults to all).
 /summary /s    Summarize (equivalent to /depth 0).
 /xml           Output to XML (defaults to the console).
 /anonymize     Anonymize the paths and filenames in the output.
 /snap /sn      Create a snapshot file for later comparison.
 /prevsnap /psn Compare against a previous snapshot file.

Pre-defined Studies
 {changes}      Report on changes since last snapshot (used with prevsnap).
 {largest}      Report on largest (used with top and all).
 {growth}       Report on top growing (used with top and all).
 {wellknown}    Report on a well-known set of folders and files.
 {apps}         Report on app sizes.
 {temp}         Report on temp and log sizes.

General usage reporting
 dfp.exe /elapsed /drives
 dfp.exe /elapsed /drives /b /summary c:\
 dfp.exe /elapsed /drives /all /xml usage.xml c:\

Create a snapshot
 dfp.exe /drives /summary /snap snap0.bin c:\

Compare against a previous snapshot
 dfp.exe /drives /all /xml usage.xml /prevsnap snap0.bin c:\

Run a pre-defined study
 dfp.exe /drives /all /xml 1.xml /prevsnap snap0.bin /study {changes} c:\
 dfp.exe /all /xml 1.xml /prevsnap snap0.bin /top 25 /study {largest} c:\



```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\WINDOWS\system32\dfp.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: dfp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


