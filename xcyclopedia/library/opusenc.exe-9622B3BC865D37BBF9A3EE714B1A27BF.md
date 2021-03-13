---
title: opusenc.exe | 
excerpt: What is opusenc.exe?
---

# opusenc.exe 

* File Path: `C:\Program Files (x86)\AIMP3\System\Encoders\opusenc.exe`

## Hashes

Type | Hash
-- | --
MD5 | `9622B3BC865D37BBF9A3EE714B1A27BF`
SHA1 | `06445C74DC318D83720762E36AA5D1F16C424665`
SHA256 | `A5FE14E1989F83E06378C54AFCA5F4D0F46A48BA7B0AFCC4EE5E406ACF0B7833`
SHA384 | `9801C7A1EA83D983F304353ED1AF72DDA3023786D541F0959C2D9CDF2D366560F6038B57EA49B022D78DC5F73690F06E`
SHA512 | `8BB2669AA2FDC67AC95A321DB32202B6AD26875A916BE021706F6C08631C0A7E3A09FC67B15EEC2A606A1EFDB515864A1E0870A6BF2E548FC6B83D3F6966DF13`
SSDEEP | `6144:Qke+TpSRcE5GKeKvSkbb8yKEDIlwodqR5fM84YBlJW6mv9mU/+jAOnnZ2h:QKV45/fSkEcDswodqR5UnYByvxwxZ`
IMP | `9A2247C5F51BFB5107CB607B0893F31B`
PESHA1 | `4D4EB2316EA229C3D16327941F6DBF5EA65D10F4`
PE256 | `904906622D1C68C7F6CE6FC2999E0F3EA0CB3659BCF328B7501356096CE46F73`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: opusenc [options] input_file output_file.opus

Encode audio using Opus.
The input format can be Wave, AIFF, FLAC, Ogg/FLAC, or raw PCM.

input_file can be:
  filename.wav      file
  -                 stdin

output_file can be:
  filename.opus     compressed file
  -                 stdout

General options:
 -h, --help         Show this help
 -V, --version      Show version information
 --help-picture     Show help on attaching album art
 --quiet            Enable quiet mode

Encoding options:
 --bitrate n.nnn    Set target bitrate in kbit/s (6-256/channel)
 --vbr              Use variable bitrate encoding (default)
 --cvbr             Use constrained variable bitrate encoding
 --hard-cbr         Use hard constant bitrate encoding
 --music            Tune low bitrates for music (override automatic detection)
 --speech           Tune low bitrates for speech (override automatic detection)
 --comp n           Set encoding complexity (0-10, default: 10 (slowest))
 --framesize n      Set maximum frame size in milliseconds
                      (2.5, 5, 10, 20, 40, 60, default: 20)
 --expect-loss n    Set expected packet loss in percent (default: 0)
 --downmix-mono     Downmix to mono
 --downmix-stereo   Downmix to stereo (if >2 channels)
 --no-phase-inv     Disable use of phase inversion for intensity stereo
 --max-delay n      Set maximum container delay in milliseconds
                      (0-1000, default: 1000)

Metadata options:
 --title title      Set track title
 --artist artist    Set artist or author, may be used multiple times
 --album album      Set album or collection
 --tracknumber n    Set track number
 --genre genre      Set genre, may be used multiple times
 --date YYYY-MM-DD  Set date of track (YYYY, YYYY-MM, or YYYY-MM-DD)
 --comment tag=val  Add the given string as an extra comment
                      This may be used multiple times
 --picture file     Attach album art (see --help-picture)
                      This may be used multiple times
 --padding n        Reserve n extra bytes for metadata (default: 512)
 --discard-comments Don't keep metadata when transcoding
 --discard-pictures Don't keep pictures when transcoding

Input options:
 --raw              Interpret input as raw PCM data without headers
 --raw-bits n       Set bits/sample for raw input (default: 16)
 --raw-rate n       Set sampling rate for raw input (default: 48000)
 --raw-chan n       Set number of channels for raw input (default: 2)
 --raw-endianness n 1 for big endian, 0 for little (default: 0)
 --ignorelength     Ignore the data length in Wave headers

Diagnostic options:
 --serial n         Force use of a specific stream serial number
 --save-range file  Save check values for every frame to a file
 --set-ctl-int x=y  Pass the encoder control x with value y (advanced)
                      Preface with s: to direct the ctl to multistream s
                      This may be used multiple times

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\AIMP3\System\Encoders\opusenc.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: The file C:\Program Files (x86)\AIMP3\System\Encoders\opusenc.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/a5fe14e1989f83e06378c54afca5f4d0f46a48ba7b0afcc4ee5e406acf0b7833/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


