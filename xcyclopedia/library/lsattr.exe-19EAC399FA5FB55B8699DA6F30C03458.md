---
title: lsattr.exe | 
excerpt: What is lsattr.exe?
---

# lsattr.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\lsattr.exe`

## Hashes

Type | Hash
-- | --
MD5 | `19EAC399FA5FB55B8699DA6F30C03458`
SHA1 | `D6A25FA50E011F6B3370A98C8B420C1AB04D490E`
SHA256 | `E2B21B8D9BB26630C56A3E1FF77DD014E96212E49CD637463B061FF5C7BF120A`
SHA384 | `4DFDEECA2F057C28D41C64B89E150B55CE3D89451CDA3C5BEAA05BD16FE35412A28AECA90703AE839D1FB61C8C04ED61`
SHA512 | `A8D66B8C0A380F8D33B2BA370F05C32B820D8CC58CCE4B9E8894AC41EC6CD72623FCE74EFEEE5A6AF4C08B57565FE7F983BA05AB8B27513801EC7853CAD801DE`
SSDEEP | `3072:wlCYI9zQRENfTioHsCnXNcbCojzhpK6eQgmMIpnqEjUNw66Hoq7kLYT:GCYI9ziE9TiUssojzhpamxpqEjcwxoqh`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: lsattr [-RVadhln] [file]...

List file attributes

  -R, --recursive     recursively list attributes of directories and their 
                      contents
  -V, --version       display the program version
  -a, --all           list all files in directories, including files that
                      start with '.'
  -d, --directory     list directories like other files, rather than listing
                      their contents.
  -l, --long          print options using long names instead of single
                      character abbreviations
  -n, --no-headers    don't print directory headers when recursing
  -h, --help          this help text

Supported attributes:

  'r', 'Readonly':      file is read-only, directory is system-marked
  'h', 'Hidden':        file or directory is hidden
  's', 'System':        file or directory that the operating system uses
  'a', 'Archive':       file or directory has the archive marker set
  't', 'Temporary':     file is being used for temporary storage
  'S', 'Sparse':        file is sparse
  'r', 'Reparse':       file or directory that has a reparse point
  'c', 'Compressed':    file or directory is compressed
  'o', 'Offline':       the data of a file is moved to offline storage
  'n', 'Notindexed':    file or directory is not to be indexed by the
                        content indexing service
  'e', 'Encrypted':     file is encrypted
  'C', 'Casesensitive': directory is handled case sensitive
                        (Windows 10 1803 or later, local NTFS only,
                         WSL must be installed)

```

### Usage (stderr):
```cmhg
lsattr: No such file or directory while trying to stat /h

```

## Signature

* Status: Signature verified.
* Serial: `045D8F14A82147641722D4FAFC66BC80`
* Thumbprint: `FB713A60A7FA79DFC03CB301CA05D4E8C1BDD431`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="GitHub, Inc.", O="GitHub, Inc.", L=San Francisco, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\chattr.exe](chattr.exe-F1F25CC18C79ED39F9AEA37CF38FC656.md) | 66

## Possible Misuse

*The following table contains possible examples of `lsattr.exe` being misused. While `lsattr.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = "displaysecinfo(\"List of Attributes\",myshellexec(\"lsattr -a\"));" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


