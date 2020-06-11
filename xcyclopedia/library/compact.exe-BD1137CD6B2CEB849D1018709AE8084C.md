
# compact.exe 

* File Path: `C:\WINDOWS\system32\compact.exe`
* Description: File Compress Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `BD1137CD6B2CEB849D1018709AE8084C`
SHA1 | `1638F0B68F658B87B66BEDC4B1A1502A45380619`
SHA256 | `AA4DBF701E5E1EFFC2B6B6215954087931FF065DC2D7B1EC682FA296FFDC4B95`
SHA384 | `36651BC87F9401E5ACC5DE3867543A9C45648A7A8D53642AB6A38D4FC9850BDFF34BDCB35182CE3E3FE92C6953839108`
SHA415 | `A399C2982E112AA556870F29D591610242CE63900759DEAA83CA52D472AFA4587129B5766D74C2E3CC1F87FC7D3740DAFA3204C28828EB43BFEB3EA54504C120`
SSDEEP | `768:ZrpfutoIhpaXIv9I3+CDw0g83oGZ6V82ZzN3JQcTlpHpocOxN+tq5uIiAD85:2aXk9IuCDhgdG8WozN3JQcTlpHpY+tqg`

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
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: COMPACT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.329 (WinBuild.160101.0800)
* Product Version: 10.0.18362.329
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


