---
title: MBR2GPT.EXE | 
---

# MBR2GPT.EXE 

* File Path: `C:\Windows\system32\MBR2GPT.EXE`

## Hashes

Type | Hash
-- | --
MD5 | `B11EA2D4EA3923FD438905B64B1361EA`
SHA1 | `ACCF21897CC6681D26F632C08C73D16705F9BF76`
SHA256 | `4B8E15BC26CEB864DD30F664FAC8A987008FD52D3FFC50C2704EA3DCCB6C06D1`
SHA384 | `E2BA64FB65A4DF2CB87B1D6DC6A31EA129FEE17FCAFC8BB2270E8A5774F85A2EBB605D155915FA50EF694A8B8E63B154`
SHA512 | `7E55C57AD8A39531E196A26128DABB3CE9558D473B2395823C8F464CEA3955BF992581DB5C91F2EFD26424A9E122B1216FDA2751A3D64D0FB8601C0C3ECF4E68`
SSDEEP | `24576:NsEzmLHGy0ANq7GE73BDPFclUPTRklVJlYWRd:mEiHX3AGE71Pd4Dl`

## Runtime Data

### Usage (stdout):
```Batchfile

Converts a disk from MBR to GPT partitioning without modifying or deleting data on the disk.

MBR2GPT.exe /validate|convert [/disk:<diskNumber>] [/logs:<logDirectory>] [/map:<source>=<destination>] [/allowFullOS]

Where:

 /validate
         - Validates that the selected disk can be converted
           without performing the actual conversion.

 /convert
         - Validates that the selected disk can be converted
           and performs the actual conversion.

 /disk:<diskNumber>
         - Specifies the disk number of the disk to be processed.
           If not specified, the system disk is processed.

 /logs:<logDirectory>
         - Specifies the directory for logging. By default logs
           are created in the %windir% directory.

 /map:<source>=<destination>
         - Specifies the GPT partition type to be used for a
           given MBR partition type not recognized by Windows.
           Multiple /map switches are allowed.

 /allowFullOS
         - Allows the tool to be used from the full Windows
           environment. By default, this tool can only be used
           from the Windows Preinstallation Environment.


```

### Usage (stderr):
```Batchfile
Invalid argument: --help

Invalid arguments


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MBR2GPT.EXE |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 





MIT License. Copyright (c) 2020 Strontic.


