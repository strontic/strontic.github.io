---
title: TpmTool.exe | 
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

## Runtime Data

### Usage (stdout):
```Batchfile
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

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
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

This utility can be used to get information about the [Trusted Platform Module (TPM)](https://docs.microsoft.com/windows/security/information-protection/tpm/trusted-platform-module-overview).

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
|getdeviceinformation|Displays the basic information of the TPM. The meaning of the information flag values can be found [here](https://docs.microsoft.com/windows/desktop/SecProv/win32-tpm-isreadyinformation#parameters).|
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

TPM-specific error codes are documented [here](https://docs.microsoft.com/windows/desktop/com/com-error-codes-6).

---



MIT License. Copyright (c) 2020 Strontic.


