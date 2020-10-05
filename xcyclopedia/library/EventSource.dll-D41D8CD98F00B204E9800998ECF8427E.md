---
title: EventSource.dll | 
excerpt: What is EventSource.dll?
---

# EventSource.dll 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\ADDINS\Microsoft Power Query for Excel Integrated\bin\EventSource.dll`

## Hashes

Type | Hash
-- | --
MD5 | `D41D8CD98F00B204E9800998ECF8427E`
SHA1 | `DA39A3EE5E6B4B0D3255BFEF95601890AFD80709`
SHA256 | `E3B0C44298FC1C149AFBF4C8996FB92427AE41E4649B934CA495991B7852B855`
SHA384 | `38B060A751AC96384CD9327EB1B1E36A21FDB71114BE07434C0CC7BF63F6E1DA274EDEBFE76F65FBD51AD2F14898B95B`
SHA512 | `CF83E1357EEFB8BDF1542850D66D8007D620E4050B5715DC83F4A921D36CE9CE47D0D13C5D85F2B0FF8318D2877EEC2F63B931BD47417A81A538327AF927DA3E`
SSDEEP | `3::`
IMP | `n/a`
PESHA1 | `n/a`
PE256 | `n/a`


## Signature

* Status: The form specified for the subject is not one supported or known by the specified trust provider
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
* Machine Type: n/a

## File Scan

* VirusTotal Detections: 0/60
* VirusTotal Link: https://www.virustotal.com/gui/file/e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesCommonX86\Microsoft Shared\EQUATION\eqnedt32.exe](eqnedt32.exe-D41D8CD98F00B204E9800998ECF8427E.md) | 100

## Possible Misuse

*The following table contains possible examples of `EventSource.dll` being misused. While `EventSource.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [aws_cloudtrail_disable_logging.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/aws_cloudtrail_disable_logging.yml) | `- eventSource: cloudtrail.amazonaws.com` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [aws_config_disable_recording.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/aws_config_disable_recording.yml) | `- eventSource: config.amazonaws.com` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [aws_ec2_download_userdata.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/aws_ec2_download_userdata.yml) | `- eventSource: ec2.amazonaws.com` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [aws_ec2_startup_script_change.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/aws_ec2_startup_script_change.yml) | `- eventSource: ec2.amazonaws.com` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [aws_ec2_vm_export_failure.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/aws_ec2_vm_export_failure.yml) | `eventSource: 'ec2.amazonaws.com'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [aws_guardduty_disruption.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/aws_guardduty_disruption.yml) | `- eventSource: guardduty.amazonaws.com` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [aws_iam_backdoor_users_keys.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/aws_iam_backdoor_users_keys.yml) | `- eventSource: iam.amazonaws.com` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [aws_rds_change_master_password.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/aws_rds_change_master_password.yml) | `- eventSource: rds.amazonaws.com` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [aws_rds_public_db_restore.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/aws_rds_public_db_restore.yml) | `- eventSource: rds.amazonaws.com` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [ecs-cloudtrail.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/ecs-cloudtrail.yml) | `eventSource: event.provider` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [stix.yml](https://github.com/Neo23x0/sigma/blob/master/tools/config/stix.yml) | `eventSource:` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


