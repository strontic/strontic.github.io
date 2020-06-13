
# regsvr32.exe 

* File Path: `C:\Windows\SysWOW64\regsvr32.exe`
* Description: Microsoft(C) Register Server
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `56CF190F4143DC68800C4125D6001B07`
SHA1 | `B087C89832B883CB54278BB72538E87303B8557D`
SHA256 | `F72ED4D11C9971A9B7CE0A5681EE35968A6B4CCDC2F2B3A9F3E81418605FA467`
SHA384 | `A3D3E35216785E60E36E6C20EA58BFDC2E1BAA397960C0934236D5E8F0AE8D2801FE91DD7CB6E8EC34EE584DBA97F0B8`
SHA512 | `6FA7AA3543BCC7F40CE72F7642F1379A6CBD6E58E9E3B7CD07EB23D82BDE57D4EDBFCB9D91E48DC17E38463ADB7201E1738C82E42CCF45B4C699BEB36C009111`
SSDEEP | `384:qAXBncnmusWLgL9XJOhFls/CbWrVLHWAK:gmZ9+hfs//LW`

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
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: REGSVR32.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
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


