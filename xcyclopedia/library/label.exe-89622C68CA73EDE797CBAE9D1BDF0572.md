---
title: label.exe | Disk Label Utility
---

# label.exe 

* File Path: `C:\Windows\SysWOW64\label.exe`
* Description: Disk Label Utility

## Hashes

Type | Hash
-- | --
MD5 | `89622C68CA73EDE797CBAE9D1BDF0572`
SHA1 | `CBDF87518AB0437CCAB8F246E9AB6DC01C876FEF`
SHA256 | `FD11A74C35A7713013474417C89C7DD61E7E3063119FBE655A759BEE0F8731A2`
SHA384 | `2CD09B575724742A7818633B9CB5016008827E996DFC0E96FF6DD81952840570BA9FC983C3F862F276B71FEBAA4F4A70`
SHA512 | `C512F17D19B5B52EAE1063CAC925565A474D05F82B2CD91F5EBF774B5E34C54435D56ED6D88ABE3839BC7A6C0226BD0C627E4144053861BBA6AC578EA17EE907`
SSDEEP | `192:U+RYVDdE+ijhYIS1eHvr5faRvaH8gY0gxiHDLtRkOc1dkYWSCjWgX:UEWp3ISiapaH8gdgxitRbjYWSCjWg`

## Runtime Data

### Usage (stdout):
```cmhg
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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\label.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Label.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `label.exe` being misused. While `label.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt29_grizzly_steppe.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt29_grizzly_steppe.yar) |       $ = "\x0D\x0AVolume label: " | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_Excel4Macro_Sharpshooter.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_Excel4Macro_Sharpshooter.yar) |         // ' 0018     23 LABEL : Cell Value, String Constant - build-in-name 1 Auto_Open | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_win_privesc.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_win_privesc.yar) | 		$s1 = "<Label x:Name=\"lblPort\" Content=\"Port:\"  HorizontalAlignment=\"Left\" Height=\"28\" Margin=\"10,0,0,0\" Width=\"35\"/>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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


