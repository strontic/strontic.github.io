
# chkntfs.exe 

* File Path: `C:\WINDOWS\system32\chkntfs.exe`
* Description: NTFS Volume Maintenance Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4D9830DB7DE498A6DA3B051200B1E0C9`
SHA1 | `7F9F14C88C2DEA2395B558A362E6F7E448A5790B`
SHA256 | `5CDFE049512C014263B0AE9A3B7898F3222693576B0595C001DB08D6EF24D5E1`
SHA384 | `B7E4EE5C5C59DA4E1971718127489B4E491833D127F3AD5DB872BF72CD15D9F567B19BB4E617D75EEC79115CC28E4EAE`
SHA415 | `B6897D3D7D2FF9EC591D7DEDA918C227992D69B529D64A110AB506DCAF11DFEEB49ECD5838C49277A8C83F9DECE1AFF6ED6B791D03F754BE1DCA5613022881EB`
SSDEEP | `384:LAq2t5E5MIoUzV5HnRPb9TcmpHBwsgFX7gT+LNTNcWX6W:0q23qlJHnVbjxyNFMGX`

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

* Original Filename: CHKNTFS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


