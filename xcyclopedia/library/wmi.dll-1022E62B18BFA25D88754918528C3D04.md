---
title: wmi.dll | WMI DC and DP functionality
excerpt: What is wmi.dll?
---

# wmi.dll 

* File Path: `C:\Windows\SysWOW64\wmi.dll`
* Description: WMI DC and DP functionality

## Hashes

Type | Hash
-- | --
MD5 | `1022E62B18BFA25D88754918528C3D04`
SHA1 | `A814C7EBAC7D6667085A8D15308DB7DE6DE63541`
SHA256 | `48AAB5E15C87062C387BABBC39DE644E82F3A6F04B3FBA3BFDFE366FD266526B`
SHA384 | `095AA54921CACF5E025DF5CD2492C4513B94768490927E1E4FE2364AA758650DBADE0A0F9AE1A032C8B8E95A64ABD505`
SHA512 | `41A57CE5FD512F38DAFED9D7C7A46C94A755FD498246576923258098EC727E4D2BC3433628AE853198EDFCAFCBEB4584B87A56265695AF0BCCD9F8529183ED3B`
SSDEEP | `96:jMZ/KvusBSHxf/ZgwHghkyPFtXmKAEqmF9u6MaEWMiWw:Y/KvusBSHxf/6wAhky8WMiW`
IMP | `n/a`
PESHA1 | `58272D6D4E2DE827BCEA6E5D737D852E9DF4327F`
PE256 | `D13547B5F4FE052A7CFEEA3BEF3F30CAE0BF5E7B3B3B31BEEA6501F41793034A`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WmiFreeBuffer` | 31 | Exported Function
`WmiFileHandleToInstanceNameW` | 30 | Exported Function
`WmiMofEnumerateResourcesA` | 32 | Exported Function
`WmiNotificationRegistrationA` | 34 | Exported Function
`WmiMofEnumerateResourcesW` | 33 | Exported Function
`WmiFileHandleToInstanceNameA` | 29 | Exported Function
`WmiDevInstToInstanceNameW` | 25 | Exported Function
`WmiDevInstToInstanceNameA` | 24 | Exported Function
`WmiEnumerateGuids` | 26 | Exported Function
`WmiExecuteMethodW` | 28 | Exported Function
`WmiExecuteMethodA` | 27 | Exported Function
`WmiSetSingleInstanceA` | 42 | Exported Function
`WmiQuerySingleInstanceW` | 41 | Exported Function
`WmiSetSingleInstanceW` | 43 | Exported Function
`WmiSetSingleItemW` | 45 | Exported Function
`WmiSetSingleItemA` | 44 | Exported Function
`WmiQuerySingleInstanceA` | 40 | Exported Function
`WmiOpenBlock` | 36 | Exported Function
`WmiNotificationRegistrationW` | 35 | Exported Function
`WmiQueryAllDataA` | 37 | Exported Function
`WmiQueryGuidInformation` | 39 | Exported Function
`WmiQueryAllDataW` | 38 | Exported Function
`WmiCloseBlock` | 23 | Exported Function
`GetTraceLoggerHandle` | 8 | Exported Function
`GetTraceEnableLevel` | 7 | Exported Function
`OpenTraceA` | 9 | Exported Function
`ProcessTrace` | 11 | Exported Function
`OpenTraceW` | 10 | Exported Function
`GetTraceEnableFlags` | 6 | Exported Function
`ControlTraceA` | 2 | Exported Function
`CloseTrace` | 1 | Exported Function
`ControlTraceW` | 3 | Exported Function
`EnableTrace` | 5 | Exported Function
`CreateTraceInstanceId` | 4 | Exported Function
`StartTraceW` | 19 | Exported Function
`StartTraceA` | 18 | Exported Function
`TraceEvent` | 20 | Exported Function
`UnregisterTraceGuids` | 22 | Exported Function
`TraceEventInstance` | 21 | Exported Function
`SetTraceCallback` | 17 | Exported Function
`QueryAllTracesW` | 13 | Exported Function
`QueryAllTracesA` | 12 | Exported Function
`RegisterTraceGuidsA` | 14 | Exported Function
`RemoveTraceCallback` | 16 | Exported Function
`RegisterTraceGuidsW` | 15 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmi.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/48aab5e15c87062c387babbc39de644e82f3a6f04b3fba3bfdfe366fd266526b/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wmi.dll](wmi.dll-6B25707FB209291415C05781FE6E2C75.md) | 97

## Possible Misuse

*The following table contains possible examples of `wmi.dll` being misused. While `wmi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $s1 = "wmi.dll 2>&1" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $x5 = "TempFile = objShell.ExpandEnvironmentStrings(\"%TEMP%\") & \"\\wmi.dll\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


