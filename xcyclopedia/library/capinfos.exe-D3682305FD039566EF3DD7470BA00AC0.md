---
title: capinfos.exe | Capinfos
excerpt: What is capinfos.exe?
---

# capinfos.exe 

* File Path: `C:\Program Files\Wireshark\capinfos.exe`
* Description: Capinfos

## Hashes

Type | Hash
-- | --
MD5 | `D3682305FD039566EF3DD7470BA00AC0`
SHA1 | `7D06AA941B98D3D244A639D9219085C23E5FF999`
SHA256 | `A8CF4F8CB851B1C648FDFF18C8653833DCF7E35727D9C0321BB376DE09A11C96`
SHA384 | `AD744CCC4F06845835D71928C53E9EBB7216F57B1105771573973F57AE28F78243CC2256319F2A25B48E87AABAFEAE14`
SHA512 | `832389B1956322C232C8E2E20A6C9E9E29A5C783B56F259A405471F759916E022222E61711BF9CFD50DC4B7517B64585EF52AFE453DF323A8EEE5829C93E48E3`
SSDEEP | `1536:3ezrMNDYS8OGFP2UeaDUlZ9rj6ky7T7ODuYUg48o0VBgWHncnFPXavErjnCj2Wec:30rMNDYSWP2UeKGPjqyr2rFP0oBju/Z`
IMP | `6FB0FA337E36524E95E0106C09031255`
PESHA1 | `7819E5B2434C83EC323E753E9B8C0AF7FD4C2CB1`
PE256 | `B6DCF864D78EF5279F519A5C589D5821FC0C693F316E47F51FD384C44F0B8457`

## Runtime Data

### Usage (stdout):
```cmhg
Capinfos (Wireshark) 3.2.7 (v3.2.7-0-gfb6522d84a3a)
Print various information (infos) about capture files.
See https://www.wireshark.org for more information.

Usage: capinfos [options] <infile> ...

General infos:
  -t display the capture file type
  -E display the capture file encapsulation
  -I display the capture file interface information
  -F display additional capture file information
  -H display the SHA256, RMD160, and SHA1 hashes of the file
  -k display the capture comment

Size infos:
  -c display the number of packets
  -s display the size of the file (in bytes)
  -d display the total length of all packets (in bytes)
  -l display the packet size limit (snapshot length)

Time infos:
  -u display the capture duration (in seconds)
  -a display the capture start time
  -e display the capture end time
  -o display the capture file chronological status (True/False)
  -S display start and end times as seconds

Statistic infos:
  -y display average data rate (in bytes/sec)
  -i display average data rate (in bits/sec)
  -z display average packet size (in bytes)
  -x display average packet rate (in packets/sec)

Metadata infos:
  -n display number of resolved IPv4 and IPv6 addresses
  -D display number of decryption secrets

Output format:
  -L generate long report (default)
  -T generate table report
  -M display machine-readable values in long reports

Table report options:
  -R generate header record (default)
  -r do not generate header record

  -B separate infos with TAB character (default)
  -m separate infos with comma (,) character
  -b separate infos with SPACE character

  -N do not quote infos (default)
  -q quote infos with single quotes (')
  -Q quote infos with double quotes (")

Miscellaneous:
  -h display this help and exit
  -C cancel processing if file open fails (default is to continue)
  -A generate all infos (default)
  -K disable displaying the capture comment

Options are processed from left to right order with later options superseding
or adding to earlier options.

If no options are given the default is to display all infos in long report
output format.

```

### Usage (stderr):
```cmhg
capinfos: The file "C:\temp\strontic-xcyclopedia\notepad.exe" doesn't exist.

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Wireshark\capinfos.exe |
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

* Original Filename: capinfos.exe
* Product Name: Capinfos
* Company Name: The Wireshark developer community
* File Version: 3.2.7
* Product Version: 3.2.7
* Language: English (United States)
* Legal Copyright: Copyright  2000 Gerald Combs <gerald@wireshark.org>, Gilbert Ramirez <gram@alumni.rice.edu> and many others
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/a8cf4f8cb851b1c648fdff18c8653833dcf7e35727d9c0321bb376de09a11c96/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Wireshark\dumpcap.exe](dumpcap.exe-FA9F38700AA8216DDB89C544A3D388DB.md) | 38
[C:\Program Files\Wireshark\editcap.exe](editcap.exe-2DEF88D5CE21E9249550A3B44FB78DF3.md) | 61
[C:\Program Files\Wireshark\mergecap.exe](mergecap.exe-AC0D181AC080AA87993F93A315A10D50.md) | 61
[C:\Program Files\Wireshark\rawshark.exe](rawshark.exe-86069A2945246A673EAB66982A4B91F3.md) | 40
[C:\Program Files\Wireshark\reordercap.exe](reordercap.exe-BB4E64589FAAE20FB48E04DB009A69C1.md) | 63
[C:\Program Files\Wireshark\text2pcap.exe](text2pcap.exe-F70E94130570EEA935381E3C5FD53A59.md) | 63




MIT License. Copyright (c) 2020 Strontic.


