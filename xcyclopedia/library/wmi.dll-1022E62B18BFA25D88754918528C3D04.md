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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CloseTrace` | 1 (0x1) | Exported Function | api-ms-win-eventing-consumer-l1-1-0.CloseTrace | 0x0000125d
`WmiDevInstToInstanceNameW` | 25 (0x19) | Exported Function | wmiclnt.WmiDevInstToInstanceNameW | 0x00001877
`WmiEnumerateGuids` | 26 (0x1a) | Exported Function | wmiclnt.WmiEnumerateGuids | 0x000018ab
`WmiExecuteMethodA` | 27 (0x1b) | Exported Function | wmiclnt.WmiExecuteMethodA | 0x000018d7
`WmiExecuteMethodW` | 28 (0x1c) | Exported Function | wmiclnt.WmiExecuteMethodW | 0x00001903
`WmiFileHandleToInstanceNameA` | 29 (0x1d) | Exported Function | wmiclnt.WmiFileHandleToInstanceNameA | 0x0000193a
`WmiFileHandleToInstanceNameW` | 30 (0x1e) | Exported Function | wmiclnt.WmiFileHandleToInstanceNameW | 0x0000197c
`WmiFreeBuffer` | 31 (0x1f) | Exported Function | wmiclnt.WmiFreeBuffer | 0x000019af
`WmiMofEnumerateResourcesA` | 32 (0x20) | Exported Function | wmiclnt.WmiMofEnumerateResourcesA | 0x000019df
`WmiMofEnumerateResourcesW` | 33 (0x21) | Exported Function | wmiclnt.WmiMofEnumerateResourcesW | 0x00001a1b
`WmiNotificationRegistrationA` | 34 (0x22) | Exported Function | wmiclnt.WmiNotificationRegistrationA | 0x00001a5a
`WmiNotificationRegistrationW` | 35 (0x23) | Exported Function | wmiclnt.WmiNotificationRegistrationW | 0x00001a9c
`WmiOpenBlock` | 36 (0x24) | Exported Function | wmiclnt.WmiOpenBlock | 0x00001ace
`WmiQueryAllDataA` | 37 (0x25) | Exported Function | wmiclnt.WmiQueryAllDataA | 0x00001af4
`WmiQueryAllDataW` | 38 (0x26) | Exported Function | wmiclnt.WmiQueryAllDataW | 0x00001b1e
`WmiQueryGuidInformation` | 39 (0x27) | Exported Function | wmiclnt.WmiQueryGuidInformation | 0x00001b4f
`WmiQuerySingleInstanceA` | 40 (0x28) | Exported Function | wmiclnt.WmiQuerySingleInstanceA | 0x00001b87
`WmiQuerySingleInstanceW` | 41 (0x29) | Exported Function | wmiclnt.WmiQuerySingleInstanceW | 0x00001bbf
`WmiSetSingleInstanceA` | 42 (0x2a) | Exported Function | wmiclnt.WmiSetSingleInstanceA | 0x00001bf5
`WmiSetSingleInstanceW` | 43 (0x2b) | Exported Function | wmiclnt.WmiSetSingleInstanceW | 0x00001c29
`WmiDevInstToInstanceNameA` | 24 (0x18) | Exported Function | wmiclnt.WmiDevInstToInstanceNameA | 0x0000183b
`WmiSetSingleItemA` | 44 (0x2c) | Exported Function | wmiclnt.WmiSetSingleItemA | 0x00001c59
`WmiCloseBlock` | 23 (0x17) | Exported Function | wmiclnt.WmiCloseBlock | 0x0000180b
`TraceEventInstance` | 21 (0x15) | Exported Function | ntdll.EtwTraceEventInstance | 0x0000178c
`ControlTraceA` | 2 (0x2) | Exported Function | api-ms-win-eventing-legacy-l1-1-0.ControlTraceA | 0x0000129a
`ControlTraceW` | 3 (0x3) | Exported Function | api-ms-win-eventing-controller-l1-1-0.ControlTraceW | 0x000012d8
`CreateTraceInstanceId` | 4 (0x4) | Exported Function | ntdll.EtwCreateTraceInstanceId | 0x00001322
`EnableTrace` | 5 (0x5) | Exported Function | api-ms-win-eventing-legacy-l1-1-0.EnableTrace | 0x0000134d
`GetTraceEnableFlags` | 6 (0x6) | Exported Function | api-ms-win-eventing-classicprovider-l1-1-0.GetTraceEnableFlags | 0x0000138f
`GetTraceEnableLevel` | 7 (0x7) | Exported Function | api-ms-win-eventing-classicprovider-l1-1-0.GetTraceEnableLevel | 0x000013e2
`GetTraceLoggerHandle` | 8 (0x8) | Exported Function | api-ms-win-eventing-classicprovider-l1-1-0.GetTraceLoggerHandle | 0x00001436
`OpenTraceA` | 9 (0x9) | Exported Function | api-ms-win-eventing-legacy-l1-1-0.OpenTraceA | 0x00001481
`OpenTraceW` | 10 (0xa) | Exported Function | api-ms-win-eventing-consumer-l1-1-0.OpenTraceW | 0x000014b9
`ProcessTrace` | 11 (0xb) | Exported Function | api-ms-win-eventing-consumer-l1-1-0.ProcessTrace | 0x000014f5
`QueryAllTracesA` | 12 (0xc) | Exported Function | api-ms-win-eventing-legacy-l1-1-0.QueryAllTracesA | 0x00001536
`QueryAllTracesW` | 13 (0xd) | Exported Function | api-ms-win-eventing-controller-l1-1-0.QueryAllTracesW | 0x00001578
`RegisterTraceGuidsA` | 14 (0xe) | Exported Function | api-ms-win-eventing-obsolete-l1-1-0.RegisterTraceGuidsA | 0x000015c2
`RegisterTraceGuidsW` | 15 (0xf) | Exported Function | api-ms-win-eventing-classicprovider-l1-1-0.RegisterTraceGuidsW | 0x0000160e
`RemoveTraceCallback` | 16 (0x10) | Exported Function | api-ms-win-eventing-obsolete-l1-1-0.RemoveTraceCallback | 0x00001661
`SetTraceCallback` | 17 (0x11) | Exported Function | api-ms-win-eventing-obsolete-l1-1-0.SetTraceCallback | 0x000016aa
`StartTraceA` | 18 (0x12) | Exported Function | api-ms-win-eventing-legacy-l1-1-0.StartTraceA | 0x000016eb
`StartTraceW` | 19 (0x13) | Exported Function | api-ms-win-eventing-controller-l1-1-0.StartTraceW | 0x00001725
`TraceEvent` | 20 (0x14) | Exported Function | ntdll.EtwLogTraceEvent | 0x00001762
`UnregisterTraceGuids` | 22 (0x16) | Exported Function | api-ms-win-eventing-classicprovider-l1-1-0.UnregisterTraceGuids | 0x000017bd
`WmiSetSingleItemW` | 45 (0x2d) | Exported Function | wmiclnt.WmiSetSingleItemW | 0x00001c85


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


