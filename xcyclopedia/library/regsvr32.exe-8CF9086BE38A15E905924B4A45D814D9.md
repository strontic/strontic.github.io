
# regsvr32.exe 

* File Path: `C:\Windows\system32\regsvr32.exe`
* Description: Microsoft(C) Register Server
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `8CF9086BE38A15E905924B4A45D814D9`
SHA1 | `EA18DB3E6D9DD28DA80760F1469090E899F6855A`
SHA256 | `00A1CF85C6AB96DF38A4023F0CEE4DF60F62280768FC9C06A235E6D2D644169D`
SHA384 | `5040567E680316B9BE436418F7BE67B6756B38FA1C21B08C1959B44F20C09C999668A000E77A39CE0498A5FF921172EA`
SHA512 | `E0D47C679BB29676FE24F395F1B744C798EADA733692BEC67317AF1958EF556FDDD0C6AC55902898DEC0AAD4F0890A9D1DEA2E153C7D484CD1DB88A1626F9147`
SSDEEP | `384:PHMQ8+gxXO3Ih7uGLQryMqcgQ7zY+ZFFlIfoosWrzLHW:EQ8pk3k7uY2ZuQfFfIfoqL`

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


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


