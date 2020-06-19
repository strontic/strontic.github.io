
# label.exe 

* File Path: `C:\WINDOWS\SysWOW64\label.exe`
* Description: Disk Label Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `64C7E8C8727967736F650D6DB522CA93`
SHA1 | `EBC5486BCFA665BA98B26A0A1DEA39286C6E6D41`
SHA256 | `60BF3477AA95EFC425674FE4FD88A3F311E6C23B50712FF42609A25A6A5B40D8`
SHA384 | `554A8B50738102C8E53D3462232DDFAF6235468AB1BEB6FDC47471EE3311C060DAE0643F33D564A798C1278EB96D7A5A`
SHA512 | `4DBD6DB5F4A528C58C592557FBEBDFA7A47509B9E11AC9255443E05D97A0DC7BADB7C8D70705AB4CA81184060D5CDF9F3EA4E69B5D19468C579DAC669F2E535F`
SSDEEP | `192:vIqTD8E5i8hWI0LHvw5pCv30wY0gxinDftd5kRtm1kwWSXjW1gT:FTYyWI1Q30wdgxiRP8NwWSXjWaT`

## Runtime Data

### Usage (stdout):
```Batchfile
Creates, changes, or deletes the volume label of a disk.

LABEL [drive:][label]
LABEL [/MP] [volume] [label]

  drive:          Specifies the drive letter of a drive.
  label           Specifies the label of the volume.
  /MP             Specifies that the volume should be treated as a
                  mount point or volume name.
  volume          Specifies the drive letter (followed by a colon),
                  mount point, or volume name.  If volume name is specified,
                  the /MP flag is unnecessary.

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

* Original Filename: Label.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## label

Creates, changes, or deletes the volume label (that is, the name) of a disk. If used without parameters, the **label** command changes the current volume label or deletes the existing label.

### Syntax

```
label [/mp] [<volume>] [<label>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /mp | Specifies that the volume should be treated as a mount point or volume name. |
| `<volume>` | Specifies a drive letter (followed by a colon), mount point, or volume name. If a volume name is specified, the **/mp** parameter is unnecessary. |
| `<label>` | Specifies the label for the volume. |
| /? | Displays help at the command prompt. |

### Remarks

- Windows displays the volume label and serial number (if it has one) as part of the directory listing.

- An NTFS volume label can be up to 32 characters in length, including spaces. NTFS volume labels retain and display the case that was used when the label was created.

### Examples

To label a disk in drive A that contains sales information for July, type:

```
label a:sales-july
```

To view and delete the current label for drive C, follow these steps:

1. At the command prompt, type:

   ```
   label
   ```

   Output similar to the following should be displayed:

   ```
   Volume in drive C: is Main Disk
   Volume Serial Number is 6789-ABCD
   Volume label (32 characters, ENTER for none)?
   ```

2. Press ENTER. The following prompt should be displayed:

   ```
   Delete current volume label (Y/N)?
   ```

3. Press **Y** to delete the current label, or **N** if you want to keep the existing label.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


