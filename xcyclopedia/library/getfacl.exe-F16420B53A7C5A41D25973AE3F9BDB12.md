---
title: getfacl.exe | 
---

# getfacl.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\getfacl.exe`

## Hashes

Type | Hash
-- | --
MD5 | `F16420B53A7C5A41D25973AE3F9BDB12`
SHA1 | `E0EAFCB1F1667174DADF5336137C8078D9FA7862`
SHA256 | `261CB9430363F25E21FA162D948A3C8637BE9D54468E32A49628A65E22027813`
SHA384 | `657F3D58AFE2729CCCC78BA45AF8ED812BEFFE0F4D51DD23789061C56229BC4BA533FBFF681444F46BBECDC9682EB03A`
SHA512 | `29778AC83C502E316A38604EFC2AD14527CE8F154770ABF2603B3A65B22D73F73509078B31A42A55A66DEE1888E8B7C760AA21D99155DA57F0A4F9E7B9FD6253`
SSDEEP | `3072:5qVvzQREpfabDTioHsYHSxZjrorzhwv9eQRmMzn4WEjEtwy/Go0Cvhr:cVvziEMTiUsBorzhwBmunvEjQwxo0qhr`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: getfacl [-adn] FILE [FILE2...]

Display file and directory access control lists (ACLs).

  -a, --access        display the file access control list only
  -d, --default       display the default access control list only
  -c, --omit-header   do not display the comment header
  -e, --all-effective print all effective rights
  -E, --no-effective  print no effective rights
  -n, --numeric       print numeric user/group identifiers
  -V, --version       print version and exit
  -h, --help          this help text

When multiple files are specified on the command line, a blank
line separates the ACLs for each file.
For each argument that is a regular file, special file or
directory, getfacl displays the owner, the group, and the ACL.
For directories getfacl displays additionally the default ACL.

With no options specified, getfacl displays the filename, the
owner, the group, the setuid (s), setgid (s), and sticky (t)
bits if available, and both the ACL and the default ACL, if it
exists.

The format for ACL output is as follows:
     # file: filename
     # owner: name or uid
     # group: name or uid
     # flags: sst
     user::perm
     user:name or uid:perm
     group::perm
     group:name or gid:perm
     mask::perm
     other::perm
     default:user::perm
     default:user:name or uid:perm
     default:group::perm
     default:group:name or gid:perm
     default:mask::perm
     default:other::perm


```

### Usage (stderr):
```Batchfile
getfacl: /h: No such file or directory


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





MIT License. Copyright (c) 2020 Strontic.


