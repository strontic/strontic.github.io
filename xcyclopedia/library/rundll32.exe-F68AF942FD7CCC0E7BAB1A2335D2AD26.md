
# rundll32.exe 

* File Path: `C:\WINDOWS\system32\rundll32.exe`
* Description: Windows host process (Rundll32)
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F68AF942FD7CCC0E7BAB1A2335D2AD26`
SHA1 | `7662A8D2F23C3474DEC6EF8E2B0365B0B86714EE`
SHA256 | `11064E9EDC605BD5B0C0A505538A0D5FD7DE53883AF342F091687CAE8628ACD0`
SHA384 | `D6B6C4319CAF90F1B0B72EC9E184D83D2113BAA9774E5ACBA23F596846E4F66A4044345C5B594B1340B7972E04158278`
SHA512 | `7476E4CDDEFF43B7BF713D24A37C406D81D801606D87801DECF23A1A07E80657988CE58832E2875CBFA45E985335347EE5C96A4842E2CE0714A57608D4D0FC34`
SSDEEP | `1536:shapQGfaVjvWogNFhkBrmZZm/7R/ln5IUmDjoX:s+faVLPgfhlATR/ln5I`

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

* Original Filename: RUNDLL32.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


