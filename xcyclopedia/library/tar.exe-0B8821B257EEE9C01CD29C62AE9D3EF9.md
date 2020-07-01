---
title: tar.exe | bsdtar archive tool
---

# tar.exe 

* File Path: `C:\windows\system32\tar.exe`
* Description: bsdtar archive tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `0B8821B257EEE9C01CD29C62AE9D3EF9`
SHA1 | `2F52C7715751AEE0ABDDDEE30C1B61586C36D1AD`
SHA256 | `1407B5BED4602A67C684363AE1582967193DF1CE7CE387B684AF031D9C94EEFA`
SHA384 | `131E8069F7139159704485252EA79407037878A7D7BF31FF2ED37E7F30CB814B93599E2C9D863A9823F300E06B2E707E`
SHA512 | `242E0124D966926FC3AF392A05404A980BFC7F59691FBB9BD3D532F1476EEF5E1ED5789F3E39BDE7DD6F6231F62432CD80965A0E7DCB0012A4ECB8FA61F4A5B2`
SSDEEP | `768:tsqAYUa+Fx7guW7clM5NuTmN9+/CeL1EjuqmbSchDArcMbv+BzcijXjHM7J5SpxJ:WDYUa+35l2bNcR6oWx7yDvHMLSp7xAk`

## Runtime Data

### Usage (stdout):
```Batchfile
tar.exe(bsdtar): manipulate archive files
First option must be a mode specifier:
  -c Create  -r Add/Replace  -t List  -u Update  -x Extract
Common Options:
  -b #  Use # 512-byte records per I/O block
  -f <filename>  Location of archive (default \\.\tape0)
  -v    Verbose
  -w    Interactive
Create: tar.exe -c [options] [<file> | <dir> | @<archive> | -C <dir> ]
  <file>, <dir>  add these items to archive
  -z, -j, -J, --lzma  Compress archive with gzip/bzip2/xz/lzma
  --format {ustar|pax|cpio|shar}  Select archive format
  --exclude <pattern>  Skip files that match pattern
  -C <dir>  Change to <dir> before processing remaining files
  @<archive>  Add entries from <archive> to output
List: tar.exe -t [options] [<patterns>]
  <patterns>  If specified, list only entries that match
Extract: tar.exe -x [options] [<patterns>]
  <patterns>  If specified, extract only entries that match
  -k    Keep (don't overwrite) existing files
  -m    Don't restore modification times
  -O    Write entries to stdout, don't restore to disk
  -p    Restore permissions (including ACLs, owner, file flags)
bsdtar 3.3.2 - libarchive 3.3.2 zlib/1.2.5.f-ipp

```

### Usage (stderr):
```Batchfile
Usage:
  List:    tar.exe -tf <archive-filename>
  Extract: tar.exe -xf <archive-filename>
  Create:  tar.exe -cf <archive-filename> [filenames...]
  Help:    tar.exe --help

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bsdtar
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 3.3.2 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright: Copyright (c) libarchive authors

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\tar.exe](tar.exe-4D188B08E9274E1360062B22E88A2F3F.md) | 27
[C:\WINDOWS\system32\tar.exe](tar.exe-5F6B04A0EC5FE46FEEEC887406F63E57.md) | 35




MIT License. Copyright (c) 2020 Strontic.


