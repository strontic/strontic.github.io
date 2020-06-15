
# regsvr32.exe 

* File Path: `C:\WINDOWS\SysWOW64\regsvr32.exe`
* Description: Microsoft(C) Register Server
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EB3B90B6989227F590BB36356DF96A30`
SHA1 | `6E5498E81964DBFEBA127AE8685FC151D10B115F`
SHA256 | `F80B4224C670E76E05A70CC5403818B11C7A4CA10542A1F9B5D935E4FCA08579`
SHA384 | `798594D5608B28A6080961913D2FF6CE93B0785484AA36E6C942253789490A24B5533793BE7934444503F83285CB1431`
SHA512 | `BCE3888459190F1FBE0653BA487017CDAF38655F87327CCCDD60DCF816C3E89052A0F4CF40CFC893EC6FB21DA14E7A540EC500300DF9C7B996128271B38AEF01`
SSDEEP | `384:WNLS9nre+ixbSfsLeDGpvg43kUskgxQl4XxAuWrNLHWM:WLIrsxb0Rx44XMLF`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: REGSVR32.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\regsvr32.exe](regsvr32.exe-578BAB56836A3FE455FFC7883041825B.md) | 33


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# regsvr32



Registers .dll files as command components in the registry.



## Syntax

```
regsvr32 [/u] [/s] [/n] [/i[:cmdline]] <DllName>
```

### Parameters

|Parameter|Description|
|---------|-----------|
|/u|Unregisters server.|
|/s|Runs **Regsvr32** without displaying messages.|
|/n|Runs **Regsvr32** without calling **DllRegisterServer**. (Requires the **/i** parameter.)|
|/i:\<cmdline>|Passes an optional command-line string (*cmdline*) to **DllInstall**. If you use this parameter in conjunction with the **/u** parameter, it calls **DllUninstall**.|
|\<DllName>|The name of the .dll file that will be registered.|
|/?|Displays help at the command prompt.|

## Examples

To register the .dll for the Active Directory Schema, type:
```
regsvr32 schmmgmt.dll
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


