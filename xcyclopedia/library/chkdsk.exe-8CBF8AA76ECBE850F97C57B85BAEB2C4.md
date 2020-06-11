
# chkdsk.exe 

* File Path: `C:\Windows\SysWOW64\chkdsk.exe`
* Description: Check Disk Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `8CBF8AA76ECBE850F97C57B85BAEB2C4`
SHA1 | `4B73E90CD3EA3933EF0DD3A29BFAEDD9E763EB2B`
SHA256 | `68F0FD913E8CBBCC0B70503EA86EE261614A460FBC0CCF46AE2F000B47FA5C69`
SHA384 | `3B973901269FA78EC9FF0203D15FFB5E8F7EC51BE34657E25841E181B8FF6A19454932A54EFB02389D4E23D21C22E506`
SHA415 | `DF3E1AF59184C46559996C1C7B624F2BB54E2B4A4A5F9A3F118521BB9A52475A2FF5CD609F5272252A0472A1D9D0AD90256A0EA698194199D5803487D167D3B2`
SSDEEP | `384:7pyYxYtvrKp9IScM056YmFXuY0MCW1eN1WSFphWdg:7YYS1rO9ISVt0+expy`

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
  /scan               NTFS only: Runs a online scan on the volume
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
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CHKDSK.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


