
# tskill.exe 

* File Path: `C:\Windows\SysWOW64\tskill.exe`
* Description: Remote Desktop Services End Process Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FB1C4D7ADE8F864BF931C7FD1948B555`
SHA1 | `BC76AA8F095D7FFF72C69D1D704849E1E71B6B50`
SHA256 | `B2FA07A9A1634079F537A5A81AF8D2C658B0F19483EEACA014C22111DB426EEC`
SHA384 | `55A9A1D4E45B49508C21727914B0F28AD3522CEC37743302BB5314F785A81C3106B39FB4638D3C865067A69762F0A16F`
SHA415 | `B30ABAF0BB04FB0931D031E134BC17C85CBF3A3682AA1144D46438991DF2231496AA9E9AE7DE8BFEE54C7DF126373C13437B4754F30E3D100746C2642D11859A`
SSDEEP | `384:nfC/dOQejY9qXIVb/Y0LhakXr3owymfj/IkC56W4kQWk5ff:nKVOQe81/R3M5dk`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tskill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


