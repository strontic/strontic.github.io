---
title: wdsutil.exe | Windows Deployment Services Management Utility
excerpt: What is wdsutil.exe?
---

# wdsutil.exe 

* File Path: `C:\Windows\system32\wdsutil.exe`
* Description: Windows Deployment Services Management Utility

## Hashes

Type | Hash
-- | --
MD5 | `A143B91F5DA31CA9C541013401B01136`
SHA1 | `726BF42F044146AE71A66265FCE0D3F5E2AA8C43`
SHA256 | `86283CFD57ABD1114449037FC8D0CF4FFE4E010CB4BB5CB6EAE7095D1D4489C3`
SHA384 | `0750D70DBF731943559927D146FFEBE37C9C91A4A16D71D86FEE08C12F1F723F010293A2215AC9C9DD438A32B101E87C`
SHA512 | `2CEB4DCC3340A065D2A3CB7CCC93051320FD53201EE6052B4A285C1C78D1A183CE1C2D88298E272F2A8F8EF75C4F25550886E4B7ED32AB5B580C7992C9FEE8BB`
SSDEEP | `6144:UAt3XEoCBfHCRGC33msjVxiYqn3D2z+uEZMPiX5ZXbDHT:UAVXEoYfHCUU3m3z2zLUwipFbDz`

## Runtime Data

### Usage (stdout):
```cmhg

Windows Deployment Services Management Utility [Version 10.0.17763.1]
 2018 Microsoft Corporation. All rights reserved.

Usage:
       WDSUTIL is a command line utility used for managing Windows Deployment
       Services (WDS).

Syntax:
        WDSUTIL [Options] <Command> [Command Parameters]

The following options are supported for all commands:

/?
        Displays help for the specified command.

/Help
        Displays help for the specified command.

/Verbose
        Displays verbose output for the specified command.

/Progress
        Displays progress while the command is being executed.

List of commands:

/Initialize
        Configures a WDS server for initial use.

/Uninitialize
        Reverts changes made during server initialization.

/Add
        Adds images, image groups, prestaged devices, driver packages, driver
        groups or driver group filters to the server. Also adds driver packages
        to a boot image.

/Remove
        Removes devices, images, image groups, driver packages, driver groups
        or driver group filters. Also used to remove multicast transmissions
        and namespaces.

/Replace
        Replaces an existing image with a new version.

/Set
        Sets properties and attributes on WDS servers, prestaged devices,
        images, image groups, driver packages, driver groups, driver group
        filters, or transport servers.

/Get
        Displays properties and attributes of WDS servers, prestaged devices,
        images, image groups, driver packages, driver groups or transport
        servers. Also displays pending devices, multicast transmissions and
        expected deployment results.

/New
        Creates new capture images, discover images, or multicast transmissions
        and namespaces.

/Copy
        Copies images within an image group, and copies driver groups.

/Export
        Exports images from the image store to a WIM file.

/Stop
        Stops all WDS services.

/Start
        Starts all WDS services. Also starts multicast transmissions and
        namespaces.

/Disable
        Disables all WDS services.

/Enable
        Enables all WDS services.

/Approve
        Approves pending devices that are awaiting approval.

/Reject
        Rejects pending devices that are awaiting approval.

/Delete
        Deletes records from the pending device database.

/Update
        Updates a server resource from a known good source.

/Disconnect
        Disconnects a client from a multicast transmission or namespace.

/AllHelp
        Displays all available commands.


For help with a specific command, type 'WDSUTIL <command> /?' where
<command> is one of the commands listed above. For example: WDSUTIL /Add /?

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WdsUtil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## wdsutil

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

wdsutil is a command-line utility used for managing your Windows Deployment Services server. To run these commands, click **start**, right-click **Command prompt**, and click **Run as administrator**.

### Commands

|Command|Description|
|------|--------|
|[wdsutil add command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-add.md)|Adds objects or prestages computers.|
|[wdsutil approve-autoadddevices command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-approve-autoadddevices.md)|Approves computers that are pending administrator approval.|
|[wdsutil convert-riprepimage command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-convert-riprepimage.md)|Converts an existing remote Installation Preparation (RIPrep) image to a Windows Image (.wim) file.|
|[wdsutil copy command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-copy.md)|Copies an image or a driver group.|
|[wdsutil delete-autoadddevices command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-delete-autoadddevices.md)|Deletes computers that are in the Auto-add database (which stores information about the computers on the server).|
|[wdsutil disable command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-disable.md)|Disables all services for Windows Deployment Services.|
|[wdsutil disconnect-client command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-disconnect-client.md)|Disconnects a client from a multicast transmission or namespace.|
|[wdsutil enable command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-enable.md)|Enables all services for Windows Deployment Services.|
|[wdsutil export-image command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-export-image.md)|Exports an image from the image store to a .wim file.|
|[wdsutil get command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-get.md)|Retrieves properties and attributes about the specified object.|
|[wdsutil initialize-server command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-initialize-server.md)|Configures a Windows Deployment Services server for initial use.|
|[wdsutil new command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-new.md)|creates new capture and discover images as well as multicast transmissions and namespaces.|
|[wdsutil progress command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-progress.md)|Displays the progress status while a command is being executed.|
|[wdsutil reject-autoadddevices command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-reject-autoadddevices.md)|Rejects computers that are pending administrator approval.|
|[wdsutil remove command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-remove.md)|removes objects.|
|[wdsutil replace-image command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-replace-image.md)|replaces a boot or installation image with a new version of that image.|
|[wdsutil set command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-set.md)|Sets properties and attributes on the specified object.|
|[wdsutil start server command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-start-server.md)|starts all services on the Windows Deployment Services server, including multicast transmissions, namespaces, and the Transport Server.|
|[wdsutil stop server command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-stop-server.md)|Stops all services on the Windows Deployment Services server.|
|[wdsutil uninitialize-server command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-uninitialize-server.md)|reverts changes made during server initialization.|
|[wdsutil update-serverfiles command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-update-serverfiles.md)|Updates server files on the remoteInstall share.|
|[wdsutil verbose command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/wdsutil-verbose.md)|Displays verbose output for the specified command.|

---



MIT License. Copyright (c) 2020 Strontic.


