---
title: label.exe | Disk Label Utility
excerpt: What is label.exe?
---

# label.exe 

* File Path: `C:\WINDOWS\system32\label.exe`
* Description: Disk Label Utility

## Hashes

Type | Hash
-- | --
MD5 | `1E218CBD5435A738B2706C93C36DB0AF`
SHA1 | `8A97344A3B794AAE4322DF8553802DEB1603E535`
SHA256 | `1B6ECBBC6A81FF26FAD8C3805CFFF9206CD17CE58BB3826520A751B09CB26000`
SHA384 | `7C491C698B729936F5F4E543884751F2F8C173E8038A4E26A46CC3A65538F62334EDC0EF20639EC30A0D9A006A82EFF4`
SHA512 | `F94EE0373173325283CACDD59F509ABE52A12AD763236C225245D474282835DB8BEEB45D7E45CC198F1FB869A2EC101753A6C04B2DAC9BD4C71B7C68BA67BF6A`
SSDEEP | `384:6L+nyKslmD3qvTU8LFveGQqPeuCQBa41poWS5jW:6Lkt3qvTUWFvetAeuCQBhpo`
IMP | `0381B464AC6986B68E15A9101F16060A`
PESHA1 | `2AD68E2AB3735BB204C2B12C826740760992579D`
PE256 | `9F5C28C2E05CF21F41102065097CD6DB032C11D55D1AE2D4EE6EE6CBD5AE34A2`

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
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\label.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Label.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/1b6ecbbc6a81ff26fad8c3805cfff9206cd17ce58bb3826520a751b09cb26000/detection


## Possible Misuse

*The following table contains possible examples of `label.exe` being misused. While `label.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt29_grizzly_steppe.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt29_grizzly_steppe.yar) | $ = "\x0D\x0AVolume label: " | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_Excel4Macro_Sharpshooter.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_Excel4Macro_Sharpshooter.yar) | // ' 0018     23 LABEL : Cell Value, String Constant - build-in-name 1 Auto_Open | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_win_privesc.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_win_privesc.yar) | $s1 = "<Label x:Name=\"lblPort\" Content=\"Port:\"  HorizontalAlignment=\"Left\" Height=\"28\" Margin=\"10,0,0,0\" Width=\"35\"/>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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



MIT License. Copyright (c) 2020-2021 Strontic.


