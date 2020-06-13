
# reset.exe 

* File Path: `C:\WINDOWS\system32\reset.exe`
* Description: Remote Desktop Services Reset Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `15D84EF11876BB1264257B0CC60C7B62`
SHA1 | `283740B7B2E90B6579E60DEF9FB23F25CDB9A243`
SHA256 | `0BCB46894104BC7ED6A6E5062BB340A0707D8282AB75387FBF6F3FBEB0696A97`
SHA384 | `191195E6E0A641CFE109D4A85C3BC296B2A76099FCCB5B23E58AD71C80D6A6F6082D591B7AA4FE0AF0201FE23012FBD2`
SHA512 | `332ADE1C24566C4560F3759B5C037829B37D843599DC2802AA28B05A18B4F81EF3A8481B4489268A3DF92C9166E4660252D8F0C9BCC2FABB77093DA7FE96B2E2`
SSDEEP | `384:oWe6KXLaxy2eeTX94d9NtGHK2aJSWmgW:Re2etd3Wk6`

## Runtime Data

### Usage (stdout):
```Batchfile
RESET { SESSION }

```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
RESET { SESSION }

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reset.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# reset



Resets DiskShadow.exe to the default state. **Reset** is especially useful in separating compound DiskShadow operations such as **create**, **import**, **backup**, or **restore**.

## Syntax

```
reset
```

## Remarks

-   When you use the **reset** command, you lose state from commands such as **add**, **set**, **load**, or **writer**. **Reset** also releases IVssBackupComponent interfaces and loses non-persistent shadow copies.

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


