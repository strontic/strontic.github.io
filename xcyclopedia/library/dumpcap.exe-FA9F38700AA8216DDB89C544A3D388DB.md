---
title: dumpcap.exe | Dumpcap
excerpt: What is dumpcap.exe?
---

# dumpcap.exe 

* File Path: `C:\Program Files\Wireshark\dumpcap.exe`
* Description: Dumpcap

## Hashes

Type | Hash
-- | --
MD5 | `FA9F38700AA8216DDB89C544A3D388DB`
SHA1 | `69887913FCC3D840D0DAD0C1429F5BE5FC2305BE`
SHA256 | `96702338BFC866FBEA133819697E992694E94D6D0AE32276728000D9B3ACE45B`
SHA384 | `671508FEFF78108FB8FEFD3C06AA70357C7D985E5677EC5109D9F86C79BDA68F89ACDD3B4E6C218A318D4EA1712CD667`
SHA512 | `2492046F4E78D8765F2BDFA3D907E2400EE790C653E821404C00478292F221334390BCFBEB426E3AE4067AD6678BEC6E6523E343D6159A15D91BA972665C31C6`
SSDEEP | `3072:vX0nLywFbVbXSypi9buQlZ6rGb4Z3KIUyr2rFP0oBjjZJ/:vkn2wVVb5aqQlUTKIUuSFP9FJ/`
IMP | `62C2ADC8A4D23E2D07B7EEB4235EEB0C`
PESHA1 | `342E07693B6695A17138E42F7B01D7886A52CA50`
PE256 | `F43353775A17D79FDCF893DADF110DDC615B026096BB5132E81E2032B1DF0152`

## Runtime Data

### Usage (stdout):
```cmhg
Dumpcap (Wireshark) 3.2.7 (v3.2.7-0-gfb6522d84a3a)
Capture network packets and dump them into a pcapng or pcap file.
See https://www.wireshark.org for more information.

Usage: dumpcap [options] ...

Capture interface:
  -i <interface>, --interface <interface>
                           name or idx of interface (def: first non-loopback),
                           or for remote capturing, use one of these formats:
                               rpcap://<host>/<interface>
                               TCP@<host>:<port>
  -f <capture filter>      packet filter in libpcap filter syntax
  -s <snaplen>, --snapshot-length <snaplen>
                           packet snapshot length (def: appropriate maximum)
  -p, --no-promiscuous-mode
                           don't capture in promiscuous mode
  -I, --monitor-mode       capture in monitor mode, if available
  -B <buffer size>, --buffer-size <buffer size>
                           size of kernel buffer in MiB (def: 2MiB)
  -y <link type>, --linktype <link type>
                           link layer type (def: first appropriate)
  --time-stamp-type <type> timestamp method for interface
  -D, --list-interfaces    print list of interfaces and exit
  -L, --list-data-link-types
                           print list of link-layer types of iface and exit
  --list-time-stamp-types  print list of timestamp types for iface and exit
  -d                       print generated BPF code for capture filter
  -k <freq>,[<type>],[<center_freq1>],[<center_freq2>]
                           set channel on wifi interface
  -S                       print statistics for each interface once per second
  -M                       for -D, -L, and -S, produce machine-readable output

RPCAP options:
  -r                       don't ignore own RPCAP traffic in capture
  -u                       use UDP for RPCAP data transfer
  -A <user>:<password>     use RPCAP password authentication
  -m <sampling type>       use packet sampling
                           count:NUM - capture one packet of every NUM
                           timer:NUM - capture no more than 1 packet in NUM ms
Stop conditions:
  -c <packet count>        stop after n packets (def: infinite)
  -a <autostop cond.> ..., --autostop <autostop cond.> ...
                           duration:NUM - stop after NUM seconds
                           filesize:NUM - stop this file after NUM kB
                              files:NUM - stop after NUM files
                            packets:NUM - stop after NUM packets
Output (files):
  -w <filename>            name of file to save (def: tempfile)
  -g                       enable group read access on the output file(s)
  -b <ringbuffer opt.> ..., --ring-buffer <ringbuffer opt.>
                           duration:NUM - switch to next file after NUM secs
                           filesize:NUM - switch to next file after NUM kB
                              files:NUM - ringbuffer: replace after NUM files
                            packets:NUM - ringbuffer: replace after NUM packets
                           interval:NUM - switch to next file when the time is
                                          an exact multiple of NUM secs
  -n                       use pcapng format instead of pcap (default)
  -P                       use libpcap format instead of pcapng
  --capture-comment <comment>
                           add a capture comment to the output file
                           (only for pcapng)

Miscellaneous:
  -N <packet_limit>        maximum number of packets buffered within dumpcap
  -C <byte_limit>          maximum number of bytes used for buffering packets
                           within dumpcap
  -t                       use a separate thread per interface
  -q                       don't report packet capture counts
  -v, --version            print version information and exit
  -h, --help               display this help and exit

Example: dumpcap -i eth0 -a duration:60 -w output.pcapng
"Capture packets from interface eth0 until 60s passed into output.pcapng"

Use Ctrl-C to stop capturing at any time.

```

### Usage (stderr):
```cmhg
dumpcap: Unable to load Npcap or WinPcap (wpcap.dll); you will not be able to
capture packets.

In order to capture packets Npcap or WinPcap must be installed. See

        https://nmap.org/npcap/

for a downloadable version of Npcap and for instructions on how to
install it.

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Wireshark\dumpcap.exe |
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

* Original Filename: Dumpcap.exe
* Product Name: Dumpcap
* Company Name: The Wireshark developer community
* File Version: 3.2.7
* Product Version: 3.2.7
* Language: English (United States)
* Legal Copyright: Copyright  2000 Gerald Combs <gerald@wireshark.org>, Gilbert Ramirez <gram@alumni.rice.edu> and others
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/96702338bfc866fbea133819697e992694e94d6d0ae32276728000d9b3ace45b/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Wireshark\capinfos.exe](capinfos.exe-D3682305FD039566EF3DD7470BA00AC0.md) | 38
[C:\Program Files\Wireshark\editcap.exe](editcap.exe-2DEF88D5CE21E9249550A3B44FB78DF3.md) | 36
[C:\Program Files\Wireshark\mergecap.exe](mergecap.exe-AC0D181AC080AA87993F93A315A10D50.md) | 38
[C:\Program Files\Wireshark\rawshark.exe](rawshark.exe-86069A2945246A673EAB66982A4B91F3.md) | 35
[C:\Program Files\Wireshark\reordercap.exe](reordercap.exe-BB4E64589FAAE20FB48E04DB009A69C1.md) | 35
[C:\Program Files\Wireshark\text2pcap.exe](text2pcap.exe-F70E94130570EEA935381E3C5FD53A59.md) | 35

## Possible Misuse

*The following table contains possible examples of `dumpcap.exe` being misused. While `dumpcap.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fin7_backdoor.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fin7_backdoor.yar) | $a2 = "dumpcap.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [7a6ba833-de40-466a-8969-5c37b13603e0.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/7a6ba833-de40-466a-8969-5c37b13603e0.yml) | `"dumpcap",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


