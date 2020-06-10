
# chkntfs.exe 
* File Path: `C:\Windows\SysWOW64\chkntfs.exe`
* Description: NTFS Volume Maintenance Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `E3C7BE10853AE9CC218A44192355984C`
SHA1 | `C6740445C81957397CD0F36CA397F1504019802D`
SHA256 | `7A28895EB731AF1D16941D3F1069E0733F1325EDAA06516E4B64AF7B9A19DA56`
SHA384 | `2E30F721DF8F90E76F51B62BE3FC0CCACA48956C0625E696651865E23842E394E3CD5030075C080F0D1E1C25A6EFD204`
SHA415 | `C5A4EE0AA834C789C2521E29CF4CBEB99084A5CAEF053253DEA5B4959D102C3D4E9CA5B124804B79A141A15BAE17CCA36D0B79B5CC5401C8B5DB83539571A9FE`
SSDEEP | `384:Lgsad7rP2v7OlZ+2cCwNK2/afV8qaLUGf4nX7U1blCCNcW56Wmd:LVad7rP2v7OlZ+2JwNK2/afVhKUGf1Ah`

## Runtime Data
### Usage (stdout):
```Batchfile
Displays or modifies the checking of disk at boot time.

CHKNTFS volume [...]
CHKNTFS /D
CHKNTFS /T[:time]
CHKNTFS /X volume [...]
CHKNTFS /C volume [...]

  volume         Specifies the drive letter (followed by a colon),
                 mount point, or volume name.
  /D             Restores the machine to the default behavior; all drives are
                 checked at boot time and chkdsk is run on those that are
                 dirty.
  /T:time        Changes the AUTOCHK initiation countdown time to the
                 specified amount of time in seconds.  If time is not
                 specified, displays the current setting.
  /X             Excludes a drive from the default boot-time check.  Excluded
                 drives are not accumulated between command invocations.
  /C             Schedules a drive to be checked at boot time; chkdsk will run
                 if the drive is dirty.

If no switches are specified, CHKNTFS will display if the specified drive is
dirty or scheduled to be checked on next reboot.

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

* Original Filename: CHKNTFS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


