---
title: template.exe | 
excerpt: What is template.exe?
---

# template.exe 

* File Path: `C:\Program Files (x86)\Common Files\Adobe AIR\Versions\1.0\Resources\template.exe`

## Hashes

Type | Hash
-- | --
MD5 | `8A5A584D5555A5D2434C0F3D90B7EC7D`
SHA1 | `481ADD59E0E2539E99EA2335B2DE4ACB6A29BB40`
SHA256 | `D3A04C8A8F4338B6A944A231B49F2996DC5A539DB92A496B658763C816CEAF80`
SHA384 | `4959D0E1D95553C91A45ECAE342C2AF6570F9990839408D24D5F32747F8012B5B1BB84EB8D1DBDC575AE30CE2CF321D7`
SHA512 | `69EA9E9CA2913E50259E872C103CF2F857DEE2D5D7EB7A75AF28DE2F7E1EBA253D5BC6F26D6A90AD69B35CAFD41C8FC0D8A230244801BD075BD7B60D47134925`
SSDEEP | `1536:QI9Z5kh5Eui32qxrBcA8zu2YEU21ggSGPhVY10MwQPyTsWjVBcd6GGkdubO1:R32IBcAeqEUkglffwyy66GGSua`
IMP | `4F601DCB43304C66CF782B449F927733`
PESHA1 | `7F5DACE0347F08416EF1609776F4A1AF27AE4748`
PE256 | `8981638ABA8EA95661E44E16FCCEAD1686808EBA853D4DCF6BE6F26C027A5676`

## Runtime Data

### Child Processes:
Adobe AIR Updater.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_5.82.19041.488_none_89e6152f0b32762e | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\MacromediaFMOmega | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme2547664911 | Section
\Windows\Theme3854699184 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Common Files\Adobe AIR\Versions\1.0\Resources\template.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: The file C:\Program Files (x86)\Common Files\Adobe AIR\Versions\1.0\Resources\template.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/d3a04c8a8f4338b6a944a231b49f2996dc5a539db92a496b658763c816ceaf80/detection/


## Possible Misuse

*The following table contains possible examples of `template.exe` being misused. While `template.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_activity_by_terminated_user.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_activity_by_terminated_user.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_activity_from_anonymous_ip_addresses.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_activity_from_anonymous_ip_addresses.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_activity_from_infrequent_country.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_activity_from_infrequent_country.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_data_exfiltration_to_unsanctioned_app.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_data_exfiltration_to_unsanctioned_app.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_from_suspicious_ip_addresses.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_from_suspicious_ip_addresses.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_impossible_travel_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_impossible_travel_activity.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_logon_from_risky_ip_address.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_logon_from_risky_ip_address.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_potential_ransomware_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_potential_ransomware_activity.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_suspicious_inbox_forwarding.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_suspicious_inbox_forwarding.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_suspicious_oauth_app_file_download_activities.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_suspicious_oauth_app_file_download_activities.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_unusual_volume_of_file_deletion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_unusual_volume_of_file_deletion.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [microsoft365_user_restricted_from_sending_email.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/m365/microsoft365_user_restricted_from_sending_email.yml) | `- https://docs.microsoft.com/en-us/cloud-app-security/policy-template-reference`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [gamaredon](https://github.com/eset/malware-ioc/blob/master/gamaredon/README.adoc) | `advansed-template.site`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [gamaredon](https://github.com/eset/malware-ioc/blob/master/gamaredon/README.adoc) | `fix-template.site`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [gamaredon](https://github.com/eset/malware-ioc/blob/master/gamaredon/README.adoc) | `new-template.site`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [gamaredon](https://github.com/eset/malware-ioc/blob/master/gamaredon/README.adoc) | `normal-template.site`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [gamaredon](https://github.com/eset/malware-ioc/blob/master/gamaredon/README.adoc) | `old-template.site`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `hxxp://hotnews.16mb.com/wp-content/themes/twentysixteen/template-parts/content-header.php``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - [T1221 Template Injection](../../T1221/T1221.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: WINWORD Remote Template Injection [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - T1137.001 Office Template Macros [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) | - T1137.001 Office Template Macros [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - [T1221 Template Injection](../../T1221/T1221.md) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: WINWORD Remote Template Injection [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - T1137.001 Office Template Macros [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/linux-matrix.md) | \|  \|  \| Office Template Macros [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Valid Accounts [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Hidden Files and Directories](../../T1564.001/T1564.001.md) \| Unsecured Credentials [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| User Activity Based Checks [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \| Protocol Tunneling [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \| Office Template Macros [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Portable Executable Injection [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Hijack Execution Flow [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/matrix.md) | \|  \|  \|  \|  \| [Template Injection](../../T1221/T1221.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \| Office Template Macros [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| Path Interception by Search Order Hijacking [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \| [Hide Artifacts](../../T1564/T1564.md) \| Web Cookies [CONTRIBUTE A TEST](https://atomicredteam.io/contributing) \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-matrix.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Matrices/windows-matrix.md) | \|  \|  \|  \|  \| [Template Injection](../../T1221/T1221.md) \|  \|  \|  \|  \|  \|  \|  \| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1137.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1137/T1137.md) | <blockquote>Adversaries may leverage Microsoft Office-based applications for persistence between startups. Microsoft Office is a fairly common application suite on Windows-based operating systems within an enterprise network. There are multiple mechanisms that can be used with Office for persistence when an Office-based application is started; this can include the use of Office Template Macros and add-ins. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1187.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1187/T1187.md) | Adversaries may take advantage of this behavior to gain access to user account hashes through forced SMB/WebDAV authentication. An adversary can send an attachment to a user through spearphishing that contains a resource link to an external server controlled by the adversary (i.e. [Template Injection](https://attack.mitre.org/techniques/T1221)), or place a specially crafted file on navigation path for privileged accounts (e.g. .SCF file placed on desktop) or on a publicly accessible share to be accessed by victim(s). When the user's system accesses the untrusted resource it will attempt authentication and send information, including the user's hashed credentials, over SMB to the adversary controlled server. (Citation: GitHub Hashjacking) With access to the credential hash, an adversary can perform off-line [Brute Force](https://attack.mitre.org/techniques/T1110) cracking to gain access to plaintext credentials. (Citation: Cylance Redirect to SMB) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1187.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1187/T1187.md) | * A spearphishing attachment containing a document with a resource that is automatically loaded when the document is opened (i.e. [Template Injection](https://attack.mitre.org/techniques/T1221)). The document can include, for example, a request similar to <code>file[:]//[remote address]/Normal.dotm</code> to trigger the SMB request. (Citation: US-CERT APT Energy Oct 2017) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1221.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1221/T1221.md) | # T1221 - Template Injection | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1221.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1221/T1221.md) | Properties within parts may reference shared public resources accessed via online URLs. For example, template properties reference a file, serving as a pre-formatted document blueprint, that is fetched when the document is loaded. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1221.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1221/T1221.md) | Adversaries may abuse this technology to initially conceal malicious code to be executed via documents. Template references injected into a document may enable malicious payloads to be fetched and executed when the document is loaded. (Citation: SANS Brian Wiltse Template Injection) These documents can be delivered via other techniques such as [Phishing](https://attack.mitre.org/techniques/T1566) and/or [Taint Shared Content](https://attack.mitre.org/techniques/T1080) and may evade static detections since no typical indicators (VBA macro, script, etc.) are present until after the malicious payload is fetched. (Citation: Redxorblue Remote Template Injection) Examples have been seen in the wild where template injection was used to load malicious code containing an exploit. (Citation: MalwareBytes Template Injection OCT 2017) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1221.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1221/T1221.md) | This technique may also enable [Forced Authentication](https://attack.mitre.org/techniques/T1187) by injecting a SMB/HTTPS (or other credential prompting) URL and triggering an authentication attempt. (Citation: Anomali Template Injection MAR 2018) (Citation: Talos Template Injection July 2017) (Citation: ryhanson phishery SEPT 2016)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1221.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1221/T1221.md) | - [Atomic Test #1 - WINWORD Remote Template Injection](#atomic-test-1---winword-remote-template-injection) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1221.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1221/T1221.md) | ## Atomic Test #1 - WINWORD Remote Template Injection | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1221.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1221/T1221.md) | Open a .docx file that loads a remote .dotm macro enabled template from https://github.com/redcanaryco/atomic-red-team/tree/master/atomics/T1221/src/opencalc.dotm  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1221.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1221/T1221.md) | Executes the code specified within the .dotm template. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_dec20.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_dec20.yar) | description = "Webshell named template-query.aspimg.asp used by APT37" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_moonlightmaze.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_moonlightmaze.yar) | $a3="template string = \|%s\|"   ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wilted_tulip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wilted_tulip.yar) | $x2 = "C:\\Users\\admin\\Documents\\visual studio 2015\\Projects\\Export\\TDTESS_ShortOne\\WinService Template\\" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wilted_tulip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wilted_tulip.yar) | $s1 = "\\WinService Template\\obj\\x64\\x64\\winlogin" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cobalt_gang_pdf.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cobalt_gang_pdf.yar) | description = "Find documents saved from the same potential Cobalt Gang PDF template" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_shitrix.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_shitrix.yar) | $s07 = "template.new({'BLOCK'='print readpipe(" ascii /* TrustedSec templae */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_shitrix.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_shitrix.yar) | $s09 = "template.new({'BLOCK'=" /* PZI exploit URL decoded form */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_shitrix.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_shitrix.yar) | $s10 = "template.new({'BLOCK'%3d" /* PZI exploit URl encoded form */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_github_net_redteam_tools_guids.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_github_net_redteam_tools_guids.yar) | reference = "https://github.com/FuzzySecurity/Driver-Template" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s12 = "iKAT Exe Template" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "<xsl:template match=\"\"/root\"\">" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


