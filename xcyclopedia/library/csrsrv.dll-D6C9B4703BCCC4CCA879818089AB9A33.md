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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CsrAddStaticServerThread` | 1 (0x1) | Exported Function | 0x0000000180006d10 | 0x00006d10
`CsrUnlockThread` | 30 (0x1e) | Exported Function | 0x0000000180002c00 | 0x00002c00
`CsrUnlockProcess` | 29 (0x1d) | Exported Function | 0x0000000180002ad0 | 0x00002ad0
`CsrUnhandledExceptionFilter` | 28 (0x1c) | Exported Function | 0x0000000180008c40 | 0x00008c40
`CsrShutdownProcesses` | 27 (0x1b) | Exported Function | 0x0000000180002c90 | 0x00002c90
`CsrSetForegroundPriority` | 26 (0x1a) | Exported Function | 0x0000000180009bb0 | 0x00009bb0
`CsrSetBackgroundPriority` | 25 (0x19) | Exported Function | 0x0000000180005dd0 | 0x00005dd0
`CsrServerInitialization` | 24 (0x18) | Exported Function | 0x0000000180003800 | 0x00003800
`CsrRevertToSelf` | 23 (0x17) | Exported Function | 0x0000000180002870 | 0x00002870
`CsrReplyToMessage` | 22 (0x16) | Exported Function | 0x0000000180008e00 | 0x00008e00
`CsrRegisterClientThreadSetup` | 21 (0x15) | Exported Function | 0x0000000180007250 | 0x00007250
`CsrReferenceThread` | 20 (0x14) | Exported Function | 0x00000001800034c0 | 0x000034c0
`CsrQueryApiPort` | 19 (0x13) | Exported Function | 0x0000000180007270 | 0x00007270
`CsrLockThreadByClientId` | 17 (0x11) | Exported Function | 0x0000000180001010 | 0x00001010
`CsrLockProcessByClientId` | 16 (0x10) | Exported Function | 0x0000000180001a60 | 0x00001a60
`CsrLockedReferenceProcess` | 18 (0x12) | Exported Function | 0x00000001800095c0 | 0x000095c0
`CsrIsClientSandboxed` | 15 (0xf) | Exported Function | 0x0000000180009580 | 0x00009580
`CsrImpersonateClient` | 14 (0xe) | Exported Function | 0x00000001800029a0 | 0x000029a0
`CsrGetProcessLuid` | 13 (0xd) | Exported Function | 0x00000001800034d0 | 0x000034d0
`CsrExecServerThread` | 12 (0xc) | Exported Function | 0x0000000180005ec0 | 0x00005ec0
`CsrDestroyThread` | 11 (0xb) | Exported Function | 0x00000001800094f0 | 0x000094f0
`CsrDestroyProcess` | 10 (0xa) | Exported Function | 0x0000000180009460 | 0x00009460
`CsrDereferenceThread` | 9 (0x9) | Exported Function | 0x0000000180003420 | 0x00003420
`CsrDereferenceProcess` | 8 (0x8) | Exported Function | 0x00000001800012c0 | 0x000012c0
`CsrDeferredCreateProcess` | 7 (0x7) | Exported Function | 0x0000000180009430 | 0x00009430
`CsrCreateThread` | 6 (0x6) | Exported Function | 0x0000000180001800 | 0x00001800
`CsrCreateRemoteThread` | 5 (0x5) | Exported Function | 0x0000000180009260 | 0x00009260
`CsrCreateProcess` | 4 (0x4) | Exported Function | 0x0000000180001af0 | 0x00001af0
`CsrConnectToUser` | 3 (0x3) | Exported Function | 0x0000000180006c80 | 0x00006c80
`CsrCallServerFromServer` | 2 (0x2) | Exported Function | 0x0000000180002b10 | 0x00002b10
`CsrValidateMessageBuffer` | 31 (0x1f) | Exported Function | 0x0000000180002730 | 0x00002730
`CsrValidateMessageString` | 32 (0x20) | Exported Function | 0x0000000180008e50 | 0x00008e50


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

*The following table contains possible examples of `csrsrv.dll` being misused. While `csrsrv.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | $s5 = "CSRSRV.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


