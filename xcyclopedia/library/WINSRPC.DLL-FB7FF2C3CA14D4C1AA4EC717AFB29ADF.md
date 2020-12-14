---
title: WINSRPC.DLL | WINS RPC LIBRARY
excerpt: What is WINSRPC.DLL?
---

# WINSRPC.DLL 

* File Path: `C:\Windows\system32\WINSRPC.DLL`
* Description: WINS RPC LIBRARY

## Hashes

Type | Hash
-- | --
MD5 | `FB7FF2C3CA14D4C1AA4EC717AFB29ADF`
SHA1 | `1379085B2298FCC7A495D7B521F6E44484F4D197`
SHA256 | `F55A55A29542CAF7ABA026FF452FE4F9375A74C38714FC95BA696FE5D0B43761`
SHA384 | `01E6F1ED6D8FDC257EDEE8E1374B30DDC1CF59E4FFADCAE3C9AE7ACA0BE2C33F985E6B9D84951E54956D9236E04546D8`
SHA512 | `90834D14E46E289AF644CD92455FEB430CA6D2EE56C3061B12D057ABE3674050EFC120D56647D42B8C1FB262A7CCC3404DA8B28627DE9F14A1C90A58DA4CAA72`
SSDEEP | `384:LcM4WkBcuVjDOLMr9sXUb8sO7Q4JHTsDA2PMZ8YetKITWDLWo:lGjOXUWzHT/Uq8BKIc7`
IMP | `D7A97F423A90C0707C029072D77B1F37`
PESHA1 | `173FD3E31632C9D7BF3C81E3D3AF7E0CDCF84704`
PE256 | `63171EF727E2B72C324EAC238889D906498132DE478B8D886905311CC3201803`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WinsSetPriorityClass` | 21 | Exported Function
`WinsStatus` | 22 | Exported Function
`WinsStatusNew` | 23 | Exported Function
`WinsSetFlags` | 20 | Exported Function
`WinsResetCounters` | 17 | Exported Function
`WinsRestore` | 18 | Exported Function
`WinsRestoreEx` | 19 | Exported Function
`WinsStatusWHdl` | 24 | Exported Function
`WinsUBind` | 29 | Exported Function
`WinsUnbind` | 30 | Exported Function
`WinsWorkerThdUpd` | 31 | Exported Function
`WinsTrigger` | 28 | Exported Function
`WinsSyncUp` | 25 | Exported Function
`WinsTerm` | 26 | Exported Function
`WinsTombstoneDbRecs` | 27 | Exported Function
`WinsRecordAction` | 16 | Exported Function
`WinsDelDbRecs` | 5 | Exported Function
`WinsDeleteWins` | 6 | Exported Function
`WinsDoScavenging` | 7 | Exported Function
`WinsCheckAccess` | 4 | Exported Function
`WinsABind` | 1 | Exported Function
`WinsAllocMem` | 2 | Exported Function
`WinsBackup` | 3 | Exported Function
`WinsDoScavengingNew` | 8 | Exported Function
`WinsGetDbRecsByName` | 13 | Exported Function
`WinsGetNameAndAdd` | 14 | Exported Function
`WinsPullRange` | 15 | Exported Function
`WinsGetDbRecs` | 12 | Exported Function
`WinsDoStaticInit` | 9 | Exported Function
`WinsFreeMem` | 10 | Exported Function
`WinsGetBrowserNames` | 11 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winsrpc.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/f55a55a29542caf7aba026ff452fe4f9375a74c38714fc95ba696fe5d0b43761/detection/


## Possible Misuse

*The following table contains possible examples of `WINSRPC.DLL` being misused. While `WINSRPC.DLL` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`winsrpc.dll`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


