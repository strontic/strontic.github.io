---
title: editcap.exe | Editcap
excerpt: What is editcap.exe?
---

# editcap.exe 

* File Path: `C:\Program Files\Wireshark\editcap.exe`
* Description: Editcap

## Hashes

Type | Hash
-- | --
MD5 | `2DEF88D5CE21E9249550A3B44FB78DF3`
SHA1 | `B5D23FCB27CD0654E23B7FBCE740A0E91433DF74`
SHA256 | `BD4E4E61AFD42D51D8CDB7B8F33590F7B2A30CA0A1CC19A0509A38ADF01E6383`
SHA384 | `077558C3D3579E1104534D5E197E5A6E51E54AF791B3C867A369DF745C46A06D11367CD7562B1E27E9DEAADBCD22C107`
SHA512 | `971EF67F44EF5D086496A4D1CF214B4378519D42FC99E9DA84C1670758B5A973AAB95DAE5AFD72D61310659452DDB713CD9DB2EB58D5654A693114ED154FBF35`
SSDEEP | `1536:WuN0ex0puy/u07kx87HpRxy7T7ODuYUg48o0VBgWHncnFPXavErjnCj2We2Vk4A2:WDOb07kx87Hpeyr2rFP0oBj7JGtb`
IMP | `FCE1A7709608524809C4CBDCCA73CDE6`
PESHA1 | `59BC8835D3301B22B61CB543A8F4B9DEF9CBD7B1`
PE256 | `FE0CF661A9FC2C6F1C597C6B8DDC90682201D5EA14236DD0DE3D8347BAE963A8`

## Runtime Data

### Usage (stdout):
```cmhg
Editcap (Wireshark) 3.2.7 (v3.2.7-0-gfb6522d84a3a)
Edit and/or translate the format of capture files.
See https://www.wireshark.org for more information.

Usage: editcap [options] ... <infile> <outfile> [ <packet#>[-<packet#>] ... ]

<infile> and <outfile> must both be present.
A single packet or a range of packets can be selected.

Packet selection:
  -r                     keep the selected packets; default is to delete them.
  -A <start time>        only output packets whose timestamp is after (or equal
                         to) the given time (format as YYYY-MM-DD hh:mm:ss).
  -B <stop time>         only output packets whose timestamp is before the
                         given time (format as YYYY-MM-DD hh:mm:ss).

Duplicate packet removal:
  --novlan               remove vlan info from packets before checking for duplicates.
  -d                     remove packet if duplicate (window == 5).
  -D <dup window>        remove packet if duplicate; configurable <dup window>.
                         Valid <dup window> values are 0 to 1000000.
                         NOTE: A <dup window> of 0 with -v (verbose option) is
                         useful to print MD5 hashes.
  -w <dup time window>   remove packet if duplicate packet is found EQUAL TO OR
                         LESS THAN <dup time window> prior to current packet.
                         A <dup time window> is specified in relative seconds
                         (e.g. 0.000001).
           NOTE: The use of the 'Duplicate packet removal' options with
           other editcap options except -v may not always work as expected.
           Specifically the -r, -t or -S options will very likely NOT have the
           desired effect if combined with the -d, -D or -w.
  --skip-radiotap-header skip radiotap header when checking for packet duplicates.
                         Useful when processing packets captured by multiple radios
                         on the same channel in the vicinity of each other.

Packet manipulation:
  -s <snaplen>           truncate each packet to max. <snaplen> bytes of data.
  -C [offset:]<choplen>  chop each packet by <choplen> bytes. Positive values
                         chop at the packet beginning, negative values at the
                         packet end. If an optional offset precedes the length,
                         then the bytes chopped will be offset from that value.
                         Positive offsets are from the packet beginning,
                         negative offsets are from the packet end. You can use
                         this option more than once, allowing up to 2 chopping
                         regions within a packet provided that at least 1
                         choplen is positive and at least 1 is negative.
  -L                     adjust the frame (i.e. reported) length when chopping
                         and/or snapping.
  -t <time adjustment>   adjust the timestamp of each packet.
                         <time adjustment> is in relative seconds (e.g. -0.5).
  -S <strict adjustment> adjust timestamp of packets if necessary to ensure
                         strict chronological increasing order. The <strict
                         adjustment> is specified in relative seconds with
                         values of 0 or 0.000001 being the most reasonable.
                         A negative adjustment value will modify timestamps so
                         that each packet's delta time is the absolute value
                         of the adjustment specified. A value of -0 will set
                         all packets to the timestamp of the first packet.
  -E <error probability> set the probability (between 0.0 and 1.0 incl.) that
                         a particular packet byte will be randomly changed.
  -o <change offset>     When used in conjunction with -E, skip some bytes from the
                         beginning of the packet. This allows one to preserve some
                         bytes, in order to have some headers untouched.
  --seed <seed>          When used in conjunction with -E, set the seed to use for
                         the pseudo-random number generator. This allows one to
                         repeat a particular sequence of errors.
  -I <bytes to ignore>   ignore the specified number of bytes at the beginning
                         of the frame during MD5 hash calculation, unless the
                         frame is too short, then the full frame is used.
                         Useful to remove duplicated packets taken on
                         several routers (different mac addresses for
                         example).
                         e.g. -I 26 in case of Ether/IP will ignore
                         ether(14) and IP header(20 - 4(src ip) - 4(dst ip)).
  -a <framenum>:<comment> Add or replace comment for given frame number

Output File(s):
  -c <packets per file>  split the packet output to different files based on
                         uniform packet counts with a maximum of
                         <packets per file> each.
  -i <seconds per file>  split the packet output to different files based on
                         uniform time intervals with a maximum of
                         <seconds per file> each.
  -F <capture type>      set the output file type; default is pcapng.
                         An empty "-F" option will list the file types.
  -T <encap type>        set the output file encapsulation type; default is the
                         same as the input file. An empty "-T" option will
                         list the encapsulation types.
  --inject-secrets <type>,<file>  Insert decryption secrets from <file>. List
                         supported secret types with "--inject-secrets help".
  --discard-all-secrets  Discard all decryption secrets from the input file
                         when writing the output file.  Does not discard
                         secrets added by "--inject-secrets" in the same
                         command line.

Miscellaneous:
  -h                     display this help and exit.
  -v                     verbose output.
                         If -v is used with any of the 'Duplicate Packet
                         Removal' options (-d, -D or -w) then Packet lengths
                         and MD5 hashes are printed to standard-error.

```

### Usage (stderr):
```cmhg

Usage: editcap [options] ... <infile> <outfile> [ <packet#>[-<packet#>] ... ]

<infile> and <outfile> must both be present.
A single packet or a range of packets can be selected.

Packet selection:
  -r                     keep the selected packets; default is to delete them.
  -A <start time>        only output packets whose timestamp is after (or equal
                         to) the given time (format as YYYY-MM-DD hh:mm:ss).
  -B <stop time>         only output packets whose timestamp is before the
                         given time (format as YYYY-MM-DD hh:mm:ss).

Duplicate packet removal:
  --novlan               remove vlan info from packets before checking for duplicates.
  -d                     remove packet if duplicate (window == 5).
  -D <dup window>        remove packet if duplicate; configurable <dup window>.
                         Valid <dup window> values are 0 to 1000000.
                         NOTE: A <dup window> of 0 with -v (verbose option) is
                         useful to print MD5 hashes.
  -w <dup time window>   remove packet if duplicate packet is found EQUAL TO OR
                         LESS THAN <dup time window> prior to current packet.
                         A <dup time window> is specified in relative seconds
                         (e.g. 0.000001).
           NOTE: The use of the 'Duplicate packet removal' options with
           other editcap options except -v may not always work as expected.
           Specifically the -r, -t or -S options will very likely NOT have the
           desired effect if combined with the -d, -D or -w.
  --skip-radiotap-header skip radiotap header when checking for packet duplicates.
                         Useful when processing packets captured by multiple radios
                         on the same channel in the vicinity of each other.

Packet manipulation:
  -s <snaplen>           truncate each packet to max. <snaplen> bytes of data.
  -C [offset:]<choplen>  chop each packet by <choplen> bytes. Positive values
                         chop at the packet beginning, negative values at the
                         packet end. If an optional offset precedes the length,
                         then the bytes chopped will be offset from that value.
                         Positive offsets are from the packet beginning,
                         negative offsets are from the packet end. You can use
                         this option more than once, allowing up to 2 chopping
                         regions within a packet provided that at least 1
                         choplen is positive and at least 1 is negative.
  -L                     adjust the frame (i.e. reported) length when chopping
                         and/or snapping.
  -t <time adjustment>   adjust the timestamp of each packet.
                         <time adjustment> is in relative seconds (e.g. -0.5).
  -S <strict adjustment> adjust timestamp of packets if necessary to ensure
                         strict chronological increasing order. The <strict
                         adjustment> is specified in relative seconds with
                         values of 0 or 0.000001 being the most reasonable.
                         A negative adjustment value will modify timestamps so
                         that each packet's delta time is the absolute value
                         of the adjustment specified. A value of -0 will set
                         all packets to the timestamp of the first packet.
  -E <error probability> set the probability (between 0.0 and 1.0 incl.) that
                         a particular packet byte will be randomly changed.
  -o <change offset>     When used in conjunction with -E, skip some bytes from the
                         beginning of the packet. This allows one to preserve some
                         bytes, in order to have some headers untouched.
  --seed <seed>          When used in conjunction with -E, set the seed to use for
                         the pseudo-random number generator. This allows one to
                         repeat a particular sequence of errors.
  -I <bytes to ignore>   ignore the specified number of bytes at the beginning
                         of the frame during MD5 hash calculation, unless the
                         frame is too short, then the full frame is used.
                         Useful to remove duplicated packets taken on
                         several routers (different mac addresses for
                         example).
                         e.g. -I 26 in case of Ether/IP will ignore
                         ether(14) and IP header(20 - 4(src ip) - 4(dst ip)).
  -a <framenum>:<comment> Add or replace comment for given frame number

Output File(s):
  -c <packets per file>  split the packet output to different files based on
                         uniform packet counts with a maximum of
                         <packets per file> each.
  -i <seconds per file>  split the packet output to different files based on
                         uniform time intervals with a maximum of
                         <seconds per file> each.
  -F <capture type>      set the output file type; default is pcapng.
                         An empty "-F" option will list the file types.
  -T <encap type>        set the output file encapsulation type; default is the
                         same as the input file. An empty "-T" option will
                         list the encapsulation types.
  --inject-secrets <type>,<file>  Insert decryption secrets from <file>. List
                         supported secret types with "--inject-secrets help".
  --discard-all-secrets  Discard all decryption secrets from the input file
                         when writing the output file.  Does not discard
                         secrets added by "--inject-secrets" in the same
                         command line.

Miscellaneous:
  -h                     display this help and exit.
  -v                     verbose output.
                         If -v is used with any of the 'Duplicate Packet
                         Removal' options (-d, -D or -w) then Packet lengths
                         and MD5 hashes are printed to standard-error.

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Wireshark\editcap.exe |
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

* Original Filename: editcap.exe
* Product Name: Editcap
* Company Name: The Wireshark developer community
* File Version: 3.2.7
* Product Version: 3.2.7
* Language: English (United States)
* Legal Copyright: Copyright  2000 Gerald Combs <gerald@wireshark.org>, Gilbert Ramirez <gram@alumni.rice.edu> and many others
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 1/71
* VirusTotal Link: https://www.virustotal.com/gui/file/bd4e4e61afd42d51d8cdb7b8f33590f7b2a30ca0a1cc19a0509a38adf01e6383/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Wireshark\capinfos.exe](capinfos.exe-D3682305FD039566EF3DD7470BA00AC0.md) | 61
[C:\Program Files\Wireshark\dumpcap.exe](dumpcap.exe-FA9F38700AA8216DDB89C544A3D388DB.md) | 36
[C:\Program Files\Wireshark\mergecap.exe](mergecap.exe-AC0D181AC080AA87993F93A315A10D50.md) | 71
[C:\Program Files\Wireshark\rawshark.exe](rawshark.exe-86069A2945246A673EAB66982A4B91F3.md) | 35
[C:\Program Files\Wireshark\reordercap.exe](reordercap.exe-BB4E64589FAAE20FB48E04DB009A69C1.md) | 66
[C:\Program Files\Wireshark\text2pcap.exe](text2pcap.exe-F70E94130570EEA935381E3C5FD53A59.md) | 65




MIT License. Copyright (c) 2020-2021 Strontic.


