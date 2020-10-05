---
title: mergecap.exe | Mergecap
excerpt: What is mergecap.exe?
---

# mergecap.exe 

* File Path: `C:\Program Files\Wireshark\mergecap.exe`
* Description: Mergecap

## Hashes

Type | Hash
-- | --
MD5 | `AC0D181AC080AA87993F93A315A10D50`
SHA1 | `9DE685C68BB7B2C3CE82D885A992B3EB65646813`
SHA256 | `C70FCBE619EFFEB1D598EA50D826369A47B56B7136DA9AF89E3238561BC28406`
SHA384 | `4560D507B94ED6285A22036241D0BB7CAC8A9A48DA2093C5A766D2EC0F511F0F4C1AE31A22A5990EDACAE6908296582F`
SHA512 | `72171CA2CB682F9060D54CD5AF93DCD6126CD51F3DA8364D756AA2EBE1F27ACB91D1A008E8CD68EE304DBD275DB52AA65B56E040528116A8587DB677B1255E0C`
SSDEEP | `1536:xXsziuHt4R29Ly7T7ODuYUg48o0VBgWHncnFPXavErjnCj2We2Vk4AUFeAnNXPTW:xqiuHt4R29Oyr2rFP0oBj+AT`
IMP | `1B305D670882178A36A7C88E5265C2D7`
PESHA1 | `6B13C88FD615D3FD70DDC973CF6089753D571BB9`
PE256 | `9B63F3D68160B51C04C3936C43E7B19FA8FAEE5FBAEAFACB725E37453BEDDD89`

## Runtime Data

### Usage (stdout):
```cmhg
Mergecap (Wireshark) 3.2.7 (v3.2.7-0-gfb6522d84a3a)
Merge two or more capture files into one.
See https://www.wireshark.org for more information.

Usage: mergecap [options] -w <outfile>|- <infile> [<infile> ...]

Output:
  -a                concatenate rather than merge files.
                    default is to merge based on frame timestamps.
  -s <snaplen>      truncate packets to <snaplen> bytes of data.
  -w <outfile>|-    set the output filename to <outfile> or '-' for stdout.
  -F <capture type> set the output file type; default is pcapng.
                    an empty "-F" option will list the file types.
  -I <IDB merge mode> set the merge mode for Interface Description Blocks; default is 'all'.
                    an empty "-I" option will list the merge modes.

Miscellaneous:
  -h                display this help and exit.
  -v                verbose output.

```

### Usage (stderr):
```cmhg
mergecap: an output filename must be set with -w
          run with -h for help

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Wireshark\mergecap.exe |
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

* Original Filename: mergecap.exe
* Product Name: Mergecap
* Company Name: The Wireshark developer community
* File Version: 3.2.7
* Product Version: 3.2.7
* Language: English (United States)
* Legal Copyright: Copyright  2000 Gerald Combs <gerald@wireshark.org>, Gilbert Ramirez <gram@alumni.rice.edu> and many others
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/c70fcbe619effeb1d598ea50d826369a47b56b7136da9af89e3238561bc28406/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Wireshark\capinfos.exe](capinfos.exe-D3682305FD039566EF3DD7470BA00AC0.md) | 61
[C:\Program Files\Wireshark\dumpcap.exe](dumpcap.exe-FA9F38700AA8216DDB89C544A3D388DB.md) | 38
[C:\Program Files\Wireshark\editcap.exe](editcap.exe-2DEF88D5CE21E9249550A3B44FB78DF3.md) | 71
[C:\Program Files\Wireshark\rawshark.exe](rawshark.exe-86069A2945246A673EAB66982A4B91F3.md) | 35
[C:\Program Files\Wireshark\reordercap.exe](reordercap.exe-BB4E64589FAAE20FB48E04DB009A69C1.md) | 80
[C:\Program Files\Wireshark\text2pcap.exe](text2pcap.exe-F70E94130570EEA935381E3C5FD53A59.md) | 60




MIT License. Copyright (c) 2020 Strontic.


