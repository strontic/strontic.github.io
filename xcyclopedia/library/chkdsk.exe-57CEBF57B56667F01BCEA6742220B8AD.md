
# chkdsk.exe 
* File Path: `C:\WINDOWS\SysWOW64\chkdsk.exe`
* Description: Check Disk Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `57CEBF57B56667F01BCEA6742220B8AD`
SHA1 | `0681E3CDFDC3F908865EB2BB0A26B51D24806E14`
SHA256 | `F6BE94BDD0F6C02438C697F37C836D5EF2BF1690573953525DB117E7D03251F1`
SHA384 | `4CB3412E84C3BC37BD1747E02BF8488074F0CC0F7652ECB7D6E37BA6275A07A60ED71EE3E3448874923838A79ADE9ACA`
SHA415 | `C2D1F616864FC07C53E897D56C7F64D60D9CD7DC1D7880FBB1CE8BB06BD2A8BBD32876187927987634D6BB27950F12FF30800B691E029BFF78D4DD21D314179A`
SSDEEP | `384:uSTpDdWVw8apAXObwp1X3xVb0FoJZ4V0cOhBN6WSFfhWvFEjDd:jT9dWTapAXObwp1X3bor0BBCfWA`

## Runtime Data
### Usage (stdout):
```Batchfile
Checks a disk and displays a status report.


CHKDSK [volume[[path]filename]]] [/F] [/V] [/R] [/X] [/I] [/C] [/L[:size]] [/B] [/scan] [/spotfix]


  volume              Specifies the drive letter (followed by a colon),
                      mount point, or volume name.
  filename            FAT/FAT32 only: Specifies the files to check for
                      fragmentation.
  /F                  Fixes errors on the disk.
  /V                  On FAT/FAT32: Displays the full path and name of every
                      file on the disk.
                      On NTFS: Displays cleanup messages if any.
  /R                  Locates bad sectors and recovers readable information
                      (implies /F, when /scan not specified).
  /L:size             NTFS only:  Changes the log file size to the specified
                      number of kilobytes.  If size is not specified, displays
                      current size.
  /X                  Forces the volume to dismount first if necessary.
                      All opened handles to the volume would then be invalid
                      (implies /F).
  /I                  NTFS only: Performs a less vigorous check of index
                      entries.
  /C                  NTFS only: Skips checking of cycles within the folder
                      structure.
  /B                  NTFS only: Re-evaluates bad clusters on the volume
                      (implies /R)
  /scan               NTFS only: Runs an online scan on the volume
  /forceofflinefix    NTFS only: (Must be used with "/scan")
                      Bypass all online repair; all defects found
                      are queued for offline repair (i.e. "chkdsk /spotfix").
  /perf               NTFS only: (Must be used with "/scan")
                      Uses more system resources to complete a scan as fast as
                      possible. This may have a negative performance impact on
                      other tasks running on the system.
  /spotfix            NTFS only: Runs spot fixing on the volume
  /sdcleanup          NTFS only: Garbage collect unneeded security descriptor
                      data (implies /F).
  /offlinescanandfix  Runs an offline scan and fix on the volume.
  /freeorphanedchains FAT/FAT32/exFAT only: Frees any orphaned cluster chains
                      instead of recovering their contents.
  /markclean          FAT/FAT32/exFAT only: Marks the volume clean if no
                      corruption was detected, even if /F was not specified.

The /I or /C switch reduces the amount of time required to run Chkdsk by
skipping certain checks of the volume.

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

* Original Filename: CHKDSK.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


