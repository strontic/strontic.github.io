---
title: mode.com | DOS Device MODE Utility
excerpt: What is mode.com?
---

# mode.com 

* File Path: `C:\Windows\system32\mode.com`
* Description: DOS Device MODE Utility

## Hashes

Type | Hash
-- | --
MD5 | `59D1ED51ACB8C3D50F1306FD75F20E99`
SHA1 | `AB7F4D369502697E54D6AB60F1B1711C114A0DDF`
SHA256 | `D3E4FBE23E03704D6EE0A0C33A630E8A51E468383E6F72112A759EFD6795EBE1`
SHA384 | `5135C98CB5E65E9AF2330BEDFE2992FFE6033AB42C986C0D89B4F688CFC177D8C33AE82E4B65BD6824FCA9E4189B1245`
SHA512 | `DABBE2E81D7BEBBAF3ECB2BE704A1E71993807AE487DCEB8661DB88D0AA80DA2972C79F82D30418154CDE84D1F0FA43B244FC55BDEA05D696BFD9DA1FCD41DE4`
SSDEEP | `768:Q/MyUH4qPmdq4rQJNVytJtCosoxoaNlAyv1U:Q/lhcD8xtCLoxoajU`
IMP | `2F60C2ED7648C832822B0B1EE9787340`
PESHA1 | `E2D18A9DCC3304038F0B402CDC95CA25525FFF3E`
PE256 | `146CC98D5BADE9994D05A261C9C8082C80C20A3D7062C3D6C6463C1CA67A289E`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\mode.com |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/d3e4fbe23e03704d6ee0a0c33a630e8a51e468383e6f72112a759efd6795ebe1/detection



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


