---
title: sdelete64.exe | Secure file delete
excerpt: What is sdelete64.exe?
---

# sdelete64.exe 

* File Path: `C:\SysinternalsSuite\sdelete64.exe`
* Description: Secure file delete

## Hashes

Type | Hash
-- | --
MD5 | `2B5CB081721B8BA454713119BE062491`
SHA1 | `7BCD946326B67F806B3DB4595EDE9FBDF29D0C36`
SHA256 | `FEEC1457836A5F84291215A2A003FCDE674E7E422DF8C4ED6FE5BB3B679CDC87`
SHA384 | `FECCCBA7D800940A373E206B76ED60C8445D25D392DD5C278D2F1C5B79A848FAFF9D84B0E850489E31893FC95113BBC7`
SHA512 | `413C1EF210C97CBDED7728BC609F9641DC16BE53BD6E0242E9CBA01AF90A3D5ABC3DBAFA9EF75E3370B23BFDD895D3D45195DFAF9CBDB44A37F37190F8233522`
SSDEEP | `3072:iIwYaZhWTnvoCuhKLaOKqoSRTrTR1KGqS4iKk5UFyrTZSRSPsxSveo+iYYqh:iIwYaZhsnO9OKIRTrTRo5p/y4GZ8`
IMP | `342934F7499D0F57D88D4434E41B7BF9`
PESHA1 | `00E2500EAACF0C97EAFC513B811D359276D34367`
PE256 | `7E260E05A9F5EEE8E6E16F1BFF74224B736BE57ACB57780130B736D140235550`

## Runtime Data

### Usage (stdout):
```cmhg

SDelete v2.02 - Secure file delete
Copyright (C) 1999-2018 Mark Russinovich
Sysinternals - www.sysinternals.com

usage: sdelete [-p passes] [-r] [-s] [-q] <file or directory> [...]
       sdelete [-p passes] [-z|-c [percent free]] <drive letter [...]>
       sdelete [-p passes] [-z|-c] <physical disk number>
   -c         Clean free space. Specify an option amount of space
              to leave free for use by a running system.
   -p         Specifies number of overwrite passes (default is 1)
   -r         Remove Read-Only attribute
   -s         Recurse subdirectories
   -z         Zero free space (good for virtual disk optimization)
   -nobanner  Do not display the startup banner and copyright message.

Disks must not have any volumes in order to be cleaned.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\sdelete64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001B1DDEDBA54E965B85F0001000001B1`
* Thumbprint: `9DC17888B5CFAD98B3CB35C1994E96227F061675`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdelete.exe
* Product Name: Sysinternals Sdelete
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 2.02
* Product Version: 2.02
* Language: English (United States)
* Legal Copyright: Copyright (C) 1999-2018 Mark Russinovich
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/feec1457836a5f84291215a2a003fcde674e7e422df8c4ed6fe5bb3b679cdc87/detection/





MIT License. Copyright (c) 2020 Strontic.


