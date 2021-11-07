---
title: TpmTool.exe | 
excerpt: What is TpmTool.exe?
---

# TpmTool.exe 

* File Path: `C:\Windows\SysWOW64\TpmTool.exe`

## Hashes

Type | Hash
-- | --
MD5 | `3FF2F48C319AD4439EE1BAFC379AEEB3`
SHA1 | `17E61F8C1F66E78DC10B2ADE45AEC3943A9242FF`
SHA256 | `600078577F9773E15EB4148AB54E9B2E56FB9AEF08901110648C69D7A7E43D4A`
SHA384 | `5BE88CD5057F4E785DCBA3F2E18F44820DE4DD0D6B050001DF8D608657D0975EE3C2C214FECCA8379613F2B2DD1181FF`
SHA512 | `D56490152580DBB40E5B51A0768253F3D3E1B8297238F487962EADC94EA2FCB04F9C9F5AA60E18D300E61F985C5AE70DA8180338B59BF702BB3889CE934F4E14`
SSDEEP | `6144:teUjnuiLsZi8SJQfqfjj3nNAiIz9SehCW:tZjB5JQfqfn3yrhCW`
IMP | `97EACDB477A98072815A1CAD741C6F35`
PESHA1 | `FFEC5CC067397315CAA19F69B9FA0CB58E52E388`
PE256 | `A105C5614E87047E44914BA1C2AD1B230A0002BD4AD9F2C9774913CF1C697A67`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\TpmTool.exe |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/600078577f9773e15eb4148ab54e9b2e56fb9aef08901110648c69d7a7e43d4a/detection



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


