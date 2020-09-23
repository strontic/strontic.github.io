---
title: tar.exe | bsdtar archive tool
excerpt: What is tar.exe?
---

# tar.exe 

* File Path: `C:\Windows\SysWOW64\tar.exe`
* Description: bsdtar archive tool

## Hashes

Type | Hash
-- | --
MD5 | `8E49D76E21295D010FF0803D65928F5A`
SHA1 | `0E42D4159BC6AFD910D45D3042E8D89EC2DC884E`
SHA256 | `9D3AB89E9AA2C2C3686F43C7C8FA312B9F80180CE86137151726D16966816C50`
SHA384 | `F1A3185BD2CBA1CD1B36C834773E425BE98BFD910581747DB1C5B454DEF4C78843D0A1CFA01CCC2208F564329A1E35B7`
SHA512 | `40D8DFFC5744EDB14920EAC3F4E029CB85F042E60CF9EEB2FEF9846498F2552E4A26DDA4FB055C868929667DA2534189612E4183DAEFCB577AC808A0A6FD5A94`
SSDEEP | `768:d1Bt3SDGP9WE1BfRO7zr9gCWUHtIU9HVweBraJmBKaK:ryiP9N1B5YsOnnNaABKaK`

## Runtime Data

### Usage (stdout):
```cmhg
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
```cmhg
Usage:
  List:    tar.exe -tf <archive-filename>
  Extract: tar.exe -xf <archive-filename>
  Create:  tar.exe -cf <archive-filename> [filenames...]
  Help:    tar.exe --help

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\tar.exe |


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






MIT License. Copyright (c) 2020 Strontic.


