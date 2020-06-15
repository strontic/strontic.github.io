
# rundll32.exe 

* File Path: `C:\Windows\SysWOW64\rundll32.exe`
* Description: Windows host process (Rundll32)
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `111474C61232202B5B588D2B512CBB25`
SHA1 | `E9BF6CAAF1A4A146BF3FB94D986666DECCCD7537`
SHA256 | `D25FF1E6C6460A7F9DE39198D182058C1712726008D187E1953B83ABE977E4A0`
SHA384 | `DDCF8D03C777B8A01E6AC89FA5BA774C4B18FE19C3BC9F6C59F99001B788E5FF8C2CDA8C7800F8307209F01FF68EA954`
SHA512 | `05E3F4A3683E67CB5DD7E434E3619CBF04103B1907A18B04B61F06013FA1F925BA9E279509FB2DF6B738E35D136E44121008980EF33E4F55AB480DD9B440427D`
SSDEEP | `1536:557g1LwvkpZruNJosIB/ROln5IUmDjoXp:5MtjCNysI9ROln5I0`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RUNDLL32.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\rundll32.exe](rundll32.exe-C7645D43451C6D94D87F4D07BDE59C89.md) | 41
[C:\WINDOWS\system32\rundll32.exe](rundll32.exe-F68AF942FD7CCC0E7BAB1A2335D2AD26.md) | 44
[C:\WINDOWS\SysWOW64\rundll32.exe](rundll32.exe-D0432468FA4B7F66166C430E1334DBDA.md) | 44


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


