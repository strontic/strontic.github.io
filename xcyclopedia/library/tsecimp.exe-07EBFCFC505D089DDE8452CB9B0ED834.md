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
MD5 | `07EBFCFC505D089DDE8452CB9B0ED834`
SHA1 | `55CDD1691B3B43AC1215C7DACA95E9C6FC12120A`
SHA256 | `29D1216A866F09D88DE8F9825DD62FE27A6981F4116DCEB2EF8376EA701259E6`
SHA384 | `230F47AC244B89572D3BEC45B172DA8DC4BA4A14003B400A23AD3F7E62678A4F7F36FDD410F09F1DC86B6CD4B4C6C1C7`
SHA512 | `63A07B17B9CF6CFC92763C7AC4595026EB9536E9E37AC750FF6461319C184F955311164B40EECDD308322A52A627CB2B15F1945B832B5280A90AF2295B25F16B`
SSDEEP | `384:2ogQnqWCY9Ft7h6weGqrkByS6aE/3nXaWyezEioduMmt/1ULAia6Cj+J0l2Wqr40:/fnqWLBb6k4a05h4MtJfiFC+I0+KC`
IMP | `7AB7329133389F594CF54872DDA762B9`
PESHA1 | `52AD924C8A0873A873FD38647C5319811D8592ED`
PE256 | `5ABE99FCF10686F7F9E14DB767D583FB632C36420A7D9480130E080185880F27`

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

### Child Processes:
csrss.exe wininit.exe

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSECIMP.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/29d1216a866f09d88de8f9825dd62fe27a6981f4116dceb2ef8376ea701259e6/detection/



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


