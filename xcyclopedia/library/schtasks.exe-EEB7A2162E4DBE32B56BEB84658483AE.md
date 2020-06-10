
# schtasks.exe 
* File Path: `C:\Windows\system32\schtasks.exe`
* Description: Task Scheduler Configuration Tool
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `EEB7A2162E4DBE32B56BEB84658483AE`
SHA1 | `58ECB25B08A24660E71CE411C2C1D8709572ABEC`
SHA256 | `A9A4FD9C1BB7C5CF8F77F761CAE60F4AC4AFB8DAEEBB46B3AD6983D5E599CDC1`
SHA384 | `635D3E950548BD61C8918B122CC1D2E30333FEA38FE82C12F4CAA1CA0F91901C8FC004B83C83480EA00706217D66CAC9`
SHA415 | `2901FF71D1F027DF4150C81B93F48E2BD3FA1F33FBC24977826945FBF570C580B6F338CC0751C3E5DF62D76789BB499847366E1F74DD15A0F97E225B80593E42`
SSDEEP | `3072:ZLEWdGDTw9q+nboxZiF9l2qeqg266jY1wPcspJNmtwHbVvUB9QMEZaS:lpUw91cZgf2VqgKPbpJNmtGUjQME`

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


