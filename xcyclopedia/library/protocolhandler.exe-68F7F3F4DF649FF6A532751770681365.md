---
title: protocolhandler.exe | Microsoft Office
excerpt: What is protocolhandler.exe?
---

# protocolhandler.exe 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\protocolhandler.exe`
* Description: Microsoft Office

## Screenshot

![protocolhandler.exe](screenshots/protocolhandler.exe-68F7F3F4DF649FF6A532751770681365-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `68F7F3F4DF649FF6A532751770681365`
SHA1 | `43AE7093979405A77B6BBD79BA24F2FF51E0ABED`
SHA256 | `F0DC0D45D12FDDE03B8C16DECC4133E6F65C9028C277E2E9170318B863CFB1BD`
SHA384 | `D4B353F45082ECB7F3D36E151D07EF1D7F15E0F370065E55C6AC1A2C5C71E76EFF4FBD145ADF70A023CFF2F1549089DB`
SHA512 | `D3C5A8D84F6B5F22833907F4CEE77670855A7012CA0A4B9E8EC8BDC88720AABDC35715068088771D04C0448EE20983F681BDB7453F663267564D0F27FD96AA39`
SSDEEP | `98304:m7u2zs2iJXDdLwAuOpFK2o6rcAM/lIqEBURAj5CGRX0KXTB:j2zs2RAuOpBhky7`
IMP | `61D6DB4DE706D865691C73363B1082C4`
PESHA1 | `AD81601FCFE4B1538524C44D161EAE8D6B978563`
PE256 | `6F33AC65C47AE37F68BFBC6C24BBE58690A459DBAADFF2C5CE069D4A853D7FF7`

## Runtime Data

### Window Title:
Microsoft Office Error

### Open Handles:

Path | Type
-- | --
(R--)   C:\ProgramData\Microsoft\Office\ClickToRunPackageLocker | File
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\mswsock.dll.mui | File
(R-D)   C:\Windows\System32\en-US\winnlsres.dll.mui | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_5.82.19041.488_none_89e6152f0b32762e | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\F932B6C7-3A20-46A0-B8A0-8894AA421973 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\UrlZonesSM_user | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\windows_webcache_counters_{9B6AB5B3-91BC-4097-835C-EA2DEC95E9CC}_S-1-5-21-2047949552-857980807-821054962-504 | Section
\Sessions\1\Windows\Theme64749523 | Section
\Windows\Theme1120315852 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft Office\root\Office16\protocolhandler.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ProtocolHandler.exe
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20482
* Product Version: 16.0.12527.20482
* Language: Language Neutral
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 1/73
* VirusTotal Link: https://www.virustotal.com/gui/file/f0dc0d45d12fdde03b8c16decc4133e6f65c9028c277e2e9170318b863cfb1bd/detection/


## Possible Misuse

*The following table contains possible examples of `protocolhandler.exe` being misused. While `protocolhandler.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #5: ProtocolHandler.exe Downloaded a Suspicious File [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #5: ProtocolHandler.exe Downloaded a Suspicious File [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | - [Atomic Test #5 - ProtocolHandler.exe Downloaded a Suspicious File](#atomic-test-5---protocolhandlerexe-downloaded-a-suspicious-file) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ## Atomic Test #5 - ProtocolHandler.exe Downloaded a Suspicious File | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | #{microsoft_wordpath}\protocolhandler.exe "ms-word:nft\|u\|#{remote_url}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | ##### Description: Microsoft Word must be installed with the correct path and protocolhandler.exe must be provided | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218/T1218.md) | if (Test-Path "#{microsoft_wordpath}\protocolhandler.exe") {exit 0} else {exit 1}  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


