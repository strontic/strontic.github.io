---
title: wdsutil.exe | Windows Deployment Services Management Utility
---

# wdsutil.exe 

* File Path: `C:\Windows\system32\wdsutil.exe`
* Description: Windows Deployment Services Management Utility
* Comments: 

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
```Batchfile

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

### Usage (stderr):
```Batchfile

```

### Child Processes:


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
|[Using the add Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-add-command.md)|adds objects or prestages computers.|
|[Using the Approve-AutoaddDevices Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-approve-autoadddevices-command.md)|Approves computers that are pending administrator approval.|
|[Using the convert-RiprepImage Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-convert-riprepimage-command.md)|converts an existing remote Installation Preparation (RIPrep) image to a Windows Image (.wim) file.|
|[Using the copy Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-copy-command.md)|Copies an image or a driver group.|
|[Using the delete-AutoaddDevices Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-delete-autoadddevices-command.md)|deletes computers that are in the Auto-add database (which stores information about the computers on the server).|
|[Using the Disable Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-disable-command.md)|Disables all services for Windows Deployment Services.|
|[Using the Disconnect-Client Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-disconnect-client-command.md)|Disconnects a client from a multicast transmission or namespace.|
|[Using the Enable Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-enable-command.md)|Enables all services for Windows Deployment Services.|
|[Using the Export-Image Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-export-image-command.md)|Exports an image from the image store to a .wim file.|
|[Using The get Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-get-command.md)|Retrieves properties and attributes about the specified object.|
|[Using the Initialize-Server Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-initialize-server-command.md)|Configures a Windows Deployment Services server for initial use.|
|[Using the New Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-new-command.md)|creates new capture and discover images as well as multicast transmissions and namespaces.|
|[The progress Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/the-progress-command.md)|Displays the progress status while a command is being executed.|
|[Using The Reject-AutoaddDevices Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-reject-autoadddevices-command.md)|Rejects computers that are pending administrator approval.|
|[Using the remove Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-remove-command.md)|removes objects.|
|[Using the replace-Image Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/using-the-replace-image-command.md)|replaces a boot or installation image with a new version of that image.|
|[The Set Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/the-set-command.md)|Sets properties and attributes on the specified object.|
|[The start Server Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/the-start-server-command.md)|starts all services on the Windows Deployment Services server, including multicast transmissions, namespaces, and the Transport Server.|
|[The Stop Server Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/the-stop-server-command.md)|Stops all services on the Windows Deployment Services server.|
|[The uninitialize-Server Option](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/the-uninitialize-server-option.md)|reverts changes made during server initialization.|
|[The Update-ServerFiles Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/the-update-serverfiles-command.md)|Updates server files on the remoteInstall share.|
|[The verbose Command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/the-verbose-command.md)|Displays verbose output for the specified command.|

---



MIT License. Copyright (c) 2020 Strontic.


