
# reg.exe 

* File Path: `C:\WINDOWS\system32\reg.exe`
* Description: Registry Console Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `601BDDF7691C5AF626A5719F1D7E35F1`
SHA1 | `EB3B03616EEE42F16D0703F64DE23E7E34FE8524`
SHA256 | `4ED2A27860FA154415F65452FF1F94BD6AF762982E2F3470030C504DC3C8A354`
SHA384 | `CCDE9D3BF859B15DD9243167C1AFDCA7B5CC3409C8CB787C41A3E0477A5FC00F93E641F8843D975B591EE2FAB74B584F`
SHA512 | `8DDD3DB48E6CE1F718DA96D9714690C8ACC3EBA15AC04AC0D825AFDEE2B3FFD0F51F9E75330DF7A0C887C74A01EDA66C2CC9858A257D4FCE4F7E05C50E301563`
SSDEEP | `1536:t/DAShu556JjYthdak1IGvA5g9ltrPibxN2sfrbCwXmnvyE1:pAVjEjY7dak1nvftjQPDbVXGvy0`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


