
# compact.exe 
* File Path: `C:\WINDOWS\SysWOW64\compact.exe`
* Description: File Compress Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `2FF6DBD252522101AB50FDFF9BC73164`
SHA1 | `21DD97C0C1D941E179DB5C7D74376C867D163F84`
SHA256 | `51471729156D29297DB97A5593E63FF54B224FAC512248C583D2208641A449B0`
SHA384 | `BD025A4BED7727712DFD2FE59F946A53DD70DE5A0893E3B7AEDBE6DD8454106D13DE70633E7E7A1900129E9A4881DF4B`
SHA415 | `291F02A3D17F8A02AB1A92B5F47C4342C7DF712CA9FA8A0BCB96CC24C96D8B53563DABE379B3B0C08E1DB3651F97E9DE112FC9F6848136F508FCD537AB086B30`
SSDEEP | `768:9ZQMj1pHpIjpq2wt3OLeENwRdIdGBDXPMaN9UTFrURZN2j08388H4upAZnFpq5ud:9ZQMj1pHpwpqyrcodrU47HFAZnFpq5ud`

## Runtime Data
### Usage (stdout):
```Batchfile
Displays or alters the compression of files on NTFS partitions.

COMPACT [/C | /U] [/S[:dir]] [/A] [/I] [/F] [/Q] [/EXE[:algorithm]]
        [/CompactOs[:option] [/WinDir:dir]] [filename [...]]

  /C         Compresses the specified files.  Directories will be marked
             so that files added afterward will be compressed unless /EXE
             is specified.
  /U         Uncompresses the specified files.  Directories will be marked
             so that files added afterward will not be compressed.  If
             /EXE is specified, only files compressed as executables will
             be uncompressed; if this is omitted, only NTFS compressed
             files will be uncompressed.
  /S         Performs the specified operation on files in the given
             directory and all subdirectories.  Default "dir" is the
             current directory.
  /A         Displays files with the hidden or system attributes.  These
             files are omitted by default.
  /I         Continues performing the specified operation even after errors
             have occurred.  By default, COMPACT stops when an error is
             encountered.
  /F         Forces the compress operation on all specified files, even
             those which are already compressed.  Already-compressed files
             are skipped by default.
  /Q         Reports only the most essential information.
  /EXE       Use compression optimized for executable files which are read
             frequently and not modified.  Supported algorithms are:
             XPRESS4K  (fastest) (default)
             XPRESS8K
             XPRESS16K
             LZX       (most compact)
  /CompactOs Set or query the system's compression state.  Supported options are:
             query  - Query the system's Compact state.
             always - Compress all OS binaries and set the system state to Compact
                      which remains unless administrator changes it.
             never  - Uncompress all OS binaries and set the system state to non
                      Compact which remains unless administrator changes it.
  /WinDir    Used with /CompactOs:query, when querying the offline OS. Specifies
             the directory where Windows is installed.
  filename   Specifies a pattern, file, or directory.

  Used without parameters, COMPACT displays the compression state of
  the current directory and any files it contains. You may use multiple
  filenames and wildcards.  You must put spaces between multiple
  parameters.

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

* Original Filename: COMPACT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.329 (WinBuild.160101.0800)
* Product Version: 10.0.18362.329
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


