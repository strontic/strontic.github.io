
# compact.exe 
* File Path: `C:\Windows\SysWOW64\compact.exe`
* Description: File Compress Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `02179EECC304A9AF7DD2F5A5B28AE0A3`
SHA1 | `0D9F00E6ECF05009EE1A7BC13DB1C47E5F09B8D2`
SHA256 | `4DE8F214708A0E45EA67B1618F77E180A7CB7A7B82708E5E6C35894E3427D869`
SHA384 | `0CA7DD8DFE813AF00E72897738954FAB9D165D9D386A3AB19BE414E7F48DFBE861E85AD4DA4CE39483488FE272FE9655`
SHA415 | `FBB02E804B6EC2EB649F392E058E52CACD1AA13899DF5A65EABAD7FED7370D3749D5B6F18710CD369A0D0EB58C73D7E5FB9B7B9C361452C0D2CE92BEF09035A7`
SSDEEP | `768:fdMd1p9eIsK/K1hbSXqTIICbWhf2olLfkcAKAnUVVPehd47XN1NKNT:fdMd1p9erhUWiUV4hd47XNDKN`

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


