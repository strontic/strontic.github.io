---
title: TpmTool.exe | 
excerpt: What is TpmTool.exe?
---

# TpmTool.exe 

* File Path: `C:\Windows\system32\TpmTool.exe`

## Hashes

Type | Hash
-- | --
MD5 | `A44D4A1E84A8587E9C57E297026AD726`
SHA1 | `4C29775B6188A911E7D5E29DB0C84EE2B92D3920`
SHA256 | `490A3E109C39EA9410341DA55995D4BFCEA89F7194A2728D40D4D06C6A7D38BC`
SHA384 | `3EC34801C290141926B2D071E41873CF5E54282444673E1539183A7DBFC15C0B30185CC2B7E8D557EB0F4015EB3FA343`
SHA512 | `D0AC958FA6FF5A2577217A65643493BA56FE4D6ABDBBEE960ECFF2313916ACC05DDAEA20868AC07DC6C6AABD3D15334997198AFE4AC8B18AB44031AC2C5F6C9A`
SSDEEP | `6144:lnuG41spiSsaqE6mqcx/oWc7JdL8ee5gjvu12FD91Xf:leMaagm87Jt8eeyj3P`
IMP | `C878BAE10AF943CC8CE7C40FA3C0AA35`
PESHA1 | `160C706CC15285F595187E46CEE6B394C28A67E0`
PE256 | `AB2E0FDCDA47B1C75B035E1AFBB2C3C91533C337E9689EBD6D20FDB86330FAD4`

## Runtime Data

### Usage (stdout):
```cmhg
Description:
    This utility can be used to get information about the Trusted Platform Module (TPM).
    For up-to-date documentation, please go to https://aka.ms/tpmtool

Syntax:
    tpmtool [parameter] [<arguments>]

Parameters:
    GETDEVICEINFORMATION                     Displays the basic information of the TPM.

    GATHERLOGS [OUTPUT DIRECTORY PATH]       Collects TPM logs and places them in the specified directory.
                                             If path is not specified, will default to current directory.

    DRIVERTRACING [START / STOP]             Start / stop collecting driver traces.

    PARSETTCGLOGS [-VALIDATE]                Displays the parsed TCG logs, and optionally validates all PCRs.

    /?                                       Displays this help message.

Examples:
    tpmtool /?

    tpmtool getdeviceinformation

    tpmtool gatherlogs C:\Users\Public

    tpmtool drivertracing start

    tpmtool drivertracing stop

    tpmtool parsetcglogs

    tpmtool parsetcglogs -validate


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\TpmTool.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/490a3e109c39ea9410341da55995d4bfcea89f7194a2728d40d4d06c6a7d38bc/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tpmtool

This utility can be used to get information about the [Trusted Platform Module (TPM)](/windows/security/information-protection/tpm/trusted-platform-module-overview).

>[!IMPORTANT]
>Some information may relate to the pre-released product, which may be substantially modified before it's commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.

### Syntax

```
tpmtool /parameter [<arguments>]
```

#### Parameters

| Parameter | Description |
|--|--|
| getdeviceinformation | Displays the basic information of the TPM. See the [Win32_Tpm::IsReadyInformation method parameters](/windows/win32/secprov/win32-tpm-isreadyinformation#parameters) article for details about the information flag values. |
| gatherlogs [output directory path] | Collects TPM logs and places them in the specified directory. If that directory doesn't exist, it's created. By default, the log files are placed in the current directory. The possible files generated are:<ul><li>TpmEvents.evtx</li><li>TpmInformation.txt</li><li>SRTMBoot.dat</li><li>SRTMResume.dat</li><li>DRTMBoot.dat</li><li>DRTMResume.dat</li></ul> |
| drivertracing `[start | stop]` | Starts or stops collecting TPM driver traces. The trace log, *TPMTRACE.etl*, is created and placed in the current directory. |
| /? | Displays help at the command prompt. |

### Examples

To display the basic information of the TPM, type:

```
tpmtool getdeviceinformation
```

To collect TPM logs and place them in the current directory, type:

```
tpmtool gatherlogs
```

To collect TPM logs and place them in `C:\Users\Public`, type:

```
tpmtool gatherlogs C:\Users\Public
```

To collect TPM driver traces, type:

```
tpmtool drivertracing start
## Run scenario
tpmtool drivertracing stop
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [COM Error Codes (TPM, PLA, FVE)](/windows/win32/com/com-error-codes-6)

---



MIT License. Copyright (c) 2020-2021 Strontic.


