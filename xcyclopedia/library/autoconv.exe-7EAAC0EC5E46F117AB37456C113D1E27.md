---
title: autoconv.exe | Auto File System Conversion Utility
excerpt: What is autoconv.exe?
---

# autoconv.exe 

* File Path: `C:\Windows\system32\autoconv.exe`
* Description: Auto File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `7EAAC0EC5E46F117AB37456C113D1E27`
SHA1 | `E462DD3FAF36B307C5A3FDCB1CA6BC808E35BEE8`
SHA256 | `31CF1CD007394E0E6F8926666917659927008BBEE9E6F4B218D4F359C215EBAA`
SHA384 | `692181E35C1150C9B13DBF37C863E480FF14F8E06A4E70FD7B0514206BCC842ED8E52A7DB2D4E9C649C9EC99F47FEB56`
SHA512 | `2A761987D453833064DF0F24EF017790CB05910559362CB22D874F7615E50F4819776850A2F00091C5310E1E8D39AD45D60DC3EE65289F20BB6306E5245BF6F0`
SSDEEP | `12288:ny7ALnaqABtb8wAnlWK82FDLpY12PyhgGP15N00Y6d6fBBtZr:y74nBetb8wAwkLpY126hgGP1H0aeTV`
IMP | `8BE61045829921D740DCA13576D33FA7`
PESHA1 | `36346D9134A8719C5ABC99B668CC69750E55A1B5`
PE256 | `8567E9B59BCABEBA4DAE7ED79A1DDB6E9BA321754B333A5CDD9ABE06A31B8EFE`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AUTOCONV.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1490 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1490
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## autoconv

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Converts file allocation table (Fat) and Fat32 volumes to the NTFS file system, leaving existing files and directories intact at startup after **autochk** runs. volumes converted to the NTFS file system cannot be converted back to Fat or Fat32.

> [!IMPORTANT]
> You can't run **autoconv** from the command-line. This can only run at startup, if set through **convert.exe**.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [autochk command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/autochk.md)

- [convert command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


