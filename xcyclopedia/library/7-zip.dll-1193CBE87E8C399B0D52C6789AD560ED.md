---
title: 7-zip.dll | 7-Zip Shell Extension
excerpt: What is 7-zip.dll?
---

# 7-zip.dll 

* File Path: `C:\Program Files\7-Zip\7-zip.dll`
* Description: 7-Zip Shell Extension

## Hashes

Type | Hash
-- | --
MD5 | `1193CBE87E8C399B0D52C6789AD560ED`
SHA1 | `39B0CFA96F37F943AA7C993D2199BB590EFBC14B`
SHA256 | `D7104B8CA24D8BD9BF42675418E7A807FFC738D25D20B613E25C274672B2D530`
SHA384 | `6AF4BCB977E4A71BE7F3EE396A88B6AF0B1D5361D648A77EB006D3F9406570D516742DE1B34FE7B878D7BE79A61DD468`
SHA512 | `989841E2265D676C17E8474B4AFF65B37846030433243C6BCEAC957368E009A7538740535C78CB09B55DEE65DA6908AE245CE7CDB4386B0B1D8421609A6CEF7F`
SSDEEP | `1536:dHQxId3XsBBBBBRR5H3GLBqiBVclOmNbGvFo2WH7D2l+8:dww38BBBBBRRhiBqiBVczGvA7D2l+8`
IMP | `B0700FBB096CFFAF79B6267E2CC0276B`
PESHA1 | `89FC9F6F38F9484DEAF73A56F27F5A2F5465AE48`
PE256 | `6460D32EFFB518B7631BABFF35BE4867FDA46FC8EFB57044C6C08A6EFA7DB286`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function


## Signature

* Status: The file C:\Program Files\7-Zip\7-zip.dll is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 7-zip.dll
* Product Name: 7-Zip
* Company Name: Igor Pavlov
* File Version: 19.00
* Product Version: 19.00
* Language: English (United States)
* Legal Copyright: Copyright (c) 1999-2018 Igor Pavlov
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/d7104b8ca24d8bd9bf42675418e7a807ffc738d25d20b613e25c274672b2d530/detection/

## Possible Misuse

*The following table contains possible examples of `7-zip.dll` being misused. While `7-zip.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certutil.yml) | `- Command: certutil.exe -urlcache -split -f http://7-zip.org/a/7z1604-x64.exe 7zip.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Certutil.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Certutil.yml) | `- Command: certutil.exe -verifyctl -f -split http://7-zip.org/a/7z1604-x64.exe 7zip.exe` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.002/T1110.002.md) | Invoke-WebRequest "https://www.7-zip.org/a/7z1900.exe" -OutFile "$env:TEMP\7z1900.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1560.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1560.001/T1560.001.md) | <blockquote>An adversary may compress or encrypt data that is collected prior to exfiltration using 3rd party utilities. Many utilities exist that can archive data, including 7-Zip(Citation: 7zip Homepage), WinRAR(Citation: WinRAR Homepage), and WinZip(Citation: WinZip Homepage). Most utilities include functionality to encrypt and/or compress data. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


