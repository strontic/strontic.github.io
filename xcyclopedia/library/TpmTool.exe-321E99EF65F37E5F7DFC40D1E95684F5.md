---
title: TpmTool.exe | 
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



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tpmtool

This utility can be used to get information about the [Trusted Platform Module (TPM)](/windows/security/information-protection/tpm/trusted-platform-module-overview).

>[!IMPORTANT]
>Some information relates to prereleased product which may be substantially modified before it's commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.

For examples of how to use this command, see [Examples](#tpmtool_examples).

### Syntax

```
tpmtool /parameter [<arguments>]
```
#### Parameters

|Parameter|Description|
|---------|-----------|
|getdeviceinformation|Displays the basic information of the TPM. The meaning of the information flag values can be found [here](/windows/desktop/secprov/win32-tpm-isreadyinformation#parameters).|
|gatherlogs [output directory path]|Collects TPM logs and places them in the specified directory. If that directory does not exist, it is created. By default, they are placed in the current directory. The possible files generated are: </br>- TpmEvents.evtx</br>- TpmInformation.txt</br>- SRTMBoot.dat</br>- SRTMResume.dat</br>- DRTMBoot.dat</br>- DRTMResume.dat</br>|
|drivertracing [start / stop]|Start / stop collecting TPM driver traces. The trace log, TPMTRACE.etl, will be generated and placed in the current directory.|
|/?|Displays help at the command prompt.|

### <a name=tpmtool_examples></a>Examples

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

### Decoding Error Codes

TPM-specific error codes are documented [here](/windows/desktop/com/com-error-codes-6).

---



MIT License. Copyright (c) 2020 Strontic.


