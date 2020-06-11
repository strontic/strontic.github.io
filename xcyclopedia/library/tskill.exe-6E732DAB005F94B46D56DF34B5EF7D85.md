
# tskill.exe 

* File Path: `C:\WINDOWS\system32\tskill.exe`
* Description: Remote Desktop Services End Process Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6E732DAB005F94B46D56DF34B5EF7D85`
SHA1 | `B86C1D15DD8812DAFE45584289D44DFDF8168CD8`
SHA256 | `1B92303B2B2D13F02F45F7164BC0B73EE39FB6CEE6C61296904BD7F7C87E4685`
SHA384 | `9A8FD7AB844CCC8895149107718FA8242346CE16D240292C60E53A1DA026D25338AA241CC3ED25A19CC19854F69C4601`
SHA415 | `DD096D8B69749202F1CCB5145D346BDC27A8FBC8D48B5C1281404BE5CB59F563AE7EDF21350265CE2571383E10BC674F883FE414099CA71C1D13A581FDB8880E`
SSDEEP | `384:deUPfdE901EeMrjS/JI8lEgz5ZhJK8bg1Kl4uwkU2i4xxC5xCInHWqSUZpyCyW42:deUoyQrjSBI8zJJK8bcKZwPNmxC5xCsp`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Ends a process.

TSKILL processid | processname [/SERVER:servername] [/ID:sessionid | /A] [/V]

  processid           Process ID for the process to be terminated.
  processname         Process name to be terminated.
  /SERVER:servername  Server containing processID (default is current).
                         /ID or /A must be specified when using processname
                         and /SERVER
  /ID:sessionid       End process running under the specified session.
  /A                  End process running under ALL sessions.
  /V                  Display information about actions being performed.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000001C422B2F79B793DACB20000000001C4
* Thumbprint: AE9C1AE54763822EEC42474983D8B635116C8452
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tskill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


