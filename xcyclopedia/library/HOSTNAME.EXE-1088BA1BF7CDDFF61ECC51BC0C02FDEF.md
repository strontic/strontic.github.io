
# HOSTNAME.EXE 

* File Path: `C:\Windows\system32\HOSTNAME.EXE`
* Description: Hostname APP
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1088BA1BF7CDDFF61ECC51BC0C02FDEF`
SHA1 | `D2090DA5E0490585AD2D859846E9A371B5E9202C`
SHA256 | `B8DA5A3AE4371E63DFD2F468E29CC23AA6F98A6A357A67955996F8F61E58FBA1`
SHA384 | `C88265F17AB6E4592F8AB1D87A80D7BFE27AB41E3FF3942636C1682FA5F55C3DAC3200048C8033FBB611301EC7D90EB3`
SHA512 | `531ED60872D48EE8EBB7B61970219790EB110680D22E04BB68FAF7213BC1A2A1B531DD1B74949175B75E656DBA7FA03A85A2AA82B3C5FE4FC6012E8C3C80F14D`
SSDEEP | `192:Eu4QmRVxfP+NhKgrsK+U7yIxESUHfGGg9GXHNyS9dVW26W:Eu4QmnINnRB7vRAftZNyinW26W`

## Runtime Data

### Usage (stdout):
```Batchfile

Prints the name of the current host.

hostname


```

### Usage (stderr):
```Batchfile
sethostname: Use the Network Control Panel Applet to set hostname.
hostname -s is not supported.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: hostname.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# hostname

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays the host name portion of the full computer name of the computer.

>[!IMPORTANT]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network.

## Syntax

```
hostname
```

### Parameters
| Parameter | Description |
| ------- | -------- |
| /? | Displays help at the command prompt. |

### Examples

To display the name of the computer, type:

```
hostname
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


