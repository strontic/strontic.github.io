---
title: tsecimp.exe | Microsoft Windows(TM) TAPI Security File Importer
excerpt: What is tsecimp.exe?
---

# tsecimp.exe 

* File Path: `C:\windows\system32\tsecimp.exe`
* Description: Microsoft Windows(TM) TAPI Security File Importer

## Hashes

Type | Hash
-- | --
MD5 | `1708E5053162625F9C5F244492BDB450`
SHA1 | `38A9EF7737E63FE1C563FCD108AAB79A1ED6F441`
SHA256 | `69DAC0F15CC877B1D3E85EFD57D486A246B839DF0D5B4CE49AE5190C78349BFE`
SHA384 | `9817F929E2F2DD9C8D3D5FB3DE53D2AC95CE0605F6FAEBFDD19F3418EA2FF1386EA382C31715D5E89FCFB85F81AC9A8F`
SHA512 | `F4B72FC582370E017FF3DFBFCD561D128841AEC1F8CD4424A47EF3DB6B297341C17C93BB012FC526AADD54689FADAEC1AD0B6712593D00D50D07FB31EC7F2C6C`
SSDEEP | `768:+2GbNkoJdmQyHSYVY2Q8f727OmQ5PyjGKC:+2Gw9HSkDRD2KnPyjGKC`

## Signature

* Status: The file C:\windows\system32\tsecimp.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: TSECIMP.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




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



MIT License. Copyright (c) 2020-2021 Strontic.


