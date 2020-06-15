
# rundll32.exe 

* File Path: `C:\WINDOWS\SysWOW64\rundll32.exe`
* Description: Windows host process (Rundll32)
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `D0432468FA4B7F66166C430E1334DBDA`
SHA1 | `F72D978F4D1CA1C435B1164E7617464CC06A9381`
SHA256 | `7D99C80A1249A1EC9AF0F3047C855778B06EA57E11943A271071985AFE09E6C2`
SHA384 | `3D3BD59498B56FD1DE7BE5FE37E80B37EAD210F0B3E7AC45A05A1F68BF31D5B58D8214417725731D21DD97FEE83C144B`
SHA512 | `C6DB867F1A240B0524D5854516D36BEDF220F256CA0BDE5F3529586E83DD52B5ECD4E1E1B89B54F67B117879DEB2D51310E9151B3C29836DE99F7AE89E24DA69`
SSDEEP | `768:pxwG48P6ESdJHC4F8t1gkXDXmekVZRNbSEln5IyYpamDjobj8SSa:n942hIpitWumbZR/ln5IUmDjoXb`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RUNDLL32.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\rundll32.exe](rundll32.exe-C7645D43451C6D94D87F4D07BDE59C89.md) | 44
[C:\WINDOWS\system32\rundll32.exe](rundll32.exe-F68AF942FD7CCC0E7BAB1A2335D2AD26.md) | 54
[C:\Windows\SysWOW64\rundll32.exe](rundll32.exe-111474C61232202B5B588D2B512CBB25.md) | 44


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# rundll32



Loads and runs 32-bit dynamic-link libraries (DLLs). There are no configurable settings for Rundll32. Help information is provided for a specific DLL you run with the **rundll32** command.

You must run the **rundll32** command from an elevated command prompt. To open an elevated command prompt, click **Start**, right-click **Command Prompt**, and then click **Run as administrator**.

## Syntax

```
Rundll32 <DLLname>
```

## Commands

|Parameter|Description|
|---------|-----------|
|[Rundll32 printui.dll,PrintUIEntry](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/rundll32-printui.md)|Displays the printer user interface|

## Remarks

Rundll32 can only call functions from a DLL explicitly written to be called by Rundll32.

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


