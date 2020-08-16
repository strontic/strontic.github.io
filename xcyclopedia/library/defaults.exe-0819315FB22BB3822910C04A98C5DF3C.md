---
title: defaults.exe | defaults
---

# defaults.exe 

* File Path: `C:\Program Files (x86)\Common Files\Apple\Apple Application Support\defaults.exe`
* Description: defaults

## Hashes

Type | Hash
-- | --
MD5 | `0819315FB22BB3822910C04A98C5DF3C`
SHA1 | `0AD18D9D8C62197363D360C2A968105555FFA031`
SHA256 | `D665A7C8AD3694E98EB8427473227C33EDD0C8A9D76720C8E95895FE4E08407C`
SHA384 | `422E5E4CF58A5CC9476157FBF8A49C7EF3F9F4772C3785727099F55441504FAD412C717ABFB410EF06D1508107545270`
SHA512 | `B59EF0F6AC1BD9968EA03890C5FDEE34ACE4B9BB029A371A853C9F2A9D3F332368DAFE1DA68F05AC64070EA32EA3944D90C2E1296B2F530BA1E88935F1A32EDA`
SSDEEP | `768:/smkzxEFknEej9a7sMtodSnx/objqvp4wa0pt3hxQ:/smkzekpjUZtNgqB4wa0pt3hxQ`

## Runtime Data

### Usage (stdout):
```Batchfile
Command line interface to a user's defaults.
Syntax:

'defaults' [-currentHost | -host <hostname>] followed by one of the following:

  read                                 shows all defaults
  read <domain>                        shows defaults for given domain
  read <domain> <key>                  shows defaults for given domain, key

  read-type <domain> <key>             shows the type for the given domain, key

  write <domain> <domain_rep>          writes domain (overwrites existing)
  write <domain> <key> <value>         writes key for domain

  rename <domain> <old_key> <new_key>  renames old_key to new_key

  delete <domain>                      deletes domain
  delete <domain> <key>                deletes key in domain

  domains                              lists all domains
  find <word>                          lists all entries containing word
  help                                 print this help

<domain> is ( <domain_name> | -app <application_name> | -globalDomain )
         or a path to a file omitting the '.plist' extension

<value> is one of:
  <value_rep>
  -string <string_value>
  -data <hex_digits>
  -int[eger] <integer_value>
  -float  <floating-point_value>
  -bool[ean] (true | false | yes | no)
  -date <date_rep>
  -array <value1> <value2> ...
  -array-add <value1> <value2> ...
  -dict <key1> <value1> <key2> <value2> ...
  -dict-add <key1> <value1> ...

```

## Signature

* Status: Signature verified.
* Serial: `4EF16586A2FF12D69C556EC4C91BAEE1`
* Thumbprint: `634A0D892E72161714861C178015AFE9C1832E14`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Apple Inc., O=Apple Inc., L=Cupertino, S=California, C=US

## File Metadata

* Original Filename: defaults.exe
* Product Name: defaults
* Company Name: Apple Inc.
* File Version: 1,950,522,0
* Product Version: 1,950,522,0
* Language: English (United States)
* Legal Copyright: Copyright (C) 2007-2011, Apple Inc.


## Possible Misuse

*The following table contains possible examples of `defaults.exe` being misused. While `defaults.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-macOS.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-macOS.misp.event.json) | `					"description": "To prevent normal users from accidentally changing special files on a system, most operating systems have the concept of a \u2018hidden\u2019 file. These files don\u2019t show up when a user browses the file system with a GUI or when using normal commands on the command line. Users must explicitly ask to show the hidden files either via a series of Graphical User Interface (GUI) prompts or with command line switches (<code>dir \/a<\/code> for Windows and <code>ls \u2013a<\/code> for Linux and macOS).\n\nAdversaries can use this to their advantage to hide files and folders anywhere on the system for persistence and evading a typical user or system analysis that does not incorporate investigation of hidden files.\n\n### Windows\n\nUsers can mark specific files as hidden by using the attrib.exe binary. Simply do <code>attrib +h filename<\/code> to mark a file or folder as hidden. Similarly, the \u201c+s\u201d marks a file as a system file and the \u201c+r\u201d flag marks the file as read only. Like most windows binaries, the attrib.exe binary provides the ability to apply these changes recursively \u201c\/S\u201d.\n\n### Linux\/Mac\n\nUsers can mark specific files as hidden simply by putting a \u201c.\u201d as the first character in the file or folder name  (Citation: Sofacy Komplex Trojan) (Citation: Antiquated Mac Malware). Files and folder that start with a period, \u2018.\u2019, are by default hidden from being viewed in the Finder application and standard command-line utilities like \u201cls\u201d. Users must specifically change settings to have these files viewable. For command line usages, there is typically a flag to see all files (including hidden ones). To view these files in the Finder Application, the following command must be executed: <code>defaults write com.apple.finder AppleShowAllFiles YES<\/code>, and then relaunch the Finder Application.\n\n### Mac\n\nFiles on macOS can be marked with the UF_HIDDEN flag which prevents them from being seen in Finder.app, but still allows them to be seen in Terminal.app (Citation: WireLurker).\nMany applications create these hidden files and folders to store information so that it doesn\u2019t clutter up the user\u2019s workspace. For example, SSH utilities create a .ssh folder that\u2019s hidden and contains the user\u2019s known hosts and keys.",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1037.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1037.002/T1037.002.md) |     sudo defaults write com.apple.loginwindow LoginHook /Library/Scripts/AtomicRedTeam.sh | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1037.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1037.002/T1037.002.md) | 	  defaults write com.apple.loginwindow LoginHook /Library/Scripts/AtomicRedTeam.sh | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.007/T1547.007.md) | Mac Defaults | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.007/T1547.007.md) | sudo defaults write com.apple.loginwindow LoginHook #{script} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.003/T1548.003.md) | In the wild, malware has disabled <code>tty_tickets</code> to potentially make scripting easier by issuing <code>echo \'Defaults !tty_tickets\' >> /etc/sudoers</code> (Citation: cybereason osx proton). In order for this change to be reflected, the malware also issued <code>killall Terminal</code>. As of macOS Sierra, the sudoers file has <code>tty_tickets</code> enabled by default.</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.003/T1548.003.md) | sudo sh -c "echo Defaults "'!'"tty_tickets >> /etc/sudoers" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.001/T1564.001.md) | defaults write com.apple.finder AppleShowAllFiles YES | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.001/T1564.001.md) | defaults write com.apple.finder AppleShowAllFiles NO | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | 		$x5 = "-p DEST_PORT, --dest_port=DEST_PORT defaults: telnet=23, ssh=22 (optional) - Change to LOCAL redirect port" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) |       $s2 = "You may enter between 1 and 6 ports to change the defaults." fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) |       $s0 = "port - Port to listen on, defaults to 2323" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | 		$s0 = "action=mysqlread&mass=loadmass\">load all defaults" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


