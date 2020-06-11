
# chkntfs.exe 

* File Path: `C:\Windows\system32\chkntfs.exe`
* Description: NTFS Volume Maintenance Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B153574FEFD4B21A45855C4267027007`
SHA1 | `BD03976BDE015ABCA84961E3AE4FAA04696FBE96`
SHA256 | `C5066D00E21F691F9716EFA0A85386EB10AF407011363B123DBB7386166339F0`
SHA384 | `6714422C73E76E5751126775F28EC4B111650763900FCECDB7D1325BDC0CF438FB67286C4A25FC8F7C23B2CC010A7353`
SHA415 | `E2D2044C967E741C4EAB91E23DE55A6CA83642AA9C3C5D82CBC2965782C86ED61643227B1BFA3B652AA3379FB53124A8457FCAA11DE5518426A2814B10D93452`
SSDEEP | `384:ZrTDt8z/kU8lV9F5ip3LiolfCTvCl0CTFLIk23jsONEW56W:tDt87klVBidnfC+mCZL4AOR`

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

MIT License. Copyright (c) 2020 Strontic.


