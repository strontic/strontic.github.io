---
title: tsecimp.exe | Microsoft Windows(TM) TAPI Security File Importer
excerpt: What is tsecimp.exe?
---

# tsecimp.exe 

* File Path: `C:\Windows\system32\tsecimp.exe`
* Description: Microsoft Windows(TM) TAPI Security File Importer

## Hashes

Type | Hash
-- | --
MD5 | `B16311C5E9AB26B2A4FC539E013EEA35`
SHA1 | `FED55939EE27F58F39464F2CF933CF29C8D7B939`
SHA256 | `03776CBEB4D7274AD68F2F3C03C289C2627F2C61FE6C2787A435DEC7F84BCDCF`
SHA384 | `AAB8943BB04E97C1E427ADA568F576600A0132742BDEC2F4CD1D48BD1997CDB0D514C0F93902635EF974B43A13680F7A`
SHA512 | `2C158DDA50636A4135B109789D74A1666F8F45F760BDC9C206C5B8AE50F01D21FD3F58319FA2EF207C5090198804B2C3D9A8C3134CB1B0B204FF4F3B4DB9CAED`
SSDEEP | `384:Pod7N4fnpBjUbDkagVfAh8aISn0HEPqO4OwZOmotlKz2zTXOxfQ9R5F+Wqv4WRKP:WyY3kfAh89S0kPnZc4eVg5FYbKC`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft Windows(TM) TAPI Security File Importer

The syntax of this command is:

tsecimp {-?|-h |-H} | { [ {-v|-V} | {-u|-U} ] -f filename} | {-d|-D}

-?|-h|-H	To print this help page
-v|-V		Validate the input XML file only
-u|-U		Validate user accounts (slower)
-f filename	The XML file to be processed
-d|-D		Display current configuration


```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSECIMP.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\tsecimp.exe](tsecimp.exe-D5F1A612B5CDD8C197DD8398B06B7E09.md) | 29


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## tsecimp

Imports assignment information from an Extensible Markup Language (XML) file into the TAPI server security file (Tsec.ini). You can also use this command to display the list of TAPI providers and the lines devices associated with each of them, validate the structure of the XML file without importing the contents, and check domain membership.

### Syntax

```
tsecimp /f <filename> [{/v | /u}]
tsecimp /d
```

#### Parameters

| Parameter | Description |
|--|--|
| /f `<filename>` | Required. Specifies the name of the XML file that contains the assignment information that you want to import. |
| /v | Validates the structure of the XML file without importing the information into the Tsec.ini file. |
| /u | Checks whether each user is a member of the domain specified in the XML file. The computer on which you use this parameter must be connected to the network. This parameter might significantly slow performance if you are processing a large amount of user assignment information. |
| /d | Displays a list of installed telephony providers. For each telephony provider, the associated line devices are listed, as well as the addresses and users associated with each line device. |
| /? | Displays help at the command prompt. |

##### Remarks

The XML file from which you want to import assignment information must follow the structure described below:

```xml
<UserList>
  <User>
    <LineList>
      <Line>
```

- `<Userlist element>` - The top element of the XML file.

- `<User element>` - Contains information about a user who is a member of a domain. Each user might be assigned one or more line devices. Additionally, each **User** element might have an attribute named **NoMerge**. When this attribute is specified, all current line device assignments for the user are removed before new ones are made. You can use this attribute to easily remove unwanted user assignments. By default, this attribute is not set. The **User** element must contain a single **DomainUserName** element, which specifies the domain and user name of the user. The **User** element might also contain one **FriendlyName** element, which specifies a friendly name for the user. The **User** element might contain one **LineList** element. If a **LineList** element is not present, all line devices for this user are removed.

- `<LineList element>` - Contains information about each line or device that might be assigned to the user. Each **LineList** element can contain more than one **Line** element.

- `<Line element>` - Specifies a line device. You must identify each line device by adding either an **Address** element or a **PermanentID** element under the **Line** element. For each **Line** element, you can set the **Remove** attribute. If you set this attribute, the user is no longer assigned that line device. If this attribute is not set, the user gains access to that line device. No error is given if the line device is not available to the user.

###### Sample output for /d parameter

This sample output appears after running the **/d** parameter to display the current TAPI configuration. For each telephony provider, the associated line devices are listed, as well as the addresses and users associated with each line device.

```
NDIS Proxy TAPI Service Provider
  Line: WAN Miniport (L2TP)
    Permanent ID: 12345678910

NDIS Proxy TAPI Service Provider
  Line: LPT1DOMAIN1\User1
    Permanent ID: 12345678910

Microsoft H.323 Telephony Service Provider
  Line: H323 Line
    Permanent ID: 123456
    Addresses:
      BLDG1-TAPI32
```

### Examples

To remove all line devices assigned to *User1*, type:

```xml
<UserList>
  <User NoMerge=1>
    <DomainUser>domain1\user1</DomainUser>
  </User>
</UserList>
```

To remove all line devices assigned to *User1*, before assigning one line with address *99999*, type:

```xml
<UserList>
  <User NoMerge=1>
  <DomainUser>domain1\user1</DomainUser>
  <FriendlyName>User1</FriendlyName>
  <LineList>
    <Line>
      <Address>99999</Address>
    </Line>
  </LineList>
  </User>
</UserList>
```

In this example, *User1* has no other line devices assigned, regardless of whether any line devices were assigned previously.

To add one line device for *User1*, without deleting any previously assigned line devices, type:

```xml
<UserList>
  <User>
  <DomainUser>domain1\user1</DomainUser>
  <FriendlyName>User1</FriendlyName>
  <LineList>
    <Line>
      <Address>99999</Address>
    </Line>
  </LineList>
  </User>
</UserList>
```

To add line address *99999* and to remove line address *88888* from *User1's* access, type:

```xml
<UserList>
  <User>
  <DomainUser>domain1\user1</DomainUser>
  <FriendlyName>User1</FriendlyName>
  <LineList>
    <Line>
      <Address>99999</Address>
    </Line>
    <Line Remove=1>
      <Address>88888</Address>
    </Line>
  </LineList>
  </User>
</UserList>
```

To add permanent device *1000* and to remove line *88888* from *User1's* access, type:

```xml
<UserList>
  <User>
  <DomainUser>domain1\user1</DomainUser>
  <FriendlyName>User1</FriendlyName>
  <LineList>
    <Line>
    <PermanentID>1000</PermanentID>
    </Line>
    <Line Remove=1>
    <Address>88888</Address>
    </Line>
  </LineList>
  </User>
</UserList>
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Command shell overview](/previous-versions/windows/it-pro/windows-server-2003/cc737438(v=ws.10))

---



MIT License. Copyright (c) 2020 Strontic.


