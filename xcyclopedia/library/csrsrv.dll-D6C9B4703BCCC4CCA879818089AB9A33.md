---
title: csrsrv.dll | Client Server Runtime Process
excerpt: What is csrsrv.dll?
---

# csrsrv.dll 

* File Path: `C:\Windows\system32\csrsrv.dll`
* Description: Client Server Runtime Process

## Hashes

Type | Hash
-- | --
MD5 | `D6C9B4703BCCC4CCA879818089AB9A33`
SHA1 | `A17F4389FA465ACA4088A176DBDBA6DD93F859DD`
SHA256 | `31C66DD46DA26C32D1457471E444E17AE05E222A2E39E895493BBA983E1324DC`
SHA384 | `4792B76D217C1466502D2BAFF2EB00AD6C0B6F72F0BFFB113E09CCBC1B4BAF04091A01BB7F46F1B8D01CAE1ECABFF63F`
SHA512 | `EAE4C69653E6FF0B0B7203A71A7F19760A32CCF7657C2772CC76983AC1F2CDB6381E4DCCC73E0FC6C2B3E9E0AA8F41D5A0BA6EFFDEC64D52F5AD843E98AC25A4`
SSDEEP | `768:vTmZYgpuwyJPVRKfkZPqmr88U3iRWroOgt2xqoGQY4CNgwYKvZwi6ccccccccccc:7mZYg9yr6kZPa3y862xjUgwY8ZD`
IMP | `E969BA43D40752671F6CD4FF029E1563`
PESHA1 | `35794E4E33B36940B04C6920DDBC74BD45650582`
PE256 | `AE531CE00F43921F42B8F00B27046BE9F1EE6CCC2C2E09388CC68B372D9D3B60`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`CsrReplyToMessage` | 22 | Exported Function
`CsrRegisterClientThreadSetup` | 21 | Exported Function
`CsrServerInitialization` | 24 | Exported Function
`CsrRevertToSelf` | 23 | Exported Function
`CsrLockThreadByClientId` | 17 | Exported Function
`CsrLockProcessByClientId` | 16 | Exported Function
`CsrReferenceThread` | 20 | Exported Function
`CsrQueryApiPort` | 19 | Exported Function
`CsrUnlockThread` | 30 | Exported Function
`CsrUnlockProcess` | 29 | Exported Function
`CsrValidateMessageString` | 32 | Exported Function
`CsrValidateMessageBuffer` | 31 | Exported Function
`CsrSetForegroundPriority` | 26 | Exported Function
`CsrSetBackgroundPriority` | 25 | Exported Function
`CsrUnhandledExceptionFilter` | 28 | Exported Function
`CsrShutdownProcesses` | 27 | Exported Function
`CsrCreateThread` | 6 | Exported Function
`CsrCreateRemoteThread` | 5 | Exported Function
`CsrDereferenceProcess` | 8 | Exported Function
`CsrDeferredCreateProcess` | 7 | Exported Function
`CsrCallServerFromServer` | 2 | Exported Function
`CsrAddStaticServerThread` | 1 | Exported Function
`CsrCreateProcess` | 4 | Exported Function
`CsrConnectToUser` | 3 | Exported Function
`CsrImpersonateClient` | 14 | Exported Function
`CsrGetProcessLuid` | 13 | Exported Function
`CsrLockedReferenceProcess` | 18 | Exported Function
`CsrIsClientSandboxed` | 15 | Exported Function
`CsrDestroyProcess` | 10 | Exported Function
`CsrDereferenceThread` | 9 | Exported Function
`CsrExecServerThread` | 12 | Exported Function
`CsrDestroyThread` | 11 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CSRSrv.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/31c66dd46da26c32d1457471e444e17ae05e222a2e39e895493bba983e1324dc/detection/


## Possible Misuse

*The following table contains possible examples of `csrsrv.dll` being misused. While `csrsrv.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | $s5 = "CSRSRV.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


