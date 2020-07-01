---
title: subst.exe | Subst Utility
---

# subst.exe 

* File Path: `C:\windows\system32\subst.exe`
* Description: Subst Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `702D9B0C494D91FA4E5C2078294A99F3`
SHA1 | `080F82E31AC2B96B8AD5CEB00C0899E599AA29BC`
SHA256 | `B52B8C9CCA6B8051E5B81AA16B51EB56A7800B4805F09D599570F87DD3C0A6C5`
SHA384 | `1880A7B76BC5F4EB3C059BF4A2FDA9FA85148FF94D5B2EB75847A0463B84F7F9EBCA79AE9ED2DEF5CD12EFCA98EB3481`
SHA512 | `D73DD7C5946F7A1FA2CC25687BBAD8B56D9776643046B010828C901691A54F183B3F39A09A508D43EC35CE81074C161FD6EFE5B7A4A4611CCF24CCACC89D7F0C`
SSDEEP | `384:Yem39Csw5u1xuhp7OOGdvdMZe/NHOV5WxGW:5mtCNu1xuDKOGdvdb/FOVc`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\subst.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Subst.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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


