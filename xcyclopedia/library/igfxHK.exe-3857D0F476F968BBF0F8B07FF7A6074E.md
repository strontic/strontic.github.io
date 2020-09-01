---
title: igfxHK.exe | igfxHK Module
---

# igfxHK.exe 

* File Path: `C:\WINDOWS\system32\DriverStore\FileRepository\igdlh64.inf_amd64_69885addc92dcf91\igfxHK.exe`
* Description: igfxHK Module

## Hashes

Type | Hash
-- | --
MD5 | `3857D0F476F968BBF0F8B07FF7A6074E`
SHA1 | `84E7ED9A246A5F24CDF7576C6B94E2E8508E48B3`
SHA256 | `566E2A37880C67C14515994A9D5FF4A2A7CBDFF889D001BF1F04B661D6D21259`
SHA384 | `4B63EE527EC55230184371D496A75DA0B4352AC1BCA9357D7CABB5F1D8137F888F1BA017E060917153CBE5F2A058F85C`
SHA512 | `B9DF87FC810BB382A8EB08B640B31108381DFCBB6F3C1DDBBDE485610A0643FCF1A8819667141786533375151A97EED63E2D188CADAD91FAEBA850F9A65BE1ED`
SSDEEP | `6144:fxWDhqR9QT76bvD6w9b8ihrGQMUm6okJo9q9:fx2Q9YCaQVmYUQ`

### Loaded Modules:

Path |
-- |
C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\ifs-compose\ifs-compose.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000002D4E7AEC99B0F05F7300000000002D`
* Thumbprint: `431FA5538299F973C06FDE9D6E97CC81C047AB0E`
* Issuer: CN=Microsoft Windows Third Party Component CA 2012, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Hardware Compatibility Publisher, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IGFXHK.EXE
* Product Name: Intel(R) Common User Interface
* Company Name: Intel Corporation
* File Version: 6.15.10.3682
* Product Version: 6.15.10.3682
* Language: English (United States)
* Legal Copyright: Copyright 2012-2015, Intel Corporation


## Possible Misuse

*The following table contains possible examples of `igfxHK.exe` being misused. While `igfxHK.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) |         description = "Detects uncommon file size of igfxhk.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) |         and filename == "igfxhk.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


