---
title: tar.exe | bsdtar archive tool
excerpt: What is tar.exe?
---

# tar.exe 

* File Path: `C:\WINDOWS\system32\tar.exe`
* Description: bsdtar archive tool

## Hashes

Type | Hash
-- | --
MD5 | `B706A3837D7D2AEAC9954B5D755A064E`
SHA1 | `6E1F4FD10764D6063D8C30B03C1E3516AE55CA46`
SHA256 | `D2D23F98BBA3CC7085DA3C70763838F4C2DB2128C04EDF3172C705740419AF8C`
SHA384 | `1B783BEFB537E1CE894AB198328244A8B84BB28B186781B9077F2A1B9752AAC1CD412C72E6F06EA129D042BE0FDC70DE`
SHA512 | `CB74006C9CA3B8092A4C0719096B2D23A46D4A9833E80563CD96017BDE2EE8C44660FE975C29C4E76F5A65B9487F5B37B9ADFCCF649FA496ABA01D6F998609F4`
SSDEEP | `1536:7sJ0hKvCclNC10Z3WUXVS5y08s/17S78:7sJ0fclY1e3lxU17SY`
IMP | `8DBF62EC19CB040B7488F521D32E9D7E`
PESHA1 | `C204E89658064DE23294890FF69AC4A7EEE7B0CE`
PE256 | `781C38BF7377AEB9E33AE02CE5EC4ADAE7490D85036D092631F8C69095DB783F`

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
bsdtar 3.4.3 - libarchive 3.4.3 zlib/1.2.5.f-ipp bz2lib/1.0.6 

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
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\tar.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bsdtar
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 3.4.3 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright: Copyright (c) libarchive authors
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/d2d23f98bba3cc7085da3c70763838f4c2db2128c04edf3172c705740419af8c/detection





MIT License. Copyright (c) 2020-2021 Strontic.


