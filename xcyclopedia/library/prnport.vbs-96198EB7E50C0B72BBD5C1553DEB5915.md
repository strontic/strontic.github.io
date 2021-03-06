﻿---
title: prnport.vbs | 
excerpt: What is prnport.vbs?
---

# prnport.vbs 

* File Path: `C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnport.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `96198EB7E50C0B72BBD5C1553DEB5915`
SHA1 | `239EF40C4E3BF5875B7DE20F76E2657F3BAFB49F`
SHA256 | `452763954976CFF39351BAFCE9A382EBEE3107D7C3D8A79362C81C5853D5BEE0`
SHA384 | `A25DE47236F73AA16907F2F7B91029304E0B0872849C1256E23A991DF47412CEB8A275856DC31C8599346F6E8CD5C765`
SHA512 | `C6C0BC25F6C88981950205AF962D50043A52379548BC0F07F8E5DDDD326A33EC95F6D148273E4288C25E5664C8741B7A175E3D1351036C42E27A17356F0499E9`
SSDEEP | `768:mDvBIRggkRq9ZpZrXe6buhoBUzNPa8XQGhJ1Kseam:SJmlZrXbbu698N+am`
PESHA1 | `239EF40C4E3BF5875B7DE20F76E2657F3BAFB49F`
PE256 | `452763954976CFF39351BAFCE9A382EBEE3107D7C3D8A79362C81C5853D5BEE0`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: prnport [-adlgt?] [-r port][-s server][-u user name][-w password]
               [-o raw|lpr][-h host address][-q queue][-n number]
               [-me | -md ][-i SNMP index][-y community][-2e | -2d]
Arguments:
-a     - add a port
-d     - delete the specified port
-g     - get configuration for a TCP port
-h     - IP address of the device
-i     - SNMP index, if SNMP is enabled
-l     - list all TCP ports
-m     - SNMP type. [e] enable, [d] disable
-n     - port number, applies to TCP RAW ports
-o     - port type, raw or lpr
-q     - queue name, applies to TCP LPR ports only
-r     - port name
-s     - server name
-t     - set configuration for a TCP port
-u     - user name
-w     - password
-y     - community name, if SNMP is enabled
-2     - double spool, applies to TCP LPR ports. [e] enable, [d] disable
-?     - display command usage

Examples:
prnport -l -s server
prnport -d -s server -r IP_1.2.3.4
prnport -a -s server -r IP_1.2.3.4 -h 1.2.3.4 -o raw -n 9100
prnport -t -s server -r IP_1.2.3.4 -me -y public -i 1 -n 9100
prnport -g -s server -r IP_1.2.3.4
prnport -a -r IP_1.2.3.4 -h 1.2.3.4

Remark:
The last example will try to get the device settings at the specified IP address.
If a device is detected, then a TCP port is added with the preferred settings for that device.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\cscript.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/452763954976cff39351bafce9a382ebee3107d7c3d8a79362c81c5853d5bee0/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Printing_Admin_Scripts\en-US\prnport.vbs](prnport.vbs-6D0114E9FBAE0DD8081C9A0D8F67D69F.md) | 60
[C:\Windows\system32\Printing_Admin_Scripts\en-US\prnqctl.vbs](prnqctl.vbs-11895A0FF5707A85D5C7C43C4AB73B18.md) | 40
[C:\Windows\system32\Printing_Admin_Scripts\en-US\pubprn.vbs](pubprn.vbs-C09F6C90E1DD04184030416D3C469206.md) | 33
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnjobs.vbs](prnjobs.vbs-16EF15265C4D06DAAA4F0BEA9AC9F11B.md) | 29
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnqctl.vbs](prnqctl.vbs-3174AA250852ED50AC058E83A06482D0.md) | 41
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\pubprn.vbs](pubprn.vbs-D960FA3DAF18F891E2FF7F81C1AF1ADC.md) | 40


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## prnport

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Creates, deletes, and lists standard TCP/IP printer ports, in addition to displaying and changing port configuration. This command is a Visual Basic script located in the `%WINdir%\System32\printing_Admin_Scripts\<language>` directory. To use this command at a command prompt, type **cscript** followed by the full path to the prnport file, or change directories to the appropriate folder. For example: `cscript %WINdir%\System32\printing_Admin_Scripts\en-US\prnport`.

### Syntax

```
cscript prnport {-a | -d | -l | -g | -t | -?} [-r <portname>] [-s <Servername>] [-u <Username>] [-w <password>] [-o {raw | lpr}] [-h <Hostaddress>] [-q <Queuename>] [-n <portnumber>] -m{e | d} [-i <SNMPindex>] [-y <communityname>] -2{e | -d}
```

#### Parameters

| Parameter | Description |
|--|--|
| -a | Creates a standard TCP/IP printer port. |
| -d | Deletes a standard TCP/IP printer port. |
| -l | Lists all standard TCP/IP printer ports on the computer specified by the **-s** parameter. |
| -g | Displays the configuration of a standard TCP/IP printer port. |
| -t | Configures the port settings for a standard TCP/IP printer port. |
| -r `<portname>` | Specifies the port to which the printer is connected. |
| -s `<Servername>` | Specifies the name of the remote computer that hosts the printer that you want to manage. If you don't specify a computer, the local computer is used. |
| -u `<Username>` -w `<password>` | Specifies an account with permissions to connect to the computer that hosts the printer that you want to manage. All members of the target computer's local Administrators group have these permissions, but the permissions can also be granted to other users. If you don't specify an account, you must be logged on under an account with these permissions for the command to work. |
| -o `{raw|lpr}` | Specifies which protocol the port uses: TCP raw or TCP lpr. The TCP raw protocol is a higher performance protocol on Windows than the lpr protocol. If you use TCP raw, you can optionally specify the port number by using the **-n** parameter. The default port number is 9100. |
| -h `<Hostaddress>` | Specifies (by IP address) the printer for which you want to configure the port. |
| -q `<Queuename>` | Specifies the queue name for a TCP raw port. |
| -n `<portnumber>` | Specifies the port number for a TCP raw port. The default port number is 9100. |
| -m`{e|d}` | Specifies whether SNMP is enabled. The parameter **e** enables SNMP. The parameter **d** disables SNMP. |
| -i `<SNMPindex` | Specifies the SNMP index, if SNMP is enabled. For more information, see **Rfc 1759** at the [Rfc editor website](https://www.ietf.org/rfc/rfc1759.txt?number=1759). |
| -y `<communityname>` | Specifies the SNMP community name, if SNMP is enabled. |
| -2`{e|-d}` | Specifies whether double spools (also known as respooling) are enabled for TCP lpr ports. Double spools are necessary because TCP lpr must include an accurate byte count in the control file that is sent to the printer, but the protocol cannot get the count from the local print provider. Therefore, when a file is spooled to a TCP lpr print queue, it is also spooled as a temporary file in the system32 directory. TCP lpr determines the size of the temporary file and sends the size to the server running LPD. The parameter **e** enables double spools. The parameter **d** disables double spools. |
| /? | Displays help at the command prompt. |

##### Remarks

- If the information that you supply contains spaces, use quotation marks around the text (for example, "Computer Name").

#### Examples

To display all standard TCP/IP printing ports on the server \\Server1, type:

```
cscript prnport -l -s Server1
```

To delete the standard TCP/IP printing port on the server \\Server1 that connects to a network printer at 10.2.3.4, type:

```
cscript prnport -d -s Server1 -r IP_10.2.3.4
```

To add a standard TCP/IP printing port on the server \\Server1 that connects to a network printer at 10.2.3.4 and uses the TCP raw protocol on port 9100, type:

```
cscript prnport -a -s Server1 -r IP_10.2.3.4 -h 10.2.3.4 -o raw -n 9100
```

To enable SNMP, specify the "public" community name and set the SNMP index to 1 on a network printer at 10.2.3.4 shared by the server \\Server1, type:

```
cscript prnport -t -s Server1 -r IP_10.2.3.4 -me -y public -i 1 -n 9100
```

To add a standard TCP/IP printing port on the local computer that connects to a network printer at 10.2.3.4 and automatically get the device settings from the printer, type:

```
cscript prnport -a -r IP_10.2.3.4 -h 10.2.3.4
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Print Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/print-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


