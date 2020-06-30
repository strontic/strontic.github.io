---
title: regedit.exe | Registry Editor
---

# regedit.exe 

* File Path: `C:\Windows\SysWOW64\regedit.exe`
* Description: Registry Editor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `08D8384279EB3E25242B270860193E1C`
SHA1 | `95A9C5AEE9B5211B93520B3CD965F2D20274DD9E`
SHA256 | `92E81342732CCE1EEFC16629B4587E8C4338AE6B180018CFB870E51C64BBC203`
SHA384 | `DBDA116D279EC1159A8F9200D607655D646619600B92DB18A8783F0D636C1629E57A5596FA8D81AE511C803463155BEC`
SHA512 | `46AB72443B84A11D080895794988C42CB58D08D5B1DD030385B88DED0CE308A635A1E7E73CBFBCFCB54B4242C9DCDFFC62FFAC115A6BD18CD1E46D6E36F78078`
SSDEEP | `6144:R8e8Pp1u42+2LFd2KBiPQRZ66z+n4VZbd8g79pgrXNgRnVLjyzhbkidNN2:R8VPpS+aoKKQRZ66z24VZbdrpgrXN2LS`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: REGEDIT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\regedit.exe](regedit.exe-0EE48CC819E58D266827F8605AF17ABD.md) | 100
[C:\WINDOWS\regedit.exe](regedit.exe-29409008DF22243BB320333F9FD5C060.md) | 77
[C:\Windows\regedit.exe](regedit.exe-A3668018735B59050AD123A5A8CDC184.md) | 74
[C:\Windows\regedit.exe](regedit.exe-BF5D30514FEA913E25CCC9E546257088.md) | 71
[C:\WINDOWS\SysWOW64\regedit.exe](regedit.exe-01CE651BAE4DB16618DF8FF1A517E6E4.md) | 77
[C:\Windows\SysWOW64\regedit.exe](regedit.exe-092D4E7FA32499F18B879080AA994C46.md) | 74
[C:\Windows\SysWOW64\regedit.exe](regedit.exe-2E327F27B5B836D8304DF46E8E20341A.md) | 71

## Possible Misuse

*The following table contains possible examples of `regedit.exe` being misused. While `regedit.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | `Name: Regedit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | `  - Command: regedit /E c:\ads\file.txt:regfile.reg HKEY_CURRENT_USER\MyCustomRegKey` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | `  - Command: regedit C:\ads\file.txt:regfile.reg` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | `  - Path: C:\Windows\System32\regedit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | `  - Path: C:\Windows\SysWOW64\regedit.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | ` - IOC: regedit.exe reading and writing to alternate data stream` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Regedit.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Regedit.yml) | ` - IOC: regedit.exe should normally not be executed by end-users` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `                "description": "Masquerading occurs when the name or location of an executable, legitimate or malicious, is manipulated or abused for the sake of evading defenses and observation. Several different variations of this technique have been observed.\n\nOne variant is for an executable to be placed in a commonly trusted directory or given the name of a legitimate, trusted program. Alternatively, the filename given may be a close approximation of legitimate programs or something innocuous. An example of this is when a common system utility or program is moved and renamed to avoid detection based on its usage.(Citation: FireEye APT10 Sept 2018) This is done to bypass tools that trust executables by relying on file name or path, as well as to deceive defenders and system administrators into thinking a file is benign by associating the name with something that is thought to be legitimate.\n\nA third variant uses the right-to-left override (RTLO or RLO) character (U+202E) as a means of tricking a user into executing what they think is a benign file type but is actually executable code. RTLO is a non-printing character that causes the text that follows it to be displayed in reverse.(Citation: Infosecinstitute RTLO Technique) For example, a Windows screensaver file named <code>March 25 \\u202Excod.scr</code> will display as <code>March 25 rcs.docx</code>. A JavaScript file named <code>photo_high_re\\u202Egnp.js</code> will be displayed as <code>photo_high_resj.png</code>. A common use of this technique is with spearphishing attachments since it can trick both end users and defenders if they are not aware of how their tools display and render the RTLO character. Use of the RTLO character has been seen in many targeted intrusion attempts and criminal activity.(Citation: Trend Micro PLEAD RTLO)(Citation: Kaspersky RTLO Cyber Crime) RTLO can be used in the Windows Registry as well, where regedit.exe displays the reversed characters but the command line tool reg.exe does not by default. \n\nAdversaries may modify a binary's metadata, including such fields as icons, version, name of the product, description, and copyright, to better blend in with the environment and increase chances of deceiving a security analyst or product.(Citation: Threatexpress MetaTwin 2017)\n\n### Windows\nIn another variation of this technique, an adversary may use a renamed copy of a legitimate utility, such as rundll32.exe. (Citation: Endgame Masquerade Ball) An alternative case occurs when a legitimate utility is moved to a different directory and also renamed to avoid detections based on system utilities executing from non-standard paths. (Citation: F-Secure CozyDuke)\n\nAn example of abuse of trusted locations in Windows would be the <code>C:\\Windows\\System32</code> directory. Examples of trusted binary names that can be given to malicious binares include \"explorer.exe\" and \"svchost.exe\".\n\n### Linux\nAnother variation of this technique includes malicious binaries changing the name of their running process to that of a trusted or benign process, after they have been launched as opposed to before. (Citation: Remaiten)\n\nAn example of abuse of trusted locations in Linux  would be the <code>/bin</code> directory. Examples of trusted binary names that can be given to malicious binaries include \"rsyncd\" and \"dbus-inotifier\". (Citation: Fysbis Palo Alto Analysis)  (Citation: Fysbis Dr Web Analysis)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `regedit.exe` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | regedit /E #{path}\file.txt:regfile.reg HKEY_CURRENT_USER\MyCustomRegKey | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


