---
title: wmi.dll | WMI DC and DP functionality
excerpt: What is wmi.dll?
---

# wmi.dll 

* File Path: `C:\Windows\system32\wmi.dll`
* Description: WMI DC and DP functionality

## Hashes

Type | Hash
-- | --
MD5 | `6B25707FB209291415C05781FE6E2C75`
SHA1 | `5C3317FB0DA9DA9561E408399A6A6344363F5737`
SHA256 | `2F26412C0F071B7655405BA3FF543B7B4CED763767DCC7309689253C2082D78A`
SHA384 | `9384279AD8E452FC7DB28823F191B99B882BF6E431BF64BCD4B60A12F6507FF24372B17220987D88D3CFC9829801FC49`
SHA512 | `8861E8494EACEC98022BEA08D233FC4AF7C7C8BD60BA1DCB89A8AB23616DA7C6FA6C37FFE5921CC00146AFC57C6CD35307CD46264DFC8EAA3AB9DBA6B17498AA`
SSDEEP | `96:BMZ/KvusBSHxf/ZgwHghkyPFtXmKAEqmF9u6McEWMiWw:O/KvusBSHxf/6wAhkyyWMiW`
IMP | `n/a`
PESHA1 | `BBB1F8D063CC456D4F6BFFDD3690EA864B853098`
PE256 | `F8607D41BB2381A25807D5AC2B321ADF9D0082F845436F569CBD39A1817DF3AD`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`CloseTrace` | 1 | Exported Function
`WmiDevInstToInstanceNameW` | 25 | Exported Function
`WmiEnumerateGuids` | 26 | Exported Function
`WmiExecuteMethodA` | 27 | Exported Function
`WmiExecuteMethodW` | 28 | Exported Function
`WmiFileHandleToInstanceNameA` | 29 | Exported Function
`WmiFileHandleToInstanceNameW` | 30 | Exported Function
`WmiFreeBuffer` | 31 | Exported Function
`WmiMofEnumerateResourcesA` | 32 | Exported Function
`WmiMofEnumerateResourcesW` | 33 | Exported Function
`WmiNotificationRegistrationA` | 34 | Exported Function
`WmiNotificationRegistrationW` | 35 | Exported Function
`WmiOpenBlock` | 36 | Exported Function
`WmiQueryAllDataA` | 37 | Exported Function
`WmiQueryAllDataW` | 38 | Exported Function
`WmiQueryGuidInformation` | 39 | Exported Function
`WmiQuerySingleInstanceA` | 40 | Exported Function
`WmiQuerySingleInstanceW` | 41 | Exported Function
`WmiSetSingleInstanceA` | 42 | Exported Function
`WmiSetSingleInstanceW` | 43 | Exported Function
`WmiDevInstToInstanceNameA` | 24 | Exported Function
`WmiSetSingleItemA` | 44 | Exported Function
`WmiCloseBlock` | 23 | Exported Function
`TraceEventInstance` | 21 | Exported Function
`ControlTraceA` | 2 | Exported Function
`ControlTraceW` | 3 | Exported Function
`CreateTraceInstanceId` | 4 | Exported Function
`EnableTrace` | 5 | Exported Function
`GetTraceEnableFlags` | 6 | Exported Function
`GetTraceEnableLevel` | 7 | Exported Function
`GetTraceLoggerHandle` | 8 | Exported Function
`OpenTraceA` | 9 | Exported Function
`OpenTraceW` | 10 | Exported Function
`ProcessTrace` | 11 | Exported Function
`QueryAllTracesA` | 12 | Exported Function
`QueryAllTracesW` | 13 | Exported Function
`RegisterTraceGuidsA` | 14 | Exported Function
`RegisterTraceGuidsW` | 15 | Exported Function
`RemoveTraceCallback` | 16 | Exported Function
`SetTraceCallback` | 17 | Exported Function
`StartTraceA` | 18 | Exported Function
`StartTraceW` | 19 | Exported Function
`TraceEvent` | 20 | Exported Function
`UnregisterTraceGuids` | 22 | Exported Function
`WmiSetSingleItemW` | 45 | Exported Function


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/2f26412c0f071b7655405ba3ff543b7b4ced763767dcc7309689253c2082d78a/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\wmi.dll](wmi.dll-1022E62B18BFA25D88754918528C3D04.md) | 97

## Possible Misuse

*The following table contains possible examples of `wmi.dll` being misused. While `wmi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $s1 = "wmi.dll 2>&1" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $x5 = "TempFile = objShell.ExpandEnvironmentStrings(\"%TEMP%\") & \"\\wmi.dll\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


