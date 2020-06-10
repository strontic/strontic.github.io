
# compact.exe 
* File Path: `C:\Windows\system32\compact.exe`
* Description: File Compress Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `06CB9005B45476BBCFA7DA89572A3012`
SHA1 | `0F67DF3CD323CAE6D0004B92D2E45CCCE2B0ACB9`
SHA256 | `CF847A846107E19BCD596479AF3B7CF848D7FA5974F514383491928FA6C2BE80`
SHA384 | `0CA8DF29A3C39F1887AED5541F1FE4276E870291E5817527E0710D4A044D9BAD77E6C829C739F64539008E660372F3BF`
SHA415 | `3A479356ED37FAC6DD5699AE677C58ABBA2E0E7052807E02974F2D7F403086EA5CB81939252133450BCF8BBA14D664456240D7B3271347D2C6B4405CC9420FFC`
SSDEEP | `768:Z7Ryb6dpu6gCRsddJA8LdCrZgPV7gGKJLz9cdlpduo/IjDw7XNImXKN:R1UqsHJA8ZCZArQLz9cdlpdusoU7XN5e`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: COMPACT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


