
# reg.exe 

* File Path: `C:\Windows\system32\reg.exe`
* Description: Registry Console Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `59A22FA6CF85026BB6BC69A1ADD75C50`
SHA1 | `0A7468368C8959F92FB001D28D727EC5F77FB7E2`
SHA256 | `9E28034CE3AEEA6951F790F8997DF44CFBF80BEFF9FB17413DBA317016A716AD`
SHA384 | `E9BF9DE08283460BD7F1DAE9213A7E8F1578346CF49A3E801D0D9FBD8D6769C5246C7E94497AF6E29C48427AB4613EF9`
SHA512 | `E5EB6439F501EED25FCF532F540DFD4DD50F595DACA02D5744A4D5057E855A884CC4B436A51B0F66A102904DC14A4CDBB81881ECA23DF96B66388DF8077C118F`
SSDEEP | `1536:wSZ9WmBPeB8VGCBJyVp/S58/JFWhF6PeH/Yp9q1cmZNp:xpP8sB8Vp/vJFmJ11Z/`

## Runtime Data

### Usage (stdout):
```Batchfile

REG Operation [Parameter List]

  Operation  [ QUERY   | ADD    | DELETE  | COPY    |
               SAVE    | LOAD   | UNLOAD  | RESTORE |
               COMPARE | EXPORT | IMPORT  | FLAGS ]

Return Code: (Except for REG COMPARE)

  0 - Successful
  1 - Failed

For help on a specific operation type:

  REG Operation /?

Examples:

  REG QUERY /?
  REG ADD /?
  REG DELETE /?
  REG COPY /?
  REG SAVE /?
  REG RESTORE /?
  REG LOAD /?
  REG UNLOAD /?
  REG COMPARE /?
  REG EXPORT /?
  REG IMPORT /?
  REG FLAGS /?

```

### Usage (stderr):
```Batchfile
ERROR: Invalid Argument/Option - '-help'.
Type "REG /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# reg



Performs operations on registry subkey information and values in registry entries. The **reg** commands include:

[Reg add](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-add.md)

[Reg compare](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-compare.md)

[Reg copy](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-copy.md)

[Reg delete](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-delete.md)

[Reg export](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-export.md)

[Reg import](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-import.md)

[Reg load](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-load.md)

[Reg query](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-query.md)

[Reg restore](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-restore.md)

[Reg save](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-save.md)

[Reg unload](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reg-unload.md)

Some operations enable you to view or configure registry entries on local or remote computers, while others allow you to configure only local computers. Using **reg** to configure the registry of remote computers limits the parameters that you can use in some operations. Check the syntax and parameters for each operation to verify that they can be used on remote computers

---


MIT License. Copyright (c) 2020 Strontic.


