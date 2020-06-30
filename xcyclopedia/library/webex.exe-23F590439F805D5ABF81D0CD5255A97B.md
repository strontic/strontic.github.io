---
title: webex.exe | Cisco Webex Meeting
---

# webex.exe 

* File Path: `C:\ProgramData\WebEx\webex.exe`
* Description: Cisco Webex Meeting
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `23F590439F805D5ABF81D0CD5255A97B`
SHA1 | `413EEFFBC3E28320B16B0D0605667FF4D5040191`
SHA256 | `615B095FC46BD3E08988B4799681473677BB4949CA7B736913BF428CC97E9E1B`
SHA384 | `09D9061EBF1E8179AB60A246611DCF6CB7CAC854CE823C60EAD5841DC2EC10860D1769D99AA2004AAA79E076D37EBAAD`
SHA512 | `3E9857AA8D2F5463FBEB4AAC2C4C259D6CA79C7F440F9FB9724BD071300C396140070F65011F4099556EE33E3A03479C08E49E97917E2EA898F90433F175FAE4`
SSDEEP | `12288:RujXKKv7VnbJKNWL5eM5fNmaKIDeyBUruYo7g1jA1F3RhNT5bsmoihBwF6kk:EXKKpJKw04mUBCuYo810n3RTdsmoiheS`

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
* Serial: `4E5B56471959570CA0F805DF61D018DF`
* Thumbprint: `2491FC608AE018A29565D564DDB14BCDE435DC9C`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Cisco WebEx LLC, O=Cisco WebEx LLC, L=San Jose, S=California, C=US

## File Metadata

* Original Filename: CiscoWebExStart.exe
* Product Name: Cisco Webex Meeting
* Company Name: Cisco Webex LLC
* File Version: 10032,999,2018,614
* Product Version: 10032,999,2018,614
* Language: English (United States)
* Legal Copyright:  2018 Cisco and/or its affiliates. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\ProgramData\WebEx\ciscowebexstart.exe](ciscowebexstart.exe-23F590439F805D5ABF81D0CD5255A97B.md) | 100

## Possible Misuse

*The following table contains possible examples of `webex.exe` being misused. While `webex.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_prog_location_network_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_susp_prog_location_network_connection.yml) | `            # - '*\ProgramData\\*'  # too many false positives, e.g. with Webex for Windows` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_prog_location_network_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_susp_prog_location_network_connection.yml) | `            # - '*\ProgramData\\*'  # too many false positives, e.g. with Webex for Windows` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


