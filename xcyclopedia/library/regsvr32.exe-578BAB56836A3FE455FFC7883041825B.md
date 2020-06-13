
# regsvr32.exe 

* File Path: `C:\WINDOWS\system32\regsvr32.exe`
* Description: Microsoft(C) Register Server
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `578BAB56836A3FE455FFC7883041825B`
SHA1 | `8A00AD3F91F4DF913A49C6083F48F9530CCF5326`
SHA256 | `8FFC7F80EFBF746E49F37EA3D140F042CF71EF20B4DA2A8F02688E79295DA11D`
SHA384 | `FA42D9E30D5622FF0678FB62D62C4C93BC24A88BAC9FFE31EEDA057AF48E64529A993DA59EBB43A6AA4B0D09A01BE8BB`
SHA512 | `42BC870B6FC68DC1F9A741540E895AE9905332CD6425D768871E6324E968FAD96DEB1F3D3D3A21E551B0E7BF16E5B43371AA0E92569DAAD71B34AB5EA62A610F`
SSDEEP | `384:gT4ZLMf7AGWMltznSBw4R9dzRK5Ew/j5rmQB/cJq4Ql4UrAuWrNLHWH:gT4ZAfhWMltzSBwqdU5bhmQB/cJq4443`

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

* Original Filename: REGSVR32.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


