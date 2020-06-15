
# reset.exe 

* File Path: `C:\Windows\system32\reset.exe`
* Description: Remote Desktop Services Reset Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `CC1B793D89733AA1D7E596EB8BD950C4`
SHA1 | `969C4270DD9830938DEA6F08065F1924F2C97305`
SHA256 | `8B669A5EF2A3CCF1C0F2DDE0A0D6A0C4EA935AFE582CA46F10C5B5E2A7DF5BD9`
SHA384 | `01ADDB166B88604EBAD59894E1779EA4C2E797C677C642C0FD1D8EAA1730746D930C4CDDE4A6725C9117A0AC259B0BE8`
SHA512 | `07ABE56E9F7808A6DFE32E59336F9F9760BF20B331CFEB742430F3A044A19A1D6B0C702EB53AA0B616A478654F27DD268F16C039DFF139FBF69BA6A96D0968AC`
SSDEEP | `384:H6LwPUBkzy6g9kq/LD2jecv2PNsr+YaWEgW:HH/mLOMYY`

## Runtime Data

### Usage (stdout):
```Batchfile
RESET { SESSION }

```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
RESET { SESSION }

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reset.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# reset



Resets DiskShadow.exe to the default state. **Reset** is especially useful in separating compound DiskShadow operations such as **create**, **import**, **backup**, or **restore**.

## Syntax

```
reset
```

## Remarks

-   When you use the **reset** command, you lose state from commands such as **add**, **set**, **load**, or **writer**. **Reset** also releases IVssBackupComponent interfaces and loses non-persistent shadow copies.

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


