---
title: TpmTool.exe | 
excerpt: What is TpmTool.exe?
---

# TpmTool.exe 

* File Path: `C:\Windows\SysWOW64\TpmTool.exe`

## Hashes

Type | Hash
-- | --
MD5 | `321E99EF65F37E5F7DFC40D1E95684F5`
SHA1 | `D13F021CA46B00151D870EA36AF7D337FAB1721F`
SHA256 | `807FD9899F1C852B5350DD975B9A9614C5C7CA6BD1FFA71559A8B840BB0CD9AE`
SHA384 | `EB0F8009076780E5A987202B371DE5735F00DA4F86AD8F22ADA391A590FE3DF334C0F09DED477A1725BF325A60DC4005`
SHA512 | `38E6AF2EA64B6C84D5CB4CC320D962E63138DE7A51F62FBDFE1C7BD85D2E70F5E03B374340BF5F06BB98C28648FEB9FCAE186C1C51A34CA797F4CC3D7F269A65`
SSDEEP | `6144:tEHjV/e+Bi+BkSJQfqfDj3n6dyIzWueQCW:tEjRxJQfqfH3KYsCW`
IMP | `97EACDB477A98072815A1CAD741C6F35`
PESHA1 | `3B644EF73733A09286F95A3E2CA140EF8A0372FF`
PE256 | `3FB454844E4C78EDA8600AC833C773D09F018D03401DAA582D59B49B640640F4`

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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/807fd9899f1c852b5350dd975b9a9614c5c7ca6bd1ffa71559a8b840bb0cd9ae/detection



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


