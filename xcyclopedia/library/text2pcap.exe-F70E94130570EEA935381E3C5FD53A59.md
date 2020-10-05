---
title: text2pcap.exe | Text2pcap
excerpt: What is text2pcap.exe?
---

# text2pcap.exe 

* File Path: `C:\Program Files\Wireshark\text2pcap.exe`
* Description: Text2pcap

## Hashes

Type | Hash
-- | --
MD5 | `F70E94130570EEA935381E3C5FD53A59`
SHA1 | `7C7D92EDA2130151997D7C3FC916FA6C70DFB082`
SHA256 | `08F3A7D62CEBE96725A6DC9DDB74B56A11ACC28EBE89E02311CC6A2F45B5C62B`
SHA384 | `254407D43A45FD227902277B9BFD1BBA930464A86BAEEE315D3E2CAC4A6DFB6DDB84BCBFCD248BF722F95E958FA2C3C6`
SHA512 | `2679C533EA4D9B7A53A6509658572648C0BD10C52D42B1B86DA70E107A61E02EB84EC748B68B7041276CDBDE25F2D4D3513CB665419470FAB2C91F3E395E6C47`
SSDEEP | `1536:36KhF4dkT5p3hNemWe/GJkuyVcNy7T7ODuYUg48o0VBgWHncnFPXavErjnCj2We2:KKflD3hNeZeGyVcMyr2rFP0oBjYUh4`
IMP | `FA3122A080121BD11EF9989D89941EEB`
PESHA1 | `22BBF1D7C25042DDDA911C485760B488DBFC8E07`
PE256 | `C4733AE2FD2136A093C026B8D358F893143A41E27D41104A9DA84618DC388919`

## Runtime Data

### Usage (stdout):
```cmhg
Text2pcap (Wireshark) 3.2.7 (v3.2.7-0-gfb6522d84a3a)
Generate a capture file from an ASCII hexdump of packets.
See https://www.wireshark.org for more information.

Usage: text2pcap [options] <infile> <outfile>

where  <infile> specifies input  filename (use - for standard input)
      <outfile> specifies output filename (use - for standard output)

Input:
  -o hex|oct|dec         parse offsets as (h)ex, (o)ctal or (d)ecimal;
                         default is hex.
  -t <timefmt>           treat the text before the packet as a date/time code;
                         the specified argument is a format string of the sort
                         supported by strptime.
                         Example: The time "10:15:14.5476" has the format code
                         "%H:%M:%S."
                         NOTE: The subsecond component delimiter, '.', must be
                         given, but no pattern is required; the remaining
                         number is assumed to be fractions of a second.
                         NOTE: Date/time fields from the current date/time are
                         used as the default for unspecified fields.
  -D                     the text before the packet starts with an I or an O,
                         indicating that the packet is inbound or outbound.
                         This is used when generating dummy headers.
                         The indication is only stored if the output format is pcapng.
  -a                     enable ASCII text dump identification.
                         The start of the ASCII text dump can be identified
                         and excluded from the packet data, even if it looks
                         like a HEX dump.
                         NOTE: Do not enable it if the input file does not
                         contain the ASCII text dump.

Output:
  -l <typenum>           link-layer type number; default is 1 (Ethernet).  See
                         https://www.tcpdump.org/linktypes.html for a list of
                         numbers.  Use this option if your dump is a complete
                         hex dump of an encapsulated packet and you wish to
                         specify the exact type of encapsulation.
                         Example: -l 7 for ARCNet packets.
  -m <max-packet>        max packet length in output; default is 262144
  -n                     use pcapng instead of pcap as output format.
  -N <intf-name>         assign name to the interface in the pcapng file.

Prepend dummy header:
  -e <l3pid>             prepend dummy Ethernet II header with specified L3PID
                         (in HEX).
                         Example: -e 0x806 to specify an ARP packet.
  -i <proto>             prepend dummy IP header with specified IP protocol
                         (in DECIMAL).
                         Automatically prepends Ethernet header as well.
                         Example: -i 46
  -4 <srcip>,<destip>    prepend dummy IPv4 header with specified
                         dest and source address.
                         Example: -4 10.0.0.1,10.0.0.2
  -6 <srcip>,<destip>    prepend dummy IPv6 header with specified
                         dest and source address.
                         Example: -6 fe80::202:b3ff:fe1e:8329,2001:0db8:85a3::8a2e:0370:7334
  -u <srcp>,<destp>      prepend dummy UDP header with specified
                         source and destination ports (in DECIMAL).
                         Automatically prepends Ethernet & IP headers as well.
                         Example: -u 1000,69 to make the packets look like
                         TFTP/UDP packets.
  -T <srcp>,<destp>      prepend dummy TCP header with specified
                         source and destination ports (in DECIMAL).
                         Automatically prepends Ethernet & IP headers as well.
                         Example: -T 50,60
  -s <srcp>,<dstp>,<tag> prepend dummy SCTP header with specified
                         source/dest ports and verification tag (in DECIMAL).
                         Automatically prepends Ethernet & IP headers as well.
                         Example: -s 30,40,34
  -S <srcp>,<dstp>,<ppi> prepend dummy SCTP header with specified
                         source/dest ports and verification tag 0.
                         Automatically prepends a dummy SCTP DATA
                         chunk header with payload protocol identifier ppi.
                         Example: -S 30,40,34

Miscellaneous:
  -h                     display this help and exit.
  -d                     show detailed debug of parser states.
  -q                     generate no output at all (automatically disables -d).

```

### Usage (stderr):
```cmhg
Must specify input and output filename

Usage: text2pcap [options] <infile> <outfile>

where  <infile> specifies input  filename (use - for standard input)
      <outfile> specifies output filename (use - for standard output)

Input:
  -o hex|oct|dec         parse offsets as (h)ex, (o)ctal or (d)ecimal;
                         default is hex.
  -t <timefmt>           treat the text before the packet as a date/time code;
                         the specified argument is a format string of the sort
                         supported by strptime.
                         Example: The time "10:15:14.5476" has the format code
                         "%H:%M:%S."
                         NOTE: The subsecond component delimiter, '.', must be
                         given, but no pattern is required; the remaining
                         number is assumed to be fractions of a second.
                         NOTE: Date/time fields from the current date/time are
                         used as the default for unspecified fields.
  -D                     the text before the packet starts with an I or an O,
                         indicating that the packet is inbound or outbound.
                         This is used when generating dummy headers.
                         The indication is only stored if the output format is pcapng.
  -a                     enable ASCII text dump identification.
                         The start of the ASCII text dump can be identified
                         and excluded from the packet data, even if it looks
                         like a HEX dump.
                         NOTE: Do not enable it if the input file does not
                         contain the ASCII text dump.

Output:
  -l <typenum>           link-layer type number; default is 1 (Ethernet).  See
                         https://www.tcpdump.org/linktypes.html for a list of
                         numbers.  Use this option if your dump is a complete
                         hex dump of an encapsulated packet and you wish to
                         specify the exact type of encapsulation.
                         Example: -l 7 for ARCNet packets.
  -m <max-packet>        max packet length in output; default is 262144
  -n                     use pcapng instead of pcap as output format.
  -N <intf-name>         assign name to the interface in the pcapng file.

Prepend dummy header:
  -e <l3pid>             prepend dummy Ethernet II header with specified L3PID
                         (in HEX).
                         Example: -e 0x806 to specify an ARP packet.
  -i <proto>             prepend dummy IP header with specified IP protocol
                         (in DECIMAL).
                         Automatically prepends Ethernet header as well.
                         Example: -i 46
  -4 <srcip>,<destip>    prepend dummy IPv4 header with specified
                         dest and source address.
                         Example: -4 10.0.0.1,10.0.0.2
  -6 <srcip>,<destip>    prepend dummy IPv6 header with specified
                         dest and source address.
                         Example: -6 fe80::202:b3ff:fe1e:8329,2001:0db8:85a3::8a2e:0370:7334
  -u <srcp>,<destp>      prepend dummy UDP header with specified
                         source and destination ports (in DECIMAL).
                         Automatically prepends Ethernet & IP headers as well.
                         Example: -u 1000,69 to make the packets look like
                         TFTP/UDP packets.
  -T <srcp>,<destp>      prepend dummy TCP header with specified
                         source and destination ports (in DECIMAL).
                         Automatically prepends Ethernet & IP headers as well.
                         Example: -T 50,60
  -s <srcp>,<dstp>,<tag> prepend dummy SCTP header with specified
                         source/dest ports and verification tag (in DECIMAL).
                         Automatically prepends Ethernet & IP headers as well.
                         Example: -s 30,40,34
  -S <srcp>,<dstp>,<ppi> prepend dummy SCTP header with specified
                         source/dest ports and verification tag 0.
                         Automatically prepends a dummy SCTP DATA
                         chunk header with payload protocol identifier ppi.
                         Example: -S 30,40,34

Miscellaneous:
  -h                     display this help and exit.
  -d                     show detailed debug of parser states.
  -q                     generate no output at all (automatically disables -d).

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Wireshark\text2pcap.exe |
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

* Original Filename: text2pcap.exe
* Product Name: Text2pcap
* Company Name: The Wireshark developer community
* File Version: 3.2.7
* Product Version: 3.2.7
* Language: English (United States)
* Legal Copyright: Copyright  2001 Ashok Narayanan <ashokn@cisco.com>
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/08f3a7d62cebe96725a6dc9ddb74b56a11acc28ebe89e02311cc6a2f45b5c62b/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Wireshark\capinfos.exe](capinfos.exe-D3682305FD039566EF3DD7470BA00AC0.md) | 63
[C:\Program Files\Wireshark\dumpcap.exe](dumpcap.exe-FA9F38700AA8216DDB89C544A3D388DB.md) | 35
[C:\Program Files\Wireshark\editcap.exe](editcap.exe-2DEF88D5CE21E9249550A3B44FB78DF3.md) | 65
[C:\Program Files\Wireshark\mergecap.exe](mergecap.exe-AC0D181AC080AA87993F93A315A10D50.md) | 60
[C:\Program Files\Wireshark\rawshark.exe](rawshark.exe-86069A2945246A673EAB66982A4B91F3.md) | 40
[C:\Program Files\Wireshark\reordercap.exe](reordercap.exe-BB4E64589FAAE20FB48E04DB009A69C1.md) | 63




MIT License. Copyright (c) 2020 Strontic.


