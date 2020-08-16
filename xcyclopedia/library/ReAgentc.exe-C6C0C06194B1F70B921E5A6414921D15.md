---
title: ReAgentc.exe | Microsoft Windows Recovery Agent
---

# ReAgentc.exe 

* File Path: `C:\Windows\system32\ReAgentc.exe`
* Description: Microsoft Windows Recovery Agent

## Hashes

Type | Hash
-- | --
MD5 | `C6C0C06194B1F70B921E5A6414921D15`
SHA1 | `36CF9A889DA67B858C6962E9A054C56E5B4825A0`
SHA256 | `6ED3121E5A6299EE1030F52D800F3F1F2EE1AAB5C73C99E0DD34034A23F7D44C`
SHA384 | `AF8FF5C893426E9DF0D027F2572AA225309EABD1ADD3A310259A96003993F7494FE662E6D207000C882840596330EE69`
SHA512 | `E4AF93849E6F8C8AEDE2793A12C3927D3B2E9C476811A15E6856A544025EDDE6D4C860156A59DB76157591DD59B5CFABF7273305F51E03653E9FDB44815F5D6E`
SSDEEP | `768:pk6DuaaMKodXVsc8EKx05aav1hrE7IrhRp4NfqavPFk/lmKVdMN8s61IY2:a6DuaaMKMMzna9asVv4Nfq9/lmKbw8Qr`

## Runtime Data

### Usage (stdout):
```Batchfile

Configures the Windows Recovery Environment (Windows RE) and system reset.

REAGENTC.EXE <command> <arguments>

The following commands can be specified:

  /info             - Displays Windows RE and system reset configuration
                      information.
  /setreimage       - Sets the location of the custom Windows RE image.
  /enable           - Enables Windows RE.
  /disable          - Disables Windows RE.
  /boottore         - Configures the system to start Windows RE next time the
                      system starts up.
  /setbootshelllink - Adds an entry to the Reset and Restore page in the boot
                      menu.

For more information about these commands and their arguments, type
REAGENTC.EXE <command> /?.

  Examples:
    REAGENTC.EXE /setreimage /?
    REAGENTC.EXE /disable /?

REAGENTC.EXE: Operation Successful.
    

```

### Usage (stderr):
```Batchfile

Configures the Windows Recovery Environment (Windows RE) and system reset.

REAGENTC.EXE <command> <arguments>

The following commands can be specified:

  /info             - Displays Windows RE and system reset configuration
                      information.
  /setreimage       - Sets the location of the custom Windows RE image.
  /enable           - Enables Windows RE.
  /disable          - Disables Windows RE.
  /boottore         - Configures the system to start Windows RE next time the
                      system starts up.
  /setbootshelllink - Adds an entry to the Reset and Restore page in the boot
                      menu.

For more information about these commands and their arguments, type
REAGENTC.EXE <command> /?.

  Examples:
    REAGENTC.EXE /setreimage /?
    REAGENTC.EXE /disable /?


```

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: reagentc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


