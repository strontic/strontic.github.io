---
title: tar.exe | bsdtar archive tool
excerpt: What is tar.exe?
---

# tar.exe 

* File Path: `C:\Windows\system32\tar.exe`
* Description: bsdtar archive tool

## Hashes

Type | Hash
-- | --
MD5 | `4D188B08E9274E1360062B22E88A2F3F`
SHA1 | `F93374196F5F6E19B370CDDD9332AC248937E5EF`
SHA256 | `0F28C8D166C7A671B0048137232E9CA6973F1EC826104834AE310681C1866E62`
SHA384 | `FE40A7B2E90581E231295F445F6DB120EA30CB4FA05A42BC0EB120E28A3F269DB1F711EFC87AB89C6DA93348EE90872B`
SHA512 | `5B0D1D2F0E48FB3B250891163C2F1E935663B6865483180EDD1167B8F3269508977893E3FAF905D0676EF0A5CBFDD3486A66D3D521643D68DDA7E55528337207`
SSDEEP | `768:CciB9nbl48DFyNO63/JoH4jEjwlz18rOq5+fQgD77uPhyHijOuPhtflM7J5SpxdG:Fy9nbktRoH4jAOz7CPZpPBMLSp7Kr`
IMP | `518D7F2D8793287656651908BECA1B27`
PESHA1 | `0F4F94501DA0A6D7FDF1917E52B1AF481D9DA394`
PE256 | `F363FB85DA8700BB2796DCEC95747B166C639D7A92679ECF43AA07669B983AEC`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\tar.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bsdtar
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 3.3.2 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright: Copyright (c) libarchive authors
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/0f28c8d166c7a671b0048137232e9ca6973f1ec826104834ae310681c1866e62/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\tar.exe](tar.exe-0B8821B257EEE9C01CD29C62AE9D3EF9.md) | 27
[C:\WINDOWS\system32\tar.exe](tar.exe-5F6B04A0EC5FE46FEEEC887406F63E57.md) | 29




MIT License. Copyright (c) 2020-2021 Strontic.


