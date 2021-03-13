---
title: rawshark.exe | Rawshark
excerpt: What is rawshark.exe?
---

# rawshark.exe 

* File Path: `C:\Program Files\Wireshark\rawshark.exe`
* Description: Rawshark

## Hashes

Type | Hash
-- | --
MD5 | `86069A2945246A673EAB66982A4B91F3`
SHA1 | `0CB1ECE787C19B019BE4C307BADC0AA5915ECEE9`
SHA256 | `06FDA8C50BEF237FD51EF4D1F6BAE0B56778CD0CDE8A1537009134D1BE36BEEE`
SHA384 | `0B5E813C013A044922F76F84830437E8C57A1D65B2B60EED80D564A1CDE612A3D4AF7B87824A8DBAB9B22210E7646D94`
SHA512 | `087F8329C365AED7FED3E891041F170D8EE06E303FE8786DAD9E5EB8B7D7600292B3154F0FED819141EA07C61EE0DB4525F3B027F36C75F270CAAF11726D3268`
SSDEEP | `3072:v6n9On8KRrg31kVVZ1JFW5PLECFuGYWqN8yyr2rFP0oBjec2:iQ83k/EEmTYWq6yuSFP972`
IMP | `D8685D903C7A11D57691093C3FF4F5C3`
PESHA1 | `BDAEF376FC8160BA86B1BCCF6D755A315F5404C7`
PE256 | `23557DD8414B272495CC4CD69F57E5FF1914ED6DA15B49A3E7BB60357183D1C2`

## Runtime Data

### Usage (stdout):
```cmhg
Rawshark (Wireshark) 3.2.7 (v3.2.7-0-gfb6522d84a3a)
Dump and analyze network traffic.
See https://www.wireshark.org for more information.

Usage: rawshark [options] ...

Input file:
  -r <infile>              set the pipe or file name to read from

Processing:
  -d <encap:linktype>|<proto:protoname>
                           packet encapsulation or protocol
  -F <field>               field to display
  -n                       disable all name resolution (def: all enabled)
  -N <name resolve flags>  enable specific name resolution(s): "mnNtdv"
  -p                       use the system's packet header format
                           (which may have 64-bit timestamps)
  -R <read filter>         packet filter in Wireshark display filter syntax
  -s                       skip PCAP header on input

Output:
  -l                       flush output after each packet
  -S                       format string for fields
                           (%D - name, %S - stringval, %N numval)
  -t ad|a|r|d|dd|e         output format of time stamps (def: r: rel. to first)

Miscellaneous:
  -h                       display this help and exit
  -o <name>:<value> ...    override preference setting
  -v                       display version info and exit

```

### Usage (stderr):
```cmhg
rawshark: No valid payload dissector specified.

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Wireshark\rawshark.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `02CCD99F7D556C13CE8710C69D09B31A`
* Thumbprint: `E8EF7325044D018B0C0DCD8CBA4190B155857F3B`
* Issuer: CN=Sectigo RSA Code Signing CA, O=Sectigo Limited, L=Salford, S=Greater Manchester, C=GB
* Subject: CN="Wireshark Foundation, Inc.", O="Wireshark Foundation, Inc.", STREET=711 4th street, L=Davis, S=CA, PostalCode=95616, C=US

## File Metadata

* Original Filename: rawshark.exe
* Product Name: Rawshark
* Company Name: The Wireshark developer community
* File Version: 3.2.7
* Product Version: 3.2.7
* Language: English (United States)
* Legal Copyright: Copyright  2000 Gerald Combs <gerald@wireshark.org>, Gilbert Ramirez <gram@alumni.rice.edu> and many others
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/06fda8c50bef237fd51ef4d1f6bae0b56778cd0cde8a1537009134d1be36beee/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Wireshark\capinfos.exe](capinfos.exe-D3682305FD039566EF3DD7470BA00AC0.md) | 40
[C:\Program Files\Wireshark\dumpcap.exe](dumpcap.exe-FA9F38700AA8216DDB89C544A3D388DB.md) | 35
[C:\Program Files\Wireshark\editcap.exe](editcap.exe-2DEF88D5CE21E9249550A3B44FB78DF3.md) | 35
[C:\Program Files\Wireshark\mergecap.exe](mergecap.exe-AC0D181AC080AA87993F93A315A10D50.md) | 35
[C:\Program Files\Wireshark\reordercap.exe](reordercap.exe-BB4E64589FAAE20FB48E04DB009A69C1.md) | 36
[C:\Program Files\Wireshark\text2pcap.exe](text2pcap.exe-F70E94130570EEA935381E3C5FD53A59.md) | 40

## Possible Misuse

*The following table contains possible examples of `rawshark.exe` being misused. While `rawshark.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_auditd_susp_C2_commands.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/auditd/lnx_auditd_susp_C2_commands.yml) | `description: Detects suspicious activities as declared by Florian Roth in its 'Best Practice Auditd Configuration'. This includes the detection of the following commands; wget, curl, base64, nc, netcat, ncat, ssh, socat, wireshark, rawshark, rdesktop, nmap. These commands match a few techniques from the tactics "Command and Control", including not exhaustively the following; Application Layer Protocol (T1071), Non-Application Layer Protocol (T1095), Data Encoding (T1132)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


