---
title: recover.exe | Recover Files Utility
excerpt: What is recover.exe?
---

# recover.exe 

* File Path: `C:\WINDOWS\system32\recover.exe`
* Description: Recover Files Utility

## Hashes

Type | Hash
-- | --
MD5 | `959C34797C8B15E7B66B8D9609D162C4`
SHA1 | `4A60EE2EABE93261F73474B152A7DADA0AE46B90`
SHA256 | `C058763D70DA19240090335942BF92BA038129D88D033994548526FA7B44367A`
SHA384 | `D95C720A1FC28DC3FF04FC7E3CE814536F81EFFA83517D30F63F68285D475A906E4B853A3C97E67891865E2C57313AF2`
SHA512 | `6FF0A02ACBE8BCCE45EC5C7B8D412AE3792745964D746A41B97A1F97A49559AF871E96DE84216176F7366BA0842B8FE3827C828629E334BF72F0DA8AFF42DD15`
SSDEEP | `192:bcqaHcXL7QQkgIEzY1aDfN0WCOZjwqnG0Vc2gSm2TWlnWVh:4qJL717lEEDmWhhhjc2TWlnW`

## Runtime Data

### Usage (stdout):
```cmhg
Access Denied as you do not have sufficient privileges or
the disk may be locked by another process.
You have to invoke this utility running in elevated mode
and make sure the disk is unlocked.

```

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Recover.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\recover.exe](recover.exe-89DA1734EAA590115A227C8E60E6C7B9.md) | 30

## Possible Misuse

*The following table contains possible examples of `recover.exe` being misused. While `recover.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [azure_keyvault_key_modified_or_deleted.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/azure/azure_keyvault_key_modified_or_deleted.yml) | `- MICROSOFT.KEYVAULT/VAULTS/KEYS/RECOVER/ACTION`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [azure_keyvault_secrets_modified_or_deleted.yml](https://github.com/Neo23x0/sigma/blob/master/rules/cloud/azure/azure_keyvault_secrets_modified_or_deleted.yml) | `- MICROSOFT.KEYVAULT/VAULTS/SECRETS/RECOVER/ACTION`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1048.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1048.003/T1048.003.md) | 3. Once the data is received, use the below command to recover the data. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.002/T1110.002.md) | <blockquote>Adversaries may use password cracking to attempt to recover usable credentials, such as plaintext passwords, when credential material such as password hashes are obtained. [OS Credential Dumping](https://attack.mitre.org/techniques/T1003) is used to obtain password hashes, this may only get an adversary so far when [Pass the Hash](https://attack.mitre.org/techniques/T1550/002) is not an option. Techniques to systematically guess the passwords used to compute hashes are available, or the adversary may use a pre-computed rainbow table to crack hashes. Cracking hashes is usually done on adversary-controlled systems outside of the target network.(Citation: Wikipedia Password cracking) The resulting plaintext password resulting from a successfully cracked hash may be used to log into systems, resources, and services in which the account has access.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## recover

Recovers readable information from a bad or defective disk. This command reads a file, sector-by-sector, and recovers data from the good sectors. Data in bad sectors is lost. Because all data in bad sectors is lost when you recover a file, you should recover only one file at a time.

Bad sectors reported by the **chkdsk** command were marked as bad when your disk was prepared for operation. They pose no danger, and **recover** does not affect them.

### Syntax

```
recover [<drive>:][<path>]<filename>
```

#### Parameters

| Parameter | Description |
|--|--|
| `[<drive>:][<path>]<filename>` | Specifies the file name (and the location of the file if it is not in the current directory) you want to recover. *Filename* is required and wildcards aren't supported. |
| /? | Displays help at the command prompt. |

#### Examples

To recover the file *story.txt* in the *\fiction* directory on drive D, type:

```
recover d:\fiction\story.txt
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


