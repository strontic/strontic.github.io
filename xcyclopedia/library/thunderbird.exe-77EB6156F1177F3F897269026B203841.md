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
MD5 | `77EB6156F1177F3F897269026B203841`
SHA1 | `0C4E07E1AACCA4FA60CF3D4FCA574EAB1C3F45AE`
SHA256 | `7DE9159646BA055BE7A7772FFED10A0FCA889071F48E4BC8D3BF8D02FF7902E3`
SHA384 | `2DA6FBF5F373B83370FA6BF8820A673BCA0068C4753E854BAAE3F61AFEC0666E383697671FA5E0F03243A49D74F3D0B9`
SHA512 | `8B38CCAA4824EC6EED126643DE06F454641B4850EB2101A1DCF0A15929B7F8176F39577C956F9261FDE778C85751C9FE55DE1D56C2DCD142F322E225B1EA4653`
SSDEEP | `6144:IVRAahVVIylMhNc1zFDk4QMcQxMCkk8oJJ1VR7LvMDfDgvNtIVyIKA:S1N1zFD9dyk8oJJ1VRvMfON+FKA`

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
  --UILocale <locale> Start with <locale> resources as UI Locale.
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
  -options           Open the options dialog.
  -file              Open the specified email file or ICS calendar file.
  -setDefaultMail    Set this app as the default mail client.

```

## Signature

* Status: Signature verified.
* Serial: `0DDEB53F957337FBEAF98C4A615B149D`
* Thumbprint: `91CABEA509662626E34326687348CAF2DD3B4BBA`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: E="release+certificates@mozilla.com", CN=Mozilla Corporation, OU=Firefox Engineering Operations, O=Mozilla Corporation, L=Mountain View, S=California, C=US

## File Metadata

* Original Filename: thunderbird.exe
* Product Name: Thunderbird
* Company Name: Mozilla Corporation
* File Version: 78.1.0
* Product Version: 78.1.1
* Language: Language Neutral
* Legal Copyright: Thunderbird and Mozilla Developers, according to the MPL 1.1/GPL 2.0/LGPL 2.1 licenses, as applicable.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\Mozilla Thunderbird\thunderbird.exe](thunderbird.exe-3C010B5C2E94A65E8BBCF62C880D9DC4.md) | 57
[C:\Program Files\Mozilla Thunderbird\thunderbird.exe](thunderbird.exe-78426A2669EAB01A71F33B7799715867.md) | 69

## Possible Misuse

*The following table contains possible examples of `thunderbird.exe` being misused. While `thunderbird.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [turla-outlook.yar](https://github.com/eset/malware-ioc/blob/master/turla/turla-outlook.yar) | `$s5 = "Software\\Mozilla\\Mozilla Thunderbird\\Profiles" ascii wide`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [general_cloaking.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/general_cloaking.yar) | and not filepath contains "Thunderbird" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


