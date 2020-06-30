---
title: subst.exe | Subst Utility
---

# subst.exe 

* File Path: `C:\WINDOWS\system32\subst.exe`
* Description: Subst Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E34A0B167101310F0949BCA9BC2DD9EE`
SHA1 | `B42B1FA04EECDFD5FEC50AE27721B829AE45F860`
SHA256 | `B79D8342239852F136263B77F2B01577812E977E26974A893DFB285D062999E1`
SHA384 | `936822F6DFF90F07E8860BC1DEB2892D1A9990AC603B1358D79562D4E3F95CA57EF5B1648E55744D327940D784C6035D`
SHA512 | `3B4A99B00F87D8466643F36BE58D5E3328DD61086A6E0D80A9D30A63B883DA2C1AB9273B59091F11406028BCF153825CBE40130096C4F83B56727B74FA9F8BCE`
SSDEEP | `192:y0C9CaXjtP0FY4Qmfoz+jm432gWtKayvOci9Im358VSm353zGGVq/bmZWeGW:y9BPX9ztOR7lvpiuY+z/5ZWeGW`

## Runtime Data

### Usage (stdout):
```Batchfile
Associates a path with a drive letter.

SUBST [drive1: [drive2:]path]
SUBST drive1: /D

  drive1:        Specifies a virtual drive to which you want to assign a path.
  [drive2:]path  Specifies a physical drive and path you want to assign to
                 a virtual drive.
  /D             Deletes a substituted (virtual) drive.

Type SUBST with no parameters to display a list of current virtual drives.

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

* Original Filename: Subst.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\subst.exe](subst.exe-4BFB2ED4A3F52E323F3AE31F3C3A08AC.md) | 52


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## subst



Associates a path with a drive letter. If used without parameters, **subst** displays the names of the virtual drives in effect.



### Syntax

```
subst [<Drive1>: [<Drive2>:]<Path>] 
subst <Drive1>: /d
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|\<Drive1>:|Specifies the virtual drive to which you want to assign a path.|
|[\<Drive2>:]\<Path>|Specifies the physical drive and path that you want to assign to a virtual drive.|
|/d|Deletes a substituted (virtual) drive.|
|/?|Displays help at the command prompt.|

### Remarks

-   The following commands do not work and should not be used on drives that are specified in the **subst** command:

    **chkdsk**

    **diskcomp**

    **diskcopy**

    **format**

    **label**

    **recover**
-   The *Drive1* parameter must be within the range that is specified by the **lastdrive** command. If not, **subst** displays the following error message:

    `Invalid parameter - drive1:`

### <a name="BKMK_examples"></a>Examples

To create a virtual drive Z for the path B:\User\Betty\Forms, type:
```
subst z: b:\user\betty\forms 
```
Instead of typing the full path, you can reach this directory by typing the letter of the virtual drive followed by a colon as follows:
```
z: 
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


