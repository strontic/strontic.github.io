---
title: mode.com | DOS Device MODE Utility
excerpt: What is mode.com?
---

# mode.com 

* File Path: `C:\Windows\SysWOW64\mode.com`
* Description: DOS Device MODE Utility

## Hashes

Type | Hash
-- | --
MD5 | `1EAE674ADD901E72BC5D374FDF37C240`
SHA1 | `D6F5595B17F7098986F5AF1A84C54BBF5A7D7B57`
SHA256 | `C3F6F6F1C310D0D61C2D07950FB2BD23D2B8A979E52D94CB623435AAED30EC60`
SHA384 | `06D64A52B0BE77BD3BF26ABE5A64024E15376130468C519906775640868C6B75BE2302E515C1A62D2AB450FD2E4A01E4`
SHA512 | `C92003873D760FA2D42C97FD1225A2635A62953D465B55EE843B13AC5A3D3910DE2C0C835A6CD16B6545FF3FCA834284F9F0FC8BDDFE62ED0D5892B19543CF70`
SSDEEP | `768:L66Bizvhg4fwX0Bz4Ev10tpOJ74sI2e0KEb:L66cH6k10tpOascLEb`
IMP | `CDF5181B2C7C446CFB494CA9F7058BBE`
PESHA1 | `9D16F9F9FA7E259EE867BB326EA0B735B8481552`
PE256 | `D540F383A9FC9C4B44F0AFA1EC75525AAE9A1F62FD36F546D5B49D8B2D338A2C`

## Runtime Data

### Usage (stdout):
```cmhg
Configures system devices.

Serial port:       MODE COMm[:] [BAUD=b] [PARITY=p] [DATA=d] [STOP=s]
                                [to=on|off] [xon=on|off] [odsr=on|off]
                                [octs=on|off] [dtr=on|off|hs]
                                [rts=on|off|hs|tg] [idsr=on|off]

Device Status:     MODE [device] [/STATUS]

Redirect printing: MODE LPTn[:]=COMm[:]

Select code page:  MODE CON[:] CP SELECT=yyy

Code page status:  MODE CON[:] CP [/STATUS]

Display mode:      MODE CON[:] [COLS=c] [LINES=n]

Typematic rate:    MODE CON[:] [RATE=r DELAY=d]

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\mode.com |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MODE.COM
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/c3f6f6f1c310d0d61c2d07950fb2bd23d2b8a979e52d94cb623435aaed30ec60/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## mode

Displays system status, changes system settings, or reconfigures ports or devices. If used without parameters, **mode** displays all the controllable attributes of the console and the available COM devices.

### Serial port

Configures a serial communications port and sets the output handshake.

#### Syntax

```
mode com<m>[:] [baud=<b>] [parity=<p>] [data=<d>] [stop=<s>] [to={on|off}] [xon={on|off}] [odsr={on|off}] [octs={on|off}] [dtr={on|off|hs}] [rts={on|off|hs|tg}] [idsr={on|off}]
```

##### Parameters

| Parameter  | Description |
| ---------- | ----------- |
| `com<m>[:]` | Specifies the number of the async Prncnfg.vbshronous communications port. |
| `baud=<b>`  | Specifies the transmission rate in bits per second. The valid values include:<ul><li>**11** - 110 baud</li><li>**15** - 150 baud</li><li>**30** - 300 baud</li><li>**60** - 600 baud</li><li>**12** - 1200 baud</li><li>**24** - 2400 baud</li><li>**48** - 4800 baud</li><li>**96** - 9600 baud</li><li>**19** - 19,200 baud</li></ul> |
| `parity=<p>` | Specifies how the system uses the parity bit to check for transmission errors. The valid values include:<ul><li>**n** - none</li><li>**e** - even (default value)</li><li>**o** - odd</li><li>**m** - mark</li><li>**s** - space</li></ul>Not all devices support using the **m** or **s** parameters. |
| `data=<d>` | Specifies the number of data bits in a character. Valid values range from **5** through **8**. The default value is **7**. Not all devices support the values **5** and **6**. |
| `stop=<s>` | Specifies the number of stop bits that define the end of a character: **1**, **1.5**, or **2**. If the baud rate is **110**, the default value is **2**. Otherwise, the default value is **1**. Not all devices support the value **1.5**. |
| `to={on | off}` | Specifies whether the device uses infinite time out processing. The default value is **off**. Turning this option **on** means that the device will never stop waiting to receive a response from a host or client computer. |
| `xon={on | off}` | Specifies whether the system allows the XON/XOFF protocol. This protocol provides flow control for serial communications, enhancing reliability, but reducing performance. |
| `odsr={on | off}` | Specifies whether the system turns on the Data Set Ready (DSR) output handshake. |
| `octs={on | off}` | Specifies whether the system turns on the Clear to Send (CTS) output handshake. |
| `dtr={on | off | hs}` | Specifies whether the system turns on the Data Terminal Ready (DTR) output handshake. Setting this value to **on** mode, provides a constant signal to show the terminal is ready to send data. Setting this value to **hs** mode provides a handshake signal between the two terminals. |
| `rts={on | off | hs | tg}` | Specifies whether the system turns on the Request to Send (RTS) output handshake. Setting this value to **on** mode, provides a constant signal to show the terminal is ready to send data. Setting this value to **hs** mode provides a handshake signal between the two terminals. Setting this value to **tg** mode provides a way to toggle between ready and not ready states. |
| `idsr={on | off}` | Specifies whether the system turns on the DSR sensitivity. You must turn this option on to use DSR handshaking.
| /? | Displays help at the command prompt. |

### Device status

Displays the status of a specified device. If used without parameters, **mode** displays the status of all devices installed on your system.

#### Syntax

```
mode [<device>] [/status]
```

##### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<device>` | Specifies the name of the device for which you want to display the status. Standard names include, LPT1: through LPT3:, COM1: through COM9:, and CON. |
| /status | Requests the status of any redirected parallel printers. You can also use **/sta** as an abbreviated version of this command. |
| /? | Displays help at the command prompt. |

### Redirect printing

Redirects printer output. You must be a member of the Administrators group to redirect printing.

> [!NOTE]
To set up your system so that it sends parallel printer output to a serial printer, you must use the **mode** command twice. The first time, you must use **mode** to configure the serial port. The second time, you must use **mode** to redirect parallel printer output to the serial port you specified in the first **mode** command.

#### Syntax

```
mode LPT<n>[:]=COM<m>[:]
```

##### Parameters

| Parameter | Description |
| --------- | ----------- |
| LPT`<n>`[:] | Specifies the number of the LPT to configure. Typically, this means providing a value from **LTP1: through LTP3:**, unless your system includes special parallel port support. This parameter is required.|
| COM`<m>`[:] | Specifies the COM port to configure. Typically, this means providing a value from **COM1: through COM9:**, unless your system has special hardware for additional COM ports. This parameter is required. |
| /? | Displays help at the command prompt.|

##### Examples

To redirect a serial printer that operates at 4800 baud with even parity, and is connected to the COM1 port (the first serial connection on your computer), type:

```
mode com1 48,e,,,b
mode lpt1=com1
```

To redirect parallel printer output from LPT1 to COM1, and then to print a file using LPT1, type the following command before you print the file:

```
mode lpt1
```

This command prevents the redirection the file from LPT1 to COM1.

### Select code page

Configures or queries the code page info for a selected device.

#### Syntax

```
mode <device> codepage select=<yyy>
mode <device> codepage [/status]
```

##### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<device>` |Specifies the device for which you want to select a code page. CON is the only valid name for a device. This parameter is required. |
| codepage | Specifies which code page to use with the specified device. You can also use **cp** as an abbreviated version of this command. This parameter is required. |
| select=`<yyy>` | Specifies the number of the code page to use with the device. The supported code pages, by country/region or language, include:<ul><li>**437:** United States</li><li>**850:** Multilingual (Latin I)</li><li>**852:** Slavic (Latin II)</li><li>**855:** Cyrillic (Russian)</li><li>**857:** Turkish</li><li>**860:** Portuguese</li><li>**861:** Icelandic</li><li>**863:** Canadian-French</li><li>**865:** Nordic</li><li>**866:** Russian</li><li>**869:** Modern Greek</li></ul> This parameter is required. |
| /status | Displays the numbers of the current code pages selected for the specified device. You can also use **/sta** as an abbreviated version of this command. Regardless whether you specify **/status**, the **mode codepage** command will display the numbers of the code pages that are selected for the specified device. |
| /? | Displays help at the command prompt. |

### Display mode

Changes the size of the command prompt screen buffer

#### Syntax

```
mode con[:] [cols=<c>] [lines=<n>]
```

##### Parameters

| Parameter | Description |
| --------- | ----------- |
| con[:] | Indicates that the change applies to the Command Prompt window. This parameter is required. |
| cols=`<c>` | Specifies the number of columns in the command prompt screen buffer. The default setting is 80 columns, but you can set this to any value. If you don't use the default, typical values are 40 and 135 columns. Using non-standard values can result in the command prompt app problems. |
| lines=`<n>` | Specifies the number of lines in the command prompt screen buffer. The default value is 25, but you can set this to any value. If you don't use the default, the other typical value is 50 lines. |
| /? | Displays help at the command prompt. |

### Typematic rate

Sets the keyboard typematic rate. The typematic rate is the speed at which Windows can repeat a character when you press the key on a keyboard.

> [!NOTE]
> Some keyboards don't recognize this command.

#### Syntax

```
mode con[:] [rate=<r> delay=<d>]
```

##### Parameters

| Parameter | Description |
| --------- | ----------- |
| con[:] | Specifies the keyboard. This parameter is required. |
| rate=`<r>` | Specifies the rate at which a character is repeated on the screen when you hold down a key. The default value is 20 characters per second for IBM AT-compatible keyboards, and 21 for IBM PS/2-compatible keyboards, but you can use any value from 1 through 32. If you set this parameter, you must also set the **delay** parameter.|
| delay=`<d>` | Specifies the amount of time that will elapse after you press and hold down a key before the character output repeats. The default value is 2 (.50 seconds), but you can also use 1 (.25 seconds), 3 (.75 seconds), or 4 (1 second). If you set this parameter, you must also set the **rate** parameter. |
| /? | Displays help at the command prompt. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


