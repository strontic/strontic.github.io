---
title: pspasswd.exe | Local and remote password changer
excerpt: What is pspasswd.exe?
---

# pspasswd.exe 

* File Path: `C:\SysinternalsSuite\pspasswd.exe`
* Description: Local and remote password changer

## Hashes

Type | Hash
-- | --
MD5 | `2AF538872742F9D578E5DD54D4440BA5`
SHA1 | `0618FEC45EAEE89CD4C7B17F77D9FF659EABE176`
SHA256 | `B2F17AB6396A5E5CD5BE12F658C22CDFA2071D377CB8BD0EE76ABBF82A9240A7`
SHA384 | `B503111266900D8D82DA5BA04D7BFF759C4D56A4C02779D02769050FF420B33BE6F56CD4352088E78ADCCEC90C28C24A`
SHA512 | `828873ED152E7C001898F2B066ED638A633920197E6B2ED9473A76C157F6DF70AF760E730BC061D535DFEF0BCAA293428292AF6A3329011995E1E527C3F62FAD`
SSDEEP | `3072:XlUGMzZk3+SMiyudxgZUFUAMrNMfxw0O1UNZEOX:1UG4rOvxNUAO1r8X`
IMP | `83D04C15148CBB0D9FA56243BF0FD610`
PESHA1 | `A8BC7A5EFD7B979CA61A89C8CD7AA692E20062A4`
PE256 | `6FF25816C57FE1BE1AE530EC7728834FD5E42670BD0B1DFFCB02684D8C5B847C`

## Runtime Data

### Usage (stdout):
```cmhg

PsPasswd v1.24 - Local and remote password changer
Copyright (C) 2003-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

PsPasswd changes passwords on a local or remote system.

Usage for local accounts:
  pspasswd [\\[computer[,computer,[,...]]|@file] [-u Username [-p Password]]] <Account> [NewPassword]
Usage for domain accounts:
  pspasswd <Domain\Account> [NewPassword]

     computer    Computer or computers on which the local account exists. If
                 you omit the computer name, the local computer is assumed.
                 If you specify a wildcard (\\*), PsPasswd runs the
                 command on all computers in the current domain or workgroup.
     @file       PsPasswd will change the password on the computers listed
                 in the file.
     -u          Specifies optional user name for login to remote computer.
     -p          Specifies optional password for user name. If you omit this
                 you will be prompted to enter a hidden password.
     -nobanner   Do not display the startup banner and copyright message.
     Domain      Specifies name of the domain of the target account.
     Account     Specifies name of the account for password change.
     NewPassword New password. If omitted a NULL password is applied.


```

### Usage (stderr):
```cmhg
The RPC server is unavailable.
Error changing password:

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\pspasswd.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000010A2C79AED7797BA6AC00010000010A`
* Thumbprint: `3BDA323E552DB1FDE5F4FBEE75D6D5B2B187EEDC`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pspasswd.exe
* Product Name: Sysinternals PsPasswd
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.24
* Product Version: 1.24
* Language: English (United States)
* Legal Copyright: Copyright (C) 2003-2016 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/b2f17ab6396a5e5cd5be12f658c22cdfa2071d377cb8bd0ee76abbf82a9240a7/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


