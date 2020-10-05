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

Function Name | Ordinal | Type
-- | -- | --
`VerifierIsAddressInAnyPageHeap` | 17 | Exported Function
`VerifierIsCurrentThreadHoldingLocks` | 18 | Exported Function
`VerifierIsDllEntryActive` | 19 | Exported Function
`VerifierGetMemoryForDump` | 14 | Exported Function
`VerifierGetPropertyValueByName` | 15 | Exported Function
`VerifierGetProviderHelper` | 16 | Exported Function
`VerifierIsPerUserSettingsEnabled` | 20 | Exported Function
`VerifierSetFlags` | 24 | Exported Function
`VerifierSetRuntimeFlags` | 25 | Exported Function
`VerifierStopMessage` | 26 | Exported Function
`VerifierQueryRuntimeFlags` | 21 | Exported Function
`VerifierRedirectStopFunctions` | 22 | Exported Function
`VerifierSetFaultInjectionProbability` | 23 | Exported Function
`VerifierCreateRpcPageHeap` | 4 | Exported Function
`VerifierDeleteFreeMemoryCallback` | 5 | Exported Function
`VerifierDestroyRpcPageHeap` | 6 | Exported Function
`AVrfAPILookupCallback` | 1 | Exported Function
`VerifierAddFreeMemoryCallback` | 2 | Exported Function
`VerifierCheckPageHeapAllocation` | 3 | Exported Function
`VerifierDisableFaultInjectionExclusionRange` | 7 | Exported Function
`VerifierEnumerateResource` | 11 | Exported Function
`VerifierForceNormalHeap` | 12 | Exported Function
`VerifierGetInfoForException` | 13 | Exported Function
`VerifierDisableFaultInjectionTargetRange` | 8 | Exported Function
`VerifierEnableFaultInjectionExclusionRange` | 9 | Exported Function
`VerifierEnableFaultInjectionTargetRange` | 10 | Exported Function


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


