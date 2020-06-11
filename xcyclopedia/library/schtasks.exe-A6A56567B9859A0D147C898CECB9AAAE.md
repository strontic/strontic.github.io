
# schtasks.exe 

* File Path: `C:\WINDOWS\SysWOW64\schtasks.exe`
* Description: Task Scheduler Configuration Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A6A56567B9859A0D147C898CECB9AAAE`
SHA1 | `2C2A0F3CEEAA89FE97211615F413CC7C7CA21C7E`
SHA256 | `97CA3FAD547C4E0FE797DB77C414213BA981BC4C39C05AA3E9E42C2A5D494139`
SHA384 | `B47AB3DCA5CD03FC904DE9323CD162BC9F094C1114860B087EE2693AB48AE1F49C6029F113ECE4AAEE8A35D21DDCC4ED`
SHA415 | `7830AB1CD66DB250B10B6AAAFD9B6D47B0F80C86DA79FA0538D15E4CD5C411C75898B42BB0E5DAB8E588149C6A6F4841D5C73CBD9945B95B7AA42F985A42D15C`
SSDEEP | `3072:i+Ok+8vWkPs5jL8eMH/6wgPAFpVAbjcZyZLvbxslDU9EAatpE:iI+8XP6L/kgPopebjcZyljxsdU9Ez`

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


