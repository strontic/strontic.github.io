---
title: psfile.exe | Lists files and directories opened remotely
excerpt: What is psfile.exe?
---

# psfile.exe 

* File Path: `C:\SysinternalsSuite\psfile.exe`
* Description: Lists files and directories opened remotely

## Hashes

Type | Hash
-- | --
MD5 | `201058594991D79D5D8891DBBEEEE3C6`
SHA1 | `3E99F3680B7E4BA4FADE90FD338999B2AB4CA7F8`
SHA256 | `9D45453285FF3B4A41056317C96866D06481751307D703E3355B18D5EEB092AD`
SHA384 | `37A47EE3C73C435E5032A2B0E1E8214DED67588608D83A592EE942D9E9AC2B70C3D229FC15E8F35B7B64F0C03550375B`
SHA512 | `B5B2C61AB892024E8A69BB93AFD392E176D71F7A07239DB9CD85B3457A08A30A35DC783D395B4FE438925B5D8BE9501EBCCF9BA6AE73AC4B0C1CDABE81FBAAD2`
SSDEEP | `3072:pFI050rRO7uwCNZUFzc1cNKxc06QreNcEw:bI0Z3zWcp/c`
IMP | `BDC943A53DDED9831FB5DC068D4B1D71`
PESHA1 | `43072771DD146EB34880DDC5B20B43C4578B333B`
PE256 | `5B151A47A9885BDF18B44F786327E1CA2FFB095CADE33ACA1D9EB99F22D36414`

## Runtime Data

### Usage (stdout):
```cmhg

PsFile v1.03 - Lists files and directories opened remotely
Copyright (C) 2001-2016 Mark Russinovich
Sysinternals

PsFile lists or closes files opened remotely.

Usage: C:\SysinternalsSuite\psfile.exe [\\RemoteComputer [-u Username [-p Password]]] [[Id | path] [-c]]
     -u        Specifies optional user name for login to
               remote computer.
     -p        Specifies password for user name.
     Id        Id of file to print information for or close.
     Path      Full or partial path of files to match.
     -c        Closes file identified by file Id.
     -nobanner Do not display the startup banner and copyright message.
Omitting a file identifier has PsFile list all files opened remotely.


```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\psfile.exe |
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

* Original Filename: psfile.exe
* Product Name: Sysinternals PsFile
* Company Name: Sysinternals
* File Version: 1.03
* Product Version: 1.03
* Language: English (United States)
* Legal Copyright: Copyright (C) 2001-2016 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/9d45453285ff3b4a41056317c96866d06481751307d703e3355b18d5eeb092ad/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


