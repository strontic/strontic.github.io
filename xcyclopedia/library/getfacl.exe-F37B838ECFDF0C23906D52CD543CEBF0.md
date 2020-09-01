---
title: getfacl.exe | 
---

# getfacl.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\getfacl.exe`

## Hashes

Type | Hash
-- | --
MD5 | `F37B838ECFDF0C23906D52CD543CEBF0`
SHA1 | `597FAD1E144904AC459AB304580E774298DA1D83`
SHA256 | `39E8892A6628255C6701E2CA3620B6AF30AF0AFFF4511493FD59BFE8793D6423`
SHA384 | `42853D643415973198FB58A4D6034C51951DDBCD2ECC6F9EDDE6ED6C3A72C10172976B6ACD0141C8DFA36E92181F0D5C`
SHA512 | `FDCF6ABA1670E5F4EF562736316D2E0579A15B135D0C15AF94E685DD407198E8D3BD450AEEE82FEEFFA7E25FBA061DD67310770C7B7F23C3D26A78201B1A8879`
SSDEEP | `3072:g9gpvCxdEysaWGI61mHJMSoPUPQeQEdpXhQtTyR8iJMkGBsI4T:g+pvCLFWGYMSoP+dthQt3iBGKdT`

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

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\getfacl.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\getfacl.exe](getfacl.exe-F37B838ECFDF0C23906D52CD543CEBF0.md) | 100




MIT License. Copyright (c) 2020 Strontic.


