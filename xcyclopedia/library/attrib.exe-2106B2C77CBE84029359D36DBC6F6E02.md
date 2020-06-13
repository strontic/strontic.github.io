
# attrib.exe 

* File Path: `C:\WINDOWS\system32\attrib.exe`
* Description: Attribute Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `2106B2C77CBE84029359D36DBC6F6E02`
SHA1 | `C2000CF2D5E0F3FD5158CAFC6E5717009371444E`
SHA256 | `96F9A8BDFE0DC0452E64313A77A82C9460D31F5DD59C7EC676A9F83BD0EA8CD9`
SHA384 | `C384549AE37A5F95D87B910049F50A7D73A272B226CE8CD94D120512F43813BC2571CB2BE0234432B40C1E68B66E1636`
SHA512 | `E39BC95E4D3F6BC8544411024EBE0851DEE351B56BC7812C4873C2737543F5CDF7EAA997DB1FEE381C02503C3E1C5C4CD0EC08E8A29EE0B82BA726F9465A6D09`
SSDEEP | `384:SvgQdcnvPVHLjGR5xq/n74AbYDb4wK1gzV3AcUyBTuxFf+HW+tW:cgjn1fGR5oj4u84wK1I4yiFf+x`

## Runtime Data

### Usage (stdout):
```Batchfile
Displays or changes file attributes.

ATTRIB [+R | -R] [+A | -A] [+S | -S] [+H | -H] [+O | -O] [+I | -I] [+X | -X] [+P | -P] [+U | -U]
       [drive:][path][filename] [/S [/D]] [/L]

  +   Sets an attribute.
  -   Clears an attribute.
  R   Read-only file attribute.
  A   Archive file attribute.
  S   System file attribute.
  H   Hidden file attribute.
  O   Offline attribute.
  I   Not content indexed file attribute.
  X   No scrub file attribute.
  V   Integrity attribute.
  P   Pinned attribute.
  U   Unpinned attribute.
  B   SMR Blob attribute.
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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ATTRIB.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


