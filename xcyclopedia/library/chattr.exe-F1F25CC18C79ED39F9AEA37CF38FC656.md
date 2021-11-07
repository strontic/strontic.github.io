---
title: chattr.exe | 
excerpt: What is chattr.exe?
---

# chattr.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\chattr.exe`

## Hashes

Type | Hash
-- | --
MD5 | `F1F25CC18C79ED39F9AEA37CF38FC656`
SHA1 | `D58118121C0086B017332BA079BAF0FA8D9A54AF`
SHA256 | `F7493D26DAFD9CC80E492A2D9E48D1BBC49BD96BAC9967FBF27F227FF0C51265`
SHA384 | `EB0DEA10AE4015B4E5E2C6A474F0C3827C7AEF9E01834E1E7ADB3C5F3F66745B2FF2C64E0ABC9ABD03F2E344E23F4DA1`
SHA512 | `F2708F7127629104AD1F95B97318DAD532DE3CAB4EDB3B4963CCBE8F38468E084933219FD409390C0D0C73DF84380770DA21D1138E235649BAC661E964C91BD5`
SSDEEP | `3072:3Hp0kzQREcugTioHskSV39pCojzhpK6eQgmMIpNMEjt+wsZLoq6F:Xp0kziEcdTiUskojzhpamxpOEjEwMoqo`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: chattr [-RVfhv] [+-=mode]... [file]...

Change file attributes

  -R, --recursive     recursively list attributes of directories and their 
                      contents
  -V, --verbose       Be verbose during operation
  -f, --force         suppress error messages
  -h, --help          this help text
  -v, --version       display the program version

The format of 'mode' is {+-=}[acCehnrsSt]

The  operator '+' causes the selected attributes to be added to the
existing attributes of the files; '-' causes them to be removed; and
'=' causes them to be the only attributes that the files have.

Supported attributes:

  'r', 'Readonly':     file is read-only
  'h', 'Hidden':        file or directory is hidden
  's', 'System':        file or directory that the operating system uses
  'a', 'Archive':       file or directory has the archive marker set
  't', 'Temporary':     file is being used for temporary storage
  'S', 'Sparse':        file is sparse
  'c', 'Compressed':    file or directory is compressed
  'n', 'Notindexed':    file or directory is not to be indexed by the
                        content indexing service
  'e', 'Encrypted':     file is encrypted
  'C', 'Casesensitive': directory is handled case sensitive
                        (Windows 10 1803 or later, local NTFS only,
                         WSL must be installed)

```

### Usage (stderr):
```cmhg
chattr: Must use at least one of =, + or -

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
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\lsattr.exe](lsattr.exe-19EAC399FA5FB55B8699DA6F30C03458.md) | 66

## Possible Misuse

*The following table contains possible examples of `chattr.exe` being misused. While `chattr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_auditd_chattr_immutable_removal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/auditd/lnx_auditd_chattr_immutable_removal.yml) | `a0\|contains: 'chattr'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #9: chattr - Remove immutable file attribute [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - Atomic Test #9: chattr - Remove immutable file attribute [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) | - Atomic Test #9: chattr - Remove immutable file attribute [macos, linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.002/T1222.002.md) | - [Atomic Test #9 - chattr - Remove immutable file attribute](#atomic-test-9---chattr---remove-immutable-file-attribute) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.002/T1222.002.md) | ## Atomic Test #9 - chattr - Remove immutable file attribute | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.002/T1222.002.md) | Remove's a file's `immutable` attribute using `chattr`. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.002/T1222.002.md) | chattr -i #{file_to_modify} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


