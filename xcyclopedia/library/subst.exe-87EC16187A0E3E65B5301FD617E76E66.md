
# subst.exe 

* File Path: `C:\Windows\SysWOW64\subst.exe`
* Description: Subst Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `87EC16187A0E3E65B5301FD617E76E66`
SHA1 | `F96E8998739A6347930F3B5B3A343D8FAC4BDB2F`
SHA256 | `3E090E518681034AA40E6A194E798B0B1A6691848746EA1D345441C575C73DAC`
SHA384 | `2DCB390A645C3D0C094EF9BD5DD7CA25F15ACFA0D82B5A9A76278F09306F24BC771602D47726E6B128512FC1CFB525C3`
SHA512 | `BA55E84BA4D2971BBB81ED3CBBCB669BB222F847C383D05155FAC516315B38A66180A374D59DF25A43443770D09131D66378C3521F55CA70EE7B6CDD9C93A3F1`
SSDEEP | `192:evlCujcdfYwuAXRBh4CtyTgModOGte6G/fvkxWsGWx6OBme:oUYcZYwzXR/EgMKOKL/xWsGWgOBme`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Subst.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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


