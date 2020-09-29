---
title: netshell.dll | Network Connections Shell
excerpt: What is netshell.dll?
---

# netshell.dll 

* File Path: `C:\Windows\SysWOW64\netshell.dll`
* Description: Network Connections Shell

## Hashes

Type | Hash
-- | --
MD5 | `2DFA0CD1D732E7E6A0C315C51FF22061`
SHA1 | `5FA419ECC414344CBD58C51E4AB98D562496F7B1`
SHA256 | `4D0982364B72B8F3AE70C4884D5DE45F8D83EEC72FB809432AC971CBE2C64D3E`
SHA384 | `3757506F5080BA24E6667C5C4729A9AB9BB20F97A5E128C8D85EE3569B9F709B90B20254D617254CC7B0EE055E0760CC`
SHA512 | `071BC614674F86F5737E3026C184C63B88BFB753A77E44BFDEEDD72FB9A97B60208FDDE808FF50AB4A1E05A3C0C385B3D6E043F322D41B7AFA8151ED392F7B7F`
SSDEEP | `6144:NVhMsnNsD9EPgOgzG94U7YtPqZgWDDIMcK8hJrq1V6vikd+/wG:xMENGE4OgzG945kZ1DDtc9AV6BOwG`
IMP | `03DC051588AD18F13E6F036FB3BF953E`
PESHA1 | `88005576065EC0130E542779C80D3427661DCB6B`
PE256 | `0D6CE336A37BCC1BFF98CEB1D072E5DC70F01A8355B73D1FE2093300B5FE1727`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x7460f9e0 | 0x0000f9e0
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x7460fa10 | 0x0000fa10
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x7460fa90 | 0x0000fa90
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x7460fa90 | 0x0000fa90
`HrCreateDesktopIcon` | 5 (0x5) | Exported Function | 0x7460fae0 | 0x0000fae0
`HrGetIconFromMediaType` | 6 (0x6) | Exported Function | 0x7460fea0 | 0x0000fea0
`HrGetIconFromMediaTypeEx` | 7 (0x7) | Exported Function | 0x7460fef0 | 0x0000fef0
`HrLaunchConnection` | 8 (0x8) | Exported Function | 0x7460fbc0 | 0x0000fbc0
`HrLaunchConnectionEx` | 9 (0x9) | Exported Function | 0x7460fca0 | 0x0000fca0
`HrRenameConnection` | 10 (0xa) | Exported Function | 0x7460fde0 | 0x0000fde0
`NcFreeNetconProperties` | 11 (0xb) | Exported Function | 0x7460faa0 | 0x0000faa0
`NcIsValidConnectionName` | 12 (0xc) | Exported Function | 0x7460fac0 | 0x0000fac0
`StartNCW` | 13 (0xd) | Exported Function | 0x7460ff20 | 0x0000ff20


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netshell.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/4d0982364b72b8f3ae70c4884d5de45f8d83eec72fb809432ac971cbe2c64d3e/detection/


## Possible Misuse

*The following table contains possible examples of `netshell.dll` being misused. While `netshell.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Netsh.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Netsh.yml) | `- Link: https://htmlpreview.github.io/?https://github.com/MatthewDemaske/blogbackup/blob/master/netshell.html` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.007/T1546.007.md) | <blockquote>Adversaries may establish persistence by executing malicious content triggered by Netsh Helper DLLs. Netsh.exe (also referred to as Netshell) is a command-line scripting utility used to interact with the network configuration of a system. It contains functionality to add helper DLLs for extending functionality of the utility. (Citation: TechNet Netsh) The paths to registered netsh.exe helper DLLs are entered into the Windows Registry at <code>HKLM\SOFTWARE\Microsoft\Netsh</code>. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


