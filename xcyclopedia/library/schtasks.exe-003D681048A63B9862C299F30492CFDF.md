
# schtasks.exe 

* File Path: `C:\WINDOWS\system32\schtasks.exe`
* Description: Task Scheduler Configuration Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `003D681048A63B9862C299F30492CFDF`
SHA1 | `2CA6101525953606730412294C36D415FEE06B18`
SHA256 | `D3222E48A036C6C730BB4E67B4C02E83C87860701975F408E5BF708B4B9CDBF4`
SHA384 | `90E71BB627D330593AF6B655CF3B913360B69F34ACA94135F02BBBF78A5C66360537C89649C8AB40452EB39B2DD34E79`
SHA415 | `D7CE887B3E447512286E469DFFF3D66E6AA0EFD6EDB1B0D8543E01F401103EC2E42495CFFA73F78618E1B31935D8A020AB2C51530457CBC22C7DE31EF96A6577`
SSDEEP | `3072:0mger10gqFAuru5LiElSZMuNuFfllBESl3wU+R2O2R3u+A6Rb5nV+7EAatmXs:VUgq2yIL1lSZAFySlLs2OFkV+7Ez/`

## Runtime Data

### Usage (stdout):
```Batchfile

SCHTASKS /parameter [arguments]

Description:
    Enables an administrator to create, delete, query, change, run and
    end scheduled tasks on a local or remote system. 

Parameter List:
    /Create         Creates a new scheduled task.

    /Delete         Deletes the scheduled task(s).

    /Query          Displays all scheduled tasks.

    /Change         Changes the properties of scheduled task.

    /Run            Runs the scheduled task on demand.

    /End            Stops the currently running scheduled task.

    /ShowSid        Shows the security identifier corresponding to a scheduled task name.

    /?              Displays this help message.

Examples:
    SCHTASKS 
    SCHTASKS /?
    SCHTASKS /Run /?
    SCHTASKS /End /?
    SCHTASKS /Create /?
    SCHTASKS /Delete /?
    SCHTASKS /Query  /?
    SCHTASKS /Change /?
    SCHTASKS /ShowSid /?

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "SCHTASKS /QUERY /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: schtasks.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


