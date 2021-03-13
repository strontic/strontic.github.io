---
title: evntcmd.exe | Event Translator Configuration Tool
excerpt: What is evntcmd.exe?
---

# evntcmd.exe 

* File Path: `C:\Windows\SysWOW64\evntcmd.exe`
* Description: Event Translator Configuration Tool

## Hashes

Type | Hash
-- | --
MD5 | `7BA52DC6D2523EFBC6E5727239781CC8`
SHA1 | `383741FB3605F6DE08025A7BE1A638910B75C8E4`
SHA256 | `DBBE94E27257934CF774DA22095FBF9F8ED373A53F995E7D94902FFACFF5A535`
SHA384 | `6260E1EED1CF5B531B72276A1C882DAC3D76F7823FFA8DCB5F819724D4E8BFFE3A8A3A02A52B44EED83AC21220102125`
SHA512 | `8720ACF8172D60EEFBDA42DAC1A2C4C7AEA32D66AB3C6BB229A9A87278366E25D34525826C11D4D885E3CAD1D87A3AD9EEDF51B5A3486B7082E7B886F5F09833`
SSDEEP | `384:5/Yh/M+Si/mcPYgnaffFOIwKNlHXjTfSQvdqnWgrWo:pYGW/mK9aXYsTjTZdw`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Event To Trap Translator; Configuration Tool 
Copyright (c) Microsoft Corporation.  All rights reserved.

[Wrn03] Command line option '-help' is unknown. Ignored.
Usage:     evntcmd [options] filename [options]
options:   -?,-h        usage help;
           -s sysname   target 'sysname' for configuration;
           -v number    verbose level: 0(silent)-10(detailed);
           -n           don't restart SNMP service on trap changes;

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: eventcmd.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## evntcmd

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Configures the translation of events to traps, trap destinations, or both based on information in a configuration file.

### Syntax

```
evntcmd [/s <computername>] [/v <verbositylevel>] [/n] <filename>
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /s `<computername>` | Specifies, by name, the computer on which you want to configure the translation of events to traps, trap destinations, or both. If you do not specify a computer, the configuration occurs on the local computer. |
| /v `<verbositylevel>` | Specifies which types of status messages appear as traps and trap destinations are configured. This parameter must be an integer between 0 and 10. If you specify 10, all types of messages appear, including tracing messages and warnings about whether trap configuration was successful. If you specify 0, no messages appear. |
| /n | Specifies that the SNMP service should not be restarted if this computer receives trap configuration changes. |
| `<filename>` | Specifies, by name, the configuration file that contains information about the translation of events to traps and trap destinations you want to configure. |
| /? | Displays help at the command prompt. |

##### Remarks

- if you want to configure traps but not trap destinations, you can create a valid configuration file by using Event to Trap Translator, which is a graphical utility. If you have the SNMP service installed, you can start Event to Trap Translator by typing **evntwin** at a command prompt. After you have defined the traps you want, click **Export** to create a file suitable for use with **evntcmd**. You can use Event to Trap Translator to easily create a configuration file and then use the configuration file with **evntcmd** at the command prompt to quickly configure traps on multiple computers.

- The syntax for configuring a trap is as follows:

  ```
  #pragma add <eventlogfile> <eventsource> <eventID> [<count> [<period>]]
  ```

  Where the text following is true:

    - **#pragma** must appear at the beginning of every entry in the file.

    - The parameter **add** specifies that you want to add an event to trap configuration.

    - The parameters **eventlogfile**, **eventsource**, and **eventID** are required, and where **eventlogfile** specifies the file in which the event is recorded, **eventsource** specifies the application that generates the event and **eventID** specifies the unique number that identifies each event.

    To determine what values correspond to each event, start the Event to Trap Translator by typing **evntwin** at a command prompt. Click **Custom**, and then click **edit**. Under **Event Sources**, browse the folders until you locate the event you want to configure, click it, and then click **add**. Information about the event source, the event log file, and the event ID appear under **Source,  Log**, and **Trap specific ID**, respectively.

    - The **count** parameter is optional, and it specifies how many times the event must occur before a trap message is sent. If you don't use this parameter, the trap message is sent after the event occurs once.

    - The **period** parameter is optional, but it requires you to use the **count** parameter. The **period** parameter specifies a length of time (in seconds) during which the event must occur the number of times specified with the **count** parameter before a trap message is sent. If you don't use this parameter, a trap message is sent after the event occurs the number of times specified with the ***count*** parameter, no matter how much time elapses between occurrences.

- The syntax for removing a trap is as follows:

  ```
  #pragma delete <eventlogfile> <eventsource> <eventID>
  ```

  Where the text following is true:

    - **#pragma** must appear at the beginning of every entry in the file.

    - The parameter **delete** specifies that you want to remove an event to trap configuration.

    - The parameters **eventlogfile**, **eventsource**, and **eventID** are required, and where **eventlogfile** specifies the file in which the event is recorded, **eventsource** specifies the application that generates the event and **eventID** specifies the unique number that identifies each event.

    To determine what values correspond to each event, start the Event to Trap Translator by typing **evntwin** at a command prompt. Click **Custom**, and then click **edit**. Under **Event Sources**, browse the folders until you locate the event you want to configure, click it, and then click **add**. Information about the event source, the event log file, and the event ID appear under **Source,  Log**, and **Trap specific ID**, respectively.

- The syntax for configuring a trap destination is as follows:

  ```
  #pragma add_TRAP_DEST <communityname> <hostID>
  ```

  Where the text following is true:

    - **#pragma** must appear at the beginning of every entry in the file.

    - The parameter **add_TRAP_DEST** specifies that you want trap messages to be sent to a specified host within a community.

    - The parameter **communityname** specifies, by name, the community in which trap messages are sent.

    - The parameter **hostID** specifies, by name or IP address, the host to which you want trap messages to be sent.

- The syntax for removing a trap destination is as follows:

  ```
  #pragma delete_TRAP_DEST <communityname> <hostID>
  ```

  Where the text following is true:

    - **#pragma** must appear at the beginning of every entry in the file.

    - The parameter **delete_TRAP_DEST** specifies that you do not want trap messages to be sent to a specified host within a community.

    - The parameter **communityname** specifies, by name, the community to which trap messages shouldn't be sent.

    - The parameter **hostID** specifies, by name or IP address, the host to which you don't want trap messages to be sent.

#### Examples

The following examples illustrate entries in the configuration file for the **evntcmd** command. They are not designed to be typed at a command prompt.

To send a trap message if the Event Log service is restarted, type:

```
##pragma add System Eventlog 2147489653
```

To send a trap message if the Event Log service is restarted twice in three minutes, type:

```
##pragma add System Eventlog 2147489653 2 180
```

To stop sending a trap message whenever the Event Log service is restarted, type:

```
##pragma delete System Eventlog 2147489653
```

To send trap messages within the community named *Public* to the host with the IP address *192.168.100.100*, type:

```
##pragma add_TRAP_DEST public 192.168.100.100
```

To send trap messages within the community named *Private* to the host named *Host1*, type:

```
##pragma add_TRAP_DEST private Host1
```

To stop sending trap messages within the community named *Private* to the same computer on which you are configuring trap destinations, type:

```
##pragma delete_TRAP_DEST private localhost
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


