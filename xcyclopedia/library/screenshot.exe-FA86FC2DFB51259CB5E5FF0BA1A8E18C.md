---
title: screenshot.exe | snappy
excerpt: What is screenshot.exe?
---

# screenshot.exe 

* File Path: `C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\screenshot\screenshot.exe`
* Description: snappy

## Hashes

Type | Hash
-- | --
MD5 | `FA86FC2DFB51259CB5E5FF0BA1A8E18C`
SHA1 | `B5525484FF55740AF7456EA86181124432A6E60D`
SHA256 | `99020FFD0722DE754CCA334CA6230F374AFCE8962156E8C5B591CA4841402B40`
SHA384 | `7041A1B1BA6F4ADF79ECEBCCE53D6E42288C2549A9FD57DB64703E5931C0BCCA6CCF4A4AE883EF1919E20932FE917E88`
SHA512 | `BA6E82919BA86CC8D8F0968EFF95DA64DFEC096846FB29DF5766BEADB4719369D7F1572E1A32BFE76F87FAE892AD499782D3BC784A7923F90E0B8B8462A9B4E2`
SSDEEP | `1536:i92kaba6OJJYdUjTmwpk2dcNWT8aipiPWMNai7DWXi4U:yVaba60/qwppcgT8fmD5DgxU`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user\Documents | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\screenshot\screenshot.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `00E7E6FE263192D15EAC485B4198E64488`
* Thumbprint: `3A427356A24983C1C8211C07CF766D4726A33E4F`
* Issuer: CN=COMODO RSA Code Signing CA, O=COMODO CA Limited, L=Salford, S=Greater Manchester, C=GB
* Subject: CN=Jernej Simoni, O=Jernej Simoni, STREET=Herbersteinova 29, L=Ljubljana, S=-, PostalCode=1000, C=SI

## File Metadata

* Original Filename: snappy.exe
* Product Name: SeteraSoft snappy
* Company Name: SeteraSoft
* File Version: 1, 0, 0, 1
* Product Version: 1, 0, 0, 1
* Language: Language Neutral
* Legal Copyright: Copyright  1999


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\GIMP 2\bin\gimp-debug-resume.exe](gimp-debug-resume.exe-47255EE357A7B27710D5F1680A4A770F.md) | 40
[C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\file-exr\file-exr.exe](file-exr.exe-1FED269F021DE40160452865E2B6DDC7.md) | 41
[C:\program files\GIMP 2\lib\gimp\2.0\plug-ins\help-browser\help-browser.exe](help-browser.exe-E72ED15D5625813A7EF8E4BBC1C7F379.md) | 35

## Possible Misuse

*The following table contains possible examples of `screenshot.exe` being misused. While `screenshot.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_powershell_exploit_scripts.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_powershell_exploit_scripts.yml) | `- '*\Get-Screenshot.ps1'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_malicious_commandlets.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_malicious_commandlets.yml) | `- "*Get-Screenshot*"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- https://www.carbonblack.com/2014/06/10/screenshot-demo-hunt-evil-faster-than-ever-with-carbon-black/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [keydnap](https://github.com/eset/malware-ioc/blob/master/keydnap/README.adoc) | `\| `78ba1152ef3883e63f10c3a85cbf00f2bb305a6a` \| screenshot_2016-06-28-01.jpg \| 2016-06-28 \| hxxp://freesafesoft.com/icloudsyncd \| BlackHat-TDS Panel screenshot` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [keydnap](https://github.com/eset/malware-ioc/blob/master/keydnap/README.adoc) | `\| `773a82343367b3d09965f6f09cc9887e7f8f01bf` \| screenshot.jpg \| 2016-05-07 \| hxxp://dev.aneros.com/media/icloudsyncd \| Firefox 20 about screenshot` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `screenshot` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | <blockquote>Adversaries may attempt to take screen captures of the desktop to gather information over the course of an operation. Screen capturing functionality may be included as a feature of a remote access tool used in post-compromise operations. Taking a screenshot is also typically possible through native utilities or API calls, such as <code>CopyFromScreen</code>, <code>xwd</code>, or <code>screencapture</code>.(Citation: CopyFromScreen .NET)(Citation: Antiquated Mac Malware) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | Use screencapture command to collect a full desktop screenshot | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | Use xwd command to collect a full desktop screenshot and review file with xwud | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | Use import command to collect a full desktop screenshot | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_freemilk.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_freemilk.yar) | $s1 = "failed to take the screenshot. err: %d" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fvey_shadowbroker_jan17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fvey_shadowbroker_jan17.yar) | Identifier: ShadowBroker Screenshot Rules | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_fireball.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_fireball.yar) | $s2 = "ScreenShot" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_crimson_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_crimson_rat.yar) | $x5 = "/screen >> ScreenShot from target PC" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $string4 = "screens\\screenshot" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


