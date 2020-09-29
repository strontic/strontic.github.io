---
title: verifier.dll | Standard application verifier provider dll
excerpt: What is verifier.dll?
---

# verifier.dll 

* File Path: `C:\Windows\system32\verifier.dll`
* Description: Standard application verifier provider dll

## Hashes

Type | Hash
-- | --
MD5 | `ADF0F2F7AB69B71E73895FD23949B318`
SHA1 | `FFD20FF94C647D49513D0ABB24415E3D72C6BABF`
SHA256 | `C1228EB181AC5FC2B6F8404404D6C5E04D78D7C85C4502D1453EAD4616F21A28`
SHA384 | `FFD46F35DA4168E578B096A5886B530CEBFB1171E19BF16C1334E4C3CDC04DDCB8EF0866AF6CB6A9615B2C697ACABDD9`
SHA512 | `38424BB115151A47BABD7A19E0FD48CC208609BFBF57B63430EAA1CD1AACA08247AE88DE056C244BDA172E648359D8FC3DE98D0D379B3C4B0F34DB4567D35B4D`
SSDEEP | `3072:40j7r+nepRUtySYKWxZRjPYas35zrdbqK4n3tZXUi928Fh5wYFQxV3Zsd8TUnIXT:Bv62RyySYFZFgaSN9Q9ZXUgh5VMnL`
IMP | `8BF144F6FDF48DA3CC6073DD4BD7B5D4`
PESHA1 | `F4110EDAF69CBB861979E51E7D12329D2EE2DCB4`
PE256 | `D574C3EA7CD0B33B38491EE7BB9967726CC09DBEE054E09931B53A9505AFA028`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AVrfAPILookupCallback` | 1 (0x1) | Exported Function | 0x00000001800091e0 | 0x000091e0
`VerifierSetFlags` | 24 (0x18) | Exported Function | 0x0000000180007960 | 0x00007960
`VerifierSetFaultInjectionProbability` | 23 (0x17) | Exported Function | 0x0000000180001ae0 | 0x00001ae0
`VerifierRedirectStopFunctions` | 22 (0x16) | Exported Function | 0x0000000180006760 | 0x00006760
`VerifierQueryRuntimeFlags` | 21 (0x15) | Exported Function | 0x000000018000a360 | 0x0000a360
`VerifierIsPerUserSettingsEnabled` | 20 (0x14) | Exported Function | 0x000000018000a940 | 0x0000a940
`VerifierIsDllEntryActive` | 19 (0x13) | Exported Function | 0x000000018000a440 | 0x0000a440
`VerifierIsCurrentThreadHoldingLocks` | 18 (0x12) | Exported Function | 0x000000018000a480 | 0x0000a480
`VerifierIsAddressInAnyPageHeap` | 17 (0x11) | Exported Function | 0x000000018000a570 | 0x0000a570
`VerifierGetProviderHelper` | 16 (0x10) | Exported Function | 0x000000018000a960 | 0x0000a960
`VerifierGetPropertyValueByName` | 15 (0xf) | Exported Function | 0x000000018000a9e0 | 0x0000a9e0
`VerifierGetMemoryForDump` | 14 (0xe) | Exported Function | 0x000000018000a790 | 0x0000a790
`VerifierGetInfoForException` | 13 (0xd) | Exported Function | 0x000000018000a6f0 | 0x0000a6f0
`VerifierForceNormalHeap` | 12 (0xc) | Exported Function | 0x000000018000a830 | 0x0000a830
`VerifierEnumerateResource` | 11 (0xb) | Exported Function | 0x000000018000a1f0 | 0x0000a1f0
`VerifierEnableFaultInjectionTargetRange` | 10 (0xa) | Exported Function | 0x0000000180001b70 | 0x00001b70
`VerifierEnableFaultInjectionExclusionRange` | 9 (0x9) | Exported Function | 0x0000000180001d40 | 0x00001d40
`VerifierDisableFaultInjectionTargetRange` | 8 (0x8) | Exported Function | 0x0000000180001c60 | 0x00001c60
`VerifierDisableFaultInjectionExclusionRange` | 7 (0x7) | Exported Function | 0x0000000180001e00 | 0x00001e00
`VerifierDestroyRpcPageHeap` | 6 (0x6) | Exported Function | 0x000000018000a400 | 0x0000a400
`VerifierDeleteFreeMemoryCallback` | 5 (0x5) | Exported Function | 0x000000018000a540 | 0x0000a540
`VerifierCreateRpcPageHeap` | 4 (0x4) | Exported Function | 0x000000018000a3c0 | 0x0000a3c0
`VerifierCheckPageHeapAllocation` | 3 (0x3) | Exported Function | 0x000000018000a8a0 | 0x0000a8a0
`VerifierAddFreeMemoryCallback` | 2 (0x2) | Exported Function | 0x000000018000a4c0 | 0x0000a4c0
`VerifierSetRuntimeFlags` | 25 (0x19) | Exported Function | 0x000000018000a320 | 0x0000a320
`VerifierStopMessage` | 26 (0x1a) | Exported Function | 0x0000000180006770 | 0x00006770


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/c1228eb181ac5fc2b6f8404404d6c5e04d78d7c85c4502d1453ead4616f21a28/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\verifier.dll](verifier.dll-B08196E5863137C12CA5BF166F16AAC7.md) | 32

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


