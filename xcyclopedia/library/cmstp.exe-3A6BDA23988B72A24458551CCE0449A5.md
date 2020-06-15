
# cmstp.exe 

* File Path: `C:\Windows\system32\cmstp.exe`
* Description: Microsoft Connection Manager Profile Installer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3A6BDA23988B72A24458551CCE0449A5`
SHA1 | `51BB20013415F3904DB6A0D9E58847D7F6FF48F6`
SHA256 | `3D95ECACACF64066AC25B17E8A458003A000BAE45F5A70D660AFB7A8D88D4F00`
SHA384 | `76725F90B98C600BE5A464D4278CC5F20CB5601FF9985F7F5CC823B459E01A43C84A7A2A428A94768B8017FC7F6F0009`
SHA512 | `BE28D4DE895A556777AA12C6C937290F3BE342CFFF8C1B95C1BA382B35AC3097777A774F6EF39FD2A32BA7FFC9B32E356C0B5C8C5EB6541C8CBE2180F0D23753`
SSDEEP | `1536:j+s9y5VG7d4FSLBnQz9h+88dEHsh2MqoaoRuE1AERu1/87BMVRXlW15x0/AyS:SIyi7WS1kymsh2/oBuE1A11k7BMVRXYr`

## Runtime Data

### Usage (stdout):
```Batchfile

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

* Original Filename: CMSTP.EXE.MUI
* Product Name: Microsoft(R) Connection Manager
* Company Name: Microsoft Corporation
* File Version: 7.2.14393.0 (rs1_release.160715-1616)
* Product Version: 7.2.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# cmstp

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Installs or removes a Connection Manager service profile. Used without optional parameters, **cmstp** installs a service profile with default settings appropriate to the operating system and to the user's permissions.

## Syntax

Syntax 1 - This is the typical syntax used in a custom installation application. To use this syntax, you must run **cmstp** from the directory that contains the `<serviceprofilefilename>.exe` file.

```
<serviceprofilefilename>.exe /q:a /c:cmstp.exe <serviceprofilefilename>.inf [/nf] [/s] [/u]
```

Syntax 2
```
cmstp.exe [/nf] [/s] [/u] [drive:][path]serviceprofilefilename.inf
```

#### Parameters
| Parameter | Description |
| --------- | ----------- |
| `<serviceprofilefilename>.exe` | Specifies, by name, the installation package that contains the profile that you want to install.<p>Required for Syntax 1, but not valid for Syntax 2. |
| /q:a | Specifies that the profile should be installed without prompting the user. The verification message that the installation has succeeded will still appear.<p>Required for Syntax 1, but not valid for Syntax 2. |
| [drive:][path] `<serviceprofilefilename>.inf` | Required. Specifies, by name, the configuration file that determines how the profile should be installed.<p>The [drive:][path] parameter isn't valid for Syntax 1. |
| /nf | Specifies that the support files should not be installed. |
| /s | Specifies that the service profile should be installed or uninstalled silently (without prompting for user response or displaying verification message). This is the only parameter that you can use in combination with **/u**.|
| /u | Specifies that the service profile should be uninstalled. |
| /? | Displays help at the command prompt. |

## Examples

To install the *fiction* service profile without any support files, type:

```
fiction.exe /c:cmstp.exe fiction.inf /nf
```

To silently install the *fiction* service profile for a single user, type:

```
fiction.exe /c:cmstp.exe fiction.inf /s /su
```

To silently uninstall the *fiction* service profile, type:

```
fiction.exe /c:cmstp.exe fiction.inf /s /u
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


