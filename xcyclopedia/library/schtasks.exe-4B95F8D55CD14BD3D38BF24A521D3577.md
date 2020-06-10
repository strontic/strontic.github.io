
# schtasks.exe 
* File Path: `C:\Windows\SysWOW64\schtasks.exe`
* Description: Task Scheduler Configuration Tool
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `4B95F8D55CD14BD3D38BF24A521D3577`
SHA1 | `37F91D720D8BD11AE48E016B65BC6027D3BD8445`
SHA256 | `CAA9AF113C1682AD8A6644342B37D96AA544F1AF712D446BD29EF9F12BA30CA0`
SHA384 | `BE06BF0A20C7A3F2862F98A6AD14DB43CB4BC578EDF3337C5BBDE7A7E8EE18BC1756AA49EDD21EBFB0ACF994A3F66A91`
SHA415 | `BFFCBAA88464DE335CC268D2AF9D8491823CCC816BF1EAD150AAAB699FF6D20989B5278256CC59DA1E20A3F48491EA8DB8B9899ED4EEE9E8A24E2962EA00FB33`
SSDEEP | `3072:5WC2/ZPT19uOFQpUGgFdXMMkdtD7P1GZazA:APdTqOFQpUHp257P1G`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sctasks.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


