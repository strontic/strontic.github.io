
# chkdsk.exe 
* File Path: `C:\Windows\system32\chkdsk.exe`
* Description: Check Disk Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `7FF8B08D7537D3EB817332D962488C69`
SHA1 | `9D3D757D38B44EA84D19A7DE63B860821217CDEF`
SHA256 | `249CE8BFC6DFDB17CF87F97DC8F5541FAFB75F8ABDC9419364204AB8144E5E29`
SHA384 | `7A3EDF82F94F4D52ED90DB72BA5E8CA1784E39A3B4B09D30A26AB6E8D11FABF8AD27D3C026360DB36E3E32F4BA7B698B`
SHA415 | `3A58412C9D091A3F8B239744877A025A139C7546D1A6DC145DA390EEA3FBF8685D8FDF21B209DF6D7204476BA6D47C507283315EEC017C6AC4EC3EB3443B2FE0`
SSDEEP | `384:Zf1Q/Mof3hE7QaVigrWBLD4APQ7fJGro1h2+0eImIoOzFNWWSFrhW:h10hP0ViYWBDMfQrM30ev4Or`

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


