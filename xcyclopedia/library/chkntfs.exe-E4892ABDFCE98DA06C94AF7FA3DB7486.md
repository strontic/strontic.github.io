
# chkntfs.exe 
* File Path: `C:\WINDOWS\SysWOW64\chkntfs.exe`
* Description: NTFS Volume Maintenance Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `E4892ABDFCE98DA06C94AF7FA3DB7486`
SHA1 | `4E1C3105C5AEDEFAEC051B5B2CABD026E42101F9`
SHA256 | `22C19A26966F581991D97D5D1CF8C4B7A9EC238DDA70401830184B83584A493D`
SHA384 | `F4EA550A6A9742AECB87D4B9112B7CC9FF5066B5FE706B76658188303C22F22DB0EFDC6C3F639DB51954FC5B00893E54`
SHA415 | `FDA77BC10A4E6B9CE9A2E8D4D055ACA07536E5588EC13EB8CE8B6019024DC9A2696DD53118A8EB58B970A2764B1CB7123E7C4C7DD40466B1FEED1684E4DC2CD5`
SSDEEP | `384:9YgCYdwB0Deyx2l/qGivECYaqNkWX6W+QR:9AYyB40l1y5WvT`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CHKNTFS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


