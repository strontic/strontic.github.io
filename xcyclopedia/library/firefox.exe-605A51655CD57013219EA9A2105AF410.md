---
title: firefox.exe | Firefox
---

# firefox.exe 

* File Path: `C:\Program Files\Mozilla Firefox\firefox.exe`
* Description: Firefox

## Hashes

Type | Hash
-- | --
MD5 | `605A51655CD57013219EA9A2105AF410`
SHA1 | `DE10A7CD3F84D5DA9C426CBA6A25DB6DE67340A8`
SHA256 | `47821033298C6D2B6EFF436F7029E199A82A46F818B91D36121D5C25F4D2DBB7`
SHA384 | `AAB5AE2D6176C9D44A4652FB4F32E98FA93E7834DBBA1181C53645FEA1CE0E7AC44638F9D290C8883174622FFFF8E1FF`
SHA512 | `6AD87571F4CC668A862AE459C482A488BCE5E4B558FF76A7DE2B8ABD4AC7092B0B8CCFAAF8EEB2594A5966B0BAD81F93EC2A920A0BC6CB1AF51C735C57AA2CF8`
SSDEEP | `12288:8kboKHxiy2M5q9cKeK5gPxYGZdNzwHJem7OzwHJe5:8y7xiy2MEyxYGZdBwpemIwpe5`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: C:\Program Files\Mozilla Firefox\firefox.exe [ options ... ] [URL]
       where options include:

  -h or --help       Print this message.
  -v or --version    Print Firefox version.
  --full-version     Print Firefox version, build and platform build ids.
  -P <profile>       Start with <profile>.
  --profile <path>   Start with profile at <path>.
  --migration        Start with migration wizard.
  --ProfileManager   Start with ProfileManager.
  --no-remote        Do not accept or send remote commands; implies
                     --new-instance.
  --new-instance     Open new instance, not a new window in running instance.
  --UILocale <locale> Start with <locale> resources as UI Locale.
  --safe-mode        Disables extensions and themes for this session.
  --allow-downgrade  Allows downgrading a profile.
  --MOZ_LOG=<modules> Treated as MOZ_LOG=<modules> environment variable,
                     overrides it.
  --MOZ_LOG_FILE=<file> Treated as MOZ_LOG_FILE=<file> environment variable,
                     overrides it. If MOZ_LOG_FILE is not specified as an
                     argument or as an environment variable, logging will be
                     written to stdout.
  --console          Start Firefox with a debugging console.
  --headless         Run without a GUI.
  --ssb <uri>        Open a site specific browser for <uri>.
  --browser          Open a browser window.
  --new-window <url> Open <url> in a new window.
  --new-tab <url>    Open <url> in a new tab.
  --private-window <url> Open <url> in a new private window.
  --preferences      Open Options dialog.
  --screenshot [<path>] Save screenshot to <path> or in working directory.
  --window-size width[,height] Width and optionally height of screenshot.
  --search <term>    Search <term> with your default search engine.
  --setDefaultBrowser Set this app as the default browser.
  --first-startup    Run post-install actions before opening a new window.
  --kiosk Start the browser in kiosk mode.
  --jsconsole        Open the Browser Console.
  --jsdebugger [<path>] Open the Browser Toolbox. Defaults to the local build
                     but can be overridden by a firefox path.
  --wait-for-jsdebugger Spin event loop until JS debugger connects.
                     Enables debugging (some) application startup code paths.
                     Only has an effect when `--jsdebugger` is also supplied.
  --devtools         Open DevTools on initial load.
  --start-debugger-server [ws:][ <port> | <path> ] Start the devtools server on
                     a TCP port or Unix domain socket path. Defaults to TCP port
                     6000. Use WebSocket protocol if ws: prefix is specified.
  --recording <file> Record drawing for a given URL.
  --recording-output <file> Specify destination file for a drawing recording.

```

### Child Processes:
firefox.exe

## Signature

* Status: Signature verified.
* Serial: `0DDEB53F957337FBEAF98C4A615B149D`
* Thumbprint: `91CABEA509662626E34326687348CAF2DD3B4BBA`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: E="release+certificates@mozilla.com", CN=Mozilla Corporation, OU=Firefox Engineering Operations, O=Mozilla Corporation, L=Mountain View, S=California, C=US

## File Metadata

* Original Filename: firefox.exe
* Product Name: Firefox
* Company Name: Mozilla Corporation
* File Version: 79.0
* Product Version: 79.0
* Language: Language Neutral
* Legal Copyright: Firefox and Mozilla Developers; available under the MPL 2 license.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\Mozilla Firefox\firefox.exe](firefox.exe-01DF6E9C1724C892E47B2D19AC5136E0.md) | 50

## Possible Misuse

*The following table contains possible examples of `firefox.exe` being misused. While `firefox.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows NT 6.; WOW64; rv:20.0) Gecko/20100101 Firefox/20.0'  # APT GrizzlySteppe - ChopStick - US CERT https://goo.gl/1DTHwi` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows NT 6.3; WOW64; rv:28.0) Gecko/20100101 Firefox/28.0'  # Sofacy - Xtunnel` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows NT 6.2; WOW64; rv:20.0) Gecko/20100101 Firefox/'  # Sofacy - Xtunnel` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows NT 6.; WOW64; rv:20.0) Gecko/20100101 Firefox/2'  # Sofacy - Xtunnel` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows; U; Windows NT 5.1; zh-EN; rv:1.7.12) Gecko/20100719 Firefox/1.0.7'  # Unit78020 Malware` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla/5.0 (Windows; U; Windows NT 5.1; en-US; rv:1.9.2.13) Firefox/3.6.13 GTB7.1'  # Winnti related` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_apt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_apt.yml) | `- 'Mozilla v5.1 (Windows NT 6.1; rv:6.0.1) Gecko/20100101 Firefox/6.0.1'  # Delphi downloader https://www.welivesecurity.com/2018/04/24/sednit-update-analysis-zebrocy/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_frameworks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_frameworks.yml) | `- 'Mozilla/5.0 (Windows NT 6.3; rv:39.0) Gecko/20100101 Firefox/35.0'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_frameworks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_frameworks.yml) | `- 'Mozilla/6.0 (X11; Linux x86_64; rv:24.0) Gecko/20140205     Firefox/27.0 Iceweasel/25.3.0'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_hacktool.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_hacktool.yml) | `- 'Mozilla/5.0 (Windows; U; Windows NT 5.1; pt-PT; rv:1.9.1.2) Gecko/20090729 Firefox/3.5.2 (.NET CLR 3.5.30729)'  # SQLi Dumper` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_malware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_malware.yml) | `- 'Mozilla/5.0 (Windows; U; Windows NT 5.1; en-US; rv:1.9.2.3) Gecko/20100401 Firefox/3.6.1 (.NET CLR 3.5.30731)'  # Sality` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_malware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_malware.yml) | `- 'Mozilla/5.0 (Windows; U; Windows NT 5.1; en-US; rv:1.9.2.3) Gecko/20100401 Firefox/3.6.1 (.NET CLR 3.5.30729)'  # Sality` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [proxy_ua_suspicious.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_ua_suspicious.yml) | `- 'Mozilla/5.0 (Windows NT 6.3; WOW64; rv:28.0) Gecko/20100101 Firefox/28.0'  # used by APT28 malware https://threatvector.cylance.com/en_us/home/inside-the-apt28-dll-backdoor-blitz.html` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_outbound_kerberos_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_suspicious_outbound_kerberos_connection.yml) | `- '\firefox.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_outbound_kerberos_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_suspicious_outbound_kerberos_connection.yml) | `- '\firefox.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\firefox.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [keydnap](https://github.com/eset/malware-ioc/blob/master/keydnap/README.adoc) | `\| `773a82343367b3d09965f6f09cc9887e7f8f01bf` \| screenshot.jpg \| 2016-05-07 \| hxxp://dev.aneros.com/media/icloudsyncd \| Firefox 20 about screenshot` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-kryptocibule.json](https://github.com/eset/malware-ioc/blob/master/kryptocibule/misp-kryptocibule.json) | `"value": "Mozilla/5.0 (Windows NT 6.1; Win64; x64; rv:47.0) Gecko/20100101 Firefox/47.0",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [kryptocibule](https://github.com/eset/malware-ioc/blob/master/kryptocibule/README.adoc) | `- `Mozilla/5.0 (Windows NT 6.1; Win64; x64; rv:47.0) Gecko/20100101 Firefox/47.0`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [mispadu](https://github.com/eset/malware-ioc/blob/master/mispadu/README.adoc) | `\| `F6021380AD6E26038B5629189A7ADA5E0022C313` \| Mozilla Firefox credential stealer   \| Win32/PSWTool.PassFox.F` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [mumblehard](https://github.com/eset/malware-ioc/blob/master/mumblehard/README.adoc) | `- `Mozilla/5.0 (Windows NT 6.1; rv:7.0.1) Gecko/<1 or more digits>.<1 or more digits>.<1 or more digits> Firefox/7.0.1`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [mumblehard](https://github.com/eset/malware-ioc/blob/master/mumblehard/README.adoc) | `- `Mozilla/5.0 (Windows NT 6.1; rv:7.0.1) Gecko/20100101 Firefox/7.0.1`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus](https://github.com/eset/malware-ioc/blob/master/oceanlotus/README.adoc) | `\|`a40ee8ff313e59aa92d48592c494a4c3d81449af`\|Firefox Installer.exe                           \|Win32/TrojanDropper.Agent.RUI` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [2020_Q2](https://github.com/eset/malware-ioc/blob/master/quarterly_reports/2020_Q2/README.adoc) | `=== Firefox addons` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `Firefox` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `firefox.exe` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #3: Firefox [linux, windows, macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #1: List Mozilla Firefox Bookmark Database Files on Linux [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #2: List Mozilla Firefox Bookmark Database Files on macOS [macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #6: List Mozilla Firefox bookmarks on Windows with command prompt [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) |   - Atomic Test #3: Firefox [linux, windows, macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [linux-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/linux-index.md) |   - Atomic Test #1: List Mozilla Firefox Bookmark Database Files on Linux [linux] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) |   - Atomic Test #3: Firefox [linux, windows, macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [macos-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/macos-index.md) |   - Atomic Test #2: List Mozilla Firefox Bookmark Database Files on macOS [macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #3: Firefox [linux, windows, macos] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #6: List Mozilla Firefox bookmarks on Windows with command prompt [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1176.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1176/T1176.md) | - [Atomic Test #3 - Firefox](#atomic-test-3---firefox) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1176.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1176/T1176.md) | ## Atomic Test #3 - Firefox | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | - [Atomic Test #1 - List Mozilla Firefox Bookmark Database Files on Linux](#atomic-test-1---list-mozilla-firefox-bookmark-database-files-on-linux) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | - [Atomic Test #2 - List Mozilla Firefox Bookmark Database Files on macOS](#atomic-test-2---list-mozilla-firefox-bookmark-database-files-on-macos) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | - [Atomic Test #6 - List Mozilla Firefox bookmarks on Windows with command prompt](#atomic-test-6---list-mozilla-firefox-bookmarks-on-windows-with-command-prompt) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | ## Atomic Test #1 - List Mozilla Firefox Bookmark Database Files on Linux | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | Searches for Mozilla Firefox's places.sqlite file (on Linux distributions) that contains bookmarks and lists any found instances to a text file. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | \| output_file \| Path where captured results will be placed. \| Path \| /tmp/T1217-Firefox.txt\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | find / -path "*.mozilla/firefox/*/places.sqlite" 2>/dev/null -exec echo {} >> #{output_file} \; | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | ## Atomic Test #2 - List Mozilla Firefox Bookmark Database Files on macOS | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | Searches for Mozilla Firefox's places.sqlite file (on macOS) that contains bookmarks and lists any found instances to a text file. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | find / -path "*/Firefox/Profiles/*/places.sqlite" -exec echo {} >> #{output_file} \; | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | ## Atomic Test #6 - List Mozilla Firefox bookmarks on Windows with command prompt | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1217.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1217/T1217.md) | Searches for Mozilla Firefox bookmarks file (on Windows distributions) that contains bookmarks in a SQLITE database. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555.003/T1555.003.md) | Adversaries have executed similar procedures for common web browsers such as FireFox, Safari, Edge, etc. (Citation: Proofpoint Vega Credential Stealer May 2018)(Citation: FireEye HawkEye Malware July 2017) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | 		$s4 = "(C)Firefox and Mozilla Developers, according to the MPL 1.1/GPL 2.0/LGPL" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_bluetermite_emdivi.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_bluetermite_emdivi.yar) | 		$s2 = "\\Mozilla\\Firefox\\Profiles\\" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_casper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_casper.yar) | 		$s2 = "firefox.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_casper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_casper.yar) | 		$x2 = "\\Roaming\\Mozilla\\Firefox\\Profiles\\*" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_casper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_casper.yar) | 		$x3 = "\\Mozilla\\Firefox\\Profiles\\*" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_danti_svcmondr.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_danti_svcmondr.yar) | 		$s3 = "%s\\Mozilla\\Firefox\\profiles.ini" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dragonfly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dragonfly.yar) |       $s4 = "***************** Mozilla Firefox ****************" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dtrack.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dtrack.yar) |       $s2 = "%s\\%s\\AppData\\Roaming\\Mozilla\\Firefox\\Profiles" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_duqu2.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_duqu2.yar) | 		$x1 = "Mozilla/5.0 (Windows NT 6.1; U; ru; rv:5.0.1.6) Gecko/20110501 Firefox/5.0.1 Firefox/5.0.1" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_duqu2.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_duqu2.yar) | 		$x4 = "Mozilla/5.0 (Windows NT 6.1; WOW64; rv:6.0a2) Gecko/20110612 Firefox/6.0a2" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | 		$x1 = "firefox http://127.0.0.1:8000/$_name" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_freemilk.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_freemilk.yar) |       $s1 = "SOFTWARE\\Clients\\StartMenuInternet\\firefox.exe\\shell\\open\\command" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_golddragon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_golddragon.yar) |       $s6 = "Mozilla/5.0 (Windows NT 5.2; rv:12.0) Gecko/20100101 Firefox/12.0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) |       $STR3 = "User-Agent: Mozilla/5.0 (Windows NT 6.; WOW64; rv:20.0) Gecko/20100101 Firefox/20.0" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_rokrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_rokrat.yar) |       $s1 = "SOFTWARE\\Clients\\StartMenuInternet\\firefox.exe\\shell\\open\\command" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sednit_delphidownloader.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sednit_delphidownloader.yar) |       $s3 = "4D6F7A696C6C612076352E31202857696E646F7773204E5420362E313B2072763A362E302E3129204765636B6F2F32303130303130312046697265666F782F36" ascii /* hex encoded string 'Mozilla v5.1 (Windows NT 6.1; rv:6.0.1) Gecko/20100101 Firefox/6.0.1' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_xtunnel_bundestag.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_xtunnel_bundestag.yar) |         $variant21 = "User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64; rv:28.0) Gecko/20100101 Firefox/28.0" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_xtunnel_bundestag.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_xtunnel_bundestag.yar) |         $x1 = "User-Agent: Mozilla/5.0 (Windows NT 6.2; WOW64; rv:20.0) Gecko/20100101 Firefox/" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_xtunnel_bundestag.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_xtunnel_bundestag.yar) |         $x2 = "User-Agent: Mozilla/5.0 (Windows NT 6.; WOW64; rv:20.0) Gecko/20100101 Firefox/2" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_unit78020_malware.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_unit78020_malware.yar) | 		$s2 = "User-Agent: Mozilla/5.0 (Windows; U; Windows NT 5.1; zh-EN; rv:1.7.12) Gecko/20100719 Firefox/1.0.7" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_unit78020_malware.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_unit78020_malware.yar) | 		$s3 = "%USERPROFILE%\\Application Data\\Mozilla\\Firefox\\Profiles" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_vpnfilter.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_vpnfilter.yar) |       $a1 = "Mozilla/5.0 Firefox/50.0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_vpnfilter.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_vpnfilter.yar) |       $a2 = "Mozilla/5.0 (X11; Ubuntu; Linux i686; rv:52.0) Gecko/20100101 Firefox/52.0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_vpnfilter.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_vpnfilter.yar) |       $a3 = "Mozilla/5.0 (Windows NT 6.1; rv:52.0) Gecko/20100101 Firefox/52.0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_zxshell.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_zxshell.yar) |       $u3 = "User-Agent:Mozilla/5.0 (X11; U; Linux i686; en-US; re:1.4.0) Gecko/20080808 Firefox/%d.0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | 		$s3 = "Mozilla/5.0 (Windows NT 6.3; WOW64; rv:26.0) Gecko/20100101 Firefox/26.0" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_andromeda_jun17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_andromeda_jun17.yar) |       $x4 = "firefox.exe.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_bad_patch.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_bad_patch.yar) |       $s3 = "\\AppData\\Roaming\\Mozilla\\Firefox\\Profiles" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_mal_nitol.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_mal_nitol.yar) |       $s3 = "User-Agent:Mozilla/5.0 (X11; U; Linux i686; en-US; re:1.4.0) Gecko/20080808 Firefox/%d.0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_rombertik_carbongrabber.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_rombertik_carbongrabber.yar) | 		$s5 = "firefox.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) |         description = "Detects uncommon file size of firefox.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) |         and filename == "firefox.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_p0wnshell.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_p0wnshell.yar) |       $x1 = "Now if we point Firefox to http://127.0.0.1" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_tscookie_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_tscookie_rat.yar) |       $x2 = "----------------------- Firefox Passwords ------------------" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


