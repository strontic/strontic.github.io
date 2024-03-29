﻿---
title: wecutil.exe | Event Collector Command Line Utility
excerpt: What is wecutil.exe?
---

# wecutil.exe 

* File Path: `C:\WINDOWS\SysWOW64\wecutil.exe`
* Description: Event Collector Command Line Utility

## Hashes

Type | Hash
-- | --
MD5 | `4AE279CC2C40E33ED828FCA85C0C06D2`
SHA1 | `BA04AAD6E13B59A8CF5E89BAC32C97124233B642`
SHA256 | `6F4DA7F4CFAFEDA512FF12C9BBBC576F2394A95B2E17F6417F0D0917F3C3A7F2`
SHA384 | `1CF9E617E18CEA4C13B6B96A8A5B42F858A5C3711A799939CCDF6545AABA79DBC28B13DDF7336F4A2390DEE77E6BB9D5`
SHA512 | `980A900AF6C1644C0FB6532179BE6443110CD1DB40FA43619E4DD53BFEE9CFA7DD50AB3049B51DDF825C017EF794E90F28248B3246B582D974F3A5F2966F5599`
SSDEEP | `1536:hq+kyHncKYWut5W65P5uidWZJPGd3pGc7+6g:w+keYWy5X9wiWZEd3pGIE`
IMP | `F141144A8C900E10BC889D966F888141`
PESHA1 | `504D7B942A12D9562F5BB724F289D64285BB0AEE`
PE256 | `CF116197B9E1A85AF67E8DA0EDF21EB06CC5904B2449EBA74753CDFA6BBC0DA4`

## Runtime Data

### Usage (stdout):
```cmhg
Windows Event Collector Utility

Enables you to create and manage subscriptions to events forwarded from remote
event sources that support WS-Management protocol.

Usage:

You can use either the short (i.e. es, /f) or long (i.e. enum-subscription, /format)
version of the command and option names. Commands, options and option values are
case-insensitive.

(ALL UPPER-CASE = VARIABLE)

wecutil COMMAND [ARGUMENT [ARGUMENT] ...] [/OPTION:VALUE [/OPTION:VALUE] ...]

Commands:

es (enum-subscription)               List existent subscriptions.
gs (get-subscription)                Get subscription configuration.
gr (get-subscriptionruntimestatus)   Get subscription runtime status.
ss (set-subscription)                Set subscription configuration.
cs (create-subscription)             Create new subscription.
ds (delete-subscription)             Delete subscription.
rs (retry-subscription)              Retry subscription.
qc (quick-config)                    Configure Windows Event Collector service.

Common options:

/h|? (help)
Get general help for the wecutil program.

wecutil { -help | -h | -? }

For arguments and options, see usage of specific commands:

wecutil COMMAND -?

```

### Usage (stderr):
```cmhg
Command help is not supported. Error = 0x57.
The parameter is incorrect.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\wecutil.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WECUTIL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/6f4da7f4cfafeda512ff12c9bbbc576f2394a95b2e17f6417f0d0917f3c3a7f2/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## wecutil

Enables you to create and manage subscriptions to events that are forwarded from remote computers. The remote computer must support the WS-Management protocol.

> [!IMPORTANT]
> If you receive the message, â€œThe RPC server is unavailable? when you try to run wecutil, you need to start the Windows Event Collector service (wecsvc). To start wecsvc, at an elevated command prompt type `net start wecsvc`.

### Syntax

```command
wecutil [{es | enum-subscription}] [{gs | get-subscription} <Subid> [/f:<Format>] [/uni:<Unicode>]] [{gr | get-subscriptionruntimestatus} <Subid> [<Eventsource> â€¦]] [{ss | set-subscription} [<Subid> [/e:[<Subenabled>]] [/esa:<Address>] [/ese:[<Srcenabled>]] [/aes] [/res] [/un:<Username>] [/up:<Password>] [/d:<Desc>] [/uri:<Uri>] [/cm:<Configmode>] [/ex:<Expires>] [/q:<Query>] [/dia:<Dialect>] [/tn:<Transportname>] [/tp:<Transportport>] [/dm:<Deliverymode>] [/dmi:<Deliverymax>] [/dmlt:<Deliverytime>] [/hi:<Heartbeat>] [/cf:<Content>] [/l:<Locale>] [/ree:[<Readexist>]] [/lf:<Logfile>] [/pn:<Publishername>] [/essp:<Enableport>] [/hn:<Hostname>] [/ct:<Type>]] [/c:<Configfile> [/cun:<Username> /cup:<Password>]]] [{cs | create-subscription} <Configfile> [/cun:<Username> /cup:<Password>]] [{ds | delete-subscription} <Subid>] [{rs | retry-subscription} <Subid> [<Eventsource>â€¦]] [{qc | quick-config} [/q:[<quiet>]]]
```

#### Parameters

| Parameter | Description |
|--|--|
| `{es | enum-subscription}` | Displays the names of all remote event subscriptions that exist. |
| `{gs | get-subscription} <Subid> [/f:<Format>] [/uni:<Unicode>]` | Displays remote subscription configuration information. `<Subid>` is a string that uniquely identifies a subscription. It's the same as the string that was specified in the `<SubscriptionId>` tag of the XML configuration file, which was used to create the subscription. |
| `{gr | get-subscriptionruntimestatus} <Subid> [<Eventsource> â€¦]` | Displays the runtime status of a subscription. `<Subid>` is a string that uniquely identifies a subscription. It's the same as the string that was specified in the `<SubscriptionId>` tag of the XML configuration file, which was used to create the subscription. `<Eventsource>` is a string that identifies a computer that serves as a source of events. It should be a fully qualified domain name, a NetBIOS name, or an IP address. |
| `{ss | set-subscription} <Subid> [/e:[<Subenabled>]] [/esa:<Address>] [/ese:[<Srcenabled>]] [/aes] [/res] [/un:<Username>] [/up:<Password>] [/d:<Desc>] [/uri:<Uri>] [/cm:<Configmode>] [/ex:<Expires>] [/q:<Query>] [/dia:<Dialect>] [/tn:<Transportname>] [/tp:<Transportport>] [/dm:<Deliverymode>] [/dmi:<Deliverymax>] [/dmlt:<Deliverytime>] [/hi:<Heartbeat>] [/cf:<Content>] [/l:<Locale>] [/ree:[<Readexist>]] [/lf:<Logfile>] [/pn:<Publishername>] [/essp:<Enableport>] [/hn:<Hostname>] [/ct:<Type>]` <br>**OR**<br>`{ss | set-subscription /c:<Configfile> [/cun:<Comusername> /cup:<Compassword>]` | Changes the subscription configuration. You can specify the subscription ID and the appropriate options to change subscription parameters, or you can specify an XML configuration file to change subscription parameters. |
| `{cs | create-subscription} <Configfile> [/cun:<Username> /cup:<Password>]` | Creates a remote subscription. `<Configfile>` specifies the path to the XML file that contains the subscription configuration. The path can be absolute or relative to the current directory. |
| `{ds | delete-subscription} <Subid>` | Deletes a subscription and unsubscribes from all event sources that deliver events into the event log for the subscription. Any events already received and logged are not deleted. `<Subid>` is a string that uniquely identifies a subscription. It's the same as the string that was specified in the `<SubscriptionId>` tag of the XML configuration file, which was used to create the subscription. |
| `{rs | retry-subscription} <Subid> [<Eventsource>â€¦]` | Retries to establish a connection and send a remote subscription request to an inactive subscription. Attempts to reactivate all event sources or specified event sources. Disabled sources are not retried. `<Subid>` is a string that uniquely identifies a subscription. It's the same as the string that was specified in the `<SubscriptionId>` tag of the XML configuration file, which was used to create the subscription. `<Eventsource>` is a string that identifies a computer that serves as a source of events. It should be a fully qualified domain name, a NetBIOS name, or an IP address. |
| `{qc | quick-config} [/q:[<Quiet>]]` | Configures the Windows Event Collector service to ensure a subscription can be created and sustained through reboots. This includes the following steps:<ol><li>Enable the ForwardedEvents channel if it is disabled.</li><li>Set the Windows Event Collector service to delay start.</li><li>Start the Windows Event Collector service if it is not running.</li></ol> |

##### Options

| Option | Description |
|--|--|
| /f:`<Format>` | Specifies the format of the information that is displayed. `<Format>` can be XML or Terse. If it's **XML**, the output is displayed in XML format. If it's **Terse**, the output is displayed in name-value pairs. The default is **Terse**. |
| /c:`<Configfile>` | Specifies the path to the XML file that contains a subscription configuration. The path can be absolute or relative to the current directory. This option can only be used with the **/cun** and **/cup** options and is mutually exclusive with all other options. |
| /e:[`<Subenabled>`] | Enables or disables a subscription. `<Subenabled>` can be true or false. The default value of this option is **true**. |
| /esa:`<Address>` | Specifies the address of an event source. `<Address>` is a string that contains a fully qualified domain name, a NetBIOS name, or an IP address, which identifies a computer that serves as a source of events. This option should be used with the **/ese**, **/aes**, **/res**, or **/un** and **/up** options. |
| /ese:[`<Srcenabled>`] | Enables or disables an event source. `<Srcenabled>` can be true or false. This option is allowed only if the **/esa** option is specified. The default value of this option is **true**. |
| /aes | Adds the event source that is specified by the **/esa** option if it is not already a part of the subscription. If the address specified by the **/esa** option is already a part of the subscription, an error is reported. This option is only allowed if the **/esa** option is specified. |
| /res | Removes the event source that is specified by the **/esa** option if it is already a part of the subscription. If the address specified by the **/esa** option is not a part of the subscription, an error is reported. This option is only allowed if **/esa** option is specified. |
| /un:`<Username>` | Specifies the user credential to use with the event source specified by the **/esa** option. This option is only allowed if the **/esa** option is specified. |
| /up:`<Password>` | Specifies the password that corresponds to the user credential. This option is only allowed if the **/un** option is specified. |
| /d:`<Desc>` | Provides a description for the subscription. |
| /uri:`<Uri>` | Specifies the type of the events that are consumed by the subscription. `<Uri>` contains a URI string that is combined with the address of the event source computer to uniquely identify the source of the events. The URI string is used for all event source addresses in the subscription. |
| /cm:`<Configmode>` | Sets the configuration mode. `<Configmode>` can be one of the following strings: **Normal**, **Custom**, **MinLatency** or **MinBandwidth**. The **Normal**, **MinLatency**, and **MinBandwidth** modes set delivery mode, delivery max items, heartbeat interval, and delivery max latency time. The **/dm**, **/dmi**, **/hi** or **/dmlt** options may only be specified if the configuration mode is set to **Custom**. |
| /ex:`<Expires>` | Sets the time when the subscription expires. `<Expires>` should be defined in standard XML or ISO8601 date-time format: `yyyy-MM-ddThh:mm:ss[.sss][Z]`, where *T* is the time separator and *Z* indicates UTC time. |
| /q:`<Query>` | Specifies the query string for the subscription. The format of `<Query>` may be different for different URI values and applies to all sources in the subscription. |
| /dia:`<Dialect>` | Defines the dialect that the query string uses. |
| /tn:`<Transportname>` | Specifies the name of the transport that is used to connect to a remote event source. |
| /tp:`<Transportport>` | Sets the port number that is used by the transport when connecting to a remote event source. |
| /dm:`<Deliverymode>` | Specifies the delivery mode. `<Deliverymode>` can be either pull or push. This option is only valid if the **/cm** option is set to **Custom**. |
| /dmi:`<Deliverymax>` | Sets the maximum number of items for batched delivery. This option is only valid if **/cm** is set to **Custom**. |
| /dmlt:`<Deliverytime>` | Sets the maximum latency in delivering a batch of events. `<Deliverytime>` is the number of milliseconds. This option is only valid if **/cm** is set to Custom. |
| /hi:`<Heartbeat>` | Defines the heartbeat interval. `<Heartbeat>` is the number of milliseconds. This option is only valid if **/cm** is set to **Custom**. |
| /cf:`<Content>` | Specifies the format of the events that are returned. `<Content>` can be Events or RenderedText. When the value is **RenderedText**, the events are returned with the localized strings (such as event description) attached to the event. The default value is **RenderedText**. |
| /l:`<Locale>` | Specifies the locale for delivery of the localized strings in RenderedText format. `<Locale>` is a language and country/region identifier, for example, EN-us. This option is only valid if the **/cf** option is set to **RenderedText**. |
| /ree:[`<Readexist>`] | Identifies the events that are delivered for the subscription. `<Readexist>` can true or false. When the `<Readexist>` is true, all existing events are read from the subscription event sources. When the `<Readexist>` is false, only future (arriving) events are delivered. The default value is **true** for a **/ree** option without a value. If no **/ree** option is specified, the default value is **false**. |
| /lf:`<Logfile>` | Specifies the local event log that is used to store events received from the event sources. |
| /pn:`<Publishername>` | Specifies the publisher name. It must be a publisher that owns or imports the log specified by the **/lf** option. |
| /essp:`<Enableport>` | Specifies that the port number must be appended to the service principal name of the remote service. `<Enableport>` can be true or false. The port number is appended when `<Enableport>` is true. When the port number is appended, some configuration may be required to prevent the access to event sources from being denied. |
| /hn:`<Hostname>` | Specifies the DNS name of the local computer. This name is used by remote event source to push back events and must be used only for a push subscription. |
| /ct:`<Type>` | Sets the credential type for the remote source access. `<Type>` should be one of the following values: **default**, **negotiate**, **digest**, **basic** or **localmachine**. The default value is **default**. |
| /cun:`<Comusername>` | Sets the shared user credential to be used for event sources that do not have their own user credentials. If this option is specified with the **/c** option, UserName and UserPassword settings for individual event sources from the configuration file are ignored. If you want to use a different credential for a specific event source, you should override this value by specifying the **/un** and **/up** options for a specific event source on the command line of another **ss** command. |
| /cup:`<Compassword>` | Sets the user password for the shared user credential. When `<Compassword>` is set to * (asterisk), the password is read from the console. This option is only valid when the **/cun** option is specified. |
| /q:[`<Quiet>`] | Specifies whether the configuration procedure prompts for confirmation. `<Quiet>` can be true or false. If `<Quiet>` is true, the configuration procedure does not prompt for confirmation. The default value of this option is **false**. |

### Examples

To show the contents of a configuration file, type:

```XML
<Subscription xmlns=https://schemas.microsoft.com/2006/03/windows/events/subscription>
<Uri>https://schemas.microsoft.com/wbem/wsman/1/windows/EventLog</Uri>
<!-- Use Normal (default), Custom, MinLatency, MinBandwidth -->
<ConfigurationMode>Normal</ConfigurationMode>
  <Description>Forward Sample Subscription</Description>
  <SubscriptionId>SampleSubscription</SubscriptionId>
  <Query><![CDATA[
    <QueryList>
      <Query Path=Application>
        <Select>*</Select>
      </Query>
    </QueryList>]]
  </Query>
<EventSources>
  <EventSource Enabled=true>
    <Address>mySource.myDomain.com</Address>
    <UserName>myUserName</UserName>
    <Password>*</Password>
  </EventSource>
</EventSources>
<CredentialsType>Default</CredentialsType>
<Locale Language=EN-US></Locale>
</Subscription>
```

To view the output configuration information for a subscription named *sub1*, type:

```command
wecutil gs sub1
```

Example output:

```output
EventSource[0]:
Address: localhost
Enabled: true
Description: Subscription 1
Uri: wsman:microsoft/logrecord/sel
DeliveryMode: pull
DeliveryMaxSize: 16000
DeliveryMaxItems: 15
DeliveryMaxLatencyTime: 1000
HeartbeatInterval: 10000
Locale:
ContentFormat: renderedtext
LogFile: HardwareEvents
```

To display the runtime status of a subscription named sub1, type:

```command
wecutil gr sub1
```

To update the subscription configuration named *sub1* from a new XML file called *WsSelRg2.xml*, type:

```command
wecutil ss sub1 /c:%Windir%system32WsSelRg2.xml
```

To update the subscription configuration named *sub2* with multiple parameters, type:

```command
wecutil ss sub2 /esa:myComputer /ese /un:uname /up:* /cm:Normal
```

To delete a subscription named *sub1*, type:
```
wecutil ds sub1
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


