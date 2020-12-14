---
title: rmdir.exe | 
excerpt: What is rmdir.exe?
---

# rmdir.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\rmdir.exe`

## Hashes

Type | Hash
-- | --
MD5 | `0E5D35BC29C949FB60705480DB84D8AE`
SHA1 | `BA90628511DB986E33F91AC536BD830B8588A880`
SHA256 | `0CF3A7218619DA063AD061740517C9A733EB89BF331E4D36F28E9BCDDD9348FB`
SHA384 | `CC301BE7BE8B8F70B8BB06568DB89306E7420EC2DBB22B1EEB8AC1F45252CF130AD086220F92B665259EEB3189546AA3`
SHA512 | `93477E69092AB38186747B78BE588645D6C7B4D1A5D326674D0AC93D3BFB207C2C34EDB502E9A312CA73F4684390E33290A82CEAE84BFEA8EC3309CFE9DA98AF`
SSDEEP | `1536:iwTW5XjmjqDer7i5+B48LyKt8lWTFPPJUfF:FqXSuD8e5SfTFPPI`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/rmdir [OPTION]... DIRECTORY...
Remove the DIRECTORY(ies), if they are empty.

      --ignore-fail-on-non-empty
                  ignore each failure that is solely because a directory
                    is non-empty
  -p, --parents   remove DIRECTORY and its ancestors; e.g., 'rmdir -p a/b/c' is
                    similar to 'rmdir a/b/c a/b a'
  -v, --verbose   output a diagnostic for every directory processed
      --help     display this help and exit
      --version  output version information and exit

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/rmdir>
or available locally via: info '(coreutils) rmdir invocation'

```

### Usage (stderr):
```cmhg
rmdir: unknown option -- h
Try '/usr/bin/rmdir --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\rmdir.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `045D8F14A82147641722D4FAFC66BC80`
* Thumbprint: `FB713A60A7FA79DFC03CB301CA05D4E8C1BDD431`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="GitHub, Inc.", O="GitHub, Inc.", L=San Francisco, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 



## Possible Misuse

*The following table contains possible examples of `rmdir.exe` being misused. While `rmdir.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- ' rmdir '       # don't match on 'dir'   "C:\Windows\System32\cmd.exe" /q /c rmdir /s /q "C:\Users\XX\AppData\Local\Microsoft\OneDrive\19.232.1124.0005"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1003.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.003/T1003.003.md) | rmdir /q /s #{output_folder} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | rmdir /S /Q %temp%\temp_T1027.zip >nul 2>nul | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.004/T1070.004.md) | rmdir /s /q #{folder_to_delete} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1222.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1222.001/T1222.001.md) | rmdir #{file_or_folder} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = "if(rmdir($_POST['mk_name']))" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "@rmdir($_GET['file']) or die (\"[-]Error deleting dir!\");" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## rmdir

Deletes a directory.

The **rmdir** command can also run from the Windows Recovery Console, using different parameters. For more information, see [Windows Recovery Environment (WinRE)](/windows-hardware/manufacture/desktop/windows-recovery-environment--windows-re--technical-reference).

> [!NOTE]
> This command is the same as the [rd command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/rd.md).

### Syntax

```
rmdir [<drive>:]<path> [/s [/q]]
```

#### Parameters

| Parameter | Description |
|--|--|
| `[<drive>:]<path>` | Specifies the location and the name of the directory that you want to delete. *Path* is required. If you include a backslash (\) at the beginning of the specified *path*, then the *path* starts at the root directory (regardless of the current directory). |
| /s | Deletes a directory tree (the specified directory and all its subdirectories, including all files). |
| /q | Specifies quiet mode. Does not prompt for confirmation when deleting a directory tree. The **/q** parameter works only if **/s** is also specified.<p>**CAUTION:** When you run in quiet mode, the entire directory tree is deleted without confirmation. Make sure that important files are moved or backed up before using the **/q** command-line option. |
| /? | Displays help at the command prompt. |

##### Remarks

- You can't delete a directory that contains files, including hidden or system files. If you attempt to do so, the following message appears:

    `The directory is not empty`

    Use the **dir /a** command to list all files (including hidden and system files). Then use the **attrib** command with **-h** to remove hidden file attributes, **-s** to remove system file attributes, or **-h -s** to remove both hidden and system file attributes. After the hidden and file attributes have been removed, you can delete the files.

- You can't use the **rmdir** command to delete the current directory. If you attempt to delete the current directory, the following error message appears:

    `The process can't access the file because it is being used by another process.`

    If you receive this error message, you must change to a different directory (not a subdirectory of the current directory), and then try again.

### Examples

To change to the parent directory so you can safely remove the desired directory, type:

```
cd ..
```

To remove a directory named *test* (and all its subdirectories and files) from the current directory, type:

```
rmdir /s test
```

To run the previous example in quiet mode, type:

```
rmdir /s /q test
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


