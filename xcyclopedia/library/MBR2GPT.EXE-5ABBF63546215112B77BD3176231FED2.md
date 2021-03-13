---
title: MBR2GPT.EXE | 
excerpt: What is MBR2GPT.EXE?
---

# MBR2GPT.EXE 

* File Path: `C:\Windows\system32\MBR2GPT.EXE`

## Hashes

Type | Hash
-- | --
MD5 | `5ABBF63546215112B77BD3176231FED2`
SHA1 | `A4FC9605276047280DEFE561E056AB01093FF257`
SHA256 | `6C6452F2461D9F77D8AB9378C089F08F73481B3DB1E1E8E5911FAC3857CD0752`
SHA384 | `3B34B549BD50E89C70268B50D181E11CC105352296ADED566D62E8E109536C3943739E711E2B5739C55D90918B8239DD`
SHA512 | `B4535D144C1B12FE1B8850E48CC33AC206C027CBE469259E5EB49FEE9B7E774000DC56FF07FCE366A57E906C4044562E95552985FFD7BBC4132797C16D604380`
SSDEEP | `12288:+x6NcdicF9e4Yb1pLAqCwNUnilk8Hx+ppxlUyJ8GjTuFGSFLQVP7xvlzb:Qkcdez123wNgTB7Sle7xN`
IMP | `E3A65FE55A8ECE1517AA67B167383A33`
PESHA1 | `7243688F30ADE97712CDD9F2B2AD8B8CD18B6556`
PE256 | `BBEC14BCF655711A50698F328A37CB20829C38D3546772A219DC1E438F389865`

## Runtime Data

### Usage (stdout):
```cmhg

Converts a disk from MBR to GPT partitioning without modifying or deleting data on the disk.

MBR2GPT.exe /validate|convert [/disk:<diskNumber>] [/logs:<logDirectory>] [/map:<source>=<destination>] [/allowFullOS]

Where:

 /validate
         - Validates that the selected disk can be converted
           without performing the actual conversion.

 /convert
         - Validates that the selected disk can be converted
           and performs the actual conversion.

 /disk:<diskNumber>
         - Specifies the disk number of the disk to be processed.
           If not specified, the system disk is processed.

 /logs:<logDirectory>
         - Specifies the directory for logging. By default logs
           are created in the %windir% directory.

 /map:<source>=<destination>
         - Specifies the GPT partition type to be used for a
           given MBR partition type not recognized by Windows.
           Multiple /map switches are allowed.

 /allowFullOS
         - Allows the tool to be used from the full Windows
           environment. By default, this tool can only be used
           from the Windows Preinstallation Environment.


```

### Usage (stderr):
```cmhg
Invalid argument: --help

Invalid arguments


```

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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


