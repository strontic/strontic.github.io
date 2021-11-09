---
title: TpmTool.exe | 
excerpt: What is TpmTool.exe?
---

# TpmTool.exe 

* File Path: `C:\WINDOWS\system32\TpmTool.exe`

## Hashes

Type | Hash
-- | --
MD5 | `4F14E1A3561B7EEA893D367789E63065`
SHA1 | `9D18785044119DE2B13B5AC1307DB82A5189C0B2`
SHA256 | `E64AB63240D7C36511BF8EEA449C9136DBA5D67737547B5A476D14F4C721BA11`
SHA384 | `65EE7101E7606989E5AFC1A3FE6FC9003A798B4E5C39994C0AECDF5BB2014FDEFEB23AB79D5C25292C6E132EEAF487C0`
SHA512 | `2089A124FF0E85B8A18EFE3E668776F9E56CE282E535E098BA7ECDCB00DC5D636C726D315238CF4676ADA9E097564A2D934545EC3741DCDDDCA9F56DEEA45734`
SSDEEP | `3072:6XpIQTf3XMjJZ6rukr/LOrKjVz1wEd5QWyC9:I+4f3XMjJEDOrKjbwuvyW`
IMP | `34AFA823858FEFAAE57BA2C836A74328`
PESHA1 | `321C631EDE1302A70E29053A3FA656C4D054116C`
PE256 | `DD53D87493098063532260F882FC8109A6BA522CEEF8A16F74BA4334A4C64A5C`

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

    OPTIONALCOMMANDS [ADD / REMOVE]          Add / Remove TpmDiagnostics tool for more Optional Commands.

    /?                                       Displays this help message.

Examples:
    tpmtool /?

    tpmtool getdeviceinformation

    tpmtool gatherlogs C:\Users\Public

    tpmtool drivertracing start

    tpmtool drivertracing stop

    tpmtool optionalcommands add

    tpmtool optionalcommands remove


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\TpmTool.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
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

* VirusTotal Detections: Unknown



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


