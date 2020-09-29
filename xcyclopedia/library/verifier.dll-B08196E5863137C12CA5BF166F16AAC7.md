---
title: verifier.dll | Standard application verifier provider dll
excerpt: What is verifier.dll?
---

# verifier.dll 

* File Path: `C:\Windows\SysWOW64\verifier.dll`
* Description: Standard application verifier provider dll

## Hashes

Type | Hash
-- | --
MD5 | `B08196E5863137C12CA5BF166F16AAC7`
SHA1 | `A5EEDE1F86B4DBF8EB920FA4B74C03FFAA19847C`
SHA256 | `2379C89382789238DCAE1433C04EEB861A2AB72955EC67D7554F4889AF2788C3`
SHA384 | `12EF7800FCAF48FEB0698E4AD91398046E848170186BB8417B5F37481C20EA705F066A2FF200A70EDE9408752CE4A8E0`
SHA512 | `ACAB6898ADB05CFD15A60B5248AD4E4C4763EB30BF32A872FE05E2FE29D663E37B7DFC812A5AA66D300AFF3178F045F10A3EA4231DD6B41BFC8BBDFDC6E7C3F4`
SSDEEP | `3072:jCuEydZX7mwKR4L5QprdZvh+h9H7WwfNfZ/CTla1nSrm9W0fQx78qYFQxV3Zsd8+:9EYZXqwKR4lQpr/GDCk3fQxUt9+C`
IMP | `65CF064F0ECE1C0C5140FE3BDAB446BC`
PESHA1 | `9325CBAFC0380758C3AE1C238978870A9EB5B2A5`
PE256 | `11D6869B91C52A8DF70C949724BCE144ED34E51C61989D45C7F74F4C462EF09E`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AVrfAPILookupCallback` | 1 (0x1) | Exported Function | 0x10010c40 | 0x00010c40
`VerifierSetFlags` | 24 (0x18) | Exported Function | 0x1000ef20 | 0x0000ef20
`VerifierSetFaultInjectionProbability` | 23 (0x17) | Exported Function | 0x10007160 | 0x00007160
`VerifierRedirectStopFunctions` | 22 (0x16) | Exported Function | 0x1000dbd0 | 0x0000dbd0
`VerifierQueryRuntimeFlags` | 21 (0x15) | Exported Function | 0x10011de0 | 0x00011de0
`VerifierIsPerUserSettingsEnabled` | 20 (0x14) | Exported Function | 0x10012250 | 0x00012250
`VerifierIsDllEntryActive` | 19 (0x13) | Exported Function | 0x10011f10 | 0x00011f10
`VerifierIsCurrentThreadHoldingLocks` | 18 (0x12) | Exported Function | 0x10011f60 | 0x00011f60
`VerifierIsAddressInAnyPageHeap` | 17 (0x11) | Exported Function | 0x10012030 | 0x00012030
`VerifierGetProviderHelper` | 16 (0x10) | Exported Function | 0x10012280 | 0x00012280
`VerifierGetPropertyValueByName` | 15 (0xf) | Exported Function | 0x10012300 | 0x00012300
`VerifierGetMemoryForDump` | 14 (0xe) | Exported Function | 0x10012100 | 0x00012100
`VerifierGetInfoForException` | 13 (0xd) | Exported Function | 0x10012060 | 0x00012060
`VerifierForceNormalHeap` | 12 (0xc) | Exported Function | 0x100121c0 | 0x000121c0
`VerifierEnumerateResource` | 11 (0xb) | Exported Function | 0x10011d30 | 0x00011d30
`VerifierEnableFaultInjectionTargetRange` | 10 (0xa) | Exported Function | 0x100071c0 | 0x000071c0
`VerifierEnableFaultInjectionExclusionRange` | 9 (0x9) | Exported Function | 0x100073b0 | 0x000073b0
`VerifierDisableFaultInjectionTargetRange` | 8 (0x8) | Exported Function | 0x100072d0 | 0x000072d0
`VerifierDisableFaultInjectionExclusionRange` | 7 (0x7) | Exported Function | 0x10007460 | 0x00007460
`VerifierDestroyRpcPageHeap` | 6 (0x6) | Exported Function | 0x10011ed0 | 0x00011ed0
`VerifierDeleteFreeMemoryCallback` | 5 (0x5) | Exported Function | 0x10011ff0 | 0x00011ff0
`VerifierCreateRpcPageHeap` | 4 (0x4) | Exported Function | 0x10011e70 | 0x00011e70
`VerifierCheckPageHeapAllocation` | 3 (0x3) | Exported Function | 0x10012230 | 0x00012230
`VerifierAddFreeMemoryCallback` | 2 (0x2) | Exported Function | 0x10011fb0 | 0x00011fb0
`VerifierSetRuntimeFlags` | 25 (0x19) | Exported Function | 0x10011d70 | 0x00011d70
`VerifierStopMessage` | 26 (0x1a) | Exported Function | 0x1000dbf0 | 0x0000dbf0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: verifier.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/2379c89382789238dcae1433c04eeb861a2ab72955ec67d7554f4889af2788c3/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\verifier.dll](verifier.dll-ADF0F2F7AB69B71E73895FD23949B318.md) | 32

## Possible Misuse

*The following table contains possible examples of `verifier.dll` being misused. While `verifier.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"description": "Adversary tools may directly use the Windows application programming interface (API) to execute binaries. Functions such as the Windows API CreateProcess will allow programs and scripts to start other processes with proper path and argument parameters. (Citation: Microsoft CreateProcess)\n\nAdditional Windows API calls that can be used to execute binaries include: (Citation: Kanthak Verifier)\n\n* CreateProcessA() and CreateProcessW(),\n* CreateProcessAsUserA() and CreateProcessAsUserW(),\n* CreateProcessInternalA() and CreateProcessInternalW(),\n* CreateProcessWithLogonW(), CreateProcessWithTokenW(),\n* LoadLibraryA() and LoadLibraryW(),\n* LoadLibraryExA() and LoadLibraryExW(),\n* LoadModule(),\n* LoadPackagedLibrary(),\n* WinExec(),\n* ShellExecuteA() and ShellExecuteW(),\n* ShellExecuteExA() and ShellExecuteExW()",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"https://skanthak.homepage.t-online.de/verifier.html"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Adversary tools may directly use the Windows application programming interface (API) to execute binaries. Functions such as the Windows API CreateProcess will allow programs and scripts to start other processes with proper path and argument parameters. (Citation: Microsoft CreateProcess)\n\nAdditional Windows API calls that can be used to execute binaries include: (Citation: Kanthak Verifier)\n\n* CreateProcessA() and CreateProcessW(),\n* CreateProcessAsUserA() and CreateProcessAsUserW(),\n* CreateProcessInternalA() and CreateProcessInternalW(),\n* CreateProcessWithLogonW(), CreateProcessWithTokenW(),\n* LoadLibraryA() and LoadLibraryW(),\n* LoadLibraryExA() and LoadLibraryExW(),\n* LoadModule(),\n* LoadPackagedLibrary(),\n* WinExec(),\n* ShellExecuteA() and ShellExecuteW(),\n* ShellExecuteExA() and ShellExecuteExW()",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"https://skanthak.homepage.t-online.de/verifier.html"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## verifier

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Driver verifier manager.

### Syntax
```
verifier /standard /driver <name> [<name> ...]
verifier /standard /all
verifier [/flags <flags>] [/faults [<probability> [<tags> [<applications> [<minutes>]]]] /driver <name> [<name>...]
verifier [/flags FLAGS] [/faults [<probability> [<tags> [<applications> [<minutes>]]]] /all
verifier /querysettings
verifier /volatile /flags <flags>
verifier /volatile /adddriver <name> [<name>...]
verifier /volatile /removedriver <name> [<name>...]
verifier /volatile /faults [<probability> [<tags> [<applications>]]
verifier /reset
verifier /query
verifier /log <LogFileName> [/interval <seconds>]
```
##### Parameters
|Parameter|Description|
|-------|--------|
|\<flags>|Must be a number in decimal or hexadecimal, combination of bits:<p>-   **Value: description**<br />-   **bit 0:** special pool checking<br />-   **bit 1:** force irql checking<br />-   **bit 2:** low resources simulation<br />-   **bit 3:** pool tracking<br />-   **bit 4:** I/O verification<br />-   **bit 5:** deadlock detection<br />-   **bit 6:** unused<br />-   **bit 7:** DMA verification<br />-   **bit 8:** security checks<br />-   **bit 9:** force pending I/O requests<br />-   **bit 10:** IRP logging<br />-   **bit 11:** miscellaneous checks<p>for example, **/flags 27** is equivalent with **/flags 0x1B**|
|/volatile|Used to change the verifier settings dynamically without restarting the system. Any new settings will be lost when the system is restarted.|
|\<probability>|Number between 1 and 10,000 specifying the fault injection probability. For example, specifying 100 means a fault injection probability of 1% (100/10,000).<p>if this parameter is not specified then the default probability of 6% will be used.|
|\<tags>|Specifies the pool tags that will be injected with faults, separated by space characters. If this parameter is not specified then any pool allocation can be injected with faults.|
|\<applications>|Specifies the image file name of the applications that will be injected with faults, separated by space characters. If this parameter is not specified then low resources simulation can take place in any application.|
|\<minutes>|A positive number specifying the length of the period after rebooting, in minutes, during which no fault injection will occur. If this parameter is not specified then the default length of 8 minutes will be used.|
|/?|Displays help at the command prompt.|

### Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


