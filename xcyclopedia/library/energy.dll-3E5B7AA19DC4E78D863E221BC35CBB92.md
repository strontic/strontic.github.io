---
title: energy.dll | Power Efficiency Diagnostics
excerpt: What is energy.dll?
---

# energy.dll 

* File Path: `C:\Windows\system32\energy.dll`
* Description: Power Efficiency Diagnostics

## Hashes

Type | Hash
-- | --
MD5 | `3E5B7AA19DC4E78D863E221BC35CBB92`
SHA1 | `4C45A803064F800C3B3B6B46216FFCE4A12EC675`
SHA256 | `3FBA66BB548EF084DAC3C4F4D1FCFAE3EB9B007669AEFC3A74298A739244D8CD`
SHA384 | `4ECBF3BC872B22EA6288B743893909C5CC19D74840C0AB475883DEC4116514F06E30CEEE43164DCFE648DC474DB54793`
SHA512 | `4261ECEF74BDEF531C8226AEF2A7C889FBA86CC4E51445CA5C5D6E5DF4BDFAD41BC4123A3610248271D4C77FC28DD4A5A7F094B6D0A0BB417CD8EA2E77720396`
SSDEEP | `12288:rcQoRWNoxN7ut+82Hh3MvJLZW1Jslhv6bljcbwv6Xg9v6dazndL:rre9Hh3MSwib1cbwCQgdkL`
IMP | `5A6C1BB2D4CDFC861B6D3485BE83E4CA`
PESHA1 | `EC853D074E10388EB6D0E3ACF608B96034EFB726`
PE256 | `C5451B013F0E102B32A063AFF4854B9E0F27751A02F74B4E926F085C0F309D64`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`EnergyWizard_Analyze` | 3 (0x3) | Exported Function | 0x00000001800109a0 | 0x000109a0
`TransformBatteryReport` | 16 (0x10) | Exported Function | 0x000000018004b790 | 0x0004b790
`SendScreenOnTelemetry` | 15 (0xf) | Exported Function | 0x0000000180057bb0 | 0x00057bb0
`SaveSystemSleepDiagnosticsReport` | 14 (0xe) | Exported Function | 0x00000001800682e0 | 0x000682e0
`SaveSleepStudyReport` | 13 (0xd) | Exported Function | 0x0000000180057450 | 0x00057450
`SaveBatteryReport` | 1 (0x1) | Exported Function | 0x000000018004b580 | 0x0004b580
`EnergyWizard_TransformReport` | 12 (0xc) | Exported Function | 0x000000018004f0c0 | 0x0004f0c0
`TransformSleepStudyReport` | 17 (0x11) | Exported Function | 0x0000000180057de0 | 0x00057de0
`EnergyWizard_SqmAnalysis` | 11 (0xb) | Exported Function | 0x0000000180011980 | 0x00011980
`EnergyWizard_GetLogEntryCounts` | 9 (0x9) | Exported Function | 0x0000000180010890 | 0x00010890
`EnergyWizard_DestroyEnergyWizard` | 8 (0x8) | Exported Function | 0x0000000180013e40 | 0x00013e40
`EnergyWizard_DefaultTraceDuration` | 7 (0x7) | Exported Function | 0x0000000180016ee0 | 0x00016ee0
`EnergyWizard_CreateEnergyWizard` | 6 (0x6) | Exported Function | 0x0000000180011010 | 0x00011010
`EnergyWizard_CollectTrace` | 5 (0x5) | Exported Function | 0x0000000180004cf0 | 0x00004cf0
`EnergyWizard_CancelTrace` | 4 (0x4) | Exported Function | 0x000000018004f0a0 | 0x0004f0a0
`EnergyWizard_SaveReport` | 10 (0xa) | Exported Function | 0x00000001800110e0 | 0x000110e0
`TransformSystemSleepDiagnosticsReport` | 2 (0x2) | Exported Function | 0x0000000180067d00 | 0x00067d00


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: energy.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3fba66bb548ef084dac3c4f4d1fcfae3eb9b007669aefc3a74298a739244d8cd/detection/


## Possible Misuse

*The following table contains possible examples of `energy.dll` being misused. While `energy.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_tropictrooper.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_tropictrooper.yml) | `description: Detects TropicTrooper activity, an actor who targeted high-profile organizations in the energy and food and beverage sectors in Asia` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nouns.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/nouns.txt) | `energy` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-telebots.json](https://github.com/eset/malware-ioc/blob/master/telebots/misp-telebots.json) | `"value": "In the second half of 2016, ESET researchers identified a unique malicious toolset that was used in targeted cyberattacks against high-value targets in the Ukrainian financial sector. We believe that the main goal of attackers using these tools is cybersabotage. This blog post outlines the details about the campaign that we discovered.\r\n\r\nWe will refer to the gang behind the malware as TeleBots. However it\u2019s important to say that these attackers, and the toolset used, share a number of similarities with the BlackEnergy group, which conducted attacks against the energy industry in Ukraine in December 2015 and January 2016. In fact, we think that the BlackEnergy group has evolved into the TeleBots group.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-telebots.json](https://github.com/eset/malware-ioc/blob/master/telebots/misp-telebots.json) | `"description": "We will refer to the gang behind the malware as TeleBots. However it\u2019s important to say that these attackers, and the toolset used, share a number of similarities with the BlackEnergy group, which conducted attacks against the energy industry in Ukraine in December 2015 and January 2016. In fact, we think that the BlackEnergy group has evolved into the TeleBots group.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-mosquito-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-mosquito-event.json) | `"description": "A 2014 Guardian article described Turla as: 'Dubbed the Turla hackers, initial intelligence had indicated western powers were key targets, but it was later determined embassies for Eastern Bloc nations were of more interest. Embassies in Belgium, Ukraine, China, Jordan, Greece, Kazakhstan, Armenia, Poland, and Germany were all attacked, though researchers from Kaspersky Lab and Symantec could not confirm which countries were the true targets. In one case from May 2012, the office of the prime minister of a former Soviet Union member country was infected, leading to 60 further computers being affected, Symantec researchers said. There were some other victims, including the ministry for health of a Western European country, the ministry for education of a Central American country, a state electricity provider in the Middle East and a medical organisation in the US, according to Symantec. It is believed the group was also responsible for a much - documented 2008 attack on the US Central Command. The attackers - who continue to operate - have ostensibly sought to carry out surveillance on targets and pilfer data, though their use of encryption across their networks has made it difficult to ascertain exactly what the hackers took.Kaspersky Lab, however, picked up a number of the attackers searches through their victims emails, which included terms such as Nato and EU energy dialogue Though attribution is difficult to substantiate, Russia has previously been suspected of carrying out the attacks and Symantecs Gavin O\u2019 Gorman told the Guardian a number of the hackers appeared to be using Russian names and language in their notes for their malicious code. Cyrillic was also seen in use.'",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-comrat-v4-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-comrat-v4-event.json) | `"description": "A 2014 Guardian article described Turla as: 'Dubbed the Turla hackers, initial intelligence had indicated western powers were key targets, but it was later determined embassies for Eastern Bloc nations were of more interest. Embassies in Belgium, Ukraine, China, Jordan, Greece, Kazakhstan, Armenia, Poland, and Germany were all attacked, though researchers from Kaspersky Lab and Symantec could not confirm which countries were the true targets. In one case from May 2012, the office of the prime minister of a former Soviet Union member country was infected, leading to 60 further computers being affected, Symantec researchers said. There were some other victims, including the ministry for health of a Western European country, the ministry for education of a Central American country, a state electricity provider in the Middle East and a medical organisation in the US, according to Symantec. It is believed the group was also responsible for a much - documented 2008 attack on the US Central Command. The attackers - who continue to operate - have ostensibly sought to carry out surveillance on targets and pilfer data, though their use of encryption across their networks has made it difficult to ascertain exactly what the hackers took.Kaspersky Lab, however, picked up a number of the attackers searches through their victims emails, which included terms such as Nato and EU energy dialogue Though attribution is difficult to substantiate, Russia has previously been suspected of carrying out the attacks and Symantecs Gavin O’ Gorman told the Guardian a number of the hackers appeared to be using Russian names and language in their notes for their malicious code. Cyrillic was also seen in use.'",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-lightneuron-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-lightneuron-event.json) | `"description": "A 2014 Guardian article described Turla as: 'Dubbed the Turla hackers, initial intelligence had indicated western powers were key targets, but it was later determined embassies for Eastern Bloc nations were of more interest. Embassies in Belgium, Ukraine, China, Jordan, Greece, Kazakhstan, Armenia, Poland, and Germany were all attacked, though researchers from Kaspersky Lab and Symantec could not confirm which countries were the true targets. In one case from May 2012, the office of the prime minister of a former Soviet Union member country was infected, leading to 60 further computers being affected, Symantec researchers said. There were some other victims, including the ministry for health of a Western European country, the ministry for education of a Central American country, a state electricity provider in the Middle East and a medical organisation in the US, according to Symantec. It is believed the group was also responsible for a much - documented 2008 attack on the US Central Command. The attackers - who continue to operate - have ostensibly sought to carry out surveillance on targets and pilfer data, though their use of encryption across their networks has made it difficult to ascertain exactly what the hackers took.Kaspersky Lab, however, picked up a number of the attackers searches through their victims emails, which included terms such as Nato and EU energy dialogue Though attribution is difficult to substantiate, Russia has previously been suspected of carrying out the attacks and Symantecs Gavin O’ Gorman told the Guardian a number of the hackers appeared to be using Russian names and language in their notes for their malicious code. Cyrillic was also seen in use.'",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-outlook-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-outlook-event.json) | `"description": "A 2014 Guardian article described Turla as: 'Dubbed the Turla hackers, initial intelligence had indicated western powers were key targets, but it was later determined embassies for Eastern Bloc nations were of more interest. Embassies in Belgium, Ukraine, China, Jordan, Greece, Kazakhstan, Armenia, Poland, and Germany were all attacked, though researchers from Kaspersky Lab and Symantec could not confirm which countries were the true targets. In one case from May 2012, the office of the prime minister of a former Soviet Union member country was infected, leading to 60 further computers being affected, Symantec researchers said. There were some other victims, including the ministry for health of a Western European country, the ministry for education of a Central American country, a state electricity provider in the Middle East and a medical organisation in the US, according to Symantec. It is believed the group was also responsible for a much - documented 2008 attack on the US Central Command. The attackers - who continue to operate - have ostensibly sought to carry out surveillance on targets and pilfer data, though their use of encryption across their networks has made it difficult to ascertain exactly what the hackers took.Kaspersky Lab, however, picked up a number of the attackers searches through their victims emails, which included terms such as Nato and EU energy dialogue Though attribution is difficult to substantiate, Russia has previously been suspected of carrying out the attacks and Symantecs Gavin O\u2019 Gorman told the Guardian a number of the hackers appeared to be using Russian names and language in their notes for their malicious code. Cyrillic was also seen in use.'",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-powershell-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-powershell-event.json) | `"description": "A 2014 Guardian article described Turla as: 'Dubbed the Turla hackers, initial intelligence had indicated western powers were key targets, but it was later determined embassies for Eastern Bloc nations were of more interest. Embassies in Belgium, Ukraine, China, Jordan, Greece, Kazakhstan, Armenia, Poland, and Germany were all attacked, though researchers from Kaspersky Lab and Symantec could not confirm which countries were the true targets. In one case from May 2012, the office of the prime minister of a former Soviet Union member country was infected, leading to 60 further computers being affected, Symantec researchers said. There were some other victims, including the ministry for health of a Western European country, the ministry for education of a Central American country, a state electricity provider in the Middle East and a medical organisation in the US, according to Symantec. It is believed the group was also responsible for a much - documented 2008 attack on the US Central Command. The attackers - who continue to operate - have ostensibly sought to carry out surveillance on targets and pilfer data, though their use of encryption across their networks has made it difficult to ascertain exactly what the hackers took.Kaspersky Lab, however, picked up a number of the attackers searches through their victims emails, which included terms such as Nato and EU energy dialogue Though attribution is difficult to substantiate, Russia has previously been suspected of carrying out the attacks and Symantecs Gavin O’ Gorman told the Guardian a number of the hackers appeared to be using Russian names and language in their notes for their malicious code. Cyrillic was also seen in use.'",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-wateringhole-armenia-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-wateringhole-armenia-event.json) | `"description": "A 2014 Guardian article described Turla as: 'Dubbed the Turla hackers, initial intelligence had indicated western powers were key targets, but it was later determined embassies for Eastern Bloc nations were of more interest. Embassies in Belgium, Ukraine, China, Jordan, Greece, Kazakhstan, Armenia, Poland, and Germany were all attacked, though researchers from Kaspersky Lab and Symantec could not confirm which countries were the true targets. In one case from May 2012, the office of the prime minister of a former Soviet Union member country was infected, leading to 60 further computers being affected, Symantec researchers said. There were some other victims, including the ministry for health of a Western European country, the ministry for education of a Central American country, a state electricity provider in the Middle East and a medical organisation in the US, according to Symantec. It is believed the group was also responsible for a much - documented 2008 attack on the US Central Command. The attackers - who continue to operate - have ostensibly sought to carry out surveillance on targets and pilfer data, though their use of encryption across their networks has made it difficult to ascertain exactly what the hackers took.Kaspersky Lab, however, picked up a number of the attackers searches through their victims emails, which included terms such as Nato and EU energy dialogue Though attribution is difficult to substantiate, Russia has previously been suspected of carrying out the attacks and Symantecs Gavin O’ Gorman told the Guardian a number of the hackers appeared to be using Russian names and language in their notes for their malicious code. Cyrillic was also seen in use.'",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_blackenergy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_blackenergy.yar) | description = "Black Energy Driver" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_blackenergy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_blackenergy.yar) | description = "Black Energy Malware" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dragonfly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dragonfly.yar) | Reference: https://www.symantec.com/connect/blogs/dragonfly-western-energy-sector-targeted-sophisticated-attack-group | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dragonfly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dragonfly.yar) | reference = "https://www.symantec.com/connect/blogs/dragonfly-western-energy-sector-targeted-sophisticated-attack-group" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_greyenergy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_greyenergy.yar) | Identifier: Grey Energy | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_greyenergy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_greyenergy.yar) | description = "Detects samples from Grey Energy report" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


