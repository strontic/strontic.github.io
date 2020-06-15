
# attrib.exe 

* File Path: `C:\Windows\SysWOW64\attrib.exe`
* Description: Attribute Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B644D71667E81B89CCAF96AC7C8896D8`
SHA1 | `E8D3ADBE17495E20824F7324BB2BAE4CAC296A35`
SHA256 | `72EEBAE5DAE45019942E5542C77007496374E305C234F110467841F46D381374`
SHA384 | `E992D3064099A3463C4498D3B4A110B23B2CF4AC697C7730F0DD3405FE461E3FC2D81B889D76E66999EB7959748644BC`
SHA512 | `9D471BC78E48B2C524B4697D0A0D9C370963D06793E7B6EE33CDADA799CDF6FE3617866B29406F7447C8AD0EC3E854BC575E1926FB76B276590F4AE5A6E70677`
SSDEEP | `384:unm7jKCZpb32ilXuFAFmEKYVSKvW8tWWj0p0:um7jKC/b3bdVSKXJjW`

## Runtime Data

### Usage (stdout):
```Batchfile
Displays or changes file attributes.

ATTRIB [+R | -R] [+A | -A ] [+S | -S] [+H | -H] [+I | -I] 
       [drive:][path][filename] [/S [/D] [/L]]

  +   Sets an attribute.
  -   Clears an attribute.
  R   Read-only file attribute.
  A   Archive file attribute.
  S   System file attribute.
  H   Hidden file attribute.
  I   Not content indexed file attribute.
  X   No scrub file attribute.
  V   Integrity attribute.  
  [drive:][path][filename]
      Specifies a file or files for attrib to process.
  /S  Processes matching files in the current folder
      and all subfolders.
  /D  Processes folders as well.
  /L  Work on the attributes of the Symbolic Link versus
      the target of the Symbolic Link


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

* Original Filename: ATTRIB.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# attrib

Displays, sets, or removes attributes assigned to files or directories. If used without parameters, **attrib** displays attributes of all files in the current directory.

## Syntax

```
attrib [{+|-}r] [{+|-}a] [{+|-}s] [{+|-}h] [{+|-}i] [<drive>:][<path>][<filename>] [/s [/d] [/l]]
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| `{+|-}r` | Sets (**+**) or clears (**-**) the Read-only file attribute. |
| `{+\|-}a` | Sets (**+**) or clears (**-**) the Archive file attribute. This attribute set marks files that have changed since the last time they were backed up. Note that the **xcopy** command uses archive attributes. |
| `{+\|-}s` | Sets (**+**) or clears (**-**) the System file attribute. If a file uses this attribute set, you must clear the attribute before you can change any other attributes for the file. |
| `{+\|-}h` | Sets (**+**) or clears (**-**) the Hidden file attribute. If a file uses this attribute set, you must clear the attribute before you can change any other attributes for the file. |
| `{+\|-}i` | Sets (**+**) or clears (**-**) the Not Content Indexed file attribute. |
| `[<drive>:][<path>][<filename>]` | Specifies the location and name of the directory, file, or group of files for which you want to display or change attributes.<p>You can use the **?** and **&#42;** wildcard characters in the *filename* parameter to display or change the attributes for a group of files. |
| /s | Applies **attrib** and any command-line options to matching files in the current directory and all of its subdirectories. |
| /d | Applies **attrib** and any command-line options to directories. |
| /l | Applies **attrib** and any command-line options to the Symbolic Link, rather than the target of the Symbolic Link. |
| /? | Displays help at the command prompt. |

## Examples

To display the attributes of a file named News86 that is located in the current directory, type:

```
attrib news86
```

To assign the Read-only attribute to the file named report.txt, type:

```
attrib +r report.txt
```

To remove the Read-only attribute from files in the public directory and its subdirectories on a disk in drive b:, type:

```
attrib -r b:\public\*.* /s
```

To set the Archive attribute for all files on drive a:, and then clear the Archive attribute for files with the .bak extension, type:

```
attrib +a a:*.* & attrib -a a:*.bak
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [xcopy command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/xcopy.md)

---


MIT License. Copyright (c) 2020 Strontic.


