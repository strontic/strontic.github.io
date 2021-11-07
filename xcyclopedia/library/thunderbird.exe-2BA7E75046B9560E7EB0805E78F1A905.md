---
title: thunderbird.exe | Thunderbird
excerpt: What is thunderbird.exe?
---

# thunderbird.exe 

* File Path: `C:\Program Files\Mozilla Thunderbird\thunderbird.exe`
* Description: Thunderbird
* Comments: Mozilla Thunderbird Mail and News Client


## Hashes

Type | Hash
-- | --
MD5 | `2BA7E75046B9560E7EB0805E78F1A905`
SHA1 | `9FD0CE66B2C737B4000A2CD343AD80B03ABD1FFF`
SHA256 | `76179D2F4074A922BE24AB942253D4562EF95066AB498786149EAB40CDD9FEE8`
SHA384 | `EB63AC99AA25E105559264AEB1F2A06F03D82ECDF2C3F3D9CD1F20C2AEDC047BD2C6820658D148F846FEB1060CDB243A`
SHA512 | `0D6A3AF496E2F8C2DFA2EE55578C156642C6ACBC3D949BA3E8FF397CDF7B086D2FD10662311C7C4F754DA594030E0E2BF81A49FFCDCA3A5BCF8D21561D380043`
SSDEEP | `6144:0OVggDlaPNs0F9hcWItg1ZuJgbQA6T8R2Bq8iSDohn5ymC1tIVy2:BS2Rtg1oI2Bq8XDoJ5ymC1+l`
IMP | `EA98ED96993C3A1B0AFAB4EF083C758B`
PESHA1 | `B5787A2829DD2150D259967AAB5AA7B4CB9348ED`
PE256 | `07CA940E896B133EFCA1A2622552FC4F43D6C88388A1E18EC7E35ADCB691BE25`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: C:\Program Files\Mozilla Thunderbird\thunderbird.exe [ options ... ] [URL]
       where options include:

  -h or --help       Print this message.
  -v or --version    Print Thunderbird version.
  --full-version     Print Thunderbird version, build and platform build ids.
  -P <profile>       Start with <profile>.
  --profile <path>   Start with profile at <path>.
  --migration        Start with migration wizard.
  --ProfileManager   Start with ProfileManager.
  --no-remote        Do not accept or send remote commands; implies
                     --new-instance.
  --new-instance     Open new instance, not a new window in running instance.
  --safe-mode        Disables extensions and themes for this session.
  --allow-downgrade  Allows downgrading a profile.
  --MOZ_LOG=<modules> Treated as MOZ_LOG=<modules> environment variable,
                     overrides it.
  --MOZ_LOG_FILE=<file> Treated as MOZ_LOG_FILE=<file> environment variable,
                     overrides it. If MOZ_LOG_FILE is not specified as an
                     argument or as an environment variable, logging will be
                     written to stdout.
  --console          Start Thunderbird with a debugging console.
  --headless         Run without a GUI.
  -addressbook       Open the address book at startup.
  -compose [ <options> ] Compose a mail or news message. Options are specified
                     as string "option='value,...',option=value,..." and
                     include: from, to, cc, bcc, newsgroups, subject, body,
                     message (file), attachment (file), format (html | text).
                     Example: "to=john@example.com,subject='Dinner tonight?'"
  --jsconsole        Open the Browser Console.
  --jsdebugger [<path>] Open the Browser Toolbox. Defaults to the local build
                     but can be overridden by a firefox path.
  --wait-for-jsdebugger Spin event loop until JS debugger connects.
                     Enables debugging (some) application startup code paths.
                     Only has an effect when `--jsdebugger` is also supplied.
  --devtools         Open DevTools on initial load.
  --start-debugger-server [ws:][ <port> | <path> ] Start the devtools server on
                     a TCP port or Unix domain socket path. Defaults to TCP port
                     6000. Use WebSocket protocol if ws: prefix is specified.
  -mail              Open the mail folder view.
  -mail <URL>        Open the message specified by this URL.
  -news              Open the news client.
  --recording <file> Record drawing for a given URL.
  --recording-output <file> Specify destination file for a drawing recording.
  --remote-debugging-port [<port>] Start the Firefox remote agent,
                     which is a low-level debugging interface based on the CDP protocol.
                     Defaults to listen on localhost:9222.
  -options           Open the options dialog.
  -file              Open the specified email file or ICS calendar file.
  -setDefaultMail    Set this app as the default mail client.

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Mozilla Thunderbird\mozglue.dll |
C:\Program Files\Mozilla Thunderbird\MSVCP140.dll |
C:\Program Files\Mozilla Thunderbird\thunderbird.exe |
C:\Program Files\Mozilla Thunderbird\VCRUNTIME140.dll |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\WINTRUST.dll |


## Signature

* Status: Signature verified.
* Serial: `0C1CD3EEA47EDDA7A032573B014D0AFD`
* Thumbprint: `1326B39C3D5D2CA012F66FB439026F7B59CB1974`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Mozilla Corporation, OU=Firefox Engineering Operations, O=Mozilla Corporation, L=Mountain View, S=California, C=US

## File Metadata

* Original Filename: thunderbird.exe
* Product Name: Thunderbird
* Company Name: Mozilla Corporation
* File Version: 91.3.0
* Product Version: 91.3.0
* Language: Language Neutral
* Legal Copyright: Thunderbird and Mozilla Developers, according to the MPL 1.1/GPL 2.0/LGPL 2.1 licenses, as applicable.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/76179d2f4074a922be24ab942253d4562ef95066ab498786149eab40cdd9fee8/detection


## Possible Misuse

*The following table contains possible examples of `thunderbird.exe` being misused. While `thunderbird.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [turla-outlook.yar](https://github.com/eset/malware-ioc/blob/master/turla/turla-outlook.yar) | `$s5 = "Software\\Mozilla\\Mozilla Thunderbird\\Profiles" ascii wide`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [general_cloaking.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/general_cloaking.yar) | and not filepath contains "Thunderbird" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


