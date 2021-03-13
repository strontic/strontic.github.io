---
title: pspasswd64.exe | Local and remote password changer
excerpt: What is pspasswd64.exe?
---

# pspasswd64.exe 

* File Path: `C:\SysinternalsSuite\pspasswd64.exe`
* Description: Local and remote password changer

## Hashes

Type | Hash
-- | --
MD5 | `BFEC8D28B818071DD898C1E18A98A242`
SHA1 | `90994F647F8CFAC2C448E6BB5371CC3DD0E4FEB5`
SHA256 | `B5A01628E544929E2DFF9F7041359D80F037E1E6DA8AFB97ABD6B2B2F67960C4`
SHA384 | `329FABAEA44952CA7E2C015E90259D55EEBE0ABF0165A44C4FE7FF8397FCB16BA0007C26207ACB5F024D1B2D1082A6A3`
SHA512 | `76C567CC70231E019CDD8DADE111597662163511E286104F91636CD23D2D4C834D7C20B277953A052ACB34CE1CC82C445F2D806431DCC624E1318F6ED7032D48`
SSDEEP | `3072:MlHoXxHSkdJ2+gTz+VBj7hYcOb5UFEN8J3urxKdKsIOSEjfY:wHPkdJ2xTqPj7hmuEN4HfY`
IMP | `A99449BE6B192D90F3303A049C6E0260`
PESHA1 | `904A8FDEA05899B0D295DE021C2ECD19A86F6A71`
PE256 | `4D0FF1F2EF04615DED5BD25EFDDE70B6FD0626FDCAB3B438893628179157F4A4`

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
C:\SysinternalsSuite\pspasswd64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/b5a01628e544929e2dff9f7041359d80f037e1e6da8afb97abd6b2b2f67960c4/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


