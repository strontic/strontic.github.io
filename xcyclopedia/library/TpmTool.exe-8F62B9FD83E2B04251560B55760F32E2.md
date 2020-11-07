---
title: TpmTool.exe | 
excerpt: What is TpmTool.exe?
---

# TpmTool.exe 

* File Path: `C:\Windows\system32\TpmTool.exe`

## Hashes

Type | Hash
-- | --
MD5 | `8F62B9FD83E2B04251560B55760F32E2`
SHA1 | `5FBA4F28E840166DE30B742F78152D2F4C09352A`
SHA256 | `8B4C6FC6CF8E6F0FDF56BDEBD7601A67336DBBC085D2D8A09893A6DD78DE05CE`
SHA384 | `705E1A3788DB487DE8FA956A3C83DBD79E86E3959BA7DF65BD6FDD614503D6E41B3B7993854F846892B6B8051363270D`
SHA512 | `DC4A4F705BBB85423B609B0881DA66767C1370DF1B30382FB3D503806CE4B4898861AB5B795696D42201DA24151A117403C9174039A30953A1044D127193D0EE`
SSDEEP | `6144:GsnCbduJJtsDXN2DMc5vP4LmmILq9j4zPJjHf/2BVurHH:GHaADcDKymI+9j47JjV`
IMP | `C878BAE10AF943CC8CE7C40FA3C0AA35`
PESHA1 | `DCBDC07AA5AD99FE03B16B7F782B4FCD1EB129E9`
PE256 | `18C6A1C8155C94906E0A71F517D1DE7359F411532E7EA18C2F4BD7651AE8C3BF`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/8b4c6fc6cf8e6f0fdf56bdebd7601a67336dbbc085d2d8a09893a6dd78de05ce/detection



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



MIT License. Copyright (c) 2020 Strontic.


